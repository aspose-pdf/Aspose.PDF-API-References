---
title: "LineInfo"
linktitle: "LineInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "表示线条的信息。"
type: docs
weight: 350
url: /zh/java/com.aspose.pdf.facades/lineinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.LineInfo

```
public final class LineInfo extends Object
```

表示线条的信息。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LineInfo](#LineInfo--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBorderStyle](#getBorderStyle--) | 获取线条的边框样式，0 表示实线，1 表示虚线，2 表示斜面，3 表示插入，4 表示下划线。 |
| [getLineColor](#getLineColor--) | 获取线条的颜色。 |
| [getLineDashPattern](#getLineDashPattern--) | 获取线条的虚线模式。 |
| [getLineWidth](#getLineWidth--) | 获取或设置线条的宽度。 |
| [getVerticeCoordinate](#getVerticeCoordinate--) | 获取一个数字数组，分别表示每个顶点交替的水平和垂直坐标。 |
| [getVisibility](#getVisibility--) | 获取线条的可见性。 |
| [setBorderStyle](#setBorderStyle-com.aspose.pdf.BorderStyle-) | 设置线条的边框样式，0 表示实线，1 表示虚线，2 表示斜面，3 表示插入，4 表示下划线。 |
| [setBorderStyle](#setBorderStyle-int-) | 设置线条的边框样式，0 表示实线，1 表示虚线，2 表示斜面，3 表示插入，4 表示下划线。 |
| [setLineColor](#setLineColor-java.awt.Color-) | 设置线条的颜色。 |
| [setLineDashPattern](#setLineDashPattern-int:A-) | 设置线条的虚线模式。 |
| [setLineWidth](#setLineWidth-int-) | 设置线条的宽度。 |
| [setVerticeCoordinate](#setVerticeCoordinate-float:A-) | 设置一个数字数组，分别表示每个顶点交替的水平和垂直坐标。 |
| [setVisibility](#setVisibility-boolean-) | 设置线条的可见性。 |

### LineInfo {#LineInfo--}
```
public LineInfo()
```



### getBorderStyle {#getBorderStyle--}
```
public BorderStyle getBorderStyle()
```

获取线条的边框样式，0 表示实线，1 表示虚线，2 表示斜面，3 表示插入，4 表示下划线。

**Returns:**
int 值

### getLineColor {#getLineColor--}
```
public Color getLineColor()
```

获取线条的颜色。

**Returns:**
颜色元素

### getLineDashPattern {#getLineDashPattern--}
```
public int[] getLineDashPattern()
```

获取线条的虚线模式。

**Returns:**
int 数组值

### getLineWidth {#getLineWidth--}
```
public int getLineWidth()
```

获取或设置线条的宽度。

**Returns:**
int 值

### getVerticeCoordinate {#getVerticeCoordinate--}
```
public float[] getVerticeCoordinate()
```

获取一个数字数组，分别表示每个顶点交替的水平和垂直坐标。

**Returns:**
float 值数组

### getVisibility {#getVisibility--}
```
public boolean getVisibility()
```

获取线条的可见性。

**Returns:**
布尔值

### setBorderStyle {#setBorderStyle-com.aspose.pdf.BorderStyle-}
设置线条的边框样式，0 表示实线，1 表示虚线，2 表示斜面，3 表示插入，4 表示下划线。

### setBorderStyle {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```

设置线条的边框样式，0 表示实线，1 表示虚线，2 表示斜面，3 表示插入，4 表示下划线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setLineColor {#setLineColor-java.awt.Color-}
设置线条的颜色。

### setLineDashPattern {#setLineDashPattern-int:A-}
```
public void setLineDashPattern(int[] value)
```

设置线条的虚线模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 数组值 |

### setLineWidth {#setLineWidth-int-}
```
public void setLineWidth(int value)
```

设置线条的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setVerticeCoordinate {#setVerticeCoordinate-float:A-}
```
public void setVerticeCoordinate(float[] value)
```

设置一个数字数组，分别表示每个顶点交替的水平和垂直坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值数组 |

### setVisibility {#setVisibility-boolean-}
```
public void setVisibility(boolean value)
```

设置线条的可见性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
