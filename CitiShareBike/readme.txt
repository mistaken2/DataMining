地图热力图实现：
1、使用百度地图api和Heatmap_min.js，初始化BMap和BMapLib(对应04)；
2、使用百度地图api和echarts.js，初始化echarts(对应02)。


热力图使用json格式：
[{"lat": 40.73221853, "count": 84, "lng": -73.98165557},...]
路径图使用json格式：
[{"slng": -73.97634151, "elat": 40.76590936, "slat": 40.76590936, "count": 74, "elng": -73.97634151},...]

目前的问题：
1、结束点图标位置在垂直方向上的不对应终止点；
2、绘制的路径直线不太美观，虽然使用宽度表示单车使用情况，但是效果不佳；
3、箭头的效果较差。