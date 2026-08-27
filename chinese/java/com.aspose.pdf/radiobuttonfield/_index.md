---
title: "RadioButtonField"
linktitle: "RadioButtonField"
second_title: "Aspose.PDF for Java API 参考"
description: "表示单选按钮字段的类。"
type: docs
weight: 4080
url: /zh/java/com.aspose.pdf/radiobuttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.ChoiceField, com.aspose.pdf.RadioButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class RadioButtonField extends ChoiceField
```

表示单选按钮字段的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.IDocument-) | RadioButtonField 的构造函数。 |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-) | RadiouttonField 的构造函数。 |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 设置单选按钮字段。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.RadioButtonOptionField-) | 向 RadioButton 字段添加新选项字段。 |
| [addOption](#addOption-java.lang.String-) | 向 radion 按钮添加选项。 |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | 使用指定的矩形向单选按钮选项添加。 |
| [getNoToggleToOff](#getNoToggleToOff--) | <p> 获取或设置允许单选按钮没有选中值的标志。如果 {@code }，始终只能选中一个单选按钮；选择当前已选中的按钮不会产生效果。如果 {@code }，点击已选中的按钮会取消选中，使得没有按钮被选中。 </p> <hr> 某些 PDF 阅读器（包括 Adobe Acrobat）可能会忽略该标志的状态。 |
| [getOptions](#getOptions--) | 获取单选按钮的选项集合。 |
| [getPageIndex](#getPageIndex--) | 获取包含此 RadioButton 字段的页面索引。 |
| [getSelected](#getSelected--) | 获取所选项的索引。项目编号从 1 开始。 |
| [getStyle](#getStyle--) | 字段框的样式。 |
| [getValue](#getValue--) | 获取字段的值。 |
| [setNoToggleToOff](#setNoToggleToOff-boolean-) | <p> 获取或设置允许单选按钮没有选中值的标志。如果 {@code }，始终只能选中一个单选按钮；选择当前已选中的按钮不会产生效果。如果 {@code }，点击已选中的按钮会取消选中，使得没有按钮被选中。 </p> <hr> 某些 PDF 阅读器（包括 Adobe Acrobat）可能会忽略该标志的状态。 |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | 将单选按钮的所有子项移动到页面上指定的位置。 |
| [setSelected](#setSelected-int-) | 设置所选项的索引。项目编号从 1 开始。 |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | 字段框的样式。 |
| [setValue](#setValue-java.lang.String-) | 设置字段的值。 |
| [updateAppearances](#updateAppearances--) | 更新外观值。 |

### RadioButtonField {#RadioButtonField-com.aspose.pdf.IDocument-}
RadioButtonField 的构造函数。

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-}
RadiouttonField 的构造函数。

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
设置单选按钮字段。

### add {#add-com.aspose.pdf.RadioButtonOptionField-}
向 RadioButton 字段添加新选项字段。

### addOption {#addOption-java.lang.String-}
向 radion 按钮添加选项。

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
使用指定的矩形向单选按钮选项添加。

### getNoToggleToOff {#getNoToggleToOff--}
```
public final boolean getNoToggleToOff()
```

<p> 获取或设置允许单选按钮没有选中值的标志。如果 {@code }，始终只能选中一个单选按钮；选择当前已选中的按钮不会产生效果。如果 {@code }，点击已选中的按钮会取消选中，使得没有按钮被选中。 </p> <hr> 某些 PDF 阅读器（包括 Adobe Acrobat）可能会忽略该标志的状态。

**Returns:**
布尔值

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

获取单选按钮的选项集合。

**Returns:**
OptionCollection 对象

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

获取包含此 RadioButton 字段的页面索引。

**Returns:**
int 值

### getSelected {#getSelected--}
```
public int getSelected()
```

获取所选项的索引。项目编号从 1 开始。

**Returns:**
int 值

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

字段框的样式。

**Returns:**
BoxStyle 值 @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

获取字段的值。

**Returns:**
字符串值

### setNoToggleToOff {#setNoToggleToOff-boolean-}
```
public final void setNoToggleToOff(boolean value)
```

<p> 获取或设置允许单选按钮没有选中值的标志。如果 {@code }，始终只能选中一个单选按钮；选择当前已选中的按钮不会产生效果。如果 {@code }，点击已选中的按钮会取消选中，使得没有按钮被选中。 </p> <hr> 某些 PDF 阅读器（包括 Adobe Acrobat）可能会忽略该标志的状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setPosition {#setPosition-com.aspose.pdf.Point-}
将单选按钮的所有子项移动到页面上指定的位置。

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

设置所选项的索引。项目编号从 1 开始。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
字段框的样式。

### setValue {#setValue-java.lang.String-}
设置字段的值。

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

更新外观值。
