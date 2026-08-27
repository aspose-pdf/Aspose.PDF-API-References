---
title: "PDF3DCrossSection"
linktitle: "PDF3DCrossSection"
second_title: "Aspose.PDF for Java API 参考"
description: "类 PDF3DCrossSection。"
type: docs
weight: 3590
url: /zh/java/com.aspose.pdf/pdf3dcrosssection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DCrossSection

```
public class PDF3DCrossSection extends Object
```

类 PDF3DCrossSection。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PDF3DCrossSection](#PDF3DCrossSection-com.aspose.pdf.Document-) | 初始化 {@code PDF3DCrossSection} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCenter](#getCenter--) | 获取或设置横截面的旋转中心。 |
| [getCuttingPlaneColor](#getCuttingPlaneColor--) | 获取或设置切割平面的颜色。 |
| [getCuttingPlaneOpacity](#getCuttingPlaneOpacity--) | 获取或设置切割平面的不透明度。 |
| [getCuttingPlaneOrientation](#getCuttingPlaneOrientation--) | 获取或设置切割平面的方向。 |
| [getCuttingPlanesIntersectionColor](#getCuttingPlanesIntersectionColor--) | 获取或设置切割平面交叉处的颜色。 |
| [getVisibility](#getVisibility--) | 获取或设置指示切割平面交叉处可见性的值。 |
| [setCenter](#setCenter-com.aspose.pdf.Point3D-) | 获取或设置横截面的旋转中心。 |
| [setCuttingPlaneColor](#setCuttingPlaneColor-com.aspose.pdf.Color-) | 获取或设置切割平面的颜色。 |
| [setCuttingPlaneOpacity](#setCuttingPlaneOpacity-double-) | 获取或设置切割平面的不透明度。 |
| [setCuttingPlaneOrientation](#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-) | 获取或设置切割平面的方向。 |
| [setCuttingPlanesIntersectionColor](#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-) | 获取或设置切割平面交叉处的颜色。 |
| [setVisibility](#setVisibility-boolean-) | 获取或设置指示切割平面交叉处可见性的值。 |

### PDF3DCrossSection {#PDF3DCrossSection-com.aspose.pdf.Document-}
初始化 {@code PDF3DCrossSection} 类的新实例。

### getCenter {#getCenter--}
```
public Point3D getCenter()
```

获取或设置横截面的旋转中心。

**Returns:**
Point3D 对象：中心。

### getCuttingPlaneColor {#getCuttingPlaneColor--}
```
public Color getCuttingPlaneColor()
```

获取或设置切割平面的颜色。

**Returns:**
com.aspose.pdf.Color 对象：切割平面的颜色。

### getCuttingPlaneOpacity {#getCuttingPlaneOpacity--}
```
public double getCuttingPlaneOpacity()
```

获取或设置切割平面的不透明度。

**Returns:**
double 值：切割平面的不透明度。 @throws Exception 该数字必须在范围 [0 , 1] 内

### getCuttingPlaneOrientation {#getCuttingPlaneOrientation--}
```
public PDF3DCuttingPlaneOrientation getCuttingPlaneOrientation()
```

获取或设置切割平面的方向。

**Returns:**
PDF3DCuttingPlaneOrientation 对象：切割平面的方向。 @throws Exception 只能有一个值为 Null

### getCuttingPlanesIntersectionColor {#getCuttingPlanesIntersectionColor--}
```
public Color getCuttingPlanesIntersectionColor()
```

获取或设置切割平面交叉处的颜色。

**Returns:**
com.aspose.pdf.Color 对象：切割平面交叉处的颜色。

### getVisibility {#getVisibility--}
```
public boolean getVisibility()
```

获取或设置指示切割平面交叉处可见性的值。

**Returns:**
：{@code true} 表示可见；否则，{@code false}。

### setCenter {#setCenter-com.aspose.pdf.Point3D-}
获取或设置横截面的旋转中心。

### setCuttingPlaneColor {#setCuttingPlaneColor-com.aspose.pdf.Color-}
获取或设置切割平面的颜色。

### setCuttingPlaneOpacity {#setCuttingPlaneOpacity-double-}
```
public void setCuttingPlaneOpacity(double value)
```

获取或设置切割平面的不透明度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值：切割平面的不透明度。 @throws Exception 该数字必须在范围 [0 , 1] 内 |

### setCuttingPlaneOrientation {#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-}
获取或设置切割平面的方向。

### setCuttingPlanesIntersectionColor {#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-}
获取或设置切割平面交叉处的颜色。

### setVisibility {#setVisibility-boolean-}
```
public void setVisibility(boolean value)
```

获取或设置指示切割平面交叉处可见性的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ：{@code true} 表示可见；否则，{@code false}。 |
