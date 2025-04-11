---
title: TextFragment.Position
second_title: Aspose.PDF for .NET API Reference
description: TextFragment 속성. TextFragment 객체로 표현된 텍스트의 위치를 가져오거나 설정합니다.
type: docs
weight: 90
url: /ko/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position 속성

[`TextFragment`](../) 객체로 표현된 텍스트의 위치를 가져오거나 설정합니다.

```csharp
public Position Position { get; set; }
```

## 예제

이 예제는 [`TextFragment`](../) 객체로 표현된 텍스트의 배치를 보는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View text and placement info of first text occurrence
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### 참조

* 클래스 [TextFragmentAbsorber](../../textfragmentabsorber/)
* 클래스 [Document](../../../aspose.pdf/document/)
* 클래스 [TextSegment](../../textsegment/)
* 클래스 [Position](../../position/)
* 클래스 [TextFragment](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)