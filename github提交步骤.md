# github提交步骤

## 一、常用命令

1. ### git init

    ```shell
   git init
   初始化github环境
    ```

   

2. ### git config

   ```shell
    git config --global user.name "1064606601xiaopang1"     (GitHub相对应的帐号名称)
   
    git config --global user.email "g19922832335@163.com"  （GitHbu相对应的邮箱帐号）
   ```

3. ### git add .

   ```shell
   git add .
   将所需要提交的代码添加
   ```

4. ### git status

   ```shell
   git status
   查看代码状态
   ```

5. ### git commit -m ''

   ```shell
   git commit -m 
   设置当前提交代码的解释
   ```

6. ### git push -u origin master

   ```shell
   git push -u origin master
   推送到分支上
   ```



## 二、扩展命令

### 	1.更改当前仓库地址

```shell
# 删除当前关联origin的远程库
git remote rm origin 
## 报错 error Could not remove config section
修改gitconfig内容  
删除remote “origin”一行

# 添加远程地址
git remote add origin github地址
```

### 	2.查看当前文件推送地址

```shell
$ git remote -v
# 来源
origin  git@github.com:1064606601xiaopang1/springcloud.git (fetch)  
# 推送
origin  git@github.com:1064606601xiaopang1/springcloud.git (push)
```

