# mapboxgl-measure-control
基于mapboxgl的测绘插件  <br >
单击测距按钮开始测距，双击地图结束测距。  <br>
采用Mapbox-gl 的官方IControl的方式。<br>
在浏览器中打开 [example/index.html](./example/index.html) 运行示例<br>

```js
var MeasureControl = new MeasureControl();
map.addControl(MeasureControl, 'top-left');
```