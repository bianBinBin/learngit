参考网站 廖雪峰 Git 教程

Git 使用时主要需要配置用户名与邮箱，以及生成 SSH 密钥与远程仓库链接
配置用户名与邮箱



配置用户名与邮箱的操作如下
git config --global user.name "[Your Name]"
git config --global user.email "[email@example.com]"


配置完成后可以在 $HOME/.gitconfig 中看到配置的内容
[user]
    name = [Your Name]
    email = [email@example.com]
也可以使用以下命令查看已配置的内容

git config -l
