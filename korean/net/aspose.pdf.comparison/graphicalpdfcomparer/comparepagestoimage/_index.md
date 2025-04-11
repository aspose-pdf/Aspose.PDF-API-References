---
title: GraphicalPdfComparer.ComparePagesToImage
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer 메서드. 페이지를 그래픽적으로 비교합니다. 비교 결과는 이미지에 배치됩니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/
---
## GraphicalPdfComparer.ComparePagesToImage 메서드

페이지를 그래픽적으로 비교합니다. 비교 결과는 이미지에 배치됩니다.

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page1 | Page | 비교할 첫 번째 페이지입니다. |
| page2 | Page | 비교할 두 번째 페이지입니다. |
| resultImagePath | String | 대상 이미지 파일의 경로입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 비교되는 페이지의 크기가 다를 경우. resultImagePath가 null이거나 빈 문자열인 경우. 알 수 없는 이미지 저장 형식이 있는 경우. |

### 참조

* 클래스 [Page](../../../aspose.pdf/page/)
* 클래스 [GraphicalPdfComparer](../)
* 네임스페이스 [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* 어셈블리 [Aspose.PDF](../../../)