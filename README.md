## sublime text

### 同步配置

* clone本项目到本地某一路径下
* 打开sublime，安装`package syncing`包
* `ctrl+shift+p`输入`Package Syncing: Define Sync Folder`设置为项目里的sublime-text目录



### 全局安装依赖

```bash
$ npm install -g prettier
$ npm install -g eslint
```



### 配置

* 生成eslint配置：在项目根目录下配置，运行`eslint --init`



## 其他
### git
* 设置用户名和邮箱
```bash
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
```
* 生成公钥和私钥
```bash
$ ssh-keygen -t rsa -C "youremail@example.com"
```


### cmder
* 解决中文乱码
在Settings > Startup > Environment里添加：set LANG=zh_CN.UTF8

* 添加到右键菜单中
路径在是在当前目录路径， 在管理员权限的终端 输入以下语句即可:
```bash
Cmder.exe /REGISTER ALL
```

### npm

* 更新

```bash
$ npm install npm -g
```

* 使用淘宝NPM镜像

```bash
$ npm install -g cnpm --registry=https://registry.npm.taobao.org
```

> 然后可以直接使用cnpm代替npm



### webpack

安装最新版本或特定版本

```bash
$ npm install --save-dev webpack
$ npm install --save-dev webpack@<version>
```

如果使用 webpack 4+ 版本，你还需要安装 CLI。

```bash
$ npm install --save-dev webpack-cli
```

> **不推荐**全局安装 webpack。这会将你项目中的 webpack 锁定到指定版本，并且在使用不同的 webpack 版本的项目中，可能会导致构建失败 



### Vue

* 全局安装`vue-cli`

```bash
$ npm install -g @vue/cli
```

* 初始化项目

```bash
$ vue create [项目名]
```



### React

* 安装`create-react-app`

```bash
$ npm install -g create-react-app
```

* 初始化项目

```bash
$ create-react-app my-app
```

* 弹出配置文件

```bash
$ npm run eject
```



## 参考链接

* [淘宝 NPM 镜像](https://npm.taobao.org/)
* [vue-cli](https://cli.vuejs.org/guide/creating-a-project.html#installation)

