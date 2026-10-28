---
title: "TextFragmentAbsorber.TextFragments"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextFragmentAbsorber 속성. TextFragment 객체로 표시된 검색 발생 컬렉션을 가져옵니다."
type: docs
weight: 90
url: /ko/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments property

[`TextFragment`](../../textfragment/) 객체로 표시된 검색 발생 컬렉션을 가져옵니다.

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 찾고 모든 검색 발생을 새 텍스트로 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 문서 텍스트 폰트를 변경하는 데 사용할 폰트를 찾습니다.
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 검색된 모든 항목의 텍스트를 변경합니다.
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


