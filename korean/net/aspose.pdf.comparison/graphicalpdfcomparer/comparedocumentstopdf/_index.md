---
title: GraphicalPdfComparer.CompareDocumentsToPdf
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer 메서드. 문서를 그래픽적으로 비교합니다. 비교 결과는 PDF 문서에 배치됩니다.
type: docs
weight: 60
url: /ko/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/
---
## GraphicalPdfComparer.CompareDocumentsToPdf 메서드

문서를 그래픽적으로 비교합니다. 비교 결과는 PDF 문서에 배치됩니다.

```csharp
public void CompareDocumentsToPdf(Document document1, Document document2, string resultPdfPath)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document1 | Document | 비교할 첫 번째 문서입니다. |
| document2 | Document | 비교할 두 번째 문서입니다. |
| resultPdfPath | String | 대상 PDF 파일 경로입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 비교되는 페이지의 크기가 다를 경우. resultPdfPath가 null이거나 빈 문자열일 경우. |

### 참조

* 클래스 [Document](../../../aspose.pdf/document/)
* 클래스 [GraphicalPdfComparer](../)
* 네임스페이스 [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* 어셈블리 [Aspose.PDF](../../../)