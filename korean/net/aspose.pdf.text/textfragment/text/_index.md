---
title: "TextFragment.Text"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextFragment 속성. TextFragment 객체가 나타내는 String 텍스트 객체를 가져오거나 설정합니다."
type: docs
weight: 130
url: /ko/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text property

[`TextFragment`](../) 객체가 나타내는 String 텍스트 객체를 가져오거나 설정합니다.

```csharp
public string Text { get; set; }
```

## 예제

예제는 텍스트를 검색하고 첫 번째 발생을 [`TextFragment`](../) 객체로 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 폰트를 변경합니다
absorber.TextFragments[1].Text = "hi world";

// 문서 저장
doc.Save(@"D:\Tests\output.pdf"); 
```

### 또 보기

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


