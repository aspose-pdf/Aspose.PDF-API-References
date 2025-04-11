---
title: Font.IsEmbedded
second_title: Aspose.PDF for .NET API Reference
description: 글꼴 속성. 글꼴이 포함되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. IFont를 기반으로 한 글꼴은 자동으로 서브셋되고 포함됩니다.
type: docs
weight: 60
url: /ko/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded 속성

글꼴이 포함되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. IFont를 기반으로 한 글꼴은 자동으로 서브셋되고 포함됩니다.

```csharp
public bool IsEmbedded { get; set; }
```

## 예제

다음 예제는 글꼴을 찾고, 이를 포함된 것으로 표시하고, 문서 페이지에서 텍스트를 검색하고 텍스트 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// open document
Document doc = new Document(@"D:\Tests\input.pdf");

// create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// change font for the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 참조

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)