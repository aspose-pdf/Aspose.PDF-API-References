---
title: "클래스 TextState"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.TextState 클래스. 텍스트의 텍스트 상태를 나타냅니다."
type: docs
weight: 11260
url: /ko/net/aspose.pdf.text/textstate/
---
## TextState class

텍스트의 텍스트 상태를 나타냅니다

```csharp
public class TextState
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextState](textstate/#constructor)() | 텍스트 상태 객체를 생성합니다. |
| [TextState](textstate/#constructor_2)(Color) | 전경색 지정으로 텍스트 상태 객체를 생성합니다. |
| [TextState](textstate/#constructor_1)(double) | 폰트 크기 지정으로 텍스트 상태 객체를 생성합니다. |
| [TextState](textstate/#constructor_4)(string) | 폰트 패밀리 지정으로 텍스트 상태 객체를 생성합니다. |
| [TextState](textstate/#constructor_3)(Color, double) | 전경색 및 폰트 크기 지정으로 텍스트 상태 객체를 생성합니다. |
| [TextState](textstate/#constructor_6)(string, double) | 폰트 패밀리와 폰트 크기 지정으로 텍스트 상태 객체를 생성합니다. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | 폰트 패밀리와 폰트 스타일 지정으로 텍스트 상태 객체를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | 텍스트의 배경색을 설정합니다. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | 텍스트의 문자 간격을 가져오거나 설정합니다. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | 텍스트 CoordinateOrigin을 가져오거나 설정합니다. CoordinateOrigin이 Descender인 경우, 텍스트 Y 좌표는 폰트의 최하단 지점에 해당합니다. CoordinateOrigin이 BaseLine인 경우, 텍스트 Y 좌표는 폰트의 기준선에 해당합니다. 기본값은 Descender입니다. 폰트의 Descent 값이 너무 크면 텍스트가 다른 폰트보다 높게 렌더링될 수 있습니다. 이 경우 더 나은 텍스트 렌더링을 위해 CoordinateOrigin을 BaseLine으로 선택할 수 있습니다. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | 텍스트의 폰트를 가져오거나 설정합니다. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | 텍스트의 글꼴 크기를 가져오거나 설정합니다. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | 텍스트의 글꼴 스타일을 설정합니다. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | 텍스트의 전경 색상을 가져오거나 설정합니다. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | 텍스트의 수평 정렬을 가져오거나 설정합니다. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | 텍스트의 수평 스케일을 가져오거나 설정합니다. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | 텍스트의 가시성을 가져오거나 설정합니다. 이는 기본적으로 [`RenderingMode`](./renderingmode/) 상태를 반영하지만, 일부 특수 경우(예: 클리핑)는 제외됩니다. |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | 텍스트의 줄 간격을 가져오거나 설정합니다. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | 텍스트의 렌더링 모드를 가져오거나 설정합니다. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | 텍스트에 대한 취소선을 가져오거나 설정합니다. 이는 [`TextSegment`](../textsegment/) 객체로 표시됩니다. |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | 텍스트의 전경 색상을 가져오거나 설정합니다. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | 텍스트의 아래 첨자를 가져오거나 설정합니다. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | 텍스트의 위 첨자를 가져오거나 설정합니다. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | 탭을 선언하려면 텍스트에 이 태그를 삽입할 수 있습니다. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | 텍스트에 대한 밑줄을 가져오거나 설정합니다. 이는 [`TextFragment`](../textfragment/) 객체로 표시됩니다. |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | 텍스트의 단어 간격을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | 다른 textState의 설정을 적용합니다. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | 문자 높이를 측정합니다. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | 문자열을 측정합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | 기본 글꼴의 공백 문자 너비에서 탭의 기본값입니다. |

### 또 보기

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


