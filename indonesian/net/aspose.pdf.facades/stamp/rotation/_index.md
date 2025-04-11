---
title: Stamp.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Properti Stamp. Mendapatkan atau mengatur rotasi cap dalam derajat
type: docs
weight: 80
url: /id/net/aspose.pdf.facades/stamp/rotation/
---
## Properti Stamp.Rotation

Mendapatkan atau mengatur rotasi cap dalam derajat.

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

* kelas [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)