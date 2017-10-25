# git 使用技巧


## 用户配置

### 添加用户名

`git config --global user.name "your github's name"`

### 添加邮箱

`git config --global user.email "emailname@xx.com"`


### 生成ssh

`ssh-keygen -t rsa -C "emailname@xx.com"`

生存ssh-key，添加到github账户中的ssh里面

### 验证ssh

ssh -T git@github.com

### 保存用户配置

`git config --global credential.helper store`
