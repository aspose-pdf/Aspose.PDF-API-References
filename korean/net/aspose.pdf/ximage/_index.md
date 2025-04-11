---
title: Class XImage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XImage 클래스. 이미지 XObject를 나타내는 클래스
type: docs
weight: 11350
url: /ko/net/aspose.pdf/ximage/
---
## XImage 클래스

이미지 X-Object를 나타내는 클래스.

```csharp
public sealed class XImage
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | 이미지에 투명성이 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | 이미지 필터 유형을 가져옵니다. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | 이미지의 그레이스케일 버전을 가져옵니다. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | 이미지의 높이를 가져옵니다. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | 이미지가 이미지 마스크로 처리되어야 하는지 여부를 나타내는 플래그를 가져옵니다(8.9.6, "마스킹된 이미지" 참조). 이 플래그가 true이면 BitsPerComponent의 값은 1이어야 하며 Mask와 ColorSpace는 지정되지 않아야 합니다; 마스킹되지 않은 영역은 현재 비스트로킹 색상을 사용하여 칠해집니다. 기본값: false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | 이미지의 메타데이터. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | 이미지 이름을 가져오거나 설정합니다. 페이지 내용에 참조가 있는 이미지의 이름을 변경하면 문서가 잘못될 수 있습니다. 이 경우 XImage.Rename 메서드를 사용하십시오. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | 이미지의 너비를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | XImage에 스텐실 마스크를 추가합니다. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | 이미지의 색상 유형을 반환합니다. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | 컬렉션에서 이미지의 이름을 반환합니다. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | 원본 이미지에서 원시 이미지 데이터를 검색합니다. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | 두 이미지가 동일한 객체를 참조하면 true를 반환합니다. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | 이미지를 이름을 바꾸고 이미지에 대한 모든 참조를 새 이름으로 교체합니다. |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | 이미지를 JPEG 이미지로 스트림에 저장합니다. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | 요청된 형식으로 이미지를 스트림에 저장합니다. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | 지정된 해상도로 JPEG 이미지로 스트림에 이미지 데이터를 저장합니다. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | 요청된 형식과 지정된 해상도로 이미지를 스트림에 저장합니다. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | 원본 이미지 스트림을 반환합니다. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)