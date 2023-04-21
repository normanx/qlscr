# 青龙面板自动脚本

## 联通自动签到chinaUnicom.js

抓取联通App的数据包，查找 https://m.client.10010.com/mobileService/onLine.htm 的POST包，从请求数据中找到token\_online字段，将对应的值复制出来，在青龙面板的环境变量管理中新建chinaUnicomCookie项，值填入从抓包中得到的token_online字段内容，然后保存。
