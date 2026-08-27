---
title: "CheckboxField"
linktitle: "CheckboxField"
second_title: "Aspose.PDF for Java API 参考"
description: "类表示复选框字段。"
type: docs
weight: 580
url: /zh/java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Field, com.aspose.pdf.CheckboxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class CheckboxField extends Field
```

类表示复选框字段。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CheckboxField](#CheckboxField--) | 创建 CheckboxField 实例。 @deprecated 要获得完整的字段功能，需要绑定到文档 - 使用 CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-) | 创建 CheckboxField 实例。 @deprecated 要获得完整的字段功能，需要绑定到文档 - 使用 CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | 创建 CheckboxField 实例。 @deprecated 要获得完整的字段功能，需要绑定到文档 - 使用 CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 创建 CheckboxField 实例。 @deprecated 要获得完整的字段功能，需要绑定到文档 - 使用 CheckboxField(Document doc) |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | 向复选框组中添加新的复选框，在该组中一次最多只能选中一个复选框。新复选框被添加到组的底部。 |
| [addOption](#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-) | 向复选框组中添加新的复选框，在该组中一次最多只能选中一个复选框。 |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | 向复选框组中添加新的复选框，在该组中一次最多只能选中一个复选框。 |
| [deepClone](#deepClone--) | 克隆复选框。 |
| [getActiveState](#getActiveState--) | 获取当前注释外观状态。 |
| [getAllowedStates](#getAllowedStates--) | 返回允许状态的列表。 |
| [getChecked](#getChecked--) | 获取复选框的状态。 |
| [getExportValue](#getExportValue--) | 获取或设置 CheckBox 字段的导出值。 |
| [getNormalCaption](#getNormalCaption--) | 获取字段的普通标题。 |
| [getOnState](#getOnState--) | 返回状态的名称，该状态是复选框的 "Checked" 状态。如果存在则为 "Yes"，否则为除 "Off" 之外的任何其他值为 "No"； |
| [getStyle](#getStyle--) | 获取复选框的样式。 |
| [getValue](#getValue--) | 获取复选框字段的值。 |
| [setActiveState](#setActiveState-java.lang.String-) | 设置当前注释的外观状态。 |
| [setChecked](#setChecked-boolean-) | 设置复选框的状态。 |
| [setExportValue](#setExportValue-java.lang.String-) | 获取或设置 CheckBox 字段的导出值。 |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | 设置复选框的样式。 |
| [setValue](#setValue-java.lang.String-) | 设置复选框字段的值。 |

### CheckboxField {#CheckboxField--}
```
@Deprecated public CheckboxField()
```

创建 CheckboxField 实例。 @deprecated 要获得完整的字段功能，需要绑定到文档 - 使用 CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-}
创建 CheckboxField 实例。 @deprecated 要获得完整的字段功能，需要绑定到文档 - 使用 CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
创建 CheckboxField 实例。 @deprecated 要获得完整的字段功能，需要绑定到文档 - 使用 CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
创建 CheckboxField 实例。 @deprecated 要获得完整的字段功能，需要绑定到文档 - 使用 CheckboxField(Document doc)

### addOption {#addOption-java.lang.String-}
向复选框组中添加新的复选框，在该组中一次最多只能选中一个复选框。新复选框被添加到组的底部。

### addOption {#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-}
向复选框组中添加新的复选框，在该组中一次最多只能选中一个复选框。

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
向复选框组中添加新的复选框，在该组中一次最多只能选中一个复选框。

### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆复选框。

**Returns:**
克隆的对象。

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

获取当前注释外观状态。

**Returns:**
字符串值

### getAllowedStates {#getAllowedStates--}
```
public List < String > getAllowedStates()
```

返回允许状态的列表。

**Returns:**
String 值的列表

### getChecked {#getChecked--}
```
public boolean getChecked()
```

获取复选框的状态。

**Returns:**
布尔值

### getExportValue {#getExportValue--}
```
public final String getExportValue()
```

获取或设置 CheckBox 字段的导出值。

**Returns:**
字符串值

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

获取字段的普通标题。

**Returns:**
字符串值

### getOnState {#getOnState--}
```
public String getOnState()
```

返回状态的名称，该状态是复选框的 "Checked" 状态。如果存在则为 "Yes"，否则为除 "Off" 之外的任何其他值为 "No"；

**Returns:**
字符串值

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

获取复选框的样式。

**Returns:**
复选框的样式。 @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

获取复选框字段的值。

**Returns:**
字符串值

### setActiveState {#setActiveState-java.lang.String-}
设置当前注释的外观状态。

### setChecked {#setChecked-boolean-}
```
public void setChecked(boolean value)
```

设置复选框的状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setExportValue {#setExportValue-java.lang.String-}
获取或设置 CheckBox 字段的导出值。

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
设置复选框的样式。

### setValue {#setValue-java.lang.String-}
设置复选框字段的值。
