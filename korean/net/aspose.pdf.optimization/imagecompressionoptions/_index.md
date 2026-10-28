---
title: "클래스 ImageCompressionOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Optimization.ImageCompressionOptions 클래스. 이 클래스는 이미지 압축을 위한 옵션 집합을 포함합니다"
type: docs
weight: 8090
url: /ko/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class

클래스는 이미지 압축을 위한 옵션 집합을 포함합니다.

```csharp
public class ImageCompressionOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | 이 플래그가 true로 설정되면 문서의 이미지가 압축됩니다. 압축 수준은 ImageQuality 속성으로 지정됩니다. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | 이미지를 저장하는 데 사용되는 인코딩을 가져오거나 설정합니다. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | CompressImages 플래그가 사용될 때 이미지 압축 수준을 지정합니다. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | 이미지의 최대 해상도를 지정합니다. 이미지 해상도가 더 높으면 크기가 조정됩니다. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | 이 플래그가 true로 설정되고 CompressImages가 true인 경우, 이미지 해상도가 지정된 MaxResolution 매개변수보다 크면 이미지가 크기 조정됩니다. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | 압축 알고리즘의 버전입니다. 가능한 값은: 1. 표준 압축, 2. fast (표준보다 빠른 향상된 압축이지만 모든 이미지에 적용되지 않을 수 있음), 3. mixed (표준 압축이 더 빠른 알고리즘으로 압축할 수 없는 이미지에 적용되며, 이는 최상의 압축을 제공하지만 \"fast\" 알고리즘보다 느립니다. \"Fast\" 버전은 이미지 크기 조정에 적용되지 않으며 (표준 방법이 사용됩니다). 기본값은 \"Standard\"입니다.) |

### 또 보기

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


