# git 操作

Fast-forward

- git init 
- git clone url
  - 克隆一个仓库到本地

- git config user.name 'xx' --global
- git config user.email 'xx@xx.com' --global

# 分支 branch

- git checkout 切换分支
  - git checkout -b 分支名 基于当前所在的分支去创建一个新分支

- git branch
  - git branch 直接查看本地所有分支
  - git branch 分支名 创建一个新分支（但不会切换过去）
  - git branch -D 分支名
  - git branch -r 查看远程分支

- git add

- git commit 

- git pull

- git push
  - git push --set-upstream origin 分支名
  - git push origin --delete 分支名

- git remote 
  - git remote add origin url 
  - git remote rm origin

- git merge 在当前分支上 把其他分支合并到当前分支
  - 适用于在主分支上合并子分支

- git rebase 在当前分支上 把其他分支合并到当前分支
  - 使用于在自己的分支上去合并主分支
  - git rebase -i

- git log

- git cherry-pick
  - 把其他的提交合并到当前分支

- git diff 比较差异

- git stash 
  - git pop
  - git apply

- git reset 

- git revert

- git tag