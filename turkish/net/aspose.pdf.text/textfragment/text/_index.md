---
title: TextFragment.Text
second_title: Aspose.PDF for .NET API Reference
description: TextFragment özelliği. TextFragment nesnesinin temsil ettiği String metin nesnesini alır veya ayarlar
type: docs
weight: 130
url: /tr/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text özelliği

[`TextFragment`](../) nesnesinin temsil ettiği String metin nesnesini alır veya ayarlar.

```csharp
public string Text { get; set; }
```

## Örnekler

Örnek, bir metni nasıl arayacağınızı ve [`TextFragment`](../) nesnesi ile temsil edilen ilk örneği nasıl değiştireceğinizi gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ayrıca Bakınız

* sınıf [TextFragmentAbsorber](../../textfragmentabsorber/)
* sınıf [Document](../../../aspose.pdf/document/)
* sınıf [TextFragment](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)