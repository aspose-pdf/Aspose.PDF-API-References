---
title: TextFragment.Position
second_title: Aspose.PDF for .NET API Reference
description: TextFragment özelliği. TextFragment nesnesi ile temsil edilen metin için metin konumunu alır veya ayarlar
type: docs
weight: 90
url: /tr/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position özelliği

[`TextFragment`](../) nesnesi ile temsil edilen metin için metin konumunu alır veya ayarlar.

```csharp
public Position Position { get; set; }
```

## Örnekler

Örnek, [`TextFragment`](../) nesnesi ile temsil edilen bir metnin yerleşimini nasıl görüntüleyeceğini gösterir.

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

### Ayrıca Bakınız

* sınıf [TextFragmentAbsorber](../../textfragmentabsorber/)
* sınıf [Document](../../../aspose.pdf/document/)
* sınıf [TextSegment](../../textsegment/)
* sınıf [Position](../../position/)
* sınıf [TextFragment](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)