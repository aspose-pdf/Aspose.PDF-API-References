---
title: "Font.IsEmbedded"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Font 속성. 글꼴이 포함되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. IFont 기반의 Font는 자동으로 서브셋되고 포함됩니다."
type: docs
weight: 60
url: /ko/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded property

글꼴이 포함되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. IFont 기반 글꼴은 자동으로 서브셋화되고 포함됩니다.

```csharp
public bool IsEmbedded { get; set; }
```

## 예제

다음 예제는 글꼴을 찾고, 포함된 것으로 표시하며, 문서 페이지에서 텍스트를 검색하고 텍스트 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// 글꼴을 생성하고 포함하도록 표시합니다.
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 모든 "hello world" 텍스트 발생을 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// 첫 번째 페이지에 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생에 대한 글꼴을 변경합니다.
absorber.TextFragments[1].TextState.Font = font;

// 문서를 저장합니다.
doc.Save(@"D:\Tests\output.pdf"); 
```

### 또 보기

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


