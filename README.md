# AutoAddto
Content Assist —— 输入建议，支持中文拼音

###options###
```html
auto: false,//是否自动开始
type: "text",//目标变色类型：text、background、border
changeChildren: false,//是否以所有子元素作为变色对象
randomcolor: false,//是否随机生成颜色
interval: 200,//变色频率
normalcolor: '#000',//目标原始颜色
colors: [
    '#00ffff',
    '#f1c40f',
    '#3498db',
    '#000000',
    '#1abc9c',
    '#e67e22',
    '#95a5a6',
    '#ffffff',
    '#2ecc71',
    '#f00000'
],//指定颜色集合，randomcolor=false时有效
randomshow: false,//是否随机展示指定的颜色集合
pause: true//是否支持点击目标暂停/恢复
```