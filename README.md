# 使用GitHub pages + Hexo 快速搭建个性化博客，[访问地址](https://hemin1003.github.io/)

## 工具使用
使用hexo搭建，主题使用next

## 环境搭建
1. 先安装[nodeJS](https://nodejs.org/en/)和[Git客户端](https://desktop.github.com/)，然后git clone该工程

2. 进入blogweb目录，npm install （下载依赖包）建议先配置一个淘宝npm下载镜像地址：[https://npm.taobao.org/](https://npm.taobao.org/)

3. hexo generate（生成项目静态资源）

4. hexo server（启动服务），访问地址：[http://localhost:4000/](http://localhost:4000/)
![avatar](/source/uploads/intro.png)

## 将本地文件部署到GitHub

1. npm install hexo-deployer-git --save

2. hexo clean

3. hexo generate

4. hexo deploy

## 参考资源
[http://blog.csdn.net/qq_23435721/article/details/50875579](http://blog.csdn.net/qq_23435721/article/details/50875579)