---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: Font 속성. 글꼴이 서브셋인지 여부를 나타내는 값을 가져오거나 설정합니다. IFont를 기반으로 한 글꼴은 자동으로 서브셋 및 포함됩니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset 속성

글꼴이 서브셋인지 여부를 나타내는 값을 가져오거나 설정합니다. IFont를 기반으로 한 글꼴은 자동으로 서브셋 및 포함됩니다.

```csharp
public bool IsSubset { get; set; }
```

## 예제

이 예제는 첫 번째 페이지에서 텍스트를 검색하고 글꼴이 서브셋인지 여부를 나타내는 값을 가져오는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### 참조

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)