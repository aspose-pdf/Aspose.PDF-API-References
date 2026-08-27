---
title: "ImageStamp"
linktitle: "ImageStamp"
second_title: "Aspose.PDF for Java API 参考"
description: "表示图形印章。"
type: docs
weight: 2360
url: /zh/java/com.aspose.pdf/imagestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.ImageStamp, com.aspose.pdf.Stamp, com.aspose.pdf.ImageStamp

```
public final class ImageStamp extends Stamp
```

表示图形印章。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageStamp](#ImageStamp-java.io.InputStream-) | 初始化 {@code ImageStamp} 类的新实例。 |
| [ImageStamp](#ImageStamp-java.lang.String-) | 通过指定文件中的图像创建图像印章。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [close](#close--) | 关闭此实例 |
| [getAlternativeText](#getAlternativeText--) | 获取图像印章的替代文本。 |
| [getHeight](#getHeight--) | 获取图像高度。设置此图像可垂直缩放图像。 |
| [getImage](#getImage--) | 获取用于印章的图像流。 |
| [getQuality](#getQuality--) | 获取图像印章的质量（百分比）。有效值为 0..100%。 |
| [getWidth](#getWidth--) | 获取图像宽度。设置此属性可水平缩放图像。 |
| [getXIndent](#getXIndent--) | 获取和设置水平印章坐标，起始于左侧。 |
| [getYIndent](#getYIndent--) | 获取和设置垂直印章坐标，起始于底部。 |
| [put](#put-com.aspose.pdf.Page-) | 在页面上添加图形印章。 |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | 设置图像印章的替代文本。 |
| [setHeight](#setHeight-double-) | 设置图像高度。设置此图像可垂直缩放图像。 |
| [setQuality](#setQuality-int-) | 设置图像印章的质量（百分比）。有效值为 0..100%。 |
| [setWidth](#setWidth-double-) | 设置图像宽度。设置此属性可水平缩放图像。 |
| [setXIndent](#setXIndent-double-) | 获取和设置水平印章坐标，起始于左侧。 |
| [setYIndent](#setYIndent-double-) | 获取和设置垂直印章坐标，起始于底部。 |

### ImageStamp {#ImageStamp-java.io.InputStream-}
初始化 {@code ImageStamp} 类的新实例。

### ImageStamp {#ImageStamp-java.lang.String-}
通过指定文件中的图像创建图像印章。

### close {#close--}
```
public void close()
```

关闭此实例

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

获取图像印章的替代文本。

**Returns:**
字符串值

### getHeight {#getHeight--}
```
public double getHeight()
```

获取图像高度。设置此图像可垂直缩放图像。

**Returns:**
double 值

### getImage {#getImage--}
```
public InputStream getImage()
```

获取用于印章的图像流。

**Returns:**
InputStream 对象

### getQuality {#getQuality--}
```
public int getQuality()
```

获取图像印章的质量（百分比）。有效值为 0..100%。

**Returns:**
int 值

### getWidth {#getWidth--}
```
public double getWidth()
```

获取图像宽度。设置此属性可水平缩放图像。

**Returns:**
double 值

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

获取和设置水平印章坐标，起始于左侧。

**Returns:**
double 值

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

获取和设置垂直印章坐标，起始于底部。

**Returns:**
double 值

### put {#put-com.aspose.pdf.Page-}
在页面上添加图形印章。

### setAlternativeText {#setAlternativeText-java.lang.String-}
设置图像印章的替代文本。

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

设置图像高度。设置此图像可垂直缩放图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

设置图像印章的质量（百分比）。有效值为 0..100%。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

设置图像宽度。设置此属性可水平缩放图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

获取和设置水平印章坐标，起始于左侧。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

获取和设置垂直印章坐标，起始于底部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |
