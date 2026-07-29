---
title: "DateField"
linktitle: "DateField"
second_title: "Aspose.PDF for Java API 参考"
description: "带日历视图的日期字段。DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField"
type: docs
weight: 920
url: /zh/java/com.aspose.pdf/datefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.DateField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.DateField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.DateField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.DateField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.DateField, com.aspose.pdf.TextBoxField, com.aspose.pdf.DateField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class DateField extends TextBoxField
```

带日历视图的日期字段。DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DateField](#DateField--) | 初始化 {@link DateField} 的新实例 |
| [DateField](#DateField-com.aspose.pdf.Document-) | 初始化 {@link DateField} 的新实例 |
| [DateField](#DateField-com.aspose.pdf.Document-com.aspose.pdf.Rectangle-) | 初始化 {@link DateField} 的新实例 |
| [DateField](#DateField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 初始化 {@link DateField} 的新实例 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addImage_DateField_New](#addImage_DateField_New-java.awt.image.BufferedImage-) | 此字段不允许添加图像。 |
| [getDateFormat](#getDateFormat--) | 获取或设置日期格式。值：日期格式。默认 dd/MM/yyyy |
| [getValue_DateField_New](#getValue_DateField_New--) | 获取或设置日期。 |
| [init](#init-com.aspose.pdf.Page-) | 初始化 JS 操作。 |
| [setDateFormat](#setDateFormat-java.lang.String-) | 获取或设置日期格式。值：日期格式。默认 dd/MM/yyyy |
| [setValue_DateField_New](#setValue_DateField_New-java.util.Date-) | 获取或设置日期。 |

### DateField {#DateField--}
```
public DateField()
```

初始化 {@link DateField} 的新实例

### DateField {#DateField-com.aspose.pdf.Document-}
初始化 {@link DateField} 的新实例

### DateField {#DateField-com.aspose.pdf.Document-com.aspose.pdf.Rectangle-}
初始化 {@link DateField} 的新实例

### DateField {#DateField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
初始化 {@link DateField} 的新实例

### addImage_DateField_New {#addImage_DateField_New-java.awt.image.BufferedImage-}
此字段不允许添加图像。

### getDateFormat {#getDateFormat--}
```
public final String getDateFormat()
```

获取或设置日期格式。值：日期格式。默认 dd/MM/yyyy

**Returns:**
字符串值

### getValue_DateField_New {#getValue_DateField_New--}
```
public final Date getValue_DateField_New()
```

获取或设置日期。

**Returns:**
java.util.Date instance

### init {#init-com.aspose.pdf.Page-}
初始化 JS 操作。

### setDateFormat {#setDateFormat-java.lang.String-}
获取或设置日期格式。值：日期格式。默认 dd/MM/yyyy

### setValue_DateField_New {#setValue_DateField_New-java.util.Date-}
获取或设置日期。
