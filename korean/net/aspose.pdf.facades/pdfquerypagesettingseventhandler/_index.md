---
title: Delegate PdfQueryPageSettingsEventHandler
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer의 PdfQueryPageSettings 이벤트를 처리하는 메서드를 나타냅니다.
type: docs
weight: 4620
url: /ko/net/aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
## PdfQueryPageSettingsEventHandler delegate

[`PdfQueryPageSettings`](../pdfviewer/pdfquerypagesettings/) 이벤트를 처리하는 메서드를 나타냅니다. [`PdfViewer`](../pdfviewer/)의.

```csharp
public delegate void PdfQueryPageSettingsEventHandler(object sender, 
    PdfQueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo);
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sender | Object | 이벤트의 출처. |
| queryPageSettingsEventArgs | PdfQueryPageSettingsEventArgs | 이벤트 데이터를 포함하는 [`PdfQueryPageSettingsEventArgs`](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)입니다. |
| currentPageInfo | PdfPrintPageInfo | 현재 인쇄된 페이지 정보. |

### 참조

* 클래스 [PdfQueryPageSettingsEventArgs](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)
* 클래스 [PdfPrintPageInfo](../pdfprintpageinfo/)
* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)