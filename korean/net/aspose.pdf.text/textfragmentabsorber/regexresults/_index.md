---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber 속성. System.Text.RegularExpressions.Regex 클래스를 키로 하고 TextFragment를 값으로 하는 검색 발생의 사전을 가져옵니다.
type: docs
weight: 60
url: /ko/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults 속성

System.Text.RegularExpressions.Regex 클래스를 키로 하고 [`TextFragment`](../../textfragment/)를 값으로 하는 검색 발생의 사전을 가져옵니다.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 정규 표현식 배열로 텍스트를 찾는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results
var results = absorber.RegexResults;
```

### 참조

* 클래스 [TextFragmentCollection](../../textfragmentcollection/)
* 클래스 [TextFragmentAbsorber](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)