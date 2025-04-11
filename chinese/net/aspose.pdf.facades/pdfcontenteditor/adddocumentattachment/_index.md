---
title: PdfContentEditor.AddDocumentAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。添加没有注释的文档附件
type: docs
weight: 70
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

添加没有注释的文档附件。

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileAttachmentPath | 字符串 | 将要附加的文件路径。 |
| description | 字符串 | 描述信息。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

添加没有注释的文档附件。

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileAttachmentStream | 流 | 将要附加的文件流。 |
| fileAttachmentName | 字符串 | 附件名称。 |
| description | 字符串 | 描述信息。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)