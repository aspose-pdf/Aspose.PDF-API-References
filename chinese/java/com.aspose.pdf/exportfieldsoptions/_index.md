---
title: "ExportFieldsOptions"
linktitle: "ExportFieldsOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示导出表单字段选项的基类。"
type: docs
weight: 1310
url: /zh/java/com.aspose.pdf/exportfieldsoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExportFieldsOptions

```
public abstract class ExportFieldsOptions extends Object
```

表示导出表单字段选项的基类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ExportFieldsOptions](#ExportFieldsOptions--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getExportPasswordValue](#getExportPasswordValue--) | 获取或设置一个值，指示是否应导出密码值。值：{@code true} 表示应导出密码值；否则 {@code false}。 |
| [getFieldSelector](#getFieldSelector--) | 获取一个委托，用于确定是否应导出特定字段。如果委托为 {@code null}，则导出所有字段（默认行为）。 |
| [setExportPasswordValue](#setExportPasswordValue-boolean-) | 获取或设置一个值，指示是否应导出密码值。值：{@code true} 表示应导出密码值；否则 {@code false}。 |
| [setFieldSelector](#setFieldSelector-com.aspose.ms.System.Predicate-) | 设置一个委托，用于确定是否应导出特定字段。 |

### ExportFieldsOptions {#ExportFieldsOptions--}
```
public ExportFieldsOptions()
```



### getExportPasswordValue {#getExportPasswordValue--}
```
public final boolean getExportPasswordValue()
```

获取或设置一个值，指示是否应导出密码值。值：{@code true} 表示应导出密码值；否则 {@code false}。

**Returns:**
布尔值

### getFieldSelector {#getFieldSelector--}
```
public final com.aspose.ms.System.Predicate< Field > getFieldSelector()
```

获取一个委托，用于确定是否应导出特定字段。如果委托为 {@code null}，则导出所有字段（默认行为）。

**Returns:**
一个委托，用于确定是否应导出特定字段。

### setExportPasswordValue {#setExportPasswordValue-boolean-}
```
public final void setExportPasswordValue(boolean value)
```

获取或设置一个值，指示是否应导出密码值。值：{@code true} 表示应导出密码值；否则 {@code false}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setFieldSelector {#setFieldSelector-com.aspose.ms.System.Predicate-}
设置一个委托，用于确定是否应导出特定字段。
