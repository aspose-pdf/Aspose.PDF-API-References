---
title: "PDF3DRenderMode"
linktitle: "PDF3DRenderMode"
second_title: "Aspose.PDF for Java API 参考"
description: "类 PDF3DRenderMode。"
type: docs
weight: 3630
url: /zh/java/com.aspose.pdf/pdf3drendermode/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DRenderMode

```
public class PDF3DRenderMode extends Object
```

类 PDF3DRenderMode。

## 字段

| 字段 | 描述 |
| --- | --- |
| [BoundingBox](#BoundingBox) | "BoundingBox" 渲染模式。 |
| [Illustration](#Illustration) | "Illustration" 渲染模式。 |
| [ShadedIllustration](#ShadedIllustration) | "ShadedIllustration" 渲染模式。 |
| [ShadedVertices](#ShadedVertices) | "ShadedVertices" 渲染模式。 |
| [ShadedWireframe](#ShadedWireframe) | "ShadedWireFrame" 渲染模式。 |
| [Solid](#Solid) | "Solid" 渲染模式。 |
| [SolidOutline](#SolidOutline) | "SolidOutline" 渲染模式。 |
| [SolidWireframe](#SolidWireframe) | "SolidWireFrame" 渲染模式。 |
| [Transparent](#Transparent) | "Transparent" 渲染模式。 |
| [TransparentBoundingBox](#TransparentBoundingBox) | "TransparentBoundingBox" 渲染模式。 |
| [TransparentBoundingBoxOutline](#TransparentBoundingBoxOutline) | "TransparentBoundingBoxOutline" 渲染模式。 |
| [TransparentWareFrame](#TransparentWareFrame) | "TransparentWareFrame" 渲染模式。 |
| [Vertices](#Vertices) | "Vertices" 渲染模式。 |
| [Wireframe](#Wireframe) | "WireFrame" 渲染模式。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PDF3DRenderMode](#PDF3DRenderMode-int-) | 初始化 {@code PDF3DRenderMode} 类的新实例。 |
| [PDF3DRenderMode](#PDF3DRenderMode-java.lang.String-) | 初始化 {@code PDF3DRenderMode} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAuxiliaryColour](#getAuxiliaryColour--) | 获取辅助颜色。 |
| [getCreaseValue](#getCreaseValue--) | 获取折痕值。 |
| [getFaceColor](#getFaceColor--) | 获取面的颜色。 |
| [getOpacity](#getOpacity--) | 获取不透明度。 |
| [getType](#getType--) | 获取类型。 |
| [setAuxiliaryColour](#setAuxiliaryColour-com.aspose.pdf.Color-) | 设置辅助颜色。 |
| [setCreaseValue](#setCreaseValue-double-) | 设置折痕值。 |
| [setFaceColor](#setFaceColor-com.aspose.pdf.Color-) | 设置面的颜色。 |
| [setOpacity](#setOpacity-double-) | 设置不透明度。 |

### BoundingBox {#BoundingBox}
```
public static final PDF3DRenderMode BoundingBox
```

"BoundingBox" 渲染模式。

### Illustration {#Illustration}
```
public static final PDF3DRenderMode Illustration
```

"Illustration" 渲染模式。

### ShadedIllustration {#ShadedIllustration}
```
public static final PDF3DRenderMode ShadedIllustration
```

"ShadedIllustration" 渲染模式。

### ShadedVertices {#ShadedVertices}
```
public static final PDF3DRenderMode ShadedVertices
```

"ShadedVertices" 渲染模式。

### ShadedWireframe {#ShadedWireframe}
```
public static final PDF3DRenderMode ShadedWireframe
```

"ShadedWireFrame" 渲染模式。

### Solid {#Solid}
```
public static final PDF3DRenderMode Solid
```

"Solid" 渲染模式。

### SolidOutline {#SolidOutline}
```
public static final PDF3DRenderMode SolidOutline
```

"SolidOutline" 渲染模式。

### SolidWireframe {#SolidWireframe}
```
public static final PDF3DRenderMode SolidWireframe
```

"SolidWireFrame" 渲染模式。

### Transparent {#Transparent}
```
public static final PDF3DRenderMode Transparent
```

"Transparent" 渲染模式。

### TransparentBoundingBox {#TransparentBoundingBox}
```
public static final PDF3DRenderMode TransparentBoundingBox
```

"TransparentBoundingBox" 渲染模式。

### TransparentBoundingBoxOutline {#TransparentBoundingBoxOutline}
```
public static final PDF3DRenderMode TransparentBoundingBoxOutline
```

"TransparentBoundingBoxOutline" 渲染模式。

### TransparentWareFrame {#TransparentWareFrame}
```
public static final PDF3DRenderMode TransparentWareFrame
```

"TransparentWareFrame" 渲染模式。

### Vertices {#Vertices}
```
public static final PDF3DRenderMode Vertices
```

"Vertices" 渲染模式。

### Wireframe {#Wireframe}
```
public static final PDF3DRenderMode Wireframe
```

"WireFrame" 渲染模式。

### PDF3DRenderMode {#PDF3DRenderMode-int-}
```
public PDF3DRenderMode(int subtype)
```

初始化 {@code PDF3DRenderMode} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 子类型 |  | 渲染模式类型。 |

### PDF3DRenderMode {#PDF3DRenderMode-java.lang.String-}
初始化 {@code PDF3DRenderMode} 类的新实例。

### getAuxiliaryColour {#getAuxiliaryColour--}
```
public Color getAuxiliaryColour()
```

获取辅助颜色。

**Returns:**
颜色。

### getCreaseValue {#getCreaseValue--}
```
public double getCreaseValue()
```

获取折痕值。

**Returns:**
System.Double.

### getFaceColor {#getFaceColor--}
```
public Object getFaceColor()
```

获取面的颜色。

**Returns:**
对象。

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

获取不透明度。

**Returns:**
System.Double.

### getType {#getType--}
```
public int getType()
```

获取类型。

**Returns:**
RenderModeType 值：类型。@see RenderModeType

### setAuxiliaryColour {#setAuxiliaryColour-com.aspose.pdf.Color-}
设置辅助颜色。

### setCreaseValue {#setCreaseValue-double-}
```
public PDF3DRenderMode setCreaseValue(double creaseValue)
```

设置折痕值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| creaseValue |  | 折痕值。 |

**Returns:**
PDF3DRenderMode.

### setFaceColor {#setFaceColor-com.aspose.pdf.Color-}
设置面的颜色。

### setOpacity {#setOpacity-double-}
```
public PDF3DRenderMode setOpacity(double opacity)
```

设置不透明度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| opacity |  | 不透明度。 |

**Returns:**
PDF3DRenderMode.
