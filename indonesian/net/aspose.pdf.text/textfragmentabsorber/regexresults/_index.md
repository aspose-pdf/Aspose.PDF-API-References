---
title: "TextFragmentAbsorber.RegexResults"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti TextFragmentAbsorber. Mendapatkan kamus kejadian pencarian yang disajikan dengan kelas System.Text.RegularExpressions.Regex sebagai kunci dan TextFragment sebagai nilai."
type: docs
weight: 60
url: /id/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults property

Mendapatkan kamus kejadian pencarian yang disajikan dengan kelas System.Text.RegularExpressions.Regex sebagai kunci dan [`TextFragment`](../../textfragment/) sebagai nilai.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Contoh

Contoh ini menunjukkan cara menemukan teks dengan array ekspresi reguler pada halaman pertama dokumen PDF.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Buat objek TextFragmentAbsorber yang mencari semua kata yang dimulai dengan 'h' dan diakhiri dengan 'o' menggunakan ekspresi reguler.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Dapatkan hasil
var results = absorber.RegexResults;
```

### Lihat Juga

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


