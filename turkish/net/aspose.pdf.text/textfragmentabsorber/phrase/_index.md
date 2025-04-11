---
title: TextFragmentAbsorber.Phrase
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber özelliği. TextFragmentAbsorber'ın PDF belgesinde veya sayfasında aradığı ifadeyi alır veya ayarlar
type: docs
weight: 50
url: /tr/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase özelliği

[`TextFragmentAbsorber`](../) tarafından PDF belgesinde veya sayfasında aranan ifadeyi alır veya ayarlar.

```csharp
public string Phrase { get; set; }
```

## Örnekler

Örnek, metni birkaç kez aramanın ve metin değiştirmelerin nasıl yapılacağını gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// search another word and replace it
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca Bakınız

* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)