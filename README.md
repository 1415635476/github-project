### README

1.配置用户名和邮箱
--global全局配置，而不是对单个项目进行配置
git config --global user.name "gym2024388120"
git config --global user.email "1415635476@qq.com"

2.查看配置信息
项目根目录的 .gitconfig
or
git config --global --list

3.将当前分支重命名为 main（默认是master）
git branch -M main

4.添加远程仓库信息
git remote add origin https://github.com/1415635476/github-project.git

5.查看远程仓库的信息
git remote -v

6.推送到远程仓库，首次需要这样，后面直接git push即可
git push -u origin main

7.git branch
查看分支

8.git staus
查看暂存区