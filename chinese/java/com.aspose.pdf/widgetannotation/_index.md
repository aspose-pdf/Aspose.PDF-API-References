---
title: "WidgetAnnotation"
linktitle: "WidgetAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示小部件注释的类。"
type: docs
weight: 5540
url: /zh/java/com.aspose.pdf/widgetannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WidgetAnnotation extends Annotation
```

表示小部件注释的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WidgetAnnotation](#WidgetAnnotation-com.aspose.pdf.IDocument-) | 创建注释（用于生成器） |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者。 |
| [getAnnotationActions](#getAnnotationActions--) | 获取注释操作。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getCheckedStateName](#getCheckedStateName--) | 根据现有状态名称返回 "checked" 状态的名称。 |
| [getDefaultAppearance](#getDefaultAppearance--) | 获取字段的默认外观。 |
| [getExportable](#getExportable--) | 获取字段的可导出标志。 |
| [getHighlighting](#getHighlighting--) | 注释高亮模式。 |
| [getOnActivated](#getOnActivated--) | 获取在注释被激活时应执行的操作。 |
| [getParent](#getParent--) | 获取注释的父对象。 |
| [getReadOnly](#getReadOnly--) | 获取字段的只读状态。 |
| [getRequired](#getRequired--) | 获取字段的必填状态。 |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | 设置字段的默认外观。 |
| [setExportable](#setExportable-boolean-) | 设置字段的只读状态。 |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | 注释高亮模式。 |
| [setOnActivated](#setOnActivated-com.aspose.pdf.PdfAction-) | 设置在注释被激活时应执行的操作。 |
| [setReadOnly](#setReadOnly-boolean-) | 设置字段的只读状态。 |
| [setRequired](#setRequired-boolean-) | 设置字段的只读状态。 |

### WidgetAnnotation {#WidgetAnnotation-com.aspose.pdf.IDocument-}
创建注释（用于生成器）

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受访问者。

### getAnnotationActions {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```

获取注释操作。

**Returns:**
AnnotationActionCollection 对象

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 元素 @see AnnotationType

### getCheckedStateName {#getCheckedStateName--}
```
public final String getCheckedStateName()
```

根据现有状态名称返回 "checked" 状态的名称。

**Returns:**
此注释的 "checked" 状态的名称。

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

获取字段的默认外观。

**Returns:**
DefaultAppearance 对象

### getExportable {#getExportable--}
```
public boolean getExportable()
```

获取字段的可导出标志。

**Returns:**
布尔值

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

注释高亮模式。

**Returns:**
HighlightingMode 值 @see HighlightingMode

### getOnActivated {#getOnActivated--}
```
public PdfAction getOnActivated()
```

获取在注释被激活时应执行的操作。

**Returns:**
PdfAction 对象

### getParent {#getParent--}
```
public Field getParent()
```

获取注释的父对象。

**Returns:**
Field 对象

### getReadOnly {#getReadOnly--}
```
public boolean getReadOnly()
```

获取字段的只读状态。

**Returns:**
布尔值

### getRequired {#getRequired--}
```
public boolean getRequired()
```

获取字段的必填状态。

**Returns:**
布尔值

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
设置字段的默认外观。

### setExportable {#setExportable-boolean-}
```
public void setExportable(boolean value)
```

设置字段的只读状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
注释高亮模式。

### setOnActivated {#setOnActivated-com.aspose.pdf.PdfAction-}
设置在注释被激活时应执行的操作。

### setReadOnly {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```

设置字段的只读状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRequired {#setRequired-boolean-}
```
public void setRequired(boolean value)
```

设置字段的只读状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
