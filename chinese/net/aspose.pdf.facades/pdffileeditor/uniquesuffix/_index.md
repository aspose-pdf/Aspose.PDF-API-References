---
title: "PdfFileEditor.UniqueSuffix"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 属性。后缀的格式在表单合并时会添加到字段名称以使其唯一。该字符串必须包含 NUM 子串，后者将在运行时被数字替换。例如，如果 UniqueSuffix 为 ABCNUM，则字段 fieldName 的名称将变为 fieldNameABC1、fieldNameABC2、fieldNameABC3 等。"
type: docs
weight: 200
url: /zh/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix property

在合并表单时添加到字段名称以使其唯一的后缀格式。此字符串必须包含 %NUM% 子串，该子串将被数字替换。例如，如果 UniqueSuffix = "ABC%NUM%"，则字段 "fieldName" 的名称将为：fieldNameABC1、fieldNameABC2、fieldNameABC3 等。

```csharp
public string UniqueSuffix { get; set; }
```

## 示例

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


