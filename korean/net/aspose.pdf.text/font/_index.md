---
title: "클래스 Font"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.Font 클래스. 글꼴 객체를 나타냅니다."
type: docs
weight: 10690
url: /ko/net/aspose.pdf.text/font/
---
## Font class

글꼴 객체를 나타냅니다.

```csharp
public sealed class Font
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | PDF 글꼴 객체의 BaseFont 값을 가져옵니다. 또한 해당 글꼴의 PostScript 이름으로도 알려져 있습니다. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | 때때로 PDF 글꼴(주로 중국어/일본어/한국어 글꼴)은 특수한 글꼴 이름을 가질 수 있습니다. 이 이름은 PDF 글꼴 속성 "BaseFont"의 값이며, 때로는 16진수 형태로 표시될 수 있습니다. 이 이름을 직접 읽으면 읽을 수 없는 형태가 될 수 있습니다. 읽을 수 있는 형태로 변환하려면 해당 글꼴에 대한 특정 규칙에 따라 글꼴 이름을 디코딩해야 합니다. 이 속성은 디코딩된 글꼴 이름을 반환하므로, 읽을 수 없는 [`FontName`](./fontname/)을 만났을 때 사용하십시오. 속성 [`FontName`](./fontname/)이 읽을 수 있는 형태라면 이 속성은 [`FontName`](./fontname/)과 동일하므로, 읽을 수 있는 형태의 글꼴 이름이 필요할 때 언제든지 이 속성을 사용할 수 있습니다. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | `Font` 객체의 글꼴 이름을 가져옵니다. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | 폰트 동작을 조정하기 위한 유용한 속성들 |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | 시스템에 글꼴이 존재(설치)하는지 여부를 가져옵니다. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | 글꼴이 포함되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. IFont 기반 글꼴은 자동으로 서브셋화되고 포함됩니다. |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | 글꼴이 서브셋인지 여부를 나타내는 값을 가져오거나 설정합니다. IFont 기반 글꼴은 자동으로 서브셋화되고 포함됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | 이 메서드의 목적은 글꼴 포함 시도가 실패했을 경우 오류 설명을 반환하는 것입니다. 오류가 없으면 빈 문자열을 반환합니다. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | 문자열을 측정합니다. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | 글꼴을 스트림에 저장합니다. 이 글꼴은 원본 문서의 변환된 복사본에서만 사용하도록 중간 TTF 형식으로 저장된다는 점에 유의하십시오. 글꼴 파일은 원본 문서 컨텍스트 외부에서 사용하도록 설계되지 않았습니다. |

## 예제

이 예제는 첫 페이지에서 텍스트를 검색하고 첫 번째 검색 결과의 글꼴을 변경하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 글꼴을 생성하고 포함하도록 표시합니다.
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// 첫 번째 텍스트 발생의 폰트를 변경합니다
absorber.TextFragments[1].TextState.Font = font;


// 문서 저장
doc.Save(@"D:\Tests\output.pdf"); 
```

### 또 보기

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [FontRepository](../fontrepository/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


