# 在Gitlab Pages上部署静态网站

## 一、Gitlab Pages功能
用来发布静态网站，并且是自动化地更新发布。每次有文件提交到Gitlab上，Gitlab Pages都会自动构建并发布更新网站。

## 二、准备
### 1、Gitlab开启Pages功能
编辑 /etc/gitlab/gitlab.rb文件，修改如下两行


