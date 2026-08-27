---
title: "TextFragmentAbsorber.TextSearchOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextFragmentAbsorber 속성. 검색 옵션을 가져오거나 설정합니다. 이 옵션은 정규식을 사용한 검색을 가능하게 합니다."
type: docs
weight: 110
url: /ko/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions property

검색 옵션을 가져오거나 설정합니다. 이 옵션은 정규식을 사용한 검색을 가능하게 합니다.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## 예제

이 예제는 정규식을 사용하여 텍스트 검색을 수행하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// 흡수기가 정규식을 사용하여 'h'로 시작하고 'o'로 끝나는 모든 단어를 검색하도록 만듭니다.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// "hello" 단어를 찾아 "Hi"로 교체해야 합니다.
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// 문서 저장
doc.Save(@"D:\Tests\output.pdf"); 
```

### 또 보기

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


