---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: Font 속성. Font 객체의 글꼴 이름을 가져옵니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf.text/font/fontname/
---
## Font.FontName 속성

[`Font`](../) 객체의 글꼴 이름을 가져옵니다.

```csharp
public string FontName { get; }
```

## 예제

이 예제는 첫 페이지에서 텍스트를 검색하고 첫 번째 텍스트 발생의 글꼴 이름을 보는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font name of first text occurrence
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### 참조

* 클래스 [TextFragmentAbsorber](../../textfragmentabsorber/)
* 클래스 [Document](../../../aspose.pdf/document/)
* 클래스 [Font](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)