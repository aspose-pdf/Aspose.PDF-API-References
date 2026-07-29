---
title: "StampInfo"
linktitle: "StampInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "表示印章信息的类。"
type: docs
weight: 710
url: /zh/java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.StampInfo

```
public final class StampInfo extends Object
```

表示印章信息的类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getForm](#getForm--) | 获取印章的 XForm。 |
| [getImage](#getImage--) | 获取印章的图像。如果印章不包含图像（例如文本印章），则可能为 null。 |
| [getImageInternal](#getImageInternal--) | 获取印章的图像。如果印章不包含图像（例如文本印章），则可能为 null。 |
| [getIndexOnPage](#getIndexOnPage--) | 获取印章在页面上的索引。 |
| [getRectangle](#getRectangle--) | 获取印章所在的矩形区域。 |
| [getStampId](#getStampId--) | 获取印章的标识符。 |
| [getStampType](#getStampType--) | 获取印章类型（图像 / 表单）。 |
| [getText](#getText--) | 获取印章中的文本。 |
| [getVisible](#getVisible--) | 获取印章的可见性。如果为 false，则印章被隐藏（使用 HideStampById）。隐藏的印章可以通过 ShowStampById 恢复。 |

### getForm {#getForm--}
```
public XForm getForm()
```

获取印章的 XForm。

**Returns:**
XForm 对象

### getImage {#getImage--}
```
public BufferedImage getImage()
```

获取印章的图像。如果印章不包含图像（例如文本印章），则可能为 null。

**Returns:**
BufferedImage 对象

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.Drawing.Image getImageInternal()
```

获取印章的图像。如果印章不包含图像（例如文本印章），则可能为 null。

**Returns:**
图像对象

### getIndexOnPage {#getIndexOnPage--}
```
public int getIndexOnPage()
```

获取印章在页面上的索引。

**Returns:**
int 值

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取印章所在的矩形区域。

**Returns:**
矩形元素

### getStampId {#getStampId--}
```
public int getStampId()
```

获取印章的标识符。

**Returns:**
int 值

### getStampType {#getStampType--}
```
public StampType getStampType()
```

获取印章类型（图像 / 表单）。

**Returns:**
StampType 元素 @see StampType

### getText {#getText--}
```
public String getText()
```

获取印章中的文本。

**Returns:**
字符串值

### getVisible {#getVisible--}
```
public boolean getVisible()
```

获取印章的可见性。如果为 false，则印章被隐藏（使用 HideStampById）。隐藏的印章可以通过 ShowStampById 恢复。

**Returns:**
布尔值
