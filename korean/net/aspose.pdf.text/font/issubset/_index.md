---
title: "Font.IsSubset"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Font 속성. 글꼴이 서브셋인지 여부를 나타내는 값을 가져오거나 설정합니다. IFont 기반의 Font는 자동으로 서브셋되고 포함됩니다."
type: docs
weight: 70
url: /ko/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset property

글꼴이 서브셋인지 여부를 나타내는 값을 가져오거나 설정합니다. IFont 기반 글꼴은 자동으로 서브셋화되고 포함됩니다.

```csharp
public bool IsSubset { get; set; }
```

## 예제

이 예제는 첫 페이지에서 텍스트를 검색하고 글꼴이 서브셋인지 여부를 나타내는 값을 가져오는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 글꼴 IsSubset 값을 확인합니다.
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### 또 보기

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


