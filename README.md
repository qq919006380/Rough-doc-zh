[英文文档](https://github.com/pshihn/rough/wiki)

### 安装

```
npm install --save roughjs
```

### 在parcel中引入

```
import rough from "roughjs/dist/rough.umd";
```

### API

- line (x1, y1, x2, y2 [, options]) ————线
- rectangle (x, y, width, height [, options]) ———— 长方形
- ellipse (x, y, width, height [, options]) ————椭圆
- circle (x, y, diameter [, options]) ———— 圆形 
- linearPath (points [, options]) ———— 线path
- polygon (vertices [, options]) ————多边形
- arc (x, y, width, height, start, stop, closed [, options]) ————弧
- curve (points [, options]) ————曲线
- path (d [, options]) ———— 路径
- draw (drawable) ———— 画

### Options

- roughness ———— 粗糙
  - type：Number
- bowing ————弯曲
- 



git remote add origin git@github.com:qq919006380/repo-name.git
git remote add origin git@github.com:qq919006380/Rough-doc-zh.git