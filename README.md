# Issyn.com 开放平台

## 注意事项

> 请勿恶意访问，关小黑屋无法恢复
>
> 本项目长期且免费提供服务

> 正在开放更多API，或联系站长反馈API

## 域名

https://openapi.issyn.com 

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
>  name | 选填 | string  | 城市名称，like查询
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

- 获取笑话

>
>路由: /op-api/v1/joke
>
>方法: get
>
> 参数：
>  type | 选填 | string  |  joke= 笑话， loveStory=土味情话，sentence=词霸每日一句，motto= 格言
>
>返回 json:
>
>


- 生成短链接

>
>路由: /op-api/v1/url/short
>
>方法: post
>
> 参数：
>  url | 必填 | string  |  跳转的目标地址 与http 开头
>
>返回 json:
>
>
