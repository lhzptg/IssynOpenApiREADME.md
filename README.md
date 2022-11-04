# MCQUIC.COM 开放平台

## 注意事项

> 请勿恶意访问，关小黑屋无法恢复
>
> 本项目长期且免费提供服务
> 
> 邮箱：itobj@itobj.anonaddy.com
> 
> Telegram : https://t.me/tcpisopen
>
> 正在开放更多API，或联系站长反馈API

## 域名

https://api.mcquic.com   新域名

https://api.itobj.net   （该域名与	2023-08-13日停止服务）

## 接口列表

- 获取15天天气预报

>
>路由：/op-api/v1/weather/{城市id}  (101300511)
>
>方法：get
>
>返回json：
>
>

- 根据ipv4获取地理地址

>
>路由: /op-api/v1/ip/location?ip={ip4或ip6}   (8.8.8.8)
>
>方法: get
>
>返回 json:
> 
>

- 获取天气城市编码 每天自动更新 天气网编码

>
>路由: /op-api/v1/weather/city/list 
>
>方法: get
>
> 参数：
>  name | 选项 | string  | 城市名称，like查询
> 
>返回 json:
>
>

- 随机获取代理ip池

>
>路由: /op-api/v1/ip/pool/random
>
>方法: get
>
>返回 json:
>
> 
  
