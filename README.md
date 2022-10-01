# qweather-ha

**使用restful sensors和Jinja2 templates把和风天气API集成到Home Assistant**

1. 去[和风天气](https://dev.qweather.com/)申请api key，普通版就可以，不需要商业版或开发者身份。
2. 使用Home Assistant插件File Editor编辑 ```/config/configuration.yaml```；其中your location替换为自己的经纬度，不清楚可以使用[高德坐标拾取器](https://lbs.amap.com/tools/picker)查询，得到的结果应该是```116.40,39.90```这样；然后api key替换为第一步中申请到的key。
3. 重启ha服务，就可以在系统中找到来自于qweather api的多个传感器，以及名为HeFeng Weather Station的整体天气服务，可以自由选择、组合并添加到dashboard。
4. 简介比较粗略，不熟悉HA的同学，具体使用过程请参见[博客文档](http://fisherworks.cn/?p=3681)。

<img src="https://user-images.githubusercontent.com/12291644/193386041-e5c89ebc-d904-477a-b5d3-09b030a5642b.png" width = "35%" />
<img src="https://user-images.githubusercontent.com/12291644/193386081-44e3d804-a9b0-4831-baf3-87d22d48d3f5.png" width = "35%" />
