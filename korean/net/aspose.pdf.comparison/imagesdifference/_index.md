---
title: Class ImagesDifference
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ImagesDifference 클래스. 두 PDF 페이지를 비교한 결과 클래스를 나타냅니다.
type: docs
weight: 3230
url: /ko/net/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class

두 PDF 페이지를 비교한 결과 클래스를 나타냅니다.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | 차이 배열을 가져옵니다. 이 배열은 LockBits 메서드의 결과로 얻어진 원본 이미지 데이터 배열과 유사합니다. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | 차이의 높이입니다. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | 첫 번째 비교된 페이지의 이미지를 가져옵니다. 이미지는 24bpp 픽셀 형식을 가지고 있습니다. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | 차이 이미지 데이터의 스트라이드입니다. |

## Methods

| Name | Description |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | 지정된 색상을 사용하여 차이 배열을 비트맵 이미지로 변환합니다. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | 객체가 파괴되기 전에 필요한 정리 작업을 수행합니다. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | 차이 배열을 소스 이미지에 적용하여 목적지 이미지를 나타내는 새 비트맵을 반환합니다. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)