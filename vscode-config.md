## 官网下载安装vscode

## 下载插件
* Beautify
* ESLint
* Vetur
* 根据自己的习惯可下载快捷键方式Sublime Text Keymap and Settings Importer 



## 安装npm依赖包

* 支持vue eslint

```bash
$ npm install -g eslint-plugin-html
```



## 修改设置`文件-首选项-设置`
* 格式化vue时4格缩进
```json
{
    "editor.fontSize": 14,
    "editor.tabSize": 4,
    "editor.wordWrap": "on", // 自动换行
    "editor.formatOnPaste": true, // 粘贴时格式化
    "editor.multiCursorModifier": "ctrlCmd", // 按ctrl键多点编辑
    "javascript.updateImportsOnFileMove.enabled": "always",
    "prettier.tabWidth": 4, // 设置格式化文件缩进为4
    "prettier.semi": false, // 格式化文件不加分号
    "prettier.singleQuote": true, // 格式化文件把双引号替换Wie单引号
    "vetur.format.defaultFormatter.html": "prettier", // 格式化vue文件时，template部分也统一缩进
    "eslint.options": {
        "configFile": "C:/Users/xpj/.eslintrc.js",
        "plugins": ["html"]
    },
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        "html",
        "vue"
    ],
    "editor.detectIndentation": false, // 所有文件统一缩进
    "terminal.integrated.shell.windows": "D:\\Program File\\Git\\git-bash.exe" // 替代默认控制台
}
```

