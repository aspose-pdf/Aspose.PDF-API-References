---
title: "TextFragmentAbsorber.TextSearchOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti TextFragmentAbsorber. Mendapatkan atau mengatur opsi pencarian. Opsi-opsi ini memungkinkan pencarian menggunakan ekspresi reguler"
type: docs
weight: 110
url: /id/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions property

Mendapatkan atau mengatur opsi pencarian. Opsi-opsi tersebut memungkinkan pencarian menggunakan ekspresi reguler.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Contoh

Contoh ini menunjukkan cara melakukan pencarian teks menggunakan ekspresi reguler.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// buat absorber untuk mencari semua kata yang dimulai dengan 'h' dan diakhiri dengan 'o' menggunakan ekspresi reguler.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// kita harus menemukan kata "hello" dan menggantinya dengan "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


