# vue
1. 更新你已经安装的NPM库，这个很简单，只需要运行。
npm update –g or npm install -g npm

2. 更新Nodejs自身，只需要运行以下2个命令即可：
npm install –g n
n latest

3.安装淘宝 NPM 镜像
npm install-g cnpm --registry=https://registry.npm.taobao.org 

4.vue项目构建
不用镜像时：
# 全局安装 vue-cli
$ npm install --global vue-cli
# 创建一个基于 webpack 模板的新项目
$ vue init webpack my-project
# 安装依赖，走你
$ cd my-project
$ npm install
$ npm run dev
使用淘宝镜像时：npm换成cnpm
