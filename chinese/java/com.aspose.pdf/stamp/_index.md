---
title: "印章"
linktitle: "印章"
second_title: "Aspose.PDF for Java API 参考"
description: "用于各种作为子类出现的印章的抽象类。"
type: docs
weight: 4620
url: /zh/java/com.aspose.pdf/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp

```
public abstract class Stamp extends Object
```

用于各种作为子类出现的印章的抽象类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Stamp](#Stamp--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBottomMargin](#getBottomMargin--) | 获取印章的底部边距。 |
| [getHeight](#getHeight--) | 获取印章在页面上的期望高度。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | 获取印章在页面上的水平对齐方式。 |
| [getLeftMargin](#getLeftMargin--) | 获取印章的左侧边距。 |
| [getOpacity](#getOpacity--) | 获取用于指示印章不透明度的值。该值范围为 0.0 到 1.0。默认值为 1.0。 |
| [getOutlineOpacity](#getOutlineOpacity--) | 获取用于指示印章轮廓不透明度的值。该值范围为 0.0 到 1.0。默认值为 1.0。 |
| [getOutlineWidth](#getOutlineWidth--) | 获取印章轮廓宽度的值。默认值为 1.0。 |
| [getRightMargin](#getRightMargin--) | 获取印章的右侧边距。 |
| [getRotate](#getRotate--) | 获取印章内容的旋转角度，依据 {@code Rotation} 值。注意：此属性用于设置 90 度的整数倍角度（0、90、180、270 度）。若要设置任意角度，请使用 RotateAngle 属性。如果由 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。 |
| [getRotateAngle](#getRotateAngle--) | 获取印章的旋转角度（以度为单位）。此属性允许设置任意旋转角度。 |
| [getStampId](#getStampId--) | 获取印章 ID。 |
| [getTopMargin](#getTopMargin--) | 获取印章的顶部边距。 |
| [getVerticalAlignment](#getVerticalAlignment--) | 获取印章在页面上的垂直对齐方式。 |
| [getWidth](#getWidth--) | 获取印章在页面上的期望宽度。 |
| [getXIndent](#getXIndent--) | 获取水平印章坐标，起点为左侧。 |
| [getYIndent](#getYIndent--) | 获取垂直印章坐标，起点为底部。 |
| [getZoom](#getZoom--) | 获取印章的缩放因子。允许对印章进行缩放。请注意，ZoomX 和 ZoomY 属性对每个轴的缩放因子可以单独设置。设置此属性会同时更改 ZoomX 和 ZoomY 属性。如果 ZoomX 和 ZoomY 不相同，则 Zoom 属性返回 ZoomX 的值。 |
| [getZoomX](#getZoomX--) | 获取印章的水平缩放因子。允许水平缩放印章。 |
| [getZoomY](#getZoomY--) | 获取印章的垂直缩放因子。允许垂直缩放印章。 |
| [isBackground](#isBackground--) | 获取一个布尔值，指示内容是否作为背景进行印章。如果值为 true，印章内容放置在底部。默认情况下，值为 false，印章内容放置在顶部。 |
| [put](#put-com.aspose.pdf.Page-) | 在页面上添加印章。 |
| [setBackground](#setBackground-boolean-) | 设置一个布尔值，指示内容是否作为背景进行印章。如果值为 true，印章内容放置在底部。默认情况下，值为 false，印章内容放置在顶部。 |
| [setBottomMargin](#setBottomMargin-double-) | 设置印章的底部边距。 |
| [setHeight](#setHeight-double-) | 设置印章在页面上的期望高度。 |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | 设置印章在页面上的水平对齐方式。 |
| [setLeftMargin](#setLeftMargin-double-) | 设置印章的左侧边距。 |
| [setOpacity](#setOpacity-double-) | 设置一个值以指示印章的不透明度。该值范围为 0.0 到 1.0。默认值为 1.0。 |
| [setOutlineOpacity](#setOutlineOpacity-double-) | 设置一个值以指示印章轮廓的不透明度。该值范围为 0.0 到 1.0。默认值为 1.0。 |
| [setOutlineWidth](#setOutlineWidth-double-) | 设置印章轮廓宽度的值。默认值为 1.0。 |
| [setRightMargin](#setRightMargin-double-) | 设置印章的右侧边距。 |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | 根据 {@code Rotation} 值设置印章内容的旋转。注意：此属性用于设置 90 度的整数倍角度（0、90、180、270 度）。若要设置任意角度，请使用 RotateAngle 属性。如果 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。 |
| [setRotateAngle](#setRotateAngle-double-) | 以度为单位设置印章的旋转角度。此属性允许设置任意旋转角度。 |
| [setStampId](#setStampId-int-) | 设置印章 Id。 |
| [setTopMargin](#setTopMargin-double-) | 设置印章的顶部边距。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 设置印章在页面上的垂直对齐方式。 |
| [setWidth](#setWidth-double-) | 设置印章在页面上的期望宽度。 |
| [setXIndent](#setXIndent-double-) | 设置水平印章坐标，从左侧开始。 |
| [setYIndent](#setYIndent-double-) | 设置垂直印章坐标，从底部开始。 |
| [setZoom](#setZoom-double-) | 获取印章的缩放因子。允许对印章进行缩放。请注意，ZoomX 和 ZoomY 属性对每个轴的缩放因子可以单独设置。设置此属性会同时更改 ZoomX 和 ZoomY 属性。如果 ZoomX 和 ZoomY 不相同，则 Zoom 属性返回 ZoomX 的值。 |
| [setZoomX](#setZoomX-double-) | 设置印章的水平缩放因子。允许水平缩放印章。 |
| [setZoomY](#setZoomY-double-) | 设置印章的垂直缩放因子。允许垂直缩放印章。 |

### Stamp {#Stamp--}
```
public Stamp()
```



### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

获取印章的底部边距。

**Returns:**
double 值

### getHeight {#getHeight--}
```
public double getHeight()
```

获取印章在页面上的期望高度。

**Returns:**
double 值

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

获取印章在页面上的水平对齐方式。

**Returns:**
HorizontalAlignment 值 @see HorizontalAlignment

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

获取印章的左侧边距。

**Returns:**
double 值

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

获取用于指示印章不透明度的值。该值范围为 0.0 到 1.0。默认值为 1.0。

**Returns:**
double 值

### getOutlineOpacity {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```

获取用于指示印章轮廓不透明度的值。该值范围为 0.0 到 1.0。默认值为 1.0。

**Returns:**
double 值

### getOutlineWidth {#getOutlineWidth--}
```
public double getOutlineWidth()
```

获取印章轮廓宽度的值。默认值为 1.0。

**Returns:**
double 值

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

获取印章的右侧边距。

**Returns:**
double 值

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

获取印章内容的旋转角度，依据 {@code Rotation} 值。注意：此属性用于设置 90 度的整数倍角度（0、90、180、270 度）。若要设置任意角度，请使用 RotateAngle 属性。如果由 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。

**Returns:**
旋转值 @see Rotation

### getRotateAngle {#getRotateAngle--}
```
public double getRotateAngle()
```

获取印章的旋转角度（以度为单位）。此属性允许设置任意旋转角度。

**Returns:**
double 值

### getStampId {#getStampId--}
```
public int getStampId()
```

获取印章 ID。

**Returns:**
印章的标识符。

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

获取印章的顶部边距。

**Returns:**
double 值

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

获取印章在页面上的垂直对齐方式。

**Returns:**
VerticalAlignment 值 @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

获取印章在页面上的期望宽度。

**Returns:**
double 值

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

获取水平印章坐标，起点为左侧。

**Returns:**
double 值

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

获取垂直印章坐标，起点为底部。

**Returns:**
double 值

### getZoom {#getZoom--}
```
public double getZoom()
```

获取印章的缩放因子。允许对印章进行缩放。请注意，ZoomX 和 ZoomY 属性对每个轴的缩放因子可以单独设置。设置此属性会同时更改 ZoomX 和 ZoomY 属性。如果 ZoomX 和 ZoomY 不相同，则 Zoom 属性返回 ZoomX 的值。

**Returns:**
double 值

### getZoomX {#getZoomX--}
```
public double getZoomX()
```

获取印章的水平缩放因子。允许水平缩放印章。

**Returns:**
double 值

### getZoomY {#getZoomY--}
```
public double getZoomY()
```

获取印章的垂直缩放因子。允许垂直缩放印章。

**Returns:**
double 值

### isBackground {#isBackground--}
```
public boolean isBackground()
```

获取一个布尔值，指示内容是否作为背景进行印章。如果值为 true，印章内容放置在底部。默认情况下，值为 false，印章内容放置在顶部。

**Returns:**
布尔值

### put {#put-com.aspose.pdf.Page-}
在页面上添加印章。

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

设置一个布尔值，指示内容是否作为背景进行印章。如果值为 true，印章内容放置在底部。默认情况下，值为 false，印章内容放置在顶部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

设置印章的底部边距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

设置印章在页面上的期望高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
设置印章在页面上的水平对齐方式。

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

设置印章的左侧边距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

设置一个值以指示印章的不透明度。该值范围为 0.0 到 1.0。默认值为 1.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setOutlineOpacity {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```

设置一个值以指示印章轮廓的不透明度。该值范围为 0.0 到 1.0。默认值为 1.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setOutlineWidth {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```

设置印章轮廓宽度的值。默认值为 1.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

设置印章的右侧边距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
根据 {@code Rotation} 值设置印章内容的旋转。注意：此属性用于设置 90 度的整数倍角度（0、90、180、270 度）。若要设置任意角度，请使用 RotateAngle 属性。如果 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。

### setRotateAngle {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```

以度为单位设置印章的旋转角度。此属性允许设置任意旋转角度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 旋转角度 |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

设置印章 Id。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | Stamp ID 的新值。 |

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

设置印章的顶部边距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
设置印章在页面上的垂直对齐方式。

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

设置印章在页面上的期望宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

设置水平印章坐标，从左侧开始。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

设置垂直印章坐标，从底部开始。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setZoom {#setZoom-double-}
```
public void setZoom(double value)
```

获取印章的缩放因子。允许对印章进行缩放。请注意，ZoomX 和 ZoomY 属性对每个轴的缩放因子可以单独设置。设置此属性会同时更改 ZoomX 和 ZoomY 属性。如果 ZoomX 和 ZoomY 不相同，则 Zoom 属性返回 ZoomX 的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setZoomX {#setZoomX-double-}
```
public void setZoomX(double value)
```

设置印章的水平缩放因子。允许水平缩放印章。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setZoomY {#setZoomY-double-}
```
public void setZoomY(double value)
```

设置印章的垂直缩放因子。允许垂直缩放印章。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |
