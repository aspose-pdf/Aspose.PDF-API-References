---
title: "클래스 TextSegment"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.TextSegment 클래스. Pdf 텍스트의 세그먼트를 나타냅니다"
type: docs
weight: 11240
url: /ko/net/aspose.pdf.text/textsegment/
---
## TextSegment class

PDF 텍스트 세그먼트를 나타냅니다.

```csharp
public sealed class TextSegment
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | TextSegment 객체를 생성합니다. |
| [TextSegment](textsegment/#constructor_1)(string) | TextSegment 객체를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | 텍스트 위치를 가져옵니다(`TextSegment` 객체로 표시). Position 구조체의 YIndent는 텍스트 세그먼트의 기준선 좌표를 나타냅니다. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | 텍스트 세그먼트의 문자에 대한 정보를 나타내는 CharInfo 객체 컬렉션을 가져옵니다. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | 표시 텍스트 연산자 (Tj, TJ) 세그먼트에서 현재 세그먼트의 끝 문자 인덱스를 가져옵니다. |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | 세그먼트 하이퍼링크를 가져오거나 설정합니다( pdf 생성기용). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | 텍스트 위치를 가져옵니다(`TextSegment` 객체로 표시). |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | TextSegment의 사각형을 가져옵니다. |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | 표시 텍스트 연산자 (Tj, TJ) 세그먼트에서 현재 세그먼트의 시작 문자 인덱스를 가져옵니다. |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | `TextSegment` 객체가 나타내는 문자열 텍스트 객체를 가져오거나 설정합니다. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | 텍스트 편집 옵션을 가져오거나 설정합니다. 옵션은 요청된 기호를 글꼴로 쓸 수 없을 때의 특수 동작을 정의합니다. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | `TextSegment` 객체가 나타내는 텍스트의 텍스트 상태를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | 문자열을 HTML로 인코딩합니다. |

## 비고

간단히 말하면, `TextSegment` 객체는 [`TextFragment`](../textfragment/) 객체의 하위 요소입니다. 자세히 설명하면: Pdf 문서의 텍스트는 두 가지 기본 객체인 [`TextFragment`](../textfragment/)와 `TextSegment` 로 표현됩니다. 이들 간의 차이는 주로 상황에 따라 달라집니다. 다음 시나리오를 고려해 보겠습니다. 사용자가 텍스트 \"hello world\"를 검색하여 해당 텍스트를 조작하고, 속성을 변경하거나 조회하려고 합니다.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

PDF 텍스트의 물리적 표현은 매우 복잡합니다. 텍스트 \"hello world\"는 여러 개의 물리적으로 독립된 텍스트 세그먼트로 구성될 수 있습니다. Aspose.Pdf 텍스트 모델은 기본적으로 [`TextFragment`](../textfragment/) 객체가 사용자의 쿼리를 나타내는 물리적 `TextSegment` 객체 집합에 대한 단일 논리 연산 집합을 제공한다고 정의합니다. 텍스트 검색 시나리오에서는 [`TextFragment`](../textfragment/)이 논리적인 \"hello world\" 텍스트 표현이며, `TextSegment` 객체 컬렉션은 \"hello world\" 텍스트 객체를 구성하는 모든 물리적 세그먼트를 나타냅니다. 따라서 [`TextFragment`](../textfragment/)은 논리 텍스트 표현에 가깝고, `TextSegment`는 물리 텍스트 표현에 가깝습니다. 각 `TextSegment` 객체는 자체 글꼴, 색상, 위치 속성을 가질 수 있습니다. [`TextFragment`](../textfragment/)은 글꼴 설정, 글꼴 크기 설정, 글꼴 색상 설정 등 텍스트와 그 속성을 간단히 변경할 수 있는 방법을 제공합니다. 반면 `TextSegment` 객체는 개별적으로 접근 가능하며 사용자는 `TextSegment` 객체를 독립적으로 조작할 수 있습니다.

## 예제

이 예제는 `TextSegment` 객체의 [`TextState`](./textstate/) 객체를 사용하여 텍스트 색상과 글꼴 크기를 변경하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생에서 첫 번째 텍스트 세그먼트의 전경색을 변경합니다.
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// 첫 번째 텍스트 발생에서 첫 번째 텍스트 세그먼트의 글꼴 크기를 변경합니다.
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


