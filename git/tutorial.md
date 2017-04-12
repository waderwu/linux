# git 基本命令
## 创建一个repository
```
git init repository_name
example:
git init helloworld
```
## 从github clone repository 到本地
```
git clone url
example：
git clone https://github.com/waderwu/linux.git
```
## 本地新增或者改动了文件
```
git add filename 把变化增加到暂存区
```
## 提交改动
```
git commit -m "message" 提交改动 message 是对本次提交的注释
```
## 显示提交记录
```
git log
```
## 显示两次提交的不同
```
git diff
```
## 增加 remote repository
```
git remote add repo_name repo_url
一般的repo name 为origin
```
## 抓取远端的repo
```
git fetch origin 我猜相当于从云端同步变化到本地
```
## 把变化提交到云端
```
git push origin branch
```
## 增加分支branch
```
git branch branch_name 
```
```
git branch 显示当前的分支
git checkout branch_name 切换到branch_name分支
git merge branch_name 在当前分支合并分支branch_name
git checkout -b branch_name 创建并切换到branch_name分支上
git branch -d branch_naem 删除分支
```

## 遇到冲突的分支合并
```
用vim打开冲突的文件然后手动修改，修改后git add ，gitcommit 
```

