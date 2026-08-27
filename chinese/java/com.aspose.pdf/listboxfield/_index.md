---
title: "ListBoxField"
linktitle: "ListBoxField"
second_title: "Aspose.PDF for Java API 参考"
description: "类表示 ListBox 字段。"
type: docs
weight: 2770
url: /zh/java/com.aspose.pdf/listboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.ChoiceField, com.aspose.pdf.ListBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class ListBoxField extends ChoiceField
```

类表示 ListBox 字段。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ListBoxField](#ListBoxField--) | 用于 Generator 的 ListBoxField 构造函数。 |
| [ListBoxField](#ListBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | 用于 Generator 的 ListBoxField 构造函数。 |
| [ListBoxField](#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 用于 Generator 的 ListBoxField 构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getTopIndex](#getTopIndex--) | 获取列表中顶部可见元素的索引。 |
| [setSelected](#setSelected-int-) | 获取所选项的索引。项目从 1 开始编号。 |
| [setSelectedItems](#setSelectedItems-int:A-) | 设置多选列表中所选项的数组。对于单选列表，返回仅包含单个项目的数组。 |
| [setTopIndex](#setTopIndex-int-) | 设置列表中顶部可见元素的索引。 |

### ListBoxField {#ListBoxField--}
```
public ListBoxField()
```

用于 Generator 的 ListBoxField 构造函数。

### ListBoxField {#ListBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
用于 Generator 的 ListBoxField 构造函数。

### ListBoxField {#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
用于 Generator 的 ListBoxField 构造函数。

### getTopIndex {#getTopIndex--}
```
public int getTopIndex()
```

获取列表中顶部可见元素的索引。

**Returns:**
int 值

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

获取所选项的索引。项目从 1 开始编号。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

设置多选列表中所选项的数组。对于单选列表，返回仅包含单个项目的数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值数组 |

### setTopIndex {#setTopIndex-int-}
```
public void setTopIndex(int value)
```

设置列表中顶部可见元素的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
