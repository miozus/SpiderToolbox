# 🕷️ 爬虫零件箱

> SpiderToolbox : Cute Spider toolbox by autohotkey

提供零件，可组合零件实现浏览器爬虫：点击网页元素，下载资源的自动化机器人。

适用场景：

- 害怕 Python 爬虫而封禁IP，或解析资源路径困难。
- 可复制的网页预览的文件（非图片）
- 上万条记录，需要人工点击下载。

```bash
CapslockMagic\bin\util
├── Timer.ahk         # 时间动画: 挂机运行非静止画面
├── FilePipe.ahk      # 文件管道：导入导出和文件名添加日期
├── FileStream.ahk    # 文件流：增删改查
├── Interceptor.ahk   # 过滤器：不必每个点开看
├── Internet.ahk      # 网络测试：是否断网
├── Locator.ahk       # 定位器：网页元素坐标
└── Logger.ahk        # 日志：每条记录处理过程和结果
```

日志示例：每个表情代表执行了一种管道操作

``` bash
[2022-12-12 05:18:44] 4582-8 🙈 *** empty file
[2022-12-12 05:20:38] 4591-2 🐘 *** too big size
[2022-12-12 16:06:50] 4: ✅: source => destination | well-done
[2022-12-12 16:33:57] 9: 🈚⭐🐞: source ⇒ destination | not exist & create file & bug
```

