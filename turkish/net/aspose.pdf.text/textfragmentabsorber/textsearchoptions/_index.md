---
title: TextFragmentAbsorber.TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber özelliği. Arama seçeneklerini alır veya ayarlar. Seçenekler, düzenli ifadeler kullanarak arama yapmayı sağlar.
type: docs
weight: 110
url: /tr/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions özelliği

Arama seçeneklerini alır veya ayarlar. Seçenekler, düzenli ifadeler kullanarak arama yapmayı sağlar.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Örnekler

Örnek, düzenli ifade kullanarak metin aramanın nasıl yapılacağını gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// make the absorber to search all words starting 'h' and ending 'o' using regular expression.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ayrıca Bakınız

* sınıf [TextSearchOptions](../../textsearchoptions/)
* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)