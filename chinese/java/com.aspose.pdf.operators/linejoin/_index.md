---
title: "LineJoin"
linktitle: "LineJoin"
second_title: "Aspose.PDF for Java API 参考"
description: "线段连接样式应指定在描边路径拐角处使用的形状。"
type: docs
weight: 370
url: /zh/java/com.aspose.pdf.operators/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.Enum, com.aspose.pdf.operators.LineJoin

```
public final class LineJoin extends com.aspose.ms.System.Enum
```

线段连接样式应指定在描边路径拐角处使用的形状。

## 字段

| 字段 | 描述 |
| --- | --- |
| [BevelJoin](#BevelJoin) | 斜角连接。两个线段应使用平头帽结束（参见 8.4.3.3，"Line Cap Style"），并且线段末端之外产生的缺口应填充为三角形。 |
| [MiterJoin](#MiterJoin) | 斜接连接。两个线段的笔画外缘应延伸直至在某个角度相交，类似相框。如果线段相交角度过锐，依据斜接限制参数（参见 8.4.3.5，"Miter Limit"），则改用斜角连接。 |
| [RoundJoin](#RoundJoin) | 圆角连接。以与线宽相等直径的圆弧围绕两个线段相交点绘制，连接两个线段的笔画外缘。该扇形应填充，从而形成圆润的拐角。 |

### BevelJoin {#BevelJoin}
```
public static final int BevelJoin
```

斜角连接。两个线段应使用平头帽结束（参见 8.4.3.3，"Line Cap Style"），并且线段末端之外产生的缺口应填充为三角形。

### MiterJoin {#MiterJoin}
```
public static final int MiterJoin
```

斜接连接。两个线段的笔画外缘应延伸直至在某个角度相交，类似相框。如果线段相交角度过锐，依据斜接限制参数（参见 8.4.3.5，"Miter Limit"），则改用斜角连接。

### RoundJoin {#RoundJoin}
```
public static final int RoundJoin
```

圆角连接。以与线宽相等直径的圆弧围绕两个线段相交点绘制，连接两个线段的笔画外缘。该扇形应填充，从而形成圆润的拐角。
