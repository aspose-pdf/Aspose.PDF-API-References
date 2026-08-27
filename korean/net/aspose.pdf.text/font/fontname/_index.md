---
title: "Font.FontName"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Font 속성. Font 객체의 글꼴 이름을 가져옵니다."
type: docs
weight: 30
url: /ko/net/aspose.pdf.text/font/fontname/
---
## Font.FontName property

[`Font`](../) 객체의 글꼴 이름을 가져옵니다.

```csharp
public string FontName { get; }
```

## 예제

이 예제는 첫 페이지에서 텍스트를 검색하고 첫 번째 텍스트 발생의 글꼴 이름을 보는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 글꼴 이름 보기
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### 또 보기

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


