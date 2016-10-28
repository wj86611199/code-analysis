# code-analysis

## Menu

### [blazy](https://github.com/dinbror/blazy)

> 源码分析戳这里：[blazy analysis](./analysis/blazy.js)

一个基于 jQuery 的图片懒加载插件。其特性有：

- 首屏图片异步加载
- 可根据预设和是否是 retina 屏幕加载高清图片
- 可进行视频懒加载

值得学习的方面：

- 针对低版本浏览器的兼容性处理，在没有某些 API 时（例如 querySelectorAll）则进行创建
- 检测模块引入方式，以不同方式进行模块暴露
- 构造类 jQuery 的 helper
- 绑定/解绑事件

### [redux](https://github.com/reactjs/redux)

> 源码分析戳这里：[redux analysis](https://github.com/ecmadao/Coding-Guide/blob/master/Notes/React/Redux/Redux%E5%85%A5%E5%9D%91%E8%BF%9B%E9%98%B6-%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90.md)

全球知名女主播。啊不，知名函数式插件，性感。

值得学习的方面：

- 函数式编程思想。柯里化、代码组合。。

### [notification-logger](https://github.com/hkirat/notification-logger)

> 源码分析戳这里：[notification-logger analysis](./analysis/notification/notification-logger.js)

一个将`console.log`转换为浏览器`Notification`的插件，功能比较简单，代码很短便于学习。

值得学习的方面：

- 对原生方法的覆盖
- 原生方法的缓存
- 浏览器`Notification`API的使用

### [nprogress]()

> 源码分析戳这里：[nprogress analysis](./analysis/nprogress.js)

一个在页面（或特定容器）顶部创建进度条的插件。

值得学习的方面：

- 代码结构
- 获取浏览器支持的兼容性 CSS
- 递归调用 func
- 构造类似 jQuery API 的函数

## Author

[ecmadao](https://github.com/ecmadao)

## License

MIT
