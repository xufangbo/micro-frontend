# 安装说明
1. 安装 lerna：npm install -g lerna
2. 进入根目录安装依赖包：lerna bootstrap
3. 启动portal：cd packages/portal && yarn start
4. 启动main：cd packages/main && yarn start
5. 启动app1：cd packages/app1 && yarn start
6. 启动app2：cd packages/app2 && yarn start
7. 打开浏览器访问： localhost:8000
# 项目说明
|编号|名称|端口|说明
|---|---|---|--|
|01|portal|8000|启动项目|
|02|main|8001||
|03|app1|8002|webpack.config.js中配置端口|
|04|app2|8003|webpack.config.js中配置端口|

# 技术笔记

# 其他
1. webpack的原理需要深入研究