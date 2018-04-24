# 基于hexo搭建于github的blog相关说明

## 分支说明
- master 展示在zzzyyj.github.io对应的静态网页文件，仅作为预览
- hexo   项目对应的源代码，相关操作均在该分支上

## 常用指令
- `hexo server` 启动本地服务器，默认为http://localhost:4000/
- `hexo generate` 生成静态文件 
  - -d, --deploy 文件生成后立即部署网站
  - -w, --watch	监视文件变动
  - `hexo g` 简写：生成静态文件
- `hexo deploy --generate` 部署网站，部署之前先预生成静态文件
  - `hexo d -g` 简写：部署网站，部署之前先预生成静态文件
- `hexo clean` 清除缓存文件 (db.json) 和已生成的静态文件 (public)

## 备注
- [hexo官网](https://hexo.io/) 
- [hexo中文网站](https://hexo.io/zh-cn/)

