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
ssh-keygen -t rsa -C "xx@qq.com"   {生成sshkey}
git remote add origin git@github.com:antlic/GitRepository.git   {关联本地仓库到github}
git push -u origin master {推送所有的本地文件到远程库，初次推送的时候用}
git push origin master {推送本地文件到远程仓库}
git pull origin master  --allow-unrelated-histories   {获取远程仓库的文件到本地，允许两个库有不相干的历史记录也合并}
git clone git@github.com:antlic/gitskills.git    {克隆远程仓库到本地}
git branch  {查看分支}
git branch <name>  {创建分支}
git switch <name>   {切换分支}
git switch -c <name>  {创建+切换分支}
git merge  <name>   {合并某分支到当前分支}
git branch -d <name>  {删除分支}