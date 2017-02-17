## 形状-刚体
### 形状-刚体-关节
创建了box2d世界后，我们需要创建一些刚体和关节添加进去，比如游戏中的边界、元素等，使得世界更丰富一些。

接下来就创造一些基本形状，然后用这些形状组成刚体，刚体又可以进一步组合成关节，换言之，世界即是由刚体和关节组成的世界。

box2d中创建刚体、关节的过程类似于堆积木，由形状构成刚体，由刚体构成关节，稍微不同的地方是，这里的形状可以多次使用，其过程：
`形状 -> 刚体 -> 关节`

此处需要注意的是，box2d只能创建顶点数不超过8的凸多边形。

### 总览  
3. 形状(shape)-刚体(body)  
  [3.1 形状](https://github.com/godbasin/box2djs-tutorial/tree/master/3-body/3-1-shape.md)  
  [3.2 矩形](https://github.com/godbasin/box2djs-tutorial/tree/master/3-body/3-2-box-shape.md)  
  [3.3 圆形](https://github.com/godbasin/box2djs-tutorial/tree/master/3-body/3-3-cicle-shape.md)  
  [3.4 凸多边形](https://github.com/godbasin/box2djs-tutorial/tree/master/3-body/3-4-poly-shape.md)  
  [3.5 由形状到刚体](https://github.com/godbasin/box2djs-tutorial/tree/master/3-body/3-5-shape-to-body.md)  
