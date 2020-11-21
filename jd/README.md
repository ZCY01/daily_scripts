# 价格保护

## Node 用户
```
# 在 scripts 目录下安装 jsdom 即可，如在安装过程中缺少其他依赖，请自行安装
npm install jsdom
```

## Quantumulx 用户
请配置 token

token的获取方式：

qx 配置抓token，可以抓网页:[价格保护](https://msitepp-fm.jd.com/rest/priceprophone/priceProPhoneMenu)或者APP，刷新一次获取一个Token

```
[rewrite_local]
https:\/\/api\.m\.jd\.com\/api\?appid=siteppM&functionId=siteppM_priceskusPull url script-request-body https://raw.githubusercontent.com/ZCY01/daily_scripts/main/jd/jd_priceProtectRewrite.js
```