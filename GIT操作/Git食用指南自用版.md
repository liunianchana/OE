# 一 获取Git仓库
## 1 现有本地提交到Git
1)初始化git仓库```git init```

2)添加内容```git add .```

3)提交```git commit -m "提交信息"```

4)上传Git```git push -u origin master```


## 2 从Git克隆仓库到本地
克隆到本地```git clone <URL>```

克隆到本地文件夹```git clone <URL>```

# 二 在Git仓库中记录变更
命令```git status```
## 1 查看文件状态
1) ```Untracked files``` ：未跟踪文件，列出的为未跟踪的文件
2) ```Changes to be commited``` ：等待提交的更改，列出的为已暂存的文件
3) ```Changes not staged for commit``` ：已更改但未添加到暂存区，列出的为已暂存的文件

## 2 显示所处分支
1) ```On branch master``` 显示master分支
2) ```On branch dev``` 显示dev分支

## 3 查看已暂存和未暂存的变更
```git diff```

## 4 提交变更
```git commit``` 

## 5 移除文件
```git rm file```

强制删除```git rm -f file```

## 6 移动文件
```git mv 旧文件 新文件```

# 三 查看提交历史
```git log```

# 四 撤销操作
```git commit -amend```

# 五 远程仓库使用
## 1 显示远程仓库
```git remote```

### 1 克隆仓库
```git clone *.git```

### 2 显示Git仓库的每个远程仓库对应的URL
```git remote -v```

### 3 查看某一远程仓库的更多信息
```git remote show [branch-name]```

```git remote show origin```

## 2 添加远程仓库
1) ```git remote add pd [地址]```




![](../附件/Pasted%20image%2020230209191036.png)