# MyFirstApp
第一个app的创建，以及GitHub的上传
## 一 创建一个项目文件
### 创建一个Empty Activity，然后命名为MyFirstApp
![image](image\1.png)
![image](image\2.png)
## 二 将项目上传至GitHub
### 1、首先下载git，配置好SSH密钥，创建一个GitHub账号，并在GitHub中配置好SSH密钥
### 2、然后在项目文件夹下右键，Open git bash here，打开git bash
![image](image\3.png)
### 3、输入**git init**，建立一个本地仓库
### 4、可以配置对应的.gitignore文件（可选）
### 5、输入**git add .**，将文件夹中项目文件，除了前面.gitignore文件忽略的文件外都加入到本地仓库中
### 6、输入**git commit -m "commit info"**，"commit info"指的是这次提交的内容，我这里输入的是**git commit -m "my first commit"**
### 7、接下来在git bash中添加GitHub的远程仓库，输入**git remote add origin git@github.com:你的github账号名/你建立的仓库名.git**
### 8、将代码上传到远程仓库，输入**git push origin master**
### 上传成功！