---
title: Class TextStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TextStamp 클래스. 텍스트 스탬프를 나타냅니다.
type: docs
weight: 11080
url: /ko/net/aspose.pdf/textstamp/
---
## TextStamp 클래스

텍스트 스탬프를 나타냅니다.

```csharp
public class TextStamp : Stamp
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextStamp](textstamp/#constructor)(FormattedText) | 형식화된 텍스트 객체로 `TextStamp` 클래스의 새 인스턴스를 초기화합니다. |
| [TextStamp](textstamp/#constructor_1)(string) | `TextStamp` 클래스의 새 인스턴스를 초기화합니다. |
| [TextStamp](textstamp/#constructor_2)(string, TextState) | `TextStamp` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | 글꼴 크기 정밀도를 자동으로 조정합니다. 기본값: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | 활성화되면 글꼴 크기가 크기에 맞게 자동으로 조정됩니다: [`Width`](./width/) 및 [`Height`](./height/). 기본 너비와 높이는 페이지 사각형에서 파생됩니다. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | 콘텐츠가 배경으로 스탬프되었음을 나타내는 bool 값을 설정하거나 가져옵니다. 값이 true이면 스탬프 콘텐츠가 하단에 배치됩니다. 기본적으로 값은 false이며, 스탬프 콘텐츠가 상단에 배치됩니다. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | 스탬프의 하단 여백을 가져오거나 설정합니다. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | 이 속성은 페이지에 스탬프가 그려지는 방식을 결정합니다. Draw = true이면 스탬프가 그래픽 연산자로 그려지고, draw = false이면 스탬프가 텍스트로 그려집니다. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | 스탬프가 배치된 후의 실제 글꼴 크기입니다. ('AutoAdjustFontSizeToFitStampRectangle' 옵션이 활성화된 경우 생성자를 통해 제공된 초기 글꼴 크기와 다를 수 있습니다.) |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | 페이지에서 스탬프의 원하는 높이입니다. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | 페이지에서 스탬프의 수평 정렬을 가져오거나 설정합니다. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | 텍스트 정당화를 정의합니다. 이 속성이 true로 설정되면 텍스트의 왼쪽 및 오른쪽 가장자리가 정렬됩니다. 기본값: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | 스탬프의 왼쪽 여백을 가져오거나 설정합니다. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | WordWrap 옵션의 최대 행 높이입니다. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | 요청된 문자가 포함되지 않은 경우의 동작을 정의하는 모드를 가져오거나 설정합니다. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | 스탬프 불투명도를 나타내는 값을 가져오거나 설정합니다. 값은 0.0에서 1.0 사이입니다. 기본적으로 값은 1.0입니다. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | 스탬프 윤곽선 불투명도를 나타내는 값을 가져오거나 설정합니다. 값은 0.0에서 1.0 사이입니다. 기본적으로 값은 1.0입니다. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | 스탬프 윤곽선의 너비 값을 가져오거나 설정합니다. 기본적으로 값은 1.0입니다. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | 사용자가 요구하는 문자를 포함하지 않는 경우 대체에 사용되는 글꼴을 가져오거나 설정합니다. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | 스탬프의 오른쪽 여백을 가져오거나 설정합니다. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | [`Rotation`](../rotation/) 값에 따라 스탬프 콘텐츠의 회전을 설정하거나 가져옵니다. 참고: 이 속성은 90도(0, 90, 180, 270도)의 배수인 각도를 설정하는 데 사용됩니다. 임의의 각도를 설정하려면 RotateAngle 속성을 사용하십시오. ArbitraryAngle로 설정된 각도가 90의 배수가 아니면 Rotate 속성은 Rotation.None을 반환합니다. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | 스탬프의 회전 각도를 도 단위로 가져오거나 설정합니다. 이 속성은 임의의 회전 각도를 설정할 수 있습니다. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | 텍스트의 스케일링을 정의합니다. 이 속성이 true로 설정되고 너비 값이 지정되면 텍스트는 지정된 너비에 맞게 스케일됩니다. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | 스탬프 내부의 텍스트 정렬입니다. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | 스탬프의 텍스트 속성을 가져옵니다. 자세한 내용은 [`TextState`](./textstate/)를 참조하십시오. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | 스탬프의 상단 여백을 가져오거나 설정합니다. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | 텍스트 배치의 좌표 원점을 정의합니다. TreatYIndentAsBaseLine = true (Draw = true일 때 기본값)인 경우 YIndent 값은 텍스트 기준선으로 처리됩니다. TreatYIndentAsBaseLine = false (Draw = false일 때 기본값)인 경우 YIndent 값은 텍스트의 하단(하강선)으로 처리됩니다. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | 페이지에서 스탬프로 사용되는 문자열 값을 가져오거나 설정합니다. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | 페이지에서 스탬프의 수직 정렬을 가져오거나 설정합니다. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | 페이지에서 스탬프의 원하는 너비입니다. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | 텍스트 렌더링을 위한 단어 줄 바꿈 모드를 가져오거나 설정합니다. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | 왼쪽에서 시작하는 수평 스탬프 좌표입니다. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | 아래에서 시작하는 수직 스탬프 좌표입니다. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | 스탬프의 확대 비율입니다. 스탬프를 스케일할 수 있습니다. ZoomX 및 ZoomY 속성 쌍을 사용하면 각 축에 대해 별도로 확대 비율을 설정할 수 있습니다. 이 속성을 설정하면 ZoomX 및 ZoomY 속성이 모두 변경됩니다. ZoomX와 ZoomY가 다르면 Zoom 속성은 ZoomX 값을 반환합니다. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | 스탬프의 수평 확대 비율입니다. 스탬프를 수평으로 스케일할 수 있습니다. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | 스탬프의 수직 확대 비율입니다. 스탬프를 수직으로 스케일할 수 있습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | 스탬프 ID를 반환합니다. |
| override [Put](../../aspose.pdf/textstamp/put/)(Page) | 페이지에 텍스트 스탬프를 추가합니다. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | 스탬프 ID를 설정합니다. |

## 기타 멤버

| 이름 | 설명 |
| --- | --- |
| enum [NoCharacterAction](../../aspose.pdf/textstamp.nocharacteraction) | 글꼴에 요구되는 문자가 포함되지 않은 경우 수행할 작업입니다. |

### 참조

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)