======================================================================

说明：

本SDK仅供参考学习，方便自动化下单

======================================================================

安装部署：

系统需求：Windows或Linux系统或Mac，python2或python3

下载后解压缩即可，不需要安装运行券商交易客户端

Windows命令行运行stock_live_trade.exe

Linux或Mac系统命令行运行 wine stock_live_trade.exe，Linux和Mac系统需安装wine，可在命令行参数指定监听端口，例： stock_live_trade.exe 0.0.0.0 58888

命令行运行pip install thrift

将alpha_live_trade.py和alpha_trade目录拷贝到自己源代码目录，import alpha_live_trade即可使用

解压目录下的example目录中是例子代码，推荐使用pycharm编辑调试代码

vs2015及以上，需要thrift，libevent，boost，zlib，openssl

=============================================================================

