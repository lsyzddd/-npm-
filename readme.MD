## 使用npm-check命令检查、更新依赖包（全局和局部）

## 1.安装npm-check（全局目录安装）
`npm install -g npm-check`

## 2.npm全局更新包（全局目录）
`npm-check -u -g`

> 通过上下键可以移动光标，使用空格键可以选择需要处理的包，回车直接进行处理。
>
## 3.更新某个项目的包（项目目录）
`npm-check -u`
> 通过上下键可以移动光标，使用空格键可以选择需要处理的包，回车直接进行处理。

> 通过npm-check -u 就可以，不需要--save就可以直接更新package.json里面的内容

## 4.npm更新单个全局包
`npm update <name> -g`

## 5.更新项目生产依赖包
`npm update <name> --save`

## 6.更新项目开发环境依赖包
`npm update <name> --save-dev`

## 7.npm查找全局安装过的包
`npm ls -g --depth 0`
