---
title: "Stamp.Rotation"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Stamp. Mendapatkan atau menetapkan rotasi stamp dalam derajat."
type: docs
weight: 80
url: /id/net/aspose.pdf.facades/stamp/rotation/
---
## Stamp.Rotation property

Mendapatkan atau mengatur rotasi stempel dalam derajat.

```csharp
public float Rotation { get; set; }
```

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Lihat Juga

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


