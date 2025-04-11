---
title: TextFragmentAbsorber.TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber 속성. 검색 옵션을 가져오거나 설정합니다. 이 옵션은 정규 표현식을 사용하여 검색을 가능하게 합니다.
type: docs
weight: 110
url: /ko/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions 속성

검색 옵션을 가져오거나 설정합니다. 이 옵션은 정규 표현식을 사용하여 검색을 가능하게 합니다.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## 예제

이 예제는 정규 표현식을 사용하여 텍스트를 검색하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// make the absorber to search all words starting 'h' and ending 'o' using regular expression.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 참조

* 클래스 [TextSearchOptions](../../textsearchoptions/)
* 클래스 [TextFragmentAbsorber](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)