---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: Properti TextFragmentAbsorber. Mendapatkan kamus kejadian pencarian yang disajikan dengan kelas System.Text.RegularExpressions.Regex sebagai kunci dan TextFragment sebagai nilai
type: docs
weight: 60
url: /id/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## Properti TextFragmentAbsorber.RegexResults

Mendapatkan kamus kejadian pencarian yang disajikan dengan kelas System.Text.RegularExpressions.Regex sebagai kunci dan [`TextFragment`](../../textfragment/) sebagai nilai.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Contoh

Contoh ini menunjukkan cara menemukan teks dengan array ekspresi reguler pada halaman pertama dokumen PDF.

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

### Lihat Juga

* kelas [TextFragmentCollection](../../textfragmentcollection/)
* kelas [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)