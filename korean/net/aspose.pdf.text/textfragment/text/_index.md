---
title: TextFragment.Text
second_title: Aspose.PDF for .NET API Reference
description: TextFragment 속성. TextFragment 객체가 나타내는 문자열 텍스트 객체를 가져오거나 설정합니다.
type: docs
weight: 130
url: /ko/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text 속성

[`TextFragment`](../) 객체가 나타내는 문자열 텍스트 객체를 가져오거나 설정합니다.

```csharp
public string Text { get; set; }
```

## 예제

이 예제는 텍스트를 검색하고 [`TextFragment`](../) 객체로 나타내는 첫 번째 발생을 교체하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 참조

* 클래스 [TextFragmentAbsorber](../../textfragmentabsorber/)
* 클래스 [Document](../../../aspose.pdf/document/)
* 클래스 [TextFragment](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)