---
title: Class GraphicalPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.GraphicalPdfComparer 클래스. PDF 문서를 그래픽적으로 비교하기 위한 클래스를 나타냅니다. 주로 그래픽적 성격의 작은 변화를 검색하는 데 사용해야 합니다. 텍스트 콘텐츠 변경을 비교하려면 다른 PDF 비교 클래스를 사용하십시오.
type: docs
weight: 3190
url: /ko/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer 클래스

PDF 문서를 그래픽적으로 비교하기 위한 클래스를 나타냅니다. 주로 그래픽적 성격의 작은 변화를 검색하는 데 사용해야 합니다. 텍스트 콘텐츠 변경을 비교하려면 다른 PDF 비교 클래스를 사용하십시오.

```csharp
public class GraphicalPdfComparer
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | 변경 플래그 색상을 가져오고 설정합니다. 기본 색상은 빨간색입니다. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | 결과 이미지의 해상도를 가져오고 설정합니다. 기본 값은 150dpi입니다. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | 백분율로 임계값을 가져오고 설정합니다. 이 값은 중요하지 않은 작은 변화를 무시할 수 있게 해줍니다. 기본 값은 0%입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | 문서를 그래픽적으로 비교합니다. 비교 결과는 이미지에 저장됩니다. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | 문서를 그래픽적으로 비교합니다. 비교 결과는 PDF 문서에 저장됩니다. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | 페이지를 그래픽적으로 비교합니다. 비교 결과는 이미지에 저장됩니다. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | 페이지를 그래픽적으로 비교합니다. 비교 결과는 PDF 문서에 저장됩니다. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | 페이지를 그래픽적으로 비교합니다. 비교 결과는 PDF 문서에 저장됩니다. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | 페이지 이미지 간의 차이를 가져옵니다. 결과에는 비교된 첫 번째 페이지의 이미지와 차이 배열이 포함됩니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* 어셈블리 [Aspose.PDF](../../)