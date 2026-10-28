---
title: "GraphicalPdfComparer.ComparePagesToPdf"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "GraphicalPdfComparer 메서드. 페이지를 그래픽으로 비교합니다. 비교 결과는 PDF 문서에 배치됩니다."
type: docs
weight: 80
url: /ko/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

페이지를 그래픽적으로 비교합니다. 비교 결과는 PDF 문서에 배치됩니다.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page1 | 페이지 | 첫 번째 페이지. |
| page2 | 페이지 | 두 번째 페이지. |
| resultPdfPath | String | 대상 PDF 파일의 경로. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 비교되는 페이지의 크기가 다른 경우. resultPdfPath가 null이거나 빈 문자열인 경우. |

### 또 보기

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

페이지를 그래픽적으로 비교합니다. 비교 결과는 PDF 문서에 배치됩니다.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page1 | 페이지 | 첫 번째 페이지. |
| page2 | 페이지 | 두 번째 페이지. |
| pdfDocument | Document | PDF 문서 인스턴스. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 비교되는 페이지의 크기가 서로 다른 경우. |

### 또 보기

* class [Page](../../../aspose.pdf/page/)
* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


