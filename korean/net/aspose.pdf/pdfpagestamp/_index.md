---
title: "Aspose.Pdf.PdfPageStamp 클래스. 이 클래스는 PDF page를 스탬프로 사용하는 스탬프를 나타냅니다."
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfPageStamp의 생성자."
type: docs
weight: 8560
url: /ko/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class

PDF 페이지를 스탬프로 사용하는 스탬프를 나타내는 클래스입니다.

```csharp
public sealed class PdfPageStamp : Stamp
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | 스트림에서 Document의 지정된 page를 사용하여 Pdf page stamp을 생성합니다. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | 지정된 파일에서 Document의 지정된 page를 사용하여 Pdf page stamp을 생성합니다. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | 콘텐츠가 배경으로 스탬프되는지를 나타내는 bool 값을 설정하거나 가져옵니다. 값이 true이면 스탬프 콘텐츠가 하단에 배치됩니다. 기본값은 false이며, 스탬프 콘텐츠가 상단에 배치됩니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | 스탬프의 하단 여백을 가져오거나 설정합니다. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | page 상의 스탬프 원하는 높이. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | page 상의 스탬프 가로 정렬을 가져오거나 설정합니다. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | 스탬프의 왼쪽 여백을 가져오거나 설정합니다. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | 스탬프 불투명도를 나타내는 값을 가져오거나 설정합니다. 값은 0.0에서 1.0 사이이며, 기본값은 1.0입니다. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | 스탬프 외곽선 불투명도를 나타내는 값을 가져오거나 설정합니다. 값은 0.0에서 1.0 사이이며, 기본값은 1.0입니다. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | 스탬프 외곽선 너비 값을 가져오거나 설정합니다. 기본값은 1.0입니다. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | 스탬프로 사용할 page를 가져오거나 설정합니다. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | 스탬프에 사용될 페이지를 가져오거나 설정합니다. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | 스탬프의 오른쪽 여백을 가져오거나 설정합니다. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | 스탬프 내용의 회전을 [`Rotation`](../rotation/) 값에 따라 설정하거나 가져옵니다. 참고: 이 속성은 90도(0, 90, 180, 270도)의 배수인 각도를 설정하기 위한 것입니다. 임의 각도를 설정하려면 RotateAngle 속성을 사용하십시오. ArbitraryAngle 로 설정된 각도가 90의 배수가 아니면 Rotate 속성은 Rotation.None을 반환합니다. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | 스탬프의 회전 각도를 도 단위로 가져오거나 설정합니다. 이 속성을 사용하면 임의의 회전 각도를 설정할 수 있습니다. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | 스탬프의 상단 여백을 가져오거나 설정합니다. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | 페이지에서 스탬프의 수직 정렬을 가져오거나 설정합니다. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | 페이지에서 스탬프의 원하는 너비입니다. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | 왼쪽부터 시작하는 스탬프의 수평 좌표입니다. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | 바닥부터 시작하는 스탬프의 수직 좌표입니다. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | 스탬프의 확대 비율입니다. 스탬프를 확대/축소할 수 있습니다. ZoomX와 ZoomY 속성 쌍을 사용하면 각 축에 대해 별도로 확대 비율을 설정할 수 있다는 점에 유의하십시오. 이 속성을 설정하면 ZoomX와 ZoomY 속성이 모두 변경됩니다. ZoomX와 ZoomY가 다르면 Zoom 속성은 ZoomX 값을 반환합니다. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | 스탬프의 수평 확대 비율입니다. 스탬프를 수평으로 확대/축소할 수 있습니다. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | 스탬프의 수직 확대 비율입니다. 스탬프를 수직으로 확대/축소할 수 있습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | 스탬프 ID를 반환합니다. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | 지정된 페이지에 스탬프를 배치합니다. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | 스탬프 ID를 설정합니다. |

### 또 보기

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


