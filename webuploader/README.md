## 本文学习 分片下载 


用webuploader对文件进行分片，多线程上传，最后再合并文件。

1 同名但是不同内容的文件上传 如何处理？ 

解决方案，使用时间戳做文件夹名，取得时候从对应的时间戳文件夹中取出。