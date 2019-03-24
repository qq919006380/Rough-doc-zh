[英文文档](https://github.com/pshihn/rough/wiki)

## 安装

```
npm install --save roughjs
```

## 引入

```
import rough from "roughjs";
```

## API

- line (x1, y1, x2, y2 [, options]) ————线
- rectangle (x, y, width, height [, options]) ———— 长方形
- ellipse (x, y, width, height [, options]) ————椭圆
- circle (x, y, diameter [, options]) ———— 圆形
- linearPath (points [, options]) ———— 线 path
- polygon (vertices [, options]) ————多边形
- arc (x, y, width, height, start, stop, closed [, options]) ————弧
- curve (points [, options]) ————曲线
- path (d [, options]) ———— 路径
- draw (drawable) ———— 画

## Options 选项

- roughness ———— 粗糙(type：Number)
- bowing ————弯曲(type:Number)
- stroke ———— 边框颜色(type:string)
- strokeWidth ———— 边框粗细(type:Number)
- fill ————填充的颜色(type:string)
- fillStyle ————填充风格
  - hachure ————影线
  - solid ———— 实心
  - zigzag ———— Z字形的
  - cross-hatch ———— 交叉影线
  - dots ———— 点
  - sunburst ————
  - dashed ———— 虚线
  - zigzag-line ————Z字形的线
- fillWeight ———— 填充线的粗细
    - 默认值设置为该形状的笔划宽度(strokeWidth)的一半。
- hachureAngle
    - 定义Hachure线角度的数值（以度为单位）。默认值为-41度。
- hachureGap
- curveStepCount
- simplification
- dashOffset
- dashGap
- zigzagOffset

## Config 配置
