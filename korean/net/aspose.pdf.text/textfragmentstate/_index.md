---
title: "클래스 TextFragmentState"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.TextFragmentState 클래스. 텍스트 조각의 텍스트 상태를 나타냅니다."
type: docs
weight: 11150
url: /ko/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

텍스트 조각의 텍스트 상태를 나타냅니다.

```csharp
public sealed class TextFragmentState : TextState
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | 지정된 [`TextFragment`](../textfragment/) 객체와 함께 `TextFragmentState` 객체의 새 인스턴스를 초기화합니다. 이 `TextFragmentState` 초기화는 지원되지 않습니다. TextFragmentState는 [`TextState`](../textfragment/textstate/) 속성에서만 사용할 수 있습니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | `[`TextFragment`](../textfragment/)` 객체가 나타내는 텍스트의 배경색을 설정합니다. |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | 텍스트의 문자 간격을 가져오거나 설정합니다. 이는 [`TextFragment`](../textfragment/) 객체에 의해 표시됩니다. |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | 텍스트 CoordinateOrigin을 가져오거나 설정합니다. CoordinateOrigin이 Descender인 경우, 텍스트 Y 좌표는 폰트의 최하단 지점에 해당합니다. CoordinateOrigin이 BaseLine인 경우, 텍스트 Y 좌표는 폰트의 기준선에 해당합니다. 기본값은 Descender입니다. 폰트의 Descent 값이 너무 크면 텍스트가 다른 폰트보다 높게 렌더링될 수 있습니다. 이 경우 더 나은 텍스트 렌더링을 위해 CoordinateOrigin을 BaseLine으로 선택할 수 있습니다. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | 텍스트 사각형 테두리 그리기 플래그를 가져오거나 설정합니다. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | 텍스트의 글꼴을 가져오거나 설정합니다. 이는 [`TextFragment`](../textfragment/) 객체에 의해 표시됩니다. |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | 텍스트의 글꼴 크기를 가져오거나 설정합니다. 이는 [`TextFragment`](../textfragment/) 객체에 의해 표시됩니다. |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | 텍스트의 글꼴 스타일을 설정합니다. 이는 [`TextFragment`](../textfragment/) 객체에 의해 표시됩니다. |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | 텍스트의 전경색을 가져오거나 설정합니다. 이는 [`TextFragment`](../textfragment/) 객체에 의해 표시됩니다. |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | 서식 옵션을 가져오거나 설정합니다. 옵션 설정은 생성기 시나리오에서만 적용됩니다. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | 텍스트의 수평 정렬을 가져오거나 설정합니다. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | 텍스트의 수평 스케일링을 가져오거나 설정합니다. 이는 [`TextFragment`](../textfragment/) 객체에 의해 표시됩니다. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | 텍스트의 투명성을 가져오거나 설정합니다. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | 텍스트의 줄 간격을 가져오거나 설정합니다. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | 텍스트의 렌더링 모드를 가져오거나 설정합니다. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | 회전 각도를 (도) 단위로 가져오거나 설정합니다. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | 텍스트에 대한 취소선을 가져오거나 설정합니다. 이는 [`TextFragment`](../textfragment/) 객체에 의해 표시됩니다. |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | `[`TextFragment`](../textfragment/)` 렌더링의 색상 스트로크 작업을 가져오거나 설정합니다 (텍스트 스트로크, 사각형 테두리). |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | 텍스트의 아래 첨자를 가져오거나 설정합니다. 이는 [`TextFragment`](../textfragment/) 객체에 의해 표시됩니다. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | 텍스트의 위 첨자를 가져오거나 설정합니다. 이는 [`TextFragment`](../textfragment/) 객체에 의해 표시됩니다. |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | 텍스트의 탭 정지를 가져옵니다. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | 탭을 선언하려면 텍스트에 이 태그를 삽입할 수 있습니다. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | 텍스트에 대한 밑줄을 가져오거나 설정합니다. 이는 [`TextFragment`](../textfragment/) 객체로 표시됩니다. |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | 텍스트의 단어 간격을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | 다른 textState의 설정을 적용합니다. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | 입력 문자열을 정의된 사각형 안에 배치할 수 있는지 확인합니다. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | 문자 높이를 측정합니다. (2가지 방법) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | 문자열을 측정합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | 기본 글꼴의 공백 문자 너비에서 탭의 기본값입니다. |

## 비고

텍스트의 다음 속성을 변경하는 방법을 제공합니다: 글꼴 ([`Font`](./font/) 속성) 글꼴 크기 ([`FontSize`](./fontsize/) 속성) 글꼴 스타일 ([`FontStyle`](./fontstyle/) 속성) 전경색 ([`ForegroundColor`](./foregroundcolor/) 속성) 배경색 ([`BackgroundColor`](./backgroundcolor/) 속성) `TextFragmentState` 속성을 변경하면 내부 [`Segments`](../textfragment/segments/) 컬렉션이 변경될 수 있습니다. TextFragment는 집합 객체이며 내부 세그먼트를 재배열하거나 단일 세그먼트로 병합할 수 있기 때문입니다. 컬렉션을 그대로 유지해야 하는 경우, 내부 세그먼트를 개별적으로 변경하십시오.

## 예제

예제는 [`TextState`](../textstate/) 객체를 사용하여 텍스트의 색상과 글꼴 크기를 변경하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 전경색을 변경합니다.
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// 첫 번째 텍스트 발생의 글꼴 크기를 변경합니다
absorber.TextFragments[1].TextState.FontSize = 15;

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* class [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


