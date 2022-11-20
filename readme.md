# Simple HTTP Server

![screenshot](screenshot.png)

基于 [UniIsland 的 Gist](https://gist.github.com/UniIsland/3346170) 和 [Tallguy297/SimpleHTTPServerWithUpload](https://github.com/Tallguy297/SimpleHTTPServerWithUpload) 的代码，稍作修改：
1. 移除了图标
2. 解决了 Ctrl-C 退出后立刻重启，提示 `port already in use` 的问题
3. 增加文本保存功能
4. 完全 UTF-8 化（除二进制文件下载/上传外）

- 适用：临时、局域网内、小文件
- 不适用：长时间运行、大文件量、高并发、面向外部网络开放、需要安全性保证
---

Based on code of [UniIsland's Gist](https://gist.github.com/UniIsland/3346170) and [Tallguy297/SimpleHTTPServerWithUpload](https://github.com/Tallguy297/SimpleHTTPServerWithUpload), with slight modification for my own use case:
1. Removes the icons
2. Fix the bug that if the script is stopped using Ctrl-C and immediately restarted, it will fail with `port already in use`
3. Add the ability to quickly save text to a text file
4. Enable UTF-8 encoding everywhere (beside actual binary file download / upload)

- For: temporary, local lan network, small files
- Not for: long term, large file, high concurrency, exposed to external network, security needed
