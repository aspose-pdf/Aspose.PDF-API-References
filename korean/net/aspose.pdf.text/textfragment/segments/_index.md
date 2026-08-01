---
title: "TextFragment.Segments"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextFragment 속성. 현재 TextFragment에 대한 텍스트 세그먼트를 가져옵니다."
type: docs
weight: 120
url: /ko/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments property

현재 [`TextFragment`](../)에 대한 텍스트 세그먼트를 가져옵니다.

```csharp
public TextSegmentCollection Segments { get; set; }
```

## 비고

간단히 말하면, [`TextSegment`](../../textsegment/) 객체는 [`TextFragment`](../) 객체의 자식입니다. 고급 사용자는 세그먼트에 직접 접근하여 보다 복잡한 텍스트 편집 시나리오를 수행할 수 있습니다. 자세한 내용은 [`TextFragment`](../) 객체 설명을 참고하십시오.

## 예제

이 예제는 [`TextFragment`](../) 내부의 모든 [`TextSegment`](../../textsegment/) 객체를 탐색하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 모든 텍스트 세그먼트를 탐색하고 해당 텍스트와 배치 정보를 출력합니다.
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### 또 보기

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [TextSegmentCollection](../../textsegmentcollection/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


