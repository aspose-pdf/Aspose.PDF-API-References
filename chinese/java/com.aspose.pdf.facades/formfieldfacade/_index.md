---
title: "FormFieldFacade"
linktitle: "FormFieldFacade"
second_title: "Aspose.PDF for Java API 参考"
description: "表示字段属性的类。"
type: docs
weight: 220
url: /zh/java/com.aspose.pdf.facades/formfieldfacade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.FormFieldFacade

```
public final class FormFieldFacade extends Object
```

表示字段属性的类。

## 字段

| 字段 | 描述 |
| --- | --- |
| [ALIGN_BOTTOM](#ALIGN_BOTTOM) | 将垂直对齐定义为底部样式。 |
| [ALIGN_CENTER](#ALIGN_CENTER) | 将对齐定义为居中样式。 |
| [ALIGN_JUSTIFIED](#ALIGN_JUSTIFIED) | 定义文本两端对齐样式。 |
| [ALIGN_LEFT](#ALIGN_LEFT) | 定义左对齐样式。 |
| [ALIGN_MIDDLE](#ALIGN_MIDDLE) | 定义垂直居中对齐样式。 |
| [ALIGN_RIGHT](#ALIGN_RIGHT) | 定义右对齐样式。 |
| [ALIGN_TOP](#ALIGN_TOP) | 定义垂直顶部对齐样式。 |
| [ALIGN_UNDEFINED](#ALIGN_UNDEFINED) | 未定义对齐样式。 |
| [BORDER_STYLE_BEVELED](#BORDER_STYLE_BEVELED) | 定义斜角边框样式。 |
| [BORDER_STYLE_DASHED](#BORDER_STYLE_DASHED) | 定义虚线边框样式。 |
| [BORDER_STYLE_INSET](#BORDER_STYLE_INSET) | 定义内嵌边框样式。 |
| [BORDER_STYLE_SOLID](#BORDER_STYLE_SOLID) | 定义实线边框样式。 |
| [BORDER_STYLE_UNDEFINED](#BORDER_STYLE_UNDEFINED) | 未定义边框样式。 |
| [BORDER_STYLE_UNDERLINE](#BORDER_STYLE_UNDERLINE) | 定义下划线边框样式。 |
| [BORDER_WIDTH_MEDIUM](#BORDER_WIDTH_MEDIUM) | 定义中等边框宽度。 |
| [BORDER_WIDTH_THICK](#BORDER_WIDTH_THICK) | 定义粗边框宽度。 |
| [BORDER_WIDTH_THIN](#BORDER_WIDTH_THIN) | 定义细边框宽度。 |
| [BORDER_WIDTH_UNDEFINED](#BORDER_WIDTH_UNDEFINED) | 未定义边框宽度。 |
| [BORDER_WIDTH_UNDIFIED](#BORDER_WIDTH_UNDIFIED) | 未定义边框宽度。 |
| [CHECK_BOX_STYLE_CHECK](#CHECK_BOX_STYLE_CHECK) | 定义复选框字段选中时的形状。 |
| [CHECK_BOX_STYLE_CIRCLE](#CHECK_BOX_STYLE_CIRCLE) | 定义圆形复选框样式。 |
| [CHECK_BOX_STYLE_CROSS](#CHECK_BOX_STYLE_CROSS) | 定义十字复选框样式。 |
| [CHECK_BOX_STYLE_DIAMOND](#CHECK_BOX_STYLE_DIAMOND) | 定义菱形复选框样式。 |
| [CHECK_BOX_STYLE_SQUARE](#CHECK_BOX_STYLE_SQUARE) | 定义方形复选框样式。 |
| [CHECK_BOX_STYLE_STAR](#CHECK_BOX_STYLE_STAR) | 定义星形复选框样式。 |
| [CHECK_BOX_STYLE_UNDEFINED](#CHECK_BOX_STYLE_UNDEFINED) | 定义未定义的复选框样式。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FormFieldFacade](#FormFieldFacade--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAlignment](#getAlignment--) | 获取字段文本的对齐方式，默认是左对齐。 |
| [getBackgroudColor](#getBackgroudColor--) | 已废弃属性。请使用 BackgroundColor。此方法已不推荐使用。 |
| [getBackgroundColor](#getBackgroundColor--) | 获取字段背景的颜色，默认是白色。 |
| [getBorderColor](#getBorderColor--) | 获取字段边框的颜色。 |
| [getBorderStyle](#getBorderStyle--) | 获取字段边框的样式。 |
| [getBorderWidth](#getBorderWidth--) | 获取字段边框的宽度。 |
| [getBox](#getBox--) | 获取保存字段位置的矩形对象。 |
| [getButtonStyle](#getButtonStyle--) | 获取复选框或单选框字段的样式，定义于 FormFieldFacade.CheckBoxStyle*。 |
| [getCaption](#getCaption--) | 获取表单字段的普通标题。 |
| [getCustomFont](#getCustomFont--) | 获取当字体非标准（即不是 14 种标准字体）时的字体名称。 |
| [getExportItems](#getExportItems--) | 获取用于添加列表/组合框/单选框的选项。 |
| [getFont](#getFont--) | 获取字段文本的字体样式类型。 |
| [getFontSize](#getFontSize--) | 获取字段文本的大小。 |
| [getItems](#getItems--) | 获取字符串数组，每个字符串表示组合框/列表/单选框字段的一个选项。 |
| [getPageNumber](#getPageNumber--) | 获取保存字段所在页码的整数值。 |
| [getPosition](#getPosition--) | 获取保存字段位置的矩形对象。 |
| [getRotation](#getRotation--) | 获取字段文本的旋转角度。 |
| [getTextColor](#getTextColor--) | 获取字段文本的颜色。 |
| [getTextEncoding](#getTextEncoding--) | 获取字段文本的文本编码类型。 |
| [reset](#reset--) | 将所有可视属性重置为空值。 |
| [setAlignment](#setAlignment-int-) | 设置字段文本的对齐方式，默认是左对齐。 |
| [setBackgroudColor](#setBackgroudColor-java.awt.Color-) | 已弃用。 |
| [setBackgroundColor](#setBackgroundColor-java.awt.Color-) | 设置字段背景的颜色，默认是白色。 |
| [setBorderColor](#setBorderColor-java.awt.Color-) | 设置字段边框的颜色。 |
| [setBorderStyle](#setBorderStyle-int-) | 设置字段边框的样式。 |
| [setBorderWidth](#setBorderWidth-float-) | 设置字段边框的宽度。 |
| [setBox](#setBox-java.awt.Rectangle-) | 设置保存字段位置的矩形对象。 |
| [setButtonStyle](#setButtonStyle-int-) | 设置复选框或单选框字段的样式，定义于 FormFieldFacade.CheckBoxStyle*。 |
| [setCaption](#setCaption-java.lang.String-) | 设置表单字段的普通标题。 |
| [setCustomFont](#setCustomFont-java.lang.String-) | 设置当字体非标准（即不是 14 种标准字体）时的字体名称。 |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | 设置添加列表/组合框/单选框的选项 |
| [setFont](#setFont-com.aspose.pdf.facades.FontStyle-) | 设置字段文本的字体样式类型。 |
| [setFontSize](#setFontSize-float-) | 设置字段文本的大小。 |
| [setItems](#setItems-java.lang.String:A-) | 设置一个字符串数组，每个字符串代表组合框/列表/单选框字段的一个选项。 |
| [setPageNumber](#setPageNumber-int-) | 设置一个整数值，表示字段所在的页码。 |
| [setPosition](#setPosition-float:A-) | 设置保存字段位置的矩形对象。 |
| [setRotation](#setRotation-int-) | 设置字段文本的旋转角度。 |
| [setTextColor](#setTextColor-java.awt.Color-) | 设置字段文本的颜色。 |
| [setTextEncoding](#setTextEncoding-int-) | 设置字段文本的 {@link EncodingType} 文本编码类型。 |

### ALIGN_BOTTOM {#ALIGN_BOTTOM}
```
public static final int ALIGN_BOTTOM
```

将垂直对齐定义为底部样式。

### ALIGN_CENTER {#ALIGN_CENTER}
```
public static final int ALIGN_CENTER
```

将对齐定义为居中样式。

### ALIGN_JUSTIFIED {#ALIGN_JUSTIFIED}
```
public static final int ALIGN_JUSTIFIED
```

定义文本两端对齐样式。

### ALIGN_LEFT {#ALIGN_LEFT}
```
public static final int ALIGN_LEFT
```

定义左对齐样式。

### ALIGN_MIDDLE {#ALIGN_MIDDLE}
```
public static final int ALIGN_MIDDLE
```

定义垂直居中对齐样式。

### ALIGN_RIGHT {#ALIGN_RIGHT}
```
public static final int ALIGN_RIGHT
```

定义右对齐样式。

### ALIGN_TOP {#ALIGN_TOP}
```
public static final int ALIGN_TOP
```

定义垂直顶部对齐样式。

### ALIGN_UNDEFINED {#ALIGN_UNDEFINED}
```
public static final int ALIGN_UNDEFINED
```

未定义对齐样式。

### BORDER_STYLE_BEVELED {#BORDER_STYLE_BEVELED}
```
public static final int BORDER_STYLE_BEVELED
```

定义斜角边框样式。

### BORDER_STYLE_DASHED {#BORDER_STYLE_DASHED}
```
public static final int BORDER_STYLE_DASHED
```

定义虚线边框样式。

### BORDER_STYLE_INSET {#BORDER_STYLE_INSET}
```
public static final int BORDER_STYLE_INSET
```

定义内嵌边框样式。

### BORDER_STYLE_SOLID {#BORDER_STYLE_SOLID}
```
public static final int BORDER_STYLE_SOLID
```

定义实线边框样式。

### BORDER_STYLE_UNDEFINED {#BORDER_STYLE_UNDEFINED}
```
public static final int BORDER_STYLE_UNDEFINED
```

未定义边框样式。

### BORDER_STYLE_UNDERLINE {#BORDER_STYLE_UNDERLINE}
```
public static final int BORDER_STYLE_UNDERLINE
```

定义下划线边框样式。

### BORDER_WIDTH_MEDIUM {#BORDER_WIDTH_MEDIUM}
```
public static final float BORDER_WIDTH_MEDIUM
```

定义中等边框宽度。

### BORDER_WIDTH_THICK {#BORDER_WIDTH_THICK}
```
public static final float BORDER_WIDTH_THICK
```

定义粗边框宽度。

### BORDER_WIDTH_THIN {#BORDER_WIDTH_THIN}
```
public static final float BORDER_WIDTH_THIN
```

定义细边框宽度。

### BORDER_WIDTH_UNDEFINED {#BORDER_WIDTH_UNDEFINED}
```
public static final float BORDER_WIDTH_UNDEFINED
```

未定义边框宽度。

### BORDER_WIDTH_UNDIFIED {#BORDER_WIDTH_UNDIFIED}
```
@Deprecated public static final float BORDER_WIDTH_UNDIFIED
```

未定义边框宽度。

### CHECK_BOX_STYLE_CHECK {#CHECK_BOX_STYLE_CHECK}
```
public static final int CHECK_BOX_STYLE_CHECK
```

定义复选框字段选中时的形状。

### CHECK_BOX_STYLE_CIRCLE {#CHECK_BOX_STYLE_CIRCLE}
```
public static final int CHECK_BOX_STYLE_CIRCLE
```

定义圆形复选框样式。

### CHECK_BOX_STYLE_CROSS {#CHECK_BOX_STYLE_CROSS}
```
public static final int CHECK_BOX_STYLE_CROSS
```

定义十字复选框样式。

### CHECK_BOX_STYLE_DIAMOND {#CHECK_BOX_STYLE_DIAMOND}
```
public static final int CHECK_BOX_STYLE_DIAMOND
```

定义菱形复选框样式。

### CHECK_BOX_STYLE_SQUARE {#CHECK_BOX_STYLE_SQUARE}
```
public static final int CHECK_BOX_STYLE_SQUARE
```

定义方形复选框样式。

### CHECK_BOX_STYLE_STAR {#CHECK_BOX_STYLE_STAR}
```
public static final int CHECK_BOX_STYLE_STAR
```

定义星形复选框样式。

### CHECK_BOX_STYLE_UNDEFINED {#CHECK_BOX_STYLE_UNDEFINED}
```
public static final int CHECK_BOX_STYLE_UNDEFINED
```

定义未定义的复选框样式。

### FormFieldFacade {#FormFieldFacade--}
```
public FormFieldFacade()
```



### getAlignment {#getAlignment--}
```
public int getAlignment()
```

获取字段文本的对齐方式，默认是左对齐。

**Returns:**
int 值

### getBackgroudColor {#getBackgroudColor--}
```
@Deprecated public Color getBackgroudColor()
```

已废弃属性。请使用 BackgroundColor。此方法已不推荐使用。

**Returns:**
背景颜色

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

获取字段背景的颜色，默认是白色。

**Returns:**
颜色元素

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

获取字段边框的颜色。

**Returns:**
字段边框的颜色。

### getBorderStyle {#getBorderStyle--}
```
public int getBorderStyle()
```

获取字段边框的样式。

**Returns:**
字段边框的样式。

### getBorderWidth {#getBorderWidth--}
```
public float getBorderWidth()
```

获取字段边框的宽度。

**Returns:**
字段边框的宽度。

### getBox {#getBox--}
```
public Rectangle getBox()
```

获取保存字段位置的矩形对象。

**Returns:**
矩形元素

### getButtonStyle {#getButtonStyle--}
```
public int getButtonStyle()
```

获取复选框或单选框字段的样式，定义于 FormFieldFacade.CheckBoxStyle*。

**Returns:**
int 值

### getCaption {#getCaption--}
```
public String getCaption()
```

获取表单字段的普通标题。

**Returns:**
字符串值

### getCustomFont {#getCustomFont--}
```
public String getCustomFont()
```

获取当字体非标准（即不是 14 种标准字体）时的字体名称。

**Returns:**
字符串值

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

获取用于添加列表/组合框/单选框的选项。

**Returns:**
String 值数组

### getFont {#getFont--}
```
public FontStyle getFont()
```

获取字段文本的字体样式类型。

**Returns:**
FontStyle 元素 @see FontStyle

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

获取字段文本的大小。

**Returns:**
float 值

### getItems {#getItems--}
```
public String [] getItems()
```

获取字符串数组，每个字符串表示组合框/列表/单选框字段的一个选项。

**Returns:**
String 值数组

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

获取保存字段所在页码的整数值。

**Returns:**
int 值

### getPosition {#getPosition--}
```
public float[] getPosition()
```

获取保存字段位置的矩形对象。

**Returns:**
float 值数组

### getRotation {#getRotation--}
```
public int getRotation()
```

获取字段文本的旋转角度。

**Returns:**
int 值

### getTextColor {#getTextColor--}
```
public Color getTextColor()
```

获取字段文本的颜色。

**Returns:**
颜色元素

### getTextEncoding {#getTextEncoding--}
```
public int getTextEncoding()
```

获取字段文本的文本编码类型。

**Returns:**
EncodingType 元素 @see EncodingType

### reset {#reset--}
```
public void reset()
```

将所有可视属性重置为空值。

### setAlignment {#setAlignment-int-}
```
public void setAlignment(int value)
```

设置字段文本的对齐方式，默认是左对齐。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setBackgroudColor {#setBackgroudColor-java.awt.Color-}
已弃用。

### setBackgroundColor {#setBackgroundColor-java.awt.Color-}
设置字段背景的颜色，默认是白色。

### setBorderColor {#setBorderColor-java.awt.Color-}
设置字段边框的颜色。

### setBorderStyle {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```

设置字段边框的样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 字段边框的样式。 |

### setBorderWidth {#setBorderWidth-float-}
```
public void setBorderWidth(float value)
```

设置字段边框的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 字段边框的宽度。 |

### setBox {#setBox-java.awt.Rectangle-}
设置保存字段位置的矩形对象。

### setButtonStyle {#setButtonStyle-int-}
```
public void setButtonStyle(int value)
```

设置复选框或单选框字段的样式，定义于 FormFieldFacade.CheckBoxStyle*。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setCaption {#setCaption-java.lang.String-}
设置表单字段的普通标题。

### setCustomFont {#setCustomFont-java.lang.String-}
设置当字体非标准（即不是 14 种标准字体）时的字体名称。

### setExportItems {#setExportItems-java.lang.String:A:A-}
设置添加列表/组合框/单选框的选项

### setFont {#setFont-com.aspose.pdf.facades.FontStyle-}
设置字段文本的字体样式类型。

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

设置字段文本的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setItems {#setItems-java.lang.String:A-}
设置一个字符串数组，每个字符串代表组合框/列表/单选框字段的一个选项。

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

设置一个整数值，表示字段所在的页码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setPosition {#setPosition-float:A-}
```
public void setPosition(float[] value)
```

设置保存字段位置的矩形对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值数组 |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

设置字段文本的旋转角度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setTextColor {#setTextColor-java.awt.Color-}
设置字段文本的颜色。

### setTextEncoding {#setTextEncoding-int-}
```
public void setTextEncoding(int value)
```

设置字段文本的 {@link EncodingType} 文本编码类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | EncodingType 元素 @see EncodingType |
