# 哈希值竞猜源码纯合约的返奖源码

转账功能#!/bin/bashPATH=/bin:/sbin:/usr/bin:/usr/local/bin:/usr/sbinstep=5 #间隔的秒数，不能大于10for (( i = 0; i &lt; 60; i=(i+step) )); docurl http://xxx/index/wpay/auto_transfer3curl http://xxx/index/wpay/auto_transfer2curl http://xxx/index/wpay/auto_transfer1sleep $stepdoneexit 0监听收款#!/bin/bashPATH=/bin:/sbin:/usr/bin:/usr/local/bin:/usr/sbinstep=3 #间隔的秒数，不能大于10for (( i = 0; i &lt; 60; i=(i+step) )); docurl http://xxx/index/wpay/index3curl http://xxx/index/wpay/index2curl http://xxx/index/wpay/index1sleep $stepdoneexit 0xxx改成你的域名玩法有index3 单双index2 尾数index1 牛牛返奖私钥和监听充值地址修改/application/index/controller/wxpay.php返奖地址和私钥在25和26行配置监听充值玩法地址在200行以后配置，具体在哪里你们自己找吧，都在wxpay.php这个文件


<p style="color: red;">源代码下载地址：<a href="https://mega-file.org/haliN" style="color: red;">https://mega-file.org/haliN</a></p>