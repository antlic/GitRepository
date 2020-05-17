git config --global user.name "name" {添加全局名称}
git config --global user.email "xx@.com" {添加全局邮箱}
git init  {初始化目录为git仓库}
git add test.txt {添加工作区的文件到暂存区}
git commit test.txt -m "日志" {把暂存区的文件提交到仓库}
git status  {当前工作区文件状态}
git diff text.txt  {对比文件的不同}
git log  {当前版本前的日志记录}
git log --preety=oneline  {简单版本的日志记录}
git reset --hard head^  {切换到上个提交的版本}
git reset --hard head^^ {切换到上上个提交的版本}
git reset --hard head~9  {切换到上9个提交的版本}
git reflog {所有日志}
git reset --hard c7cc795{切换到id头为c7cc795的版本}
git reset head test.txt  {把暂存区里的文件撤销掉，从新放回工作区}
git checkout -- text.txt  {把工作区里的文件撤销掉}
git rm text.txt  {删除掉text.txt文件}
