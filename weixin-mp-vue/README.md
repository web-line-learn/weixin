# mpvue 小程序框架demo
- [参考文档](http://mpvue.com/mpvue/)
## 快速使用
    # 全局安装 vue-cli
    $ npm install --global vue-cli
    # 创建一个基于 mpvue-quickstart 模板的新项目
    $ vue init mpvue/mpvue-quickstart xeixin-mp
    # 安装依赖
    $ cd my-project
    $ npm install
    # 启动构建
    $ npm run dev

- 使用微信开发者工具引入到项目即可 [开发者工具下载](https://developers.weixin.qq.com/miniprogram/dev/quickstart/basic/getting-started.html#%E5%AE%89%E8%A3%85%E5%BC%80%E5%8F%91%E5%B7%A5%E5%85%B7)


## api 总结
1. 如何获取小程序在 page onLoad 时候传递的 options
在所有 页面 的组件内可以通过 this.$root.$mp.query 进行获取。
2. 如何获取小程序在 app onLaunch/onShow 时候传递的 options
在所有的组件内可以通过 this.$root.$mp.appOptions 进行获取。

开始用vue开发风格写小程序吧


