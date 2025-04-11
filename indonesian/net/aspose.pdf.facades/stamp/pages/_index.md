---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: Properti Stamp. Mendapatkan atau mengatur array dengan nomor halaman yang akan terpengaruh oleh stempel. Jika Pages = null, semua halaman dokumen terpengaruh
type: docs
weight: 60
url: /id/net/aspose.pdf.facades/stamp/pages/
---
## Properti Stamp.Pages

Mendapatkan atau mengatur array dengan nomor halaman yang akan terpengaruh oleh stempel. Jika Pages = null, semua halaman dokumen terpengaruh.

```csharp
public int[] Pages { get; set; }
```

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Lihat Juga

* kelas [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)