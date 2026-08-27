---
title: "클래스 ImagesDifference"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Comparison.ImagesDifference 클래스. 두 PDF Page를 비교한 결과 클래스를 나타냅니다."
type: docs
weight: 3340
url: /ko/net/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class

두 PDF 페이지를 비교한 결과 클래스를 나타냅니다.

```csharp
public sealed class ImagesDifference : IDisposable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | 차이 배열을 가져옵니다. 이 배열은 LockBits 메서드 결과로 얻은 원본 이미지 데이터 배열과 유사합니다. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | 차이의 높이. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | 첫 번째 비교된 Page의 이미지를 가져옵니다. 해당 이미지의 픽셀 형식은 24bpp입니다. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | 차이 이미지 데이터의 스트라이드. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | 지정된 색상을 사용하여 차이 배열을 비트맵 이미지로 변환합니다. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | 객체가 파괴되기 전에 필요한 정리 작업을 수행합니다. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | 차이 배열을 원본 이미지에 적용하여 대상 이미지를 나타내는 새 비트맵을 반환합니다. |

### 또 보기

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


