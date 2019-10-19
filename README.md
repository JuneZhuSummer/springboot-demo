#这是一个专用于学习的spring boot小项目

#参考文档
https://spring.io/guides/

#项目远程Git仓库
https://github.com/zzjcom/springboot-demo

#Git命令
    将当前目录作为一个Git仓库
    git init
    显示Git当前状态
    git status
    添加当前目录所有文件到暂存中
    git add .
    提交当前暂存中的所有文件，并添加描述
    git commit -m "提交说明"
    指定Git远程仓库地址
    git remote add origin 远程仓库地址
    
    git push -u origin master
    
    可以通过notepad .git/config命令(Linux下用Vi或Vim编辑器打开)打开隐藏配置文件，更改用户名和邮箱
    格式：
    [user]
        name = 用户名
        email = 邮箱
    也可以通过git config --global user.name+用户名 git config --global user.email+邮箱 直接修改