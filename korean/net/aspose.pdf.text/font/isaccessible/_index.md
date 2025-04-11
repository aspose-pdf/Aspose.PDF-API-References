---
title: Font.IsAccessible
second_title: Aspose.PDF for .NET API Reference
description: 글꼴 속성. 시스템에 글꼴이 설치되어 있는지 여부를 나타냅니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible 속성

시스템에 글꼴이 존재하는지(설치되어 있는지) 여부를 나타냅니다.

```csharp
public bool IsAccessible { get; }
```

## 비고

시스템에서 찾을 수 없는 글꼴로는 일부 작업을 수행할 수 없습니다.

## 예제

이 예제는 첫 번째 페이지에서 텍스트를 검색하고 시스템에 글꼴이 설치되어 있는지 여부를 나타내는 값을 가져오는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### 참조

* 클래스 [TextFragmentAbsorber](../../textfragmentabsorber/)
* 클래스 [Document](../../../aspose.pdf/document/)
* 클래스 [Font](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)