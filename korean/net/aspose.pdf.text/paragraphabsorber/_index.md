---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.ParagraphAbsorber 클래스. 섹션 및 단락과 같은 페이지 구조 객체의 흡수기 객체를 나타냅니다. 텍스트의 섹션 및 단락을 검색하고 텍스트 좌표 공간에서 이를 설명하는 사각형 및 다각형에 대한 액세스를 제공합니다. 또한 텍스트 세그먼트 검색을 수행하고 구조 요소별로 그룹화된 TextFragments 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.
type: docs
weight: 10670
url: /ko/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber 클래스

섹션 및 단락과 같은 페이지 구조 객체의 흡수기 객체를 나타냅니다. 텍스트의 섹션 및 단락을 검색하고 텍스트 좌표 공간에서 이를 설명하는 사각형 및 다각형에 대한 액세스를 제공합니다. 또한 텍스트 세그먼트 검색을 수행하고 구조 요소별로 그룹화된 !:TextFragments 컬렉션을 통해 검색 결과에 대한 액세스를 제공합니다.

```csharp
public class ParagraphAbsorber
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | 문서 또는 페이지의 섹션/단락을 검색하는 `ParagraphAbsorber`의 새 인스턴스를 초기화합니다. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | 문서 또는 페이지의 섹션/단락을 검색하는 `ParagraphAbsorber`의 새 인스턴스를 초기화합니다. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | 지정된 매개변수로 문서 또는 페이지의 섹션/단락을 검색하는 `ParagraphAbsorber`의 새 인스턴스를 초기화합니다. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | 지정된 매개변수로 문서 또는 페이지의 섹션/단락을 검색하는 `ParagraphAbsorber`의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | 다음 섹션의 시작 텍스트 줄이 이전 섹션의 마지막 단락의 연속으로 처리될 수 있는지를 나타내는 값을 가져오거나 설정합니다. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | 흡수된 [`PageMarkup`](../pagemarkup/)의 컬렉션을 가져옵니다. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | ParagraphAbsorberOptions를 가져오거나 설정합니다. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | 구조의 더 세부 요소에 대한 순차적 검색이 몇 번 수행될지를 지시하는 값을 가져오거나 설정합니다. 기본 검색 깊이는 3입니다. 이는 수평으로 나누어진 섹션(헤더, 단락 등)에 대해 세 번의 검색과 수직으로 나누어진 섹션(열)에 대해 세 번의 검색을 의미합니다. |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | TextReplaceOptions를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | 지정된 [`Document`](../../aspose.pdf/document/)에서 섹션 및 단락을 검색합니다. |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | 지정된 [`Page`](../../aspose.pdf/page/)에서 검색을 수행합니다. |

## 비고

검색이 완료되면 [`PageMarkups`](./pagemarkups/) 컬렉션은 [`MarkupSection`](../markupsection/) 및 [`MarkupParagraph`](../markupparagraph/)의 컬렉션으로 페이지 구조를 나타내는 [`PageMarkup`](../pagemarkup/) 객체를 포함합니다. [`TextFragment`](../textfragment/) 객체는 검색된 텍스트, 텍스트 속성에 대한 액세스를 제공하며 텍스트를 편집하고 텍스트 상태(글꼴, 글꼴 크기, 색상 등)를 변경할 수 있습니다.

## 예제

이 예제는 첫 번째 PDF 문서 페이지의 각 단락에서 첫 번째 텍스트 세그먼트를 찾고 강조 표시하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### 참조

* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)