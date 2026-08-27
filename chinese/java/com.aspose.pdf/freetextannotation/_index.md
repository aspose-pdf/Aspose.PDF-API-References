---
title: "FreeTextAnnotation"
linktitle: "FreeTextAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示一种自由文本注释，可直接在页面上显示文本。与普通文本注释不同，自由文本注释没有打开或关闭状态；相反，"
type: docs
weight: 1790
url: /zh/java/com.aspose.pdf/freetextannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FreeTextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FreeTextAnnotation extends MarkupAnnotation
```

表示一种自由文本注释，可直接在页面上显示文本。与普通文本注释不同，自由文本注释没有打开或关闭状态；文本始终可见，而不是显示在弹出窗口中。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | 与 Generator 一起使用的构造函数。 |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | 在指定页面上创建新的 FreeText 注释。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者对象以处理该注释。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getCallout](#getCallout--) | 指定标注线的点数组。 |
| [getDefaultAppearance](#getDefaultAppearance--) | 获取用于格式化文本的默认外观字符串。 |
| [getDefaultAppearanceObject](#getDefaultAppearanceObject--) | 表示 FreeText 注释默认外观的对象。 |
| [getDefaultStyle](#getDefaultStyle--) | 获取默认样式字符串。 |
| [getEndingStyle](#getEndingStyle--) | 获取线段终点的结束样式。 |
| [getIntent](#getIntent--) | 获取自由文本注释的意图。 |
| [getJustification](#getJustification--) | 获取指定在显示注释文本时使用的对齐方式（齐行）的代码。 |
| [getRotate](#getRotate--) | 注释旋转的角度。 |
| [getStartingStyle](#getStartingStyle--) | 获取或设置线段终点的结束样式。此属性已过时，请使用 EndingStyle。 |
| [getTextRectangle](#getTextRectangle--) | 矩形描述两个矩形之间的数值差异：注释的 Rect 条目以及包含在该矩形内的另一个矩形。内部矩形是注释文本应显示的区域。 |
| [getTextStyle](#getTextStyle--) | 获取或设置外观中文本的样式。当文本样式更改时，文本外观会更新。 |
| [isValidXml](#isValidXml-java.lang.String-) |  |
| [setCallout](#setCallout-com.aspose.pdf.Point:A-) | 指定标注线的点数组。 |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | 设置用于格式化文本的默认外观字符串。 |
| [setDefaultStyle](#setDefaultStyle-java.lang.String-) | 设置默认样式字符串。 |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | 设置线段结束点的线尾样式。 |
| [setIntent](#setIntent-com.aspose.pdf.FreeTextIntent-) | 设置自由文本注释的意图。 |
| [setJustification](#setJustification-com.aspose.pdf.Justification-) | 设置用于显示注释文本的排版（justification）形式的代码。 |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | 注释旋转的角度。 |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | 获取或设置线段终点的结束样式。此属性已过时，请使用 EndingStyle。 |
| [setTextRectangle](#setTextRectangle-com.aspose.pdf.Rectangle-) | 矩形描述两个矩形之间的数值差异：注释的 Rect 条目以及包含在该矩形内的另一个矩形。内部矩形是注释文本应显示的区域。 |
| [setTextStyle](#setTextStyle-int-int-int-) | 设置由参数 textStyle 确定的格式，用于从 fromInd 索引到 toInd 索引的文本片段。 |
| [setTextStyle](#setTextStyle-int-java.lang.String-double-java.awt.Color-) | 设置由参数 textStyle 确定的格式，用于所有注释文本。 |
| [setTextStyle](#setTextStyle-com.aspose.pdf.TextStyle-) | 设置外观中文本的样式。当文本样式更改时，文本外观会更新。 |
| [updateAppearance](#updateAppearance--) | 在文本被更改/移动后，更新外观。 |

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
与 Generator 一起使用的构造函数。

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
在指定页面上创建新的 FreeText 注释。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受访问者对象以处理该注释。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
int 值

### getCallout {#getCallout--}
```
public final Point [] getCallout()
```

指定标注线的点数组。

**Returns:**
Point 数组

### getDefaultAppearance {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```

获取用于格式化文本的默认外观字符串。

**Returns:**
字符串值

### getDefaultAppearanceObject {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```

表示 FreeText 注释默认外观的对象。

**Returns:**
DefaultAppearance 对象

### getDefaultStyle {#getDefaultStyle--}
```
public String getDefaultStyle()
```

获取默认样式字符串。

**Returns:**
字符串值

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

获取线段终点的结束样式。

**Returns:**
LineEnding 值 @see LineEnding

### getIntent {#getIntent--}
```
public FreeTextIntent getIntent()
```

获取自由文本注释的意图。

**Returns:**
int 值 @see FreeTextIntent

### getJustification {#getJustification--}
```
public Justification getJustification()
```

获取指定在显示注释文本时使用的对齐方式（齐行）的代码。

**Returns:**
int 值 @see Justification

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

注释旋转的角度。

**Returns:**
Rotation 元素 @see Rotation

### getStartingStyle {#getStartingStyle--}
```
public final LineEnding getStartingStyle()
```

获取或设置线段终点的结束样式。此属性已过时，请使用 EndingStyle。

**Returns:**
LineEnding 元素

### getTextRectangle {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```

矩形描述两个矩形之间的数值差异：注释的 Rect 条目以及包含在该矩形内的另一个矩形。内部矩形是注释文本应显示的区域。

**Returns:**
Rectangle 实例

### getTextStyle {#getTextStyle--}
```
public TextStyle getTextStyle()
```

获取或设置外观中文本的样式。当文本样式更改时，文本外观会更新。

**Returns:**
TextStyle 值

### isValidXml {#isValidXml-java.lang.String-}


### setCallout {#setCallout-com.aspose.pdf.Point:A-}
指定标注线的点数组。

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
设置用于格式化文本的默认外观字符串。

### setDefaultStyle {#setDefaultStyle-java.lang.String-}
设置默认样式字符串。

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
设置线段结束点的线尾样式。

### setIntent {#setIntent-com.aspose.pdf.FreeTextIntent-}
设置自由文本注释的意图。

### setJustification {#setJustification-com.aspose.pdf.Justification-}
设置用于显示注释文本的排版（justification）形式的代码。

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
注释旋转的角度。

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
获取或设置线段终点的结束样式。此属性已过时，请使用 EndingStyle。

### setTextRectangle {#setTextRectangle-com.aspose.pdf.Rectangle-}
矩形描述两个矩形之间的数值差异：注释的 Rect 条目以及包含在该矩形内的另一个矩形。内部矩形是注释文本应显示的区域。

### setTextStyle {#setTextStyle-int-int-int-}
```
public final void setTextStyle(int fromInd, int toInd, int textStyles)
```

设置由参数 textStyle 确定的格式，用于从 fromInd 索引到 toInd 索引的文本片段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fromInd |  | 文本片段的起始索引（从 0 开始）。 |
| toInd |  | 文本片段的结束索引（从 0 开始计数，不包括此索引）。 |
| textStyles |  | 应用于文本片段的样式。 |

### setTextStyle {#setTextStyle-int-java.lang.String-double-java.awt.Color-}
设置由参数 textStyle 确定的格式，用于所有注释文本。

### setTextStyle {#setTextStyle-com.aspose.pdf.TextStyle-}
设置外观中文本的样式。当文本样式更改时，文本外观会更新。

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

在文本被更改/移动后，更新外观。
