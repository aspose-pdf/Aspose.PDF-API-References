---
title: Single2Multiple
second_title: Aspose.PDF for .NET API 参考
description: 将单行文本字段更改为多行文本字段
type: docs
weight: 390
url: /zh/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple method

将单行文本字段更改为多行文本字段。

```csharp
public bool Single2Multiple(string fieldName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 限定的字段名称。 |

### 返回值

如果成功，则返回 true；否则返回 false。

### 例子

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### 也可以看看

* class [FormEditor](../../formeditor)
* 命名空间 [Aspose.Pdf.Facades](../../formeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
