---
title: "TextFragmentAbsorber.Phrase"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextFragmentAbsorber 속성. PDF 문서 또는 페이지에서 TextFragmentAbsorber가 검색하는 구문을 가져오거나 설정합니다."
type: docs
weight: 50
url: /ko/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase property

PDF 문서 또는 페이지에서 [`TextFragmentAbsorber`](../)가 검색하는 구문을 가져오거나 설정합니다.

```csharp
public string Phrase { get; set; }
```

## 예제

이 예제는 텍스트를 여러 번 검색하고 텍스트 교체를 수행하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// "hello" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// 다른 단어를 검색하고 교체합니다.
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


