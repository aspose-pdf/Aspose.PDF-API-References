---
title: Class Font
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.Font 클래스. 글꼴 객체를 나타냅니다.
type: docs
weight: 10510
url: /ko/net/aspose.pdf.text/font/
---
## 글꼴 클래스

글꼴 객체를 나타냅니다.

```csharp
public sealed class Font
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | PDF 글꼴 객체의 BaseFont 값을 가져옵니다. 글꼴의 PostScript 이름으로도 알려져 있습니다. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | 때때로 PDF 글꼴(주로 중국어/일본어/한국어 글꼴)은 특정 글꼴 이름을 가질 수 있습니다. 이 이름은 PDF 글꼴 속성 "BaseFont"의 값이며, 때때로 이 속성은 16진수 형식으로 표현될 수 있습니다. 이 이름을 직접 읽으면 읽을 수 없는 형식으로 표현될 수 있습니다. 읽을 수 있는 형식을 얻으려면 이 글꼴에 특정한 규칙에 따라 글꼴 이름을 디코딩해야 합니다. 이 속성은 디코딩된 글꼴 이름을 반환하므로, 읽을 수 없는 [`FontName`](./fontname/)을 만날 때 사용하십시오. [`FontName`](./fontname/) 속성이 읽을 수 있는 형식을 가지면 이 속성은 [`FontName`](./fontname/)과 동일하므로, 읽을 수 있는 형식의 글꼴 이름을 얻어야 할 때 이 속성을 사용할 수 있습니다. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | `Font` 객체의 글꼴 이름을 가져옵니다. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | 글꼴 동작을 조정하는 데 유용한 속성 |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | 글꼴이 시스템에 존재(설치)하는지 여부를 나타내는 값을 가져옵니다. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | 글꼴이 포함되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. IFont를 기반으로 한 글꼴은 자동으로 서브셋되고 포함됩니다. |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | 글꼴이 서브셋인지 여부를 나타내는 값을 가져오거나 설정합니다. IFont를 기반으로 한 글꼴은 자동으로 서브셋되고 포함됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | 이 메서드의 목적은 글꼴 포함 시도가 실패했을 경우 오류 설명을 반환하는 것입니다. 오류가 없는 경우 빈 문자열을 반환합니다. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | 문자열의 크기를 측정합니다. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | 글꼴을 스트림에 저장합니다. 글꼴은 원본 문서의 변환된 복사본에서만 사용하도록 설계된 중간 TTF 형식으로 저장됩니다. 글꼴 파일은 원본 문서의 맥락 외부에서 사용하도록 설계되지 않았습니다. |

## 예제

이 예제는 첫 페이지에서 텍스트를 검색하고 첫 번째 검색 결과의 글꼴을 변경하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;


// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 참조

* 클래스 [TextFragmentAbsorber](../textfragmentabsorber/)
* 클래스 [FontRepository](../fontrepository/)
* 클래스 [Document](../../aspose.pdf/document/)
* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)