## 文件增量同步-rsync算法 demo

以浏览器作为新文件，同步给服务端为例子。

若服务端作为新文件，同步给客户端，则需调整内容，相同块取自本地文件，不同块通过http range请求.