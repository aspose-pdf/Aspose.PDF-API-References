---
title: "Stamp.Pages"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Stamp. Mendapatkan atau mengatur array dengan nomor halaman yang akan dipengaruhi oleh stempel. Jika Pages null, semua halaman dokumen akan dipengaruhi"
type: docs
weight: 60
url: /id/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages property

Mendapatkan atau mengatur array dengan nomor halaman yang akan dipengaruhi oleh stempel. Jika Pages = null, semua halaman dokumen akan dipengaruhi.

```csharp
public int[] Pages { get; set; }
```

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//letakkan stempel hanya pada halaman ke-1, ke-4, dan ke-6.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Lihat Juga

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


