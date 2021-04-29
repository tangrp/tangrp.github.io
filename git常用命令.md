## 拉取
git clone https://github.com/tangrp/tangrp.github.io.git

## 更新
git pull

## 冲突
git reset --merge

## 强制覆盖本地  取回远程端所有修改
git fetch --all   

## 添加文件到git
1. 查看本地修改状态
	git status
2. 添加远程 (.表示提交所有 也可指定某一个文件提交)
	git add .
	撤销: git reset HEAD
3. 提交
	git commit -m 'git常用命令'
	撤销：git reset --soft HEAD^
4. 推送到远程库
	git push




## 将版本号置到develop这个版本上
git reset --hard origin/develop  
