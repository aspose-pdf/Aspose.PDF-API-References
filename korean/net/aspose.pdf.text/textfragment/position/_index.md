---
title: "TextFragment.Position"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextFragment 속성. TextFragment 객체가 나타내는 텍스트의 위치를 가져오거나 설정합니다."
type: docs
weight: 90
url: /ko/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position property

[`TextFragment`](../) 객체가 나타내는 텍스트의 위치를 가져오거나 설정합니다.

```csharp
public Position Position { get; set; }
```

## 예제

이 예제는 [`TextFragment`](../) 객체가 나타내는 텍스트의 배치를 보는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 텍스트 및 배치 정보를 확인합니다.
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### 또 보기

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [Position](../../position/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


