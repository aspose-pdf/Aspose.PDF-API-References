---
title: "클래스 TextFragment"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.TextFragment 클래스. Pdf 텍스트 조각을 나타냅니다"
type: docs
weight: 11120
url: /ko/net/aspose.pdf.text/textfragment/
---
## TextFragment class

PDF 텍스트 조각을 나타냅니다.

```csharp
public class TextFragment : BaseParagraph
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | 새 `TextFragment` 객체의 인스턴스를 초기화합니다. |
| [TextFragment](textfragment/#constructor_2)(string) | 단일 [`TextSegment`](../textsegment/) 객체를 포함하는 `TextFragment` 객체를 생성합니다. 세그먼트 내부의 텍스트 문자열을 지정합니다. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | 미리 정의된 [`TabStops`](../tabstops/) 위치를 사용하여 `TextFragment` 객체의 새 인스턴스를 초기화합니다. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | 단일 [`TextSegment`](../textsegment/) 객체와 미리 정의된 [`TabStops`](../tabstops/) 위치를 포함하는 `TextFragment` 객체를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | `TextFragment` 객체로 표현된 텍스트의 위치를 가져옵니다. Position 구조의 YIndent는 텍스트 조각의 기준선 좌표를 나타냅니다. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | 단락 끝 주석을 가져오거나 설정합니다.(pdf 생성 전용) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | 단락 각주를 가져오거나 설정합니다.(pdf 생성 전용) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | TextFragment를 포함하는 폼 객체를 가져옵니다 |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | 텍스트 조각의 수평 정렬을 가져오거나 설정합니다. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | 조각 하이퍼링크를 설정합니다 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 가져오거나 설정합니다. 이 단락이 다음 열에 배치될지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 가져오거나 설정합니다. 단락이 인라인인지 여부입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 가져오거나 설정합니다. 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 가져오거나 설정합니다. 현재 단락이 다음 단락과 함께 동일한 페이지에 남아 있는지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다. (pdf 생성용) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | TextFragment를 포함하는 페이지를 가져옵니다 |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | `TextFragment` 객체로 표현된 텍스트의 위치를 가져오거나 설정합니다. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | TextFragment의 사각형을 가져옵니다 |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | 텍스트 교체 옵션을 가져옵니다. 옵션은 조각 텍스트가 더 짧거나 길게 교체될 때의 동작을 정의합니다. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | 현재 `TextFragment`의 텍스트 세그먼트를 가져옵니다. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | `TextFragment` 객체가 나타내는 문자열 텍스트 객체를 가져오거나 설정합니다. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | 텍스트 편집 옵션을 가져오거나 설정합니다. 옵션은 요청된 기호를 글꼴로 쓸 수 없을 때의 특수 동작을 정의합니다. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | `TextFragment` 객체가 나타내는 텍스트의 상태를 가져오거나 설정합니다. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | 텍스트 조각의 수직 정렬을 가져오거나 설정합니다. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | 이 단락의 줄 바꿈 횟수를 가져오거나 설정합니다.(pdf 생성 전용) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z 순서를 나타내는 int 값을 가져오거나 설정합니다. ZIndex가 큰 그래프는 ZIndex가 작은 그래프 위에 배치됩니다. ZIndex는 음수일 수 있습니다. ZIndex가 음수인 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | 조각을 복제합니다. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | 모든 세그먼트를 포함하여 조각을 복제합니다. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | 지정된 `TextFragment` 텍스트 부분을 나타내는 [`TextSegment`](../textsegment/)(s)을 가져옵니다. |

## 비고

간단히 말하면, `TextFragment` 객체는 [`TextSegment`](../textsegment/) 객체 목록을 포함합니다. 자세히 말하면: Pdf 문서의 텍스트는 두 가지 기본 객체, `TextFragment`와 [`TextSegment`](../textsegment/) 로 표현됩니다. 이들 간의 차이는 주로 상황에 따라 달라집니다. 다음 시나리오를 고려해 보겠습니다. 사용자가 텍스트 \"hello world\"를 검색하여 해당 텍스트를 조작하고, 속성을 변경하거나 등을 수행합니다.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

PDF 텍스트의 물리적 표현은 매우 복잡합니다. 텍스트 \"hello world\"는 여러 개의 물리적으로 독립된 텍스트 세그먼트로 구성될 수 있습니다. Aspose.Pdf 텍스트 모델은 기본적으로 `TextFragment` 객체가 사용자의 쿼리를 나타내는 물리적 [`TextSegment`](../textsegment/) 객체 집합에 대해 단일 논리 연산 집합을 제공한다는 것을 정의합니다. 텍스트 검색 시나리오에서 `TextFragment`는 논리적인 \"hello world\" 텍스트 표현이며, [`TextSegment`](../textsegment/) 객체 컬렉션은 \"hello world\" 텍스트 객체를 구성하는 모든 물리적 세그먼트를 나타냅니다. 따라서 `TextFragment`는 논리 텍스트 표현에 가깝고, [`TextSegment`](../textsegment/)은 물리 텍스트 표현에 가깝습니다. 각 [`TextSegment`](../textsegment/) 객체는 자체 폰트, 색상, 위치 속성을 가질 수 있습니다. `TextFragment`는 폰트 설정, 폰트 크기 설정, 폰트 색상 설정 등 텍스트와 그 속성을 간단히 변경할 수 있는 방법을 제공합니다. 반면에 [`TextSegment`](../textsegment/) 객체는 별도로 접근 가능하며 사용자는 [`TextSegment`](../textsegment/) 객체를 독립적으로 조작할 수 있습니다. TextFragment 속성을 변경하면 내부 [`Segments`](./segments/) 컬렉션이 변경될 수 있는데, 이는 TextFragment가 집합 객체이며 내부 세그먼트를 재배열하거나 하나의 세그먼트로 병합할 수 있기 때문입니다. 만약 [`Segments`](./segments/) 컬렉션을 그대로 유지해야 한다면, 내부 세그먼트를 개별적으로 변경하십시오.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 찾고 해당 텍스트와 폰트를 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 문서 텍스트 폰트를 변경하는 데 사용할 폰트를 찾습니다.
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 텍스트와 폰트를 변경합니다.
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


