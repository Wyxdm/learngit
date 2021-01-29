Git is a distributed version control system.
Git is free software under the GRL.

git add "文件名"
git commit -m "给此版本的注释说明"

git log
git status
get reset --hard HEAD^
get reset --hard 版本号
git reflog

#版本修改#
git restore -- firename  :撤销修改回到最近一次git commit或者git add的状态
git restore --staged filename   ：将上传到暂存区的文件撤回
git reset HEAD filename    :撤销已经上传到暂存区的错误
git checkout --filename    :撤销工作区的修改（比如在文本编辑软件界面内的修改）

git tracks changes