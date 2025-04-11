---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 属性。添加到字段名称以使其在表单连接时唯一的后缀格式。该字符串必须包含 NUM 子字符串，该子字符串将被数字替换。例如，如果 UniqueSuffix 为 ABCNUM，则字段 fieldName 的名称将为 fieldNameABC1、fieldNameABC2、fieldNameABC3 等。
type: docs
weight: 200
url: /zh/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix 属性

添加到字段名称以使其在表单连接时唯一的后缀格式。该字符串必须包含 %NUM% 子字符串，该子字符串将被数字替换。例如，如果 UniqueSuffix = "ABC%NUM%"，则字段 "fieldName" 的名称将为：fieldNameABC1、fieldNameABC2、fieldNameABC3 等。

```csharp
public string UniqueSuffix { get; set; }
```

## 示例

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)