---
title: "PdfContentEditor.DeleteAttachments"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. PDF 문서의 모든 첨부 파일을 삭제합니다."
type: docs
weight: 310
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/deleteattachments/
---
## PdfContentEditor.DeleteAttachments method

PDF 문서의 모든 첨부 파일을 삭제합니다.

```csharp
public void DeleteAttachments()
```

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteAttachments();
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


