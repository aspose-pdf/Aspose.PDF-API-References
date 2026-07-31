---
title: "Stamp.IsBackground"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Stamp. Mendapatkan atau mengatur status latar belakang. Jika true, stempel akan ditempatkan sebagai latar belakang halaman yang disegel. Secara default diatur ke false"
type: docs
weight: 30
url: /id/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground property

Mendapatkan atau mengatur status latar belakang. Jika true, stempel akan ditempatkan sebagai latar belakang halaman yang distempel. Secara default diatur ke false.

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

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


