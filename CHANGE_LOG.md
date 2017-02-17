## AMap 和 GoogleMap 的不同

- AMap 不支持的 map_types:
```
  "hybrid", AMap.MAP_TYPE_HYBRID,
  "terrain", AMap.MAP_TYPE_TERRAIN,
  "none", AMap.MAP_TYPE_NONE
```

- AMap 新增加的 map_types:
```
  "navi", AMap.MAP_TYPE_NAVI,
  "night", AMap.MAP_TYPE_NIGHT
```

- Polygon 不支持属性`geodesic`

- Polygon 不支持`click`

- Polyline 不支持`click`

- Map 不支持`toolbarEnabled`

- Map 的`customMapStyleString`属性替换成`customMapStylePath`

- marker 不支持 `calloutAnchor`

- 不支持`liteMode`
