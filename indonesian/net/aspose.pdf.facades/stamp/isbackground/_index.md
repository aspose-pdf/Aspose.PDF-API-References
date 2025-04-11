---
title: Stamp.IsBackground
second_title: Aspose.PDF for .NET API Reference
description: Properti Stamp. Mengambil atau mengatur status latar belakang. Jika benar, cap akan ditempatkan sebagai latar belakang halaman yang dicap. Secara default diatur ke false
type: docs
weight: 30
url: /id/net/aspose.pdf.facades/stamp/isbackground/
---
## Properti Stamp.IsBackground

Mengambil atau mengatur status latar belakang. Jika benar, cap akan ditempatkan sebagai latar belakang halaman yang dicap. Secara default diatur ke false.

```csharp
public bool IsBackground { get; set; }
```

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Lihat Juga

* kelas [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)