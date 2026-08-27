---
title: "TextFragmentAbsorber.RegexResults"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextFragmentAbsorber 속성. 검색 발생을 사전 형태로 가져오며, 키는 System.Text.RegularExpressions.Regex 클래스이고 값은 TextFragment입니다"
type: docs
weight: 60
url: /ko/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults property

키는 System.Text.RegularExpressions.Regex 클래스이고 값은 [`TextFragment`](../../textfragment/)인 검색 발생 사전을 가져옵니다.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 정규식 배열을 사용해 텍스트를 찾는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// 정규식을 사용하여 'h'로 시작하고 'o'로 끝나는 모든 단어를 검색하는 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// 결과 가져오기
var results = absorber.RegexResults;
```

### 또 보기

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


