## 1.安装[git](https://git-scm.com/downloads/)
## 2.建立本地仓库
  1.进入到要提交的代码文件根目录，右键，选择Git Bash Here
  
  <img align="center" width=473 src="pics/pic1.png" />
  2.输入：git init //创建仓库
  
  3.输入：git add . //在仓库中加入当前目录所有文件
  
  4.输入：git status //查看当前git状态

## 3.上传到远程仓库
  1.输入命令：ssh-keygen -t rsa -C "651897335@qq.com"，然后一路Enter键，如果提示是否Overwrite，输入y表示覆盖，最后会在C:\Users\Administrator\.ssh目录下找到id_rsa.pub文件
  
  2.用记事本打开它，复制里面的内容
  
  3.如下图，在github上新建一个ssh
  
  4.将复制的内容粘贴进key中去，并点击Add ssh key提交保存
  
  5.输入：ssh -T git@github.com 会返馈类似下图这样的成功信息
  
  6.输入：ssh remote -v可以查看远程状态，如果是第一次，则有可能不显示任何内容，否则会显示下图信息，稍等一会，才会退出本命令
  
  7.在github上新建一个仓库，例如，新建为test
