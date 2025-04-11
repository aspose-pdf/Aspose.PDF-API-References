---
title: PdfViewer.PrintDocument
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer 메서드. 기본 프린터를 사용하여 Pdf 문서를 인쇄합니다.
type: docs
weight: 320
url: /ko/net/aspose.pdf.facades/pdfviewer/printdocument/
---
## PdfViewer.PrintDocument 메서드

기본 프린터를 사용하여 Pdf 문서를 인쇄합니다.

```csharp
public void PrintDocument()
```

## 예제

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintDocument(ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")
iewer.AutoResize = true;         'print the file with adjusted size
iewer.AutoRotate = true;         'print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
iewer.PrintDocument(ps);
iewer.ClosePdfFile()
```

### 참조

* 클래스 [PdfViewer](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)