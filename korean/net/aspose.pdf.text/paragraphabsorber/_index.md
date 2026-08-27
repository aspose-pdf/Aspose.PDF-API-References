---
title: "클래스 ParagraphAbsorber"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.ParagraphAbsorber 클래스. 섹션 및 단락과 같은 페이지 구조 객체의 흡수 객체를 나타냅니다. 텍스트의 섹션 및 단락을 검색하고 텍스트 좌표 공간에서 이를 설명하는 사각형 및 폴리곤에 대한 접근을 제공합니다. 또한 텍스트 세그먼트 검색을 수행하고 구조 요소별로 그룹화된 TextFragments 컬렉션을 통해 검색 결과에 접근할 수 있습니다."
type: docs
weight: 10850
url: /ko/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

섹션 및 단락과 같은 페이지 구조 객체의 흡수 객체를 나타냅니다. 텍스트 섹션을 검색하고 텍스트 좌표 공간에서 이를 설명하는 사각형 및 폴리곤에 대한 접근을 제공합니다. 또한 텍스트 세그먼트 검색을 수행하고 구조 요소별로 그룹화된 !:TextFragments 컬렉션을 통해 검색 결과에 접근할 수 있습니다.

```csharp
public class ParagraphAbsorber
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | `ParagraphAbsorber`의 새 인스턴스를 초기화합니다. 이 인스턴스는 문서 또는 페이지의 섹션/단락을 검색합니다. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | `ParagraphAbsorber`의 새 인스턴스를 초기화합니다. 이 인스턴스는 문서 또는 페이지의 섹션/단락을 검색합니다. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | 지정된 매개변수를 사용하여 문서 또는 페이지의 섹션/단락을 검색하는 `ParagraphAbsorber`의 새 인스턴스를 초기화합니다. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | 지정된 매개변수를 사용하여 문서 또는 페이지의 섹션/단락을 검색하는 `ParagraphAbsorber`의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | 다음 섹션의 시작 텍스트 줄이 이전 섹션의 마지막 단락의 연속으로 간주될 수 있는지를 나타내는 값을 가져오거나 설정합니다. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | 흡수된 [`PageMarkup`](../pagemarkup/) 컬렉션을 가져옵니다. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | ParagraphAbsorberOptions를 가져오거나 설정합니다. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | 구조의 더 세부적인 요소에 대해 순차 검색을 수행할 횟수를 지정하는 값을 가져오거나 설정합니다. 기본 검색 깊이는 3이며, 이는 수평으로 구분된 섹션(헤더, 단락 등)에 대해 세 번, 수직으로 구분된 섹션(열 등)에 대해 세 번 검색한다는 의미입니다. |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | TextReplaceOptions를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | 지정된 [`Document`](../../aspose.pdf/document/)에서 섹션 및 단락을 검색합니다. |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | 지정된 [`Page`](../../aspose.pdf/page/)에서 검색을 수행합니다. |

## 비고

검색이 완료되면 [`PageMarkups`](./pagemarkups/) 컬렉션에 [`PageMarkup`](../pagemarkup/) 객체가 포함되며, 이는 [`MarkupSection`](../markupsection/) 및 [`MarkupParagraph`](../markupparagraph/) 컬렉션을 통해 페이지 구조를 나타냅니다. [`TextFragment`](../textfragment/) 객체는 검색된 텍스트, 텍스트 속성에 대한 접근을 제공하고 텍스트를 편집하고 텍스트 상태(글꼴, 글꼴 크기, 색상 등)를 변경할 수 있게 합니다.

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 각 단락의 첫 번째 텍스트 구간을 찾아 강조 표시하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document("input.pdf");

// ParagraphAbsorber 객체를 생성합니다.
ParagraphAbsorber absorber = new ParagraphAbsorber();

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
absorber.Visit(doc.Pages[1]);

// 첫 번째 페이지의 마크업 객체를 가져옵니다.
PageMarkup markup = absorber.PageMarkups[0];

// 페이지 텍스트의 구조 요소를 순회하여 각 단락의 첫 번째 텍스트 조각을 찾습니다.
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // 텍스트 속성을 업데이트합니다.
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// 문서 저장
doc.Save(GetOutputPath("output.pdf"));
```

### 또 보기

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


