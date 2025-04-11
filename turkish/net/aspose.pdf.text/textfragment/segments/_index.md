---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: TextFragment özelliği. Mevcut TextFragment için metin segmentlerini alır
type: docs
weight: 120
url: /tr/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments özelliği

Mevcut [`TextFragment`](../) için metin segmentlerini alır.

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Açıklamalar

Kısaca, [`TextSegment`](../../textsegment/) nesneleri [`TextFragment`](../) nesnesinin çocuklarıdır. İleri düzey kullanıcılar, daha karmaşık metin düzenleme senaryoları gerçekleştirmek için segmentlere doğrudan erişebilirler. Ayrıntılar için lütfen [`TextFragment`](../) nesne tanımına bakın.

## Örnekler

Örnek, [`TextFragment`](../) içindeki tüm [`TextSegment`](../../textsegment/) nesneleri arasında nasıl gezileceğini gösterir.

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

### Ayrıca Bakınız

* sınıf [TextFragmentAbsorber](../../textfragmentabsorber/)
* sınıf [Document](../../../aspose.pdf/document/)
* sınıf [TextSegment](../../textsegment/)
* sınıf [TextSegmentCollection](../../textsegmentcollection/)
* sınıf [TextFragment](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)