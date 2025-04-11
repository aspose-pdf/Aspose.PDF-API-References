---
title: GraphicalPdfComparer.GetDifference
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer 메서드. 페이지 이미지 간의 차이를 가져옵니다. 결과에는 비교된 첫 번째 페이지의 이미지와 차이 배열이 포함됩니다.
type: docs
weight: 90
url: /ko/net/aspose.pdf.comparison/graphicalpdfcomparer/getdifference/
---
## GraphicalPdfComparer.GetDifference 메서드

페이지 이미지 간의 차이를 가져옵니다. 결과에는 비교된 첫 번째 페이지의 이미지와 차이 배열이 포함됩니다.

```csharp
public ImagesDifference GetDifference(Page page1, Page page2)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page1 | Page | 첫 번째 페이지. |
| page2 | Page | 두 번째 페이지. |

### 반환 값

[`ImagesDifference`](../../imagesdifference/) 인스턴스.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 비교되는 페이지의 크기가 다를 경우. |

### 참조

* 클래스 [ImagesDifference](../../imagesdifference/)
* 클래스 [Page](../../../aspose.pdf/page/)
* 클래스 [GraphicalPdfComparer](../)
* 네임스페이스 [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* 어셈블리 [Aspose.PDF](../../../)