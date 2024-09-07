# 动态 HTML 模板

在本书的这一部分中，我们将集中精力在一些适当的 HTML 页面中显示来自 MySQL 数据库的动态数据。

你将学习如何：

- 通过简单、可扩展且类型安全的方式[将动态数据传递到你的 HTML 模板。](./5.1 显示动态数据.md)
- 使用Go包中的各种[动作和函数](05.02-template-actions-and-functions.html)`html/template`来控制动态数据的显示。
- 创建[模板缓存](05.03-caching-templates.html)，这样你的模板就不会从磁盘读取并针对每个 HTTP 请求进行解析。
- 在运行时优雅地处理[模板渲染错误](05.04-catching-runtime-errors.html)。
- [实现一种将常见动态数据](05.05-common-dynamic-data.html)传递到网页而无需重复代码的模式。
- 创建你自己的[自定义函数](05.06-custom-template-functions.html)来格式化和显示 HTML 模板中的数据。
