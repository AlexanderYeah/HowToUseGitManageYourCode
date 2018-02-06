# 用Git 管理代码还是很方便的
##一  常用的命令 （自己都知道 简写）   

* gitK --all 图形化显示更改记录信息
* git log 查询提交记录
* git init 初始化仓库
* git clone 远程拉取代码
* git status 查看状态 工作区修改代码为红颜色的
* git commit -m"注释" 提交到本地
* git add . 添加到暂缓区 ，代码变为绿色 
* git push 推送到远程   
* git config --list 查看本地配置git账户的信息
* git config user.name 查看本地配置的用户名
* git config user.email 查看本地配置的邮箱  
* git config --global user.name 'username' 修改用户名
* git config --global user.email 'email'  修改邮箱


## 二  自己不常用的命令  

tag 的添加 ,就是对应的一个版本号，就是一个代码的记录  
举栗来讲

* git tag 查看本地仓库所有的标签，也就是所有的版本
* git tag -a '0.0.1' -m"打个标签测试下"
* git push ---tags 将本地所有的标签提交到远程  
* git push origin 0.01 只提交0.0.1 版本到远程 
* git tag -d 0.0.1 删除本地的 0.0.1的版本  
* git push origin :0.0.1 删除远程的0.0.1的版本



git push 报错  
git push 403错误

产生原因 本地缓存了用户名和密码  
解决方案 重新设置用户名和密码 
git remote set -url origin + 地址 
 






