---
title: TextFragmentAbsorber.TextFragments
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber özelliği. TextFragment nesneleri ile sunulan arama olaylarının koleksiyonunu alır
type: docs
weight: 90
url: /tr/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments özelliği

TextFragment nesneleri ile sunulan arama olaylarının koleksiyonunu alır [`TextFragment`](../../textfragment/) nesneleri.

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Örnekler

Örnek, ilk PDF belge sayfasında metni nasıl bulacağınızı ve tüm arama olaylarını yeni metinle nasıl değiştireceğinizi gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca Bakınız

* sınıf [TextFragmentCollection](../../textfragmentcollection/)
* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)