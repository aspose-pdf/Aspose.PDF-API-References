---
title: Class StartEndPageEventArgs
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Printing.StartEndPageEventArgs 클래스. PdfViewer 클래스의 StartPage 및 EndPage 이벤트에 대한 데이터를 제공합니다.
type: docs
weight: 9710
url: /ko/net/aspose.pdf.printing/startendpageeventargs/
---
## StartEndPageEventArgs 클래스

[`PdfViewer`](../../aspose.pdf.facades/pdfviewer/) 클래스의 [`StartPage`](../../aspose.pdf.facades/pdfviewer/startpage/) 및 [`EndPage`](../../aspose.pdf.facades/pdfviewer/endpage/) 이벤트에 대한 데이터를 제공합니다.

```csharp
public sealed class StartEndPageEventArgs : EventArgs
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [StartEndPageEventArgs](startendpageeventargs/)(int, int, int, int) | `StartEndPageEventArgs` 클래스의 새 인스턴스를 초기화합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| readonly [CurrentCopy](../../aspose.pdf.printing/startendpageeventargs/currentcopy/) | 현재 인쇄 중인 복사본의 번호를 가져옵니다. |
| readonly [CurrentPage](../../aspose.pdf.printing/startendpageeventargs/currentpage/) | 현재 인쇄 중인 페이지의 번호를 가져옵니다. |
| readonly [TotalCopies](../../aspose.pdf.printing/startendpageeventargs/totalcopies/) | 인쇄할 총 복사본 수를 가져옵니다. |
| readonly [TotalPages](../../aspose.pdf.printing/startendpageeventargs/totalpages/) | 인쇄할 총 페이지 수를 가져옵니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Printing](../../aspose.pdf.printing/)
* 어셈블리 [Aspose.PDF](../../)