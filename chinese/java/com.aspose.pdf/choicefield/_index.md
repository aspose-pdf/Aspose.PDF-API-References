---
title: "ChoiceField"
linktitle: "ChoiceField"
second_title: "Aspose.PDF for Java API 参考"
description: "表示选择字段的基类。"
type: docs
weight: 590
url: /zh/java/com.aspose.pdf/choicefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public abstract class ChoiceField extends Field
```

表示选择字段的基类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-) | 创建选择字段（用于 Generator） |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | ChoiceField 的构造函数。 |
| [ChoiceField](#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | ChoiceField 的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | 添加具有指定名称的新选项。 |
| [addOption](#addOption-java.lang.String-java.lang.String-) | 添加具有指定导出值和名称的新选项。 |
| [deleteOption](#deleteOption-java.lang.String-) | 按名称删除选项。 |
| [getCommitImmediately](#getCommitImmediately--) | 获取在选择更改时提交的标志。 |
| [getMultiSelect](#getMultiSelect--) | 获取多选标志。 |
| [getOptions](#getOptions--) | 获取选择选项的集合。 |
| [getSelected](#getSelected--) | 获取所选选项的索引。此属性允许更改选择。 |
| [getSelectedItems](#getSelectedItems--) | 设置所选项的数组。对于多选列表，数组包含多个项。对于单选列表，数组仅包含一个项。 |
| [getValue](#getValue--) | 获取字段的值。 |
| [setCommitImmediately](#setCommitImmediately-boolean-) | 设置在选择更改时提交的标志。 |
| [setMultiSelect](#setMultiSelect-boolean-) | 设置多选标志。 |
| [setOptions](#setOptions-java.util.List-) | 用 options 参数中给出的名称替换可用选项。 |
| [setSelected](#setSelected-int-) | 设置所选选项的索引。此属性允许更改选择。 |
| [setSelectedItems](#setSelectedItems-int:A-) | 设置所选项的数组。对于多选列表，数组包含多个项。对于单选列表，数组仅包含一个项。 |
| [setValue](#setValue-java.lang.String-) | 设置字段的值。 |

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-}
创建选择字段（用于 Generator）

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
ChoiceField 的构造函数。

### ChoiceField {#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
ChoiceField 的构造函数。

### addOption {#addOption-java.lang.String-}
添加具有指定名称的新选项。

### addOption {#addOption-java.lang.String-java.lang.String-}
添加具有指定导出值和名称的新选项。

### deleteOption {#deleteOption-java.lang.String-}
按名称删除选项。

### getCommitImmediately {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```

获取在选择更改时提交的标志。

**Returns:**
布尔值

### getMultiSelect {#getMultiSelect--}
```
public boolean getMultiSelect()
```

获取多选标志。

**Returns:**
布尔值

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

获取选择选项的集合。

**Returns:**
OptionCollection 对象

### getSelected {#getSelected--}
```
public int getSelected()
```

获取所选选项的索引。此属性允许更改选择。

**Returns:**
int 值

### getSelectedItems {#getSelectedItems--}
```
public int[] getSelectedItems()
```

设置所选项的数组。对于多选列表，数组包含多个项。对于单选列表，数组仅包含一个项。

**Returns:**
int 值数组

### getValue {#getValue--}
```
public String getValue()
```

获取字段的值。

**Returns:**
字符串值

### setCommitImmediately {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```

设置在选择更改时提交的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMultiSelect {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```

设置多选标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setOptions {#setOptions-java.util.List-}
用 options 参数中给出的名称替换可用选项。

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

设置所选选项的索引。此属性允许更改选择。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

设置所选项的数组。对于多选列表，数组包含多个项。对于单选列表，数组仅包含一个项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值数组 |

### setValue {#setValue-java.lang.String-}
设置字段的值。
