---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: TextFragment 속성. 현재 TextFragment에 대한 텍스트 세그먼트를 가져옵니다.
type: docs
weight: 120
url: /ko/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments 속성

현재 [`TextFragment`](../)에 대한 텍스트 세그먼트를 가져옵니다.

```csharp
public TextSegmentCollection Segments { get; set; }
```

## 비고

간단히 말해, [`TextSegment`](../../textsegment/) 객체는 [`TextFragment`](../) 객체의 자식입니다. 고급 사용자는 더 복잡한 텍스트 편집 시나리오를 수행하기 위해 세그먼트에 직접 접근할 수 있습니다. 자세한 내용은 [`TextFragment`](../) 객체 설명을 참조하십시오.

## 예제

이 예제는 [`TextFragment`](../) 내의 모든 [`TextSegment`](../../textsegment/) 객체를 탐색하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Navigate all text segments and out their text and placement info
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### 참조

* 클래스 [TextFragmentAbsorber](../../textfragmentabsorber/)
* 클래스 [Document](../../../aspose.pdf/document/)
* 클래스 [TextSegment](../../textsegment/)
* 클래스 [TextSegmentCollection](../../textsegmentcollection/)
* 클래스 [TextFragment](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)