本地操作：

仓库初始化：git init

文件修改之后添加到工作区 git add a.txt

提交到版本库 git commit -m "修改说明"

创建github的链接：$ git remote add origin git@github.com:zhangmin173/test.git



查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>

提交当前分支到github：git push -u origin master