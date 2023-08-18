# Headline

## 安装nodejs
 - 设置国内镜像 npm config set registry https://registry.npmmirror.com
 - npm config set registry https://registry.npmmirror.com
## 安装docsify
 ### npm i docsify-cli -g
 ### 在git上创建项目my-docs
 ### 克隆到本地 git clone git@github.com:zhansc/my-docs.git
 ### 初始化文档工程
  - cd my-docs
  - docsify init ./docs
 ### 本地预览
 - docsify serve docs  // Ctrl + c 或 终端退出会导致服务挂掉
 - setsid docsify serve docs & // 将进程交给后台
 ### 自定义文档
 ### 服务部署
 - 在das-ci平台配置触发规则、部署到docker（每次需要打一个新的镜像，rancher部署，必须手动部署很麻烦）
 - 在linux服务器中增加crontab定时任务，定时每分钟拉一次代码（服务仅md文件变更，不需要部署，执行git pull获取代码即可展示）

[**返回首页**](README.md)

> An awesome project.

### starting
####写一首诗
- 红豆生南国
- 春来发几枝
- 劝君多采撷
- 此物最相思

####写一句话
 - 爱

