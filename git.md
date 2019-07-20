# Github 笔记

## 创建版本库
1. 进入文件夹
2. 添加用户名和用户密码
```bash{cmd}
git config --global user.name "name"
git config --global user.email "email"
```
3. 建立git管理文件
```bash{cmd}
git init
```
## 添加文件（add）
1. 建立新文件
```bash{cmd}
touch test.py
```
2. 查看版本库状态
```bash{cmd}
git status
```
3. 将文件添加到版本库中
```bash{cmd}
git add test.py
```
4. 一次性添加文件夹中所有未被添加的文件
```bash{cmd}
git add .
```
## 提交改变（commit）
1. 提交改变
```bash
git commit -m "test.py"
```
## 流程图
![](https://morvanzhou.github.io/static/results/git/2-1-1.png)

## 查看修改

1. 查看日志（修改记录）
```bash
git log
```
2. 查看修改内容（查看还没add的修改部分）
```bash
git diff
```
3. 查看修改内容（查看已经add的修改部分）
```bash
git diff --cached
```
4. 查看修改内容（包括已经add的和没有add的）
```bash
git diff HEAD
```
## 回到过去

1. 从**staged**返回**modified**
```bash
git reset test.py
```
2. **commit**倒退和跳转
```bash
git reset --hard HEAD~3 #倒退三步
```
```bash
git reset --hard 9c65f80 #指定id
```
```bash
git reset --hard HEAD@{0} #指定指针
```
3. 查看**commit id**
```bash
git reflog
```
![](https://morvanzhou.github.io/static/results/git/2-2-1.png)
![](https://morvanzhou.github.io/static/results/git/2-2-2.png)
![](https://morvanzhou.github.io/static/results/git/2-2-3.png)
![](https://morvanzhou.github.io/static/results/git/2-2-4.png)
每次`commit`有自己的`id`, `HEAD`是一个指针，指引当前的状态是哪个`commit`

## 回到过去（文件）

```bash
git checkout 185fe31 -- test.py #前面是commit id 后面是文件
```




