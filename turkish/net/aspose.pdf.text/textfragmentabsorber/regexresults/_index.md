---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber özelliği. Anahtar olarak System.Text.RegularExpressions.Regex sınıfı ve değer olarak TextFragment ile sunulan arama olaylarının sözlüğünü alır.
type: docs
weight: 60
url: /tr/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults özelliği

Anahtar olarak System.Text.RegularExpressions.Regex sınıfı ve değer olarak [`TextFragment`](../../textfragment/) ile sunulan arama olaylarının sözlüğünü alır.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Örnekler

Örnek, ilk PDF belgesi sayfasında bir dizi düzenli ifadeyle metin bulmanın nasıl yapılacağını gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results
var results = absorber.RegexResults;
```

### Ayrıca Bakınız

* sınıf [TextFragmentCollection](../../textfragmentcollection/)
* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)