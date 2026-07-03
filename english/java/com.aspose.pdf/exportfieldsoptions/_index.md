---
title: ExportFieldsOptions
second_title: Aspose.PDF for Java API Reference
description: Represents base class of options for exporting form fields.
type: docs
weight: 1310
url: /java/com.aspose.pdf/exportfieldsoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExportFieldsOptions

```
public abstract class ExportFieldsOptions extends Object
```

Represents base class of options for exporting form fields.

## Constructors

| Constructor | Description |
| --- | --- |
| [ExportFieldsOptions](#ExportFieldsOptions--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getExportPasswordValue](#getExportPasswordValue--) | Gets or sets a value indicating whether the password value should be exported. Value: {@code true} if the password value should be exported; otherwise, {@code false}. |
| [getFieldSelector](#getFieldSelector--) | Gets a delegate that determines whether a particular field should be exported. If the delegate is {@code null}, all fields are exported (the default behaviour). |
| [setExportPasswordValue](#setExportPasswordValue-boolean-) | Gets or sets a value indicating whether the password value should be exported. Value: {@code true} if the password value should be exported; otherwise, {@code false}. |
| [setFieldSelector](#setFieldSelector-com.aspose.ms.System.Predicate-) | Sets a delegate that determines whether a particular field should be exported. |

### ExportFieldsOptions {#ExportFieldsOptions--}
```
public ExportFieldsOptions()
```



### getExportPasswordValue {#getExportPasswordValue--}
```
public final boolean getExportPasswordValue()
```

Gets or sets a value indicating whether the password value should be exported. Value: {@code true} if the password value should be exported; otherwise, {@code false}.

**Returns:**
boolean value

### getFieldSelector {#getFieldSelector--}
```
public final com.aspose.ms.System.Predicate< Field > getFieldSelector()
```

Gets a delegate that determines whether a particular field should be exported. If the delegate is {@code null}, all fields are exported (the default behaviour).

**Returns:**
a delegate that determines whether a particular field should be exported.

### setExportPasswordValue {#setExportPasswordValue-boolean-}
```
public final void setExportPasswordValue(boolean value)
```

Gets or sets a value indicating whether the password value should be exported. Value: {@code true} if the password value should be exported; otherwise, {@code false}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setFieldSelector {#setFieldSelector-com.aspose.ms.System.Predicate-}
Sets a delegate that determines whether a particular field should be exported.
