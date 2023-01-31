# 文件介绍
shims-vue.d.ts文件 ts声明.vue类型文件的模块
tsconfig.json文件 配置vue支持JSX语法
## 第一节思考
### 如何使用vite从零搭建vue开发环境
> pnpm init 包环境
> 安装vite(vite是一个开发服务器), 并使用index.html测试vite是否正常
> package.json中设置vite启动命令
> 安装vue包, vite只支持vue render函数渲染,template语法需要安装plugin-vue插件 JSX语法需要安装plugin-vue-jsx插件, 插件安装完成后需要再vite.config.ts文件中配置
> index.ts文件为index.html入口文件
> 写完vue组件或这JSX组件后, 挂载到vue App实例上

### 
