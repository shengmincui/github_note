# Upload Kaggle Material (上传kaggle结果)



## Download and Install git (下载和安装git)

1. link (链接): https://git-scm.com/
2. 配置git环境变量

![systemenviroment](./img/systemenviroment.png)

## Sign up GitHub

1. link (链接): https://github.com/



## Fork the Project

1. open link (打开链接): https://github.com/seculayer/AI_Competitions_2
2. click Fork button (点击Fork):

![fork](./img/fork.jpg)

3. Fork之后会进入自己的github仓库，如图，自己的仓库中出现了AI_Competitions_2的项目

   ![myproject](./img/myproject.png)



## Clone the Project

1. open cmd or terminal (打开命令提示符(windows)或者终端(mac or linux))

```bash
git clone https://github.com/shengmincui/AI_Competitions_2.git
```

![clonelink](./img/clonelink.jpg)

2. AI_Competitions_2文件夹已经成功下载到本地

## Prepare your kaggle files

![](./img/kagglefile.jpg)

1. 将需要提交的所有文件放在一个文件夹里，命名为kaggle比赛的ID(注意：ID不等于比赛名字，ID可以在对应URL中找到)

   ![projectfile](./img/projectfile.png)

2. 将整个文件放到下载的AI_Competitions_2/kaggle中

   ![file](./img/file.png)



## Submit Your Files (提交你的文件)

 1. 进入终端，进入到AI_Competitions_2路径

    ![cmd-AI](./img/cmd-AI.png)

 2. Create a Branch (创建并进入一个分支)

    命令为 git checkout -b 分支名

    ```bash
    git checkout -b test
    ```

 3. Save your changes (保存修改)

    ```bash
    git add .
    ```

    4. Commit our change to the branch (将修改内容提交到分支)

    ```bash
    git commit -m "Hanyang University Your name"
    ```

    5. Push your branch to you GitHub fork (将分支推送到GitHub的副本中)

    ```bash
    git push origin test
    ```

6. push的时候，会让你输入你的github信息，按要求输入即可

7. 打开你的github，会看到你创建的分支

   ![branch](./img/branch.png)

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