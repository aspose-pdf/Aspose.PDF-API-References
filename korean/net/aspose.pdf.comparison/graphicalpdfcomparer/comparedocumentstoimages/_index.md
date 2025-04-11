---
title: GraphicalPdfComparer.CompareDocumentsToImages
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer 메서드. 문서를 그래픽적으로 비교합니다. 비교 결과는 이미지에 배치됩니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer.CompareDocumentsToImages 메서드

문서를 그래픽적으로 비교합니다. 비교 결과는 이미지에 배치됩니다.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document1 | Document | 비교할 첫 번째 문서입니다. |
| document2 | Document | 비교할 두 번째 문서입니다. |
| targetDirectory | String | 비교 결과를 저장할 디렉터리입니다. |
| fileNamePrefix | String | 이미지 이름 접두사입니다. |
| imageFormat | ImageFormat | 저장할 이미지 형식입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 비교되는 페이지의 크기가 다를 경우. targetDirectory가 null이거나 빈 문자열인 경우. fileNamePrefix가 null이거나 빈 문자열인 경우. |

### 참조

* 클래스 [Document](../../../aspose.pdf/document/)
* 클래스 [GraphicalPdfComparer](../)
* 네임스페이스 [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* 어셈블리 [Aspose.PDF](../../../)