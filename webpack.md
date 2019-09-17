# ***webpack***

### 一.工程化目录结构

> webpack基本目录结构
>
> src(源码文件夹)
>
> dist(打包后文件目录)
>
> package.json(项目依赖以及配置webpack部分命令)
>
> webpack.config.js(打包配置文件)

### 二.webpack的安装

> 推荐项目本地安装,便于分割管理
>
> 安装命令:cnpm i webpack webpack-cli -D (4.0已经分隔开两个包,都需要安装)

### 三.webpack命令的使用

> 因为webpack会装在当前目录的依赖文件夹(node_modules)下的bin目录下,所以无法在当前目录直接执行命令
> 
> 解决方法:
>
> 1.npx 可以直接运行node_modules/bin目录下的命令
>
> 2.配置package.json中的script