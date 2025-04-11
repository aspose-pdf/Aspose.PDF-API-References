---
title: Class TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSegment 클래스. Pdf 텍스트의 세그먼트를 나타냅니다.
type: docs
weight: 11050
url: /ko/net/aspose.pdf.text/textsegment/
---
## TextSegment 클래스

Pdf 텍스트의 세그먼트를 나타냅니다.

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
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | `TextSegment` 객체로 표현된 텍스트의 위치를 가져옵니다. Position 구조체의 YIndent는 텍스트 세그먼트의 기준선 좌표를 나타냅니다. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | 텍스트 세그먼트의 문자에 대한 정보를 나타내는 CharInfo 객체의 컬렉션을 가져옵니다. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | 현재 세그먼트의 끝 문자 인덱스를 가져옵니다. |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | 세그먼트 하이퍼링크를 가져오거나 설정합니다( pdf 생성기용). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | `TextSegment` 객체로 표현된 텍스트의 위치를 가져옵니다. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | TextSegment의 사각형을 가져옵니다. |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | 현재 세그먼트의 시작 문자 인덱스를 가져옵니다. |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | `TextSegment` 객체가 나타내는 문자열 텍스트 객체를 가져오거나 설정합니다. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | 텍스트 편집 옵션을 가져오거나 설정합니다. 이 옵션은 요청된 기호를 글꼴로 쓸 수 없을 때의 특별한 동작을 정의합니다. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | `TextSegment` 객체가 나타내는 텍스트의 텍스트 상태를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | 문자열을 html로 인코딩합니다. |

## 비고

간단히 말해, `TextSegment` 객체는 [`TextFragment`](../textfragment/) 객체의 자식입니다. 자세히 설명하자면: Pdf 문서의 텍스트는 두 가지 기본 객체인 [`TextFragment`](../textfragment/)와 `TextSegment`로 표현됩니다. 이들 간의 차이는 대부분 문맥에 따라 다릅니다. 다음 시나리오를 고려해 보겠습니다. 사용자가 "hello world"라는 텍스트를 검색하여 이를 조작하고, 속성을 변경하고, 보기 등을 원합니다.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

물리적으로 pdf 텍스트의 표현은 매우 복잡합니다. "hello world"라는 텍스트는 여러 물리적으로 독립적인 텍스트 세그먼트로 구성될 수 있습니다. Aspose.Pdf 텍스트 모델은 기본적으로 [`TextFragment`](../textfragment/) 객체가 사용자의 쿼리를 나타내는 물리적 `TextSegment` 객체 집합에 대한 단일 논리 작업 집합을 제공한다고 규정합니다. 텍스트 검색 시나리오에서, [`TextFragment`](../textfragment/)는 논리적 "hello world" 텍스트 표현이며, `TextSegment` 객체 컬렉션은 "hello world" 텍스트 객체를 구성하는 모든 물리적 세그먼트를 나타냅니다. 따라서 [`TextFragment`](../textfragment/)는 논리적 텍스트 표현에 가깝고, `TextSegment`는 물리적 텍스트 표현에 가깝습니다. 분명히 각 `TextSegment` 객체는 고유한 글꼴, 색상, 위치 속성을 가질 수 있습니다. [`TextFragment`](../textfragment/)는 텍스트와 그 속성을 변경하는 간단한 방법을 제공합니다: 글꼴 설정, 글꼴 크기 설정, 글꼴 색상 설정 등. 한편, `TextSegment` 객체는 접근 가능하며 사용자는 `TextSegment` 객체를 독립적으로 조작할 수 있습니다.

## 예제

이 예제는 `TextSegment` 객체의 [`TextState`](./textstate/) 객체를 사용하여 텍스트의 색상과 글꼴 크기를 변경하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 참조

* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)