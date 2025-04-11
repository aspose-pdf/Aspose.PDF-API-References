---
title: Font.IsEmbedded
second_title: Aspose.PDF for .NET API Reference
description: Font özelliği. Fontun gömülü olup olmadığını belirten bir değeri alır veya ayarlar. IFont'a dayalı font otomatik olarak alt küme yapılacak ve gömülecektir.
type: docs
weight: 60
url: /tr/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded özelliği

Fontun gömülü olup olmadığını belirten bir değeri alır veya ayarlar. IFont'a dayalı font otomatik olarak alt küme yapılacak ve gömülecektir.

```csharp
public bool IsEmbedded { get; set; }
```

## Örnekler

Aşağıdaki örnek, bir fontu bulmayı, onu gömülü olarak işaretlemeyi, belgenin sayfasında metin aramayı ve metin fontunu değiştirmeyi göstermektedir.

```csharp
// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// open document
Document doc = new Document(@"D:\Tests\input.pdf");

// create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// change font for the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ayrıca Bakınız

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)