---
title: "클래스 ImageStamp"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.ImageStamp 클래스. 그래픽 스탬프를 나타냅니다."
type: docs
weight: 6060
url: /ko/net/aspose.pdf/imagestamp/
---
## ImageStamp class

그래픽 스탬프를 나타냅니다.

```csharp
public sealed class ImageStamp : Stamp
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | `ImageStamp` 클래스의 새 인스턴스를 초기화합니다. |
| [ImageStamp](imagestamp/#constructor_1)(string) | 지정된 파일의 이미지를 사용하여 이미지 스탬프를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | 이미지 스탬프의 대체 텍스트를 가져오거나 설정합니다. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | 스탬프의 하단 여백을 가져오거나 설정합니다. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | page 상의 스탬프 원하는 높이. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | 이미지 높이를 가져오거나 설정합니다. 이 이미지를 설정하면 이미지를 수직으로 스케일링할 수 있습니다. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | 스탬프의 왼쪽 여백을 가져오거나 설정합니다. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | 스탬프에 사용되는 이미지 스트림을 가져옵니다. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | 스탬프 불투명도를 나타내는 값을 가져오거나 설정합니다. 값은 0.0에서 1.0 사이이며, 기본값은 1.0입니다. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | 스탬프 외곽선 불투명도를 나타내는 값을 가져오거나 설정합니다. 값은 0.0에서 1.0 사이이며, 기본값은 1.0입니다. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | 스탬프 외곽선 너비 값을 가져오거나 설정합니다. 기본값은 1.0입니다. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | 스탬프로 사용할 page를 가져오거나 설정합니다. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | 이미지 스탬프의 품질을 백분율로 가져오거나 설정합니다. 유효값은 0..100%입니다. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | 스탬프의 오른쪽 여백을 가져오거나 설정합니다. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | 스탬프 내용의 회전을 [`Rotation`](../rotation/) 값에 따라 설정하거나 가져옵니다. 참고: 이 속성은 90도(0, 90, 180, 270도)의 배수인 각도를 설정하기 위한 것입니다. 임의 각도를 설정하려면 RotateAngle 속성을 사용하십시오. ArbitraryAngle 로 설정된 각도가 90의 배수가 아니면 Rotate 속성은 Rotation.None을 반환합니다. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | 스탬프의 회전 각도를 도 단위로 가져오거나 설정합니다. 이 속성을 사용하면 임의의 회전 각도를 설정할 수 있습니다. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | 스탬프의 상단 여백을 가져오거나 설정합니다. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | 페이지에서 스탬프의 수직 정렬을 가져오거나 설정합니다. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | 이미지 너비를 가져오거나 설정합니다. 이 속성을 설정하면 이미지를 수평으로 스케일링할 수 있습니다. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | 왼쪽부터 시작하는 수평 스탬프 좌표를 가져오고 설정합니다. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | 아래쪽부터 시작하는 수직 스탬프 좌표를 가져오고 설정합니다. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | 스탬프의 확대 비율입니다. 스탬프를 확대/축소할 수 있습니다. ZoomX와 ZoomY 속성 쌍을 사용하면 각 축에 대해 별도로 확대 비율을 설정할 수 있다는 점에 유의하십시오. 이 속성을 설정하면 ZoomX와 ZoomY 속성이 모두 변경됩니다. ZoomX와 ZoomY가 다르면 Zoom 속성은 ZoomX 값을 반환합니다. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | 스탬프의 수평 확대 비율입니다. 스탬프를 수평으로 확대/축소할 수 있습니다. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | 스탬프의 수직 확대 비율입니다. 스탬프를 수직으로 확대/축소할 수 있습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | 스탬프 ID를 반환합니다. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Page에 그래픽 스탬프를 추가합니다. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | 스탬프 ID를 설정합니다. |

### 또 보기

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


