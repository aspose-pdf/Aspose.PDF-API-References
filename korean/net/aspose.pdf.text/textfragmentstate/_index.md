---
title: Class TextFragmentState
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentState 클래스. 텍스트 조각의 텍스트 상태를 나타냅니다.
type: docs
weight: 10970
url: /ko/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState 클래스

텍스트 조각의 텍스트 상태를 나타냅니다.

```csharp
public sealed class TextFragmentState : TextState
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | 지정된 [`TextFragment`](../textfragment/) 객체로 `TextFragmentState` 객체의 새 인스턴스를 초기화합니다. 이 `TextFragmentState` 초기화는 지원되지 않습니다. TextFragmentState는 [`TextState`](../textfragment/textstate/) 속성과 함께만 사용할 수 있습니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | [`TextFragment`](../textfragment/) 객체로 표현된 텍스트의 배경 색상을 설정합니다. |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | [`TextFragment`](../textfragment/) 객체로 표현된 텍스트의 문자 간격을 가져오거나 설정합니다. |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | 텍스트의 CoordinateOrigin을 가져오거나 설정합니다. CoordinateOrigin이 Descender인 경우 텍스트 Y 좌표는 글꼴의 가장 낮은 지점에 해당합니다. CoordinateOrigin이 BaseLine인 경우 텍스트 Y 좌표는 글꼴의 기준선에 해당합니다. 기본값은 Descender입니다. 글꼴의 Descent 값이 너무 크면 텍스트가 다른 글꼴보다 높게 렌더링될 수 있습니다. 이 경우 더 나은 텍스트 렌더링을 위해 CoordinateOrigin BaseLine을 선택할 수 있습니다. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | 텍스트 사각형 테두리 그리기 플래그를 가져오거나 설정합니다. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | [`TextFragment`](../textfragment/) 객체로 표현된 텍스트의 글꼴을 가져오거나 설정합니다. |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | [`TextFragment`](../textfragment/) 객체로 표현된 텍스트의 글꼴 크기를 가져오거나 설정합니다. |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | [`TextFragment`](../textfragment/) 객체로 표현된 텍스트의 글꼴 스타일을 설정합니다. |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | [`TextFragment`](../textfragment/) 객체로 표현된 텍스트의 전경 색상을 가져오거나 설정합니다. |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | 서식 옵션을 가져오거나 설정합니다. 옵션 설정은 생성기 시나리오에서만 효과적입니다. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | 텍스트의 수평 정렬을 가져오거나 설정합니다. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | [`TextFragment`](../textfragment/) 객체로 표현된 텍스트의 수평 스케일링을 가져오거나 설정합니다. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | 텍스트의 불투명성을 가져오거나 설정합니다. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | 텍스트의 줄 간격을 가져오거나 설정합니다. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | 텍스트의 렌더링 모드를 가져오거나 설정합니다. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | 각도를 도 단위로 가져오거나 설정합니다. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | [`TextFragment`](../textfragment/) 객체로 표현된 텍스트의 취소선을 가져오거나 설정합니다. |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | [`TextFragment`](../textfragment/) 렌더링의 색상 스트로킹 작업(스트로크 텍스트, 사각형 테두리)을 가져오거나 설정합니다. |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | [`TextFragment`](../textfragment/) 객체로 표현된 텍스트의 아래 첨자를 가져오거나 설정합니다. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | [`TextFragment`](../textfragment/) 객체로 표현된 텍스트의 위 첨자를 가져오거나 설정합니다. |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | 텍스트의 탭 정지를 가져옵니다. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | [`TextFragment`](../textfragment/) 객체로 표현된 텍스트의 밑줄을 가져오거나 설정합니다. |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | 텍스트의 단어 간격을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | 다른 textState에서 설정을 적용합니다. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | 입력 문자열이 정의된 사각형 안에 배치될 수 있는지 확인합니다. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | 문자 높이를 측정합니다. (2개의 메서드) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | 문자열을 측정합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | 기본 글꼴의 공백 문자 너비에서 탭의 기본값입니다. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | 탭을 선언하기 위해 텍스트에 이 태그를 배치할 수 있습니다. |

## 비고

다음 텍스트 속성을 변경하는 방법을 제공합니다: 글꼴 ([`Font`](./font/) 속성) 글꼴 크기 ([`FontSize`](./fontsize/) 속성) 글꼴 스타일 ([`FontStyle`](./fontstyle/) 속성) 전경 색상 ([`ForegroundColor`](./foregroundcolor/) 속성) 배경 색상 ([`BackgroundColor`](./backgroundcolor/) 속성) `TextFragmentState` 속성을 변경하면 내부 [`Segments`](../textfragment/segments/) 컬렉션이 변경될 수 있습니다. TextFragment는 집합체 객체이므로 내부 세그먼트를 재배열하거나 단일 세그먼트로 병합할 수 있습니다. [`Segments`](../textfragment/segments/) 컬렉션을 변경하지 않으려면 내부 세그먼트를 개별적으로 변경하십시오.

## 예제

이 예제는 [`TextState`](../textstate/) 객체로 텍스트의 색상과 글꼴 크기를 변경하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 참조

* 클래스 [TextFragmentAbsorber](../textfragmentabsorber/)
* 클래스 [Document](../../aspose.pdf/document/)
* 클래스 [TextState](../textstate/)
* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)