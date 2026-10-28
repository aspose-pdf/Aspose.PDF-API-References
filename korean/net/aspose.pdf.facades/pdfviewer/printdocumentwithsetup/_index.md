---
title: "PdfViewer.PrintDocumentWithSetup"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfViewer 메서드. 설정 대화 상자를 사용하여 Pdf Document를 인쇄합니다. 대화 상자를 통해 프린터를 선택하십시오."
type: docs
weight: 340
url: /ko/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## PdfViewer.PrintDocumentWithSetup method

설정 대화 상자를 사용하여 Pdf 문서를 인쇄합니다. 대화 상자를 통해 프린터를 선택하십시오.

```csharp
public void PrintDocumentWithSetup()
```

## 예제

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.BindPdf(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog = false;   //do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup();
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.BindPdf(@"d:\test.pdf")
iewer.AutoResize = True          'print the file with adjusted size
iewer.AutoRotate = True          'print the file with adjusted rotation
iewer.PrintPageDialog = False    'do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup()
iewer.Close()
```

### 또 보기

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


