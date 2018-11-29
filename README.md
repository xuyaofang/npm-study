# npm-study
npm 是 Nodejs 的包管理工具

## npm 安装模块

##### 自动把模块和版本号添加到dependencies部分:
> npm install module-name -save
##### 自动把模块和版本号添加到devdependencies部分:
> npm install module-name -save-dev

至于配置文件区分这俩部分，是用于区别开发依赖模块和产品依赖模块，常见 devDepandencies主要是配置测试框架， 例如jshint、mocha。

> npm install --production , 只安装package.json中dependdencies部分的模块

> npm install ，则package.json中指定的dependencies和devDependencies都会被自动安装进来

#### npm 参数
```
-S, --save: Package will appear in your dependencies.
-D, --save-dev: Package will appear in your devDependencies.
-O, --save-optional: Package will appear in your optionalDependencies.
```
