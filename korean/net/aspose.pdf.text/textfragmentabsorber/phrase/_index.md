---
title: TextFragmentAbsorber.Phrase
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber 속성. PDF 문서 또는 페이지에서 TextFragmentAbsorber가 검색하는 구문을 가져오거나 설정합니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase 속성

PDF 문서 또는 페이지에서 [`TextFragmentAbsorber`](../)가 검색하는 구문을 가져오거나 설정합니다.

```csharp
public string Phrase { get; set; }
```

## 예제

이 예제는 여러 번 텍스트를 검색하고 텍스트 교체를 수행하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// search another word and replace it
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 참조

* 클래스 [TextFragmentAbsorber](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)