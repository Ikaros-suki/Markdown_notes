### 创建版本库
1. 在某个文件夹内打开 git bash
2. ==git init==
3. ==git add *filename.filetype*==
   (可以一次 add 多个)
4. ==git commit -m *"xxx (输入你想写的注释)"*==

![](image/2022-02-23-21-18-10.png)

---

# 时光机穿梭

* 要随时掌握工作区的状态，
  使用==git status==命令。


* 如果==git status==告诉你有文件被修改过，
  用==git diff==可以查看修改内容。

---

## 版本回退

* HEAD指向的版本就是当前版本，因此，Git允许我们在版本的历史之间穿梭，使用命令==git reset --hard commit_id==。

* 穿梭前，用==git log==可以查看提交历史，以便确定要回退到哪个版本。

* 要重返未来，用==git reflog==查看命令历史，以便确定要回到未来的哪个版本。

---

## 工作区与暂缓区

#### 工作区

* 就是 git 库 所在的文件夹

#### 版本库

* 工作区文件夹内的 .git 文件夹
* git add 就是将文件修改添加到暂存区
* git commit 把暂存区的所有文件提交到当前分支
  
---

## 管理修改

* 每次修改，如果不用git add到暂存区，那就不会加入到commit中。
  
---

## 撤销修改

* 修改完文件, 还没有 add 时, 可以用 ==git restore <file>==
* add 之后, 可以使用 ==git restore --staged <file>==
* ***善用 git status***

---

## 删除文件

* ==git rm== 用于删除 git 库中的文件

---
---


# 远程仓库

在 cmd 中使用 

$ ssh-keygen -t rsa -C "youremail@example.com"

创建 ssh , pub 为公钥

---

## 添加远程库

* 要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；
* 改为使用 ==git remote add origin https==

* 关联一个远程库时必须给远程库指定一个名字，origin是默认习惯命名；

* 关联后，使用命令==git push -u origin master==**第一次**推送master分支的所有内容；

* 此后，每次本地提交后，只要有必要，就可以使用命令==git push origin master==推送最新修改；

* **==SSL certificate problem: unable to get local issuer certificate
    解决方法 : $ git config --global http.sslverify false==**



---

## 从远程库克隆

* 要克隆一个仓库，首先必须知道仓库的地址，然后使用==git clone==命令克隆。

* Git支持多种协议，包括https，但ssh协议速度最快。




