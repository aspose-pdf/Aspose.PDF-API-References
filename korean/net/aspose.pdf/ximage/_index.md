---
title: "클래스 XImage"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.XImage 클래스. 이미지 XObject를 나타내는 클래스"
type: docs
weight: 11540
url: /ko/net/aspose.pdf/ximage/
---
## XImage class

이미지 X-Object를 나타내는 클래스입니다.

```csharp
public sealed class XImage
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | 이미지에 투명성이 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | 이미지 필터 유형을 가져옵니다. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | 이미지의 회색조 버전을 가져옵니다. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | 이미지의 높이를 가져옵니다. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | 이미지를 이미지 마스크로 처리할지 여부를 나타내는 플래그를 가져옵니다 (8.9.6, "Masked Images" 참조). 이 플래그가 true이면 BitsPerComponent 값은 1이어야 하고 Mask와 ColorSpace는 지정되지 않아야 합니다; 마스크되지 않은 영역은 현재 비스트로크 색으로 채워집니다. 기본값: false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | 이미지의 메타데이터. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | 이미지 이름을 가져오거나 설정합니다. 페이지 내용에 참조가 있는 이미지의 이름을 변경하면 Document가 올바르지 않을 수 있습니다. 이 경우 XImage.Rename 메서드를 사용하십시오. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | 이미지의 너비를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | XImage에 스텐실 마스크를 추가합니다. |
| [GetAlternativeText](../../aspose.pdf/ximage/getalternativetext/)(Page) | XImage에 대한 대체 텍스트 문자열 목록을 반환합니다. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | 이미지의 색상 유형을 반환합니다. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | 컬렉션 내 이미지의 이름을 반환합니다. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | 원본 이미지에서 원시 이미지 데이터를 검색합니다. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | 두 이미지가 동일한 객체를 참조하면 true를 반환합니다. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | 이미지의 이름을 바꾸고 이미지에 대한 모든 참조를 새 이름으로 교체합니다. |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | 이미지 데이터를 JPEG 이미지로 스트림에 저장합니다. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | 요청된 형식으로 이미지를 스트림에 저장합니다. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | 지정된 해상도로 JPEG 이미지로 이미지 데이터를 스트림에 저장합니다. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | 요청된 형식과 지정된 해상도로 이미지를 스트림에 저장합니다. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | 원본 이미지 스트림을 반환합니다. |
| [TrySetAlternativeText](../../aspose.pdf/ximage/trysetalternativetext/)(string, Page) | 페이지의 XImage에 대한 대체 텍스트를 설정합니다. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


