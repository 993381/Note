本项目由ffplay.c 4.1移植过来。
ffplay显示视频、音频及线程相关操作用的是SDL库提供的功能，本项目将其替换为了iOS平台相关的API。
移植过程中保留了绝大部分功能，去掉了字幕流(并没有去除完整)，去掉了一些option的初始化。

详细移植过程请参见博客：
https://blog.csdn.net/whoyouare888/article/details/98870898

由于ffmpeg的库文件过大，故放到了别处，下载后，放到项目当中即可。
库文件下载地址：
https://download.csdn.net/download/whoyouare888/11200878
