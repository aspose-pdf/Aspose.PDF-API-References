---
title: FormEditor.SetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。设置文本字段的最大字符数
type: docs
weight: 310
url: /zh/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit 方法

设置文本字段的最大字符数。

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 文本字段的名称。 |
| fieldLimit | Int32 | 字段的新限制值。 |

### 返回值

如果字段限制成功设置，则返回 true。

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### 另请参阅

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)