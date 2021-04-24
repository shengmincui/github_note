# Upload Kaggle Material (上传kaggle结果)

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

 1. Create a Branch (创建一个分支)

    ```bash
    git checkout -b test
    ```

 2. Save your changes (保存修改)

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

1. change your branch
2. click Pull request button

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

