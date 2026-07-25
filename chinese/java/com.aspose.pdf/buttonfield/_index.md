---
title: "ButtonField"
linktitle: "ButtonField"
second_title: "Aspose.PDF for Java API 参考"
description: "类表示按钮字段。"
type: docs
weight: 440
url: /zh/java/com.aspose.pdf/buttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Field, com.aspose.pdf.ButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class ButtonField extends Field
```

类表示按钮字段。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ButtonField](#ButtonField--) | Generator 的按钮字段构造函数。 |
| [ButtonField](#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Generator 的按钮字段构造函数。 |
| [ButtonField](#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Generator 的按钮字段构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addImage](#addImage-java.awt.image.BufferedImage-) | 向字段资源中添加图像并绘制它。 |
| [addImage](#addImage-java.awt.image.BufferedImage-boolean-) | 将图像添加到字段资源并绘制它。 |
| [getAlternateCaption](#getAlternateCaption--) | 获取按钮的备用标题，当在其活动区域内按下鼠标按钮时显示。 |
| [getAlternateIcon](#getAlternateIcon--) | 获取备用图标，当在其活动区域内按下鼠标按钮时显示。 |
| [getIconFit](#getIconFit--) | 获取图标适配对象，指定小部件注释的图标在其注释矩形内的显示方式。 |
| [getICPosition](#getICPosition--) | 获取图标标题位置。 |
| [getNormalCaption](#getNormalCaption--) | 获取普通标题。 |
| [getNormalIcon](#getNormalIcon--) | 获取按钮的普通图标，当未与用户交互时显示。 |
| [getRolloverCaption](#getRolloverCaption--) | 获取按钮的悬停标题，当用户将光标移入其活动区域且未按下鼠标按钮时显示。 |
| [getRolloverIcon](#getRolloverIcon--) | 获取按钮的悬停图标，当用户将光标移入其活动区域且未按下鼠标按钮时显示。 |
| [setAlternateCaption](#setAlternateCaption-java.lang.String-) | 设置按钮的备用标题，当在其活动区域内按下鼠标按钮时显示。 |
| [setAlternateIcon](#setAlternateIcon-com.aspose.pdf.XForm-) | 设置备用图标，当在其活动区域内按下鼠标按钮时显示。 |
| [setICPosition](#setICPosition-com.aspose.pdf.IconCaptionPosition-) | 设置图标标题位置。 |
| [setNormalCaption](#setNormalCaption-java.lang.String-) | 设置普通标题。 |
| [setNormalIcon](#setNormalIcon-com.aspose.pdf.XForm-) | 设置按钮的普通图标，当未与用户交互时显示。 |
| [setRolloverCaption](#setRolloverCaption-java.lang.String-) | 设置按钮的悬停标题，当用户将光标移入其活动区域且未按下鼠标按钮时显示。 |
| [setRolloverIcon](#setRolloverIcon-com.aspose.pdf.XForm-) | 设置按钮的悬停图标，当用户将光标移入其活动区域且未按下鼠标按钮时显示。 |

### ButtonField {#ButtonField--}
```
public ButtonField()
```

Generator 的按钮字段构造函数。

### ButtonField {#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Generator 的按钮字段构造函数。

### ButtonField {#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Generator 的按钮字段构造函数。

### addImage {#addImage-java.awt.image.BufferedImage-}
向字段资源中添加图像并绘制它。

### addImage {#addImage-java.awt.image.BufferedImage-boolean-}
将图像添加到字段资源并绘制它。

### getAlternateCaption {#getAlternateCaption--}
```
public String getAlternateCaption()
```

获取按钮的备用标题，当在其活动区域内按下鼠标按钮时显示。

**Returns:**
字符串值

### getAlternateIcon {#getAlternateIcon--}
```
public XForm getAlternateIcon()
```

获取备用图标，当在其活动区域内按下鼠标按钮时显示。

**Returns:**
XForm 对象

### getIconFit {#getIconFit--}
```
public IconFit getIconFit()
```

获取图标适配对象，指定小部件注释的图标在其注释矩形内的显示方式。

**Returns:**
IconFit 对象

### getICPosition {#getICPosition--}
```
public IconCaptionPosition getICPosition()
```

获取图标标题位置。

**Returns:**
图标标题位置。 @see IconCaptionPosition

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

获取普通标题。

**Returns:**
字符串值

### getNormalIcon {#getNormalIcon--}
```
public XForm getNormalIcon()
```

获取按钮的普通图标，当未与用户交互时显示。

**Returns:**
XForm 对象

### getRolloverCaption {#getRolloverCaption--}
```
public String getRolloverCaption()
```

获取按钮的悬停标题，当用户将光标移入其活动区域且未按下鼠标按钮时显示。

**Returns:**
字符串值

### getRolloverIcon {#getRolloverIcon--}
```
public XForm getRolloverIcon()
```

获取按钮的悬停图标，当用户将光标移入其活动区域且未按下鼠标按钮时显示。

**Returns:**
XForm 对象

### setAlternateCaption {#setAlternateCaption-java.lang.String-}
设置按钮的备用标题，当在其活动区域内按下鼠标按钮时显示。

### setAlternateIcon {#setAlternateIcon-com.aspose.pdf.XForm-}
设置备用图标，当在其活动区域内按下鼠标按钮时显示。

### setICPosition {#setICPosition-com.aspose.pdf.IconCaptionPosition-}
设置图标标题位置。

### setNormalCaption {#setNormalCaption-java.lang.String-}
设置普通标题。

### setNormalIcon {#setNormalIcon-com.aspose.pdf.XForm-}
设置按钮的普通图标，当未与用户交互时显示。

### setRolloverCaption {#setRolloverCaption-java.lang.String-}
设置按钮的悬停标题，当用户将光标移入其活动区域且未按下鼠标按钮时显示。

### setRolloverIcon {#setRolloverIcon-com.aspose.pdf.XForm-}
设置按钮的悬停图标，当用户将光标移入其活动区域且未按下鼠标按钮时显示。
