---
title: "PdfContentEditor.AddDocumentAttachment"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。添加没有注释的文档附件"
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
| fileAttachmentPath | String | 将附加文件的路径。 |
| description | String | 描述信息。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

添加没有注释的文档附件。

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileAttachmentStream | Stream | 文件的流将被附加。 |
| fileAttachmentName | String | 附件名称。 |
| description | String | 描述信息。 |

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

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


