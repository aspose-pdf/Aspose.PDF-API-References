---
title: PdfContentEditor.AddDocumentAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 주석 없이 문서 첨부파일을 추가합니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

주석 없이 문서 첨부파일을 추가합니다.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileAttachmentPath | String | 첨부할 파일의 경로입니다. |
| description | String | 설명 정보입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### 참조

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

주석 없이 문서 첨부파일을 추가합니다.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileAttachmentStream | Stream | 첨부할 파일의 스트림입니다. |
| fileAttachmentName | String | 첨부파일 이름입니다. |
| description | String | 설명 정보입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### 참조

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)