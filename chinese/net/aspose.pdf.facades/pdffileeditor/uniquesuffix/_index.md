---
title: UniqueSuffix
second_title: Aspose.PDF for .NET API 参考
description: 添加到字段名称以使其在连接表单时唯一的后缀格式 此字符串必须包含将替换为数字的 NUM 子字符串 例如如果 UniqueSuffix  ABCNUM 那么对于字段fieldName名称将是 fieldNameABC1fieldNameABC2fieldNameABC3 等
type: docs
weight: 230
url: /zh/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix property

添加到字段名称以使其在连接表单时唯一的后缀格式。 此字符串必须包含将替换为数字的 %NUM% 子字符串。 例如，如果 UniqueSuffix = "ABC%NUM%" 那么对于字段“fieldName”名称将是： fieldNameABC1、fieldNameABC2、fieldNameABC3 等

```csharp
public string UniqueSuffix { get; set; }
```

### 例子

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
