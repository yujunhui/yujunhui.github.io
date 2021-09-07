---
title: 关闭 windows 视频文件预览
date: 2021-07-18 17:53:11
tags: 
  - windows
categories: 
---

最近在 youtube 上面下载了一些视频, 都是 ts 格式的, 在我的 windows 上会显示预览图, 但是我并不需要这个预览图, 可以从注册表删一些条目, 从而 windows 就不会为这类文件生成预览图.

文件是 ts 格式的, 也就是后缀是 .ts, 在注册表找到 `HKEY_CLASSES_ROOT\.ts\ShellEx`, 然后把它删掉即可. 删除前可以做一次导出备份.

----

参考:

- [教你如何关闭Win7视频预览节约资源](https://blog.csdn.net/afiych/article/details/72858721)
