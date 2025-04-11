---
title: Class TextFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragment 클래스. Pdf 텍스트의 조각을 나타냅니다.
type: docs
weight: 10940
url: /ko/net/aspose.pdf.text/textfragment/
---
## TextFragment 클래스

Pdf 텍스트의 조각을 나타냅니다.

```csharp
public class TextFragment : BaseParagraph
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | `TextFragment` 객체의 새 인스턴스를 초기화합니다. |
| [TextFragment](textfragment/#constructor_2)(string) | 내부에 단일 [`TextSegment`](../textsegment/) 객체가 있는 `TextFragment` 객체를 생성합니다. 세그먼트 내부의 텍스트 문자열을 지정합니다. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | 미리 정의된 [`TabStops`](../tabstops/) 위치로 `TextFragment` 객체의 새 인스턴스를 초기화합니다. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | 내부에 단일 [`TextSegment`](../textsegment/) 객체와 미리 정의된 [`TabStops`](../tabstops/) 위치가 있는 `TextFragment` 객체를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | `TextFragment` 객체로 표현된 텍스트의 위치를 가져옵니다. Position 구조체의 YIndent는 텍스트 조각의 기준선 좌표를 나타냅니다. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | 단락 끝 주석을 가져오거나 설정합니다.(pdf 생성 전용) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | 단락 각주를 가져오거나 설정합니다.(pdf 생성 전용) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | TextFragment를 포함하는 양식 객체를 가져옵니다. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | 텍스트 조각의 수평 정렬을 가져오거나 설정합니다. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | 조각 하이퍼링크를 설정합니다. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 이 단락이 다음 열에 있을지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(pdf 생성 전용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 단락이 인라인인지 여부를 가져오거나 설정합니다. 기본값은 false입니다.(pdf 생성 전용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(pdf 생성 전용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 현재 단락이 다음 단락과 함께 같은 페이지에 남아 있는지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(pdf 생성 전용) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다.(pdf 생성 전용) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | TextFragment를 포함하는 페이지를 가져옵니다. |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | `TextFragment` 객체로 표현된 텍스트의 위치를 가져오거나 설정합니다. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | TextFragment의 사각형을 가져옵니다. |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | 텍스트 교체 옵션을 가져옵니다. 옵션은 조각 텍스트가 더 짧거나 긴 텍스트로 교체될 때의 동작을 정의합니다. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | 현재 `TextFragment`의 텍스트 세그먼트를 가져오거나 설정합니다. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | `TextFragment` 객체가 나타내는 문자열 텍스트 객체를 가져오거나 설정합니다. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | 텍스트 편집 옵션을 가져오거나 설정합니다. 옵션은 요청된 기호가 글꼴로 작성될 수 없을 때의 특별한 동작을 정의합니다. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | `TextFragment` 객체가 나타내는 텍스트의 텍스트 상태를 가져옵니다. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | 텍스트 조각의 수직 정렬을 가져오거나 설정합니다. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | 이 단락의 줄 바꿈 수를 가져오거나 설정합니다.(pdf 생성 전용) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z-순서를 나타내는 int 값을 가져오거나 설정합니다. 더 큰 ZIndex를 가진 그래프는 더 작은 ZIndex를 가진 그래프 위에 배치됩니다. ZIndex는 음수가 될 수 있습니다. 음수 ZIndex를 가진 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | 조각을 복제합니다. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | 모든 세그먼트와 함께 조각을 복제합니다. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | `TextFragment` 텍스트의 지정된 부분을 나타내는 [`TextSegment`](../textsegment/)를 가져옵니다. |

## 비고

간단히 말해, `TextFragment` 객체는 [`TextSegment`](../textsegment/) 객체 목록을 포함합니다. 자세히 설명하면: Pdf 문서의 텍스트는 `TextFragment`와 [`TextSegment`](../textsegment/)라는 두 가지 기본 객체로 표현됩니다. 이들 간의 차이는 대부분 문맥에 따라 다릅니다. 다음 시나리오를 고려해 보겠습니다. 사용자가 "hello world"라는 텍스트를 검색하여 이를 조작하고, 속성을 변경하고, 보기 등을 원합니다.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

물리적으로 pdf 텍스트의 표현은 매우 복잡합니다. "hello world"라는 텍스트는 여러 개의 물리적으로 독립적인 텍스트 세그먼트로 구성될 수 있습니다. Aspose.Pdf 텍스트 모델은 기본적으로 `TextFragment` 객체가 사용자의 쿼리를 나타내는 물리적 [`TextSegment`](../textsegment/) 객체 집합에 대한 단일 논리 작업 집합을 제공한다고 규정합니다. 텍스트 검색 시나리오에서 `TextFragment`는 논리적인 "hello world" 텍스트 표현이며, [`TextSegment`](../textsegment/) 객체 컬렉션은 "hello world" 텍스트 객체를 구성하는 모든 물리적 세그먼트를 나타냅니다. 따라서 `TextFragment`는 논리적 텍스트 표현에 가깝고, [`TextSegment`](../textsegment/)는 물리적 텍스트 표현에 가깝습니다. 각 [`TextSegment`](../textsegment/) 객체는 고유한 글꼴, 색상, 위치 속성을 가질 수 있습니다. `TextFragment`는 글꼴 설정, 글꼴 크기 설정, 글꼴 색상 설정 등과 같은 속성을 가진 텍스트를 변경하는 간단한 방법을 제공합니다. 한편, [`TextSegment`](../textsegment/) 객체는 접근 가능하며 사용자는 [`TextSegment`](../textsegment/) 객체를 독립적으로 조작할 수 있습니다. `TextFragment` 속성을 변경하면 내부 [`Segments`](./segments/) 컬렉션이 변경될 수 있습니다. `TextFragment`는 집합체 객체이며 내부 세그먼트를 재배열하거나 단일 세그먼트로 병합할 수 있습니다. [`Segments`](./segments/) 컬렉션을 변경하지 않으려면 내부 세그먼트를 개별적으로 변경하십시오.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 찾고 텍스트와 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 참조

* 클래스 [BaseParagraph](../../aspose.pdf/baseparagraph/)
* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)