# AutoAddto
Content Assist —— 轻量 输入建议 插件，支持中文拼音、异步请求数据

###options###
```html
data: [],//匹配的数据数组
sourceUrl: null,//异步请求数据url，不为空时data无效
cache: true,//异步请求的数据是否缓存
result: true,//是否显示结果数等信息
noReturnText: "no result",//没有找到结果时文字
returnTemplete: null//自定义返回模板
```
###method###
+ setData(dataArray);//设置数据