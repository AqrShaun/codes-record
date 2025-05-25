# Git学习笔记

## 学习资料来源
- [如何学习git版本管理 - 编程学习网](https://www.528045.com/question/185905316705.html)
- [自动化学习 - 使用git进行版本管理 - CSDN博客](https://blog.csdn.net/m066501929/article/details/146007457)

## git版本学习
### 1. 什么是git
git简单来说就是一个代码管理工具，它可以用来进行版本控制，多人协作以及分支管理，也叫做分布式版本控制系统。
#### 流程
- 1.从远程仓库中克隆(clone)代码到本地仓库；
- 2.从本地仓库中检出(git checkout)一个分支进行修订；
- 将代码提交(git add)到暂存区；
- 将代码提交(git commit)到本地仓库；
- 将远程库代码拉(git pull)到本地仓库并自动进行合并，然后放到到工作区，确保本地仓库有远程仓库的所有代码
- 修改完成后，将代码推送（git push）到远程仓库

### 2.git如何使用
#### git的下载安装和配置
- [git下载地址](Git  https://git-scm.com/)
- [安装git](https://blog.csdn.net/orange228/article/details/79365795)
- [Git下载安装及设置详细教程](https://blog.csdn.net/sanxd/article/details/82624127)
## 实践流程
1. 安装Git
2. 创建本地仓库
3. 注册GitHub账号
4. 推送代码到远程仓库

## 遇到的困难及解决方法
- **问题**：无法推送代码到远程仓库
- **解决**：检查SSH密钥配置，重新生成密钥并添加到GitHub

## 心得体会
Git让代码管理更加高效，分支功能尤其适合团队协作，未来需要进一步学习高级命令和协作技巧。
