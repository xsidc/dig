# dig
检查落地机返回DNS IP

安装依赖软件包
yum install -y bind-utils

在落地机中测试返回DNS IP
dig @填写DNSIP 填写检测网址
比如
dig @123.123.123.123 twitter.com
