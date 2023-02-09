
# 一 Git创建仓库
## ```git init```
在项目根目录使用```git init```初始化一个git仓库

该命令会在项目根目录下创建一个```.git```文件夹
## ```git init 文件夹名称```
若使用```git init 文件夹名称```命令，则会在指定路径下创建```.git```文件夹

# 二 Git clone克隆仓库
使用```git clone```从现有 Git 仓库中拷贝项目

克隆仓库的命令格式为：
```
git clone <repo>
```

克隆到指定目录的命令格式为：
```
git clone <repo> <directory>
```

```
参数说明：
repo：Git仓库（地址）
directory：本地目录
```
# 三 配置
## ```git config ```
显示当前配置信息```git config --list```

# 编辑 git 配置文件
```
git config -e    # 针对当前仓库
```

```
git config -e --global   # 针对系统上所有仓库
```

# 设置提交代码时的用户信息
```
git config (--global) user.name "用户名"
git config (--global) user.email liunianchana@163.com
```