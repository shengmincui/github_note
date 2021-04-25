# Upload Kaggle Material (上传kaggle结果)



## Download and Install git (下载和安装git)

1. link (链接): https://git-scm.com/



## Sign up GitHub

1. link (链接): https://github.com/



## Fork the Project

1. open link (打开链接): https://github.com/seculayer/AI_Competitions_2
2. click Fork button (点击Fork):

![fork](./img/fork.jpg)





## Clone the Project

1. open cmd or terminal (打开命令提示符(windows)或者终端(mac or linux))

```bash
git clone https://github.com/shengmincui/AI_Competitions_2.git
```

![clonelink](./img/clonelink.jpg)



## Prepare your kaggle files

![](./img/kagglefile.jpg)



## Submit Your Files (提交你的文件)

 1. Config your GitHub information

    ```bash
    git config --global user.email "your@example.com"
    git config --global user.name "Your Name"
    ```

 2. Create a Branch (创建一个分支)

    ```bash
    git checkout -b test
    ```

 3. Save your changes (保存修改)

    ```bash
    git add .
    ```

    3. Commit our change to the branch (将修改内容提交到分支)

    ```bash
    git commit -m "Hanyang University Your name"
    ```

    4. Push your branch to you GitHub fork (将分支推送到GitHub的副本中)

    ```bash
    git push origin test
    ```



## Pull Request

1. open your github link: https://github.com/shengmincui/AI_Competitions_2
2. change your branch
3. click Pull request button

![](./img/pullrequest1.jpg)



## Update from Forked Project (更新你派生的仓库)

1. Return to your branch (回到你设定的分支)

```bash
git checkout test
```

2. Fetch changes from forked project and merge them into your branch (从源仓库获取更改并且合并到你的分支)

```bash
git pull https://github.com/seculayer/AI_Competitions_2.git
```

3. Push your branch to origin (将你的分支推送到origin)

```bash
git push origin test
```



## Reference (参考)

[Seculayer AI_competitions_2](https://github.com/seculayer/AI_Competitions_2)

[Progit section 6.2 contributing to a Project (English)](https://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project)

[Progit section 6.2 contributing to a Project (Chinese)](https://git-scm.com/book/zh/v2/GitHub-%E5%AF%B9%E9%A1%B9%E7%9B%AE%E5%81%9A%E5%87%BA%E8%B4%A1%E7%8C%AE)