## sublime text
### 初始化
* `ctrl+shift+p`输入package control，然后install它
* 安装完`package control`后，`ctrl+shift+p`输入`install package`回车，输入`package syncing`然后安装

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
* 配置HTML/CSS/JS Prettify插件使之支持vue格式化，在tools->HTML/CSS/JS Prettify-> set node path里面的在"allowed_file_extensions": ["htm", "html", "xhtml", "shtml", "xml", "svg","vue"] 加上vue就好

> 来源：https://segmentfault.com/q/1010000004221470
