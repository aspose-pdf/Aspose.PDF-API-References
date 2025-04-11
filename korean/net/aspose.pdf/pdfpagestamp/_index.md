---
title: Class PdfPageStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfPageStamp 클래스. 클래스는 PDF 페이지를 스탬프로 사용하는 스탬프를 나타냅니다.
type: docs
weight: 8420
url: /ko/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp 클래스

클래스는 PDF 페이지를 스탬프로 사용하는 스탬프를 나타냅니다.

```csharp
public sealed class PdfPageStamp : Stamp
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | PdfPageStamp의 생성자. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | 스트림에서 문서의 지정된 페이지로부터 Pdf 페이지 스탬프를 생성합니다. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | 지정된 파일의 문서에서 지정된 페이지로부터 Pdf 페이지 스탬프를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | 콘텐츠가 배경으로 스탬프되었음을 나타내는 bool 값을 설정하거나 가져옵니다. 값이 true이면 스탬프 콘텐츠가 바닥에 놓입니다. 기본값은 false이며, 스탬프 콘텐츠가 위에 놓입니다. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | 스탬프의 하단 여백을 가져오거나 설정합니다. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | 페이지에서 스탬프의 원하는 높이입니다. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | 페이지에서 스탬프의 수평 정렬을 가져오거나 설정합니다. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | 스탬프의 왼쪽 여백을 가져오거나 설정합니다. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | 스탬프 불투명도를 나타내는 값을 가져오거나 설정합니다. 값은 0.0에서 1.0까지입니다. 기본값은 1.0입니다. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | 스탬프 윤곽선 불투명도를 나타내는 값을 가져오거나 설정합니다. 값은 0.0에서 1.0까지입니다. 기본값은 1.0입니다. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | 스탬프 윤곽선의 너비 값을 가져오거나 설정합니다. 기본값은 1.0입니다. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | 스탬프로 사용될 페이지를 가져오거나 설정합니다. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | 스탬프의 오른쪽 여백을 가져오거나 설정합니다. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | [`Rotation`](../rotation/) 값에 따라 스탬프 콘텐츠의 회전을 설정하거나 가져옵니다. 참고: 이 속성은 90도(0, 90, 180, 270도)의 배수인 각도를 설정하는 데 사용됩니다. 임의의 각도를 설정하려면 RotateAngle 속성을 사용하십시오. ArbitraryAngle로 설정된 각도가 90의 배수가 아니면 Rotate 속성은 Rotation.None을 반환합니다. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | 스탬프의 회전 각도를 도 단위로 가져오거나 설정합니다. 이 속성은 임의의 회전 각도를 설정할 수 있습니다. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | 스탬프의 상단 여백을 가져오거나 설정합니다. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | 페이지에서 스탬프의 수직 정렬을 가져오거나 설정합니다. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | 페이지에서 스탬프의 원하는 너비입니다. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | 왼쪽에서 시작하는 수평 스탬프 좌표입니다. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | 아래에서 시작하는 수직 스탬프 좌표입니다. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | 스탬프의 확대 비율입니다. 스탬프를 스케일할 수 있습니다. ZoomX 및 ZoomY 속성 쌍은 각 축에 대해 별도로 확대 비율을 설정할 수 있습니다. 이 속성을 설정하면 ZoomX 및 ZoomY 속성이 모두 변경됩니다. ZoomX와 ZoomY가 다르면 Zoom 속성은 ZoomX 값을 반환합니다. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | 스탬프의 수평 확대 비율입니다. 스탬프를 수평으로 스케일할 수 있습니다. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | 스탬프의 수직 확대 비율입니다. 스탬프를 수직으로 스케일할 수 있습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | 스탬프 ID를 반환합니다. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | 지정된 페이지에 스탬프를 놓습니다. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | 스탬프 ID를 설정합니다. |

### 참조

* 클래스 [Stamp](../stamp/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)