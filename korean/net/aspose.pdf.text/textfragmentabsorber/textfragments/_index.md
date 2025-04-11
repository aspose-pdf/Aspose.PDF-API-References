---
title: TextFragmentAbsorber.TextFragments
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber 속성. TextFragment 객체와 함께 제공되는 검색 발생의 컬렉션을 가져옵니다.
type: docs
weight: 90
url: /ko/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments 속성

[`TextFragment`](../../textfragment/) 객체와 함께 제공되는 검색 발생의 컬렉션을 가져옵니다.

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 찾고 모든 검색 발생을 새 텍스트로 교체하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 참조

* 클래스 [TextFragmentCollection](../../textfragmentcollection/)
* 클래스 [TextFragmentAbsorber](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)