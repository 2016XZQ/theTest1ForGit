# theTest1ForGit

+ git init 在目录中创建新的 Git 仓库
+ git add [file] 将修改添加到暂存区
+ git status 用于显示工作目录和暂存区的状态
+ git commit -m [log] 将更改记录提交到存储库
+ git diff 显示当前文件和暂存区域快照之间的差异
+ git reset --hard HEAD^ 版本回退到上一次提交
+ git reset --hard <commit id> 版本回退到指定提交
+ git log 显示提交日志信息
+ git log --pretty=oneline 显示提交日志信息（其中一种格式）
+ git reflog 显示所有提交记录（包括回滚记录）
+ git diff HEAD -- file 显示工作区中的文件与版本库中文件的差异
+ git checkout -- file 撤销（恢复）对工作区修改
+ git reset HEAD file 清空add命令向暂存区提交的关于file文件的修改
+ git rm file 从工作区和索引中删除文件
+ git clone http/ssh 从远程主机克隆一个版本库
+ git checkout -b dev 创建并切换分支
+ git branch dev 创建分支
+ git checkout dev 切换分支
+ git branch 列出分支
+ git merge dev 合并分支
+ git merge --no-ff -m "log" 不使用fast-forward方式合并，保留分支的commit历史
+ git branch -d dev 删除分支
+ git log --graph --pretty=oneline --abbrev-commit 查看分支合并图
+ git stash 不提交临时保存
+ git stash apply 恢复临时保存的状态
+ git stash pop 恢复的同时删除stash内容
+ git stash list 查看现有的保存
