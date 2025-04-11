---
title: PdfFileStamp.AddStamp
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileStamp. Menambahkan stempel ke file
type: docs
weight: 140
url: /id/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## Metode PdfFileStamp.AddStamp

Menambahkan stempel ke file.

```csharp
public void AddStamp(Stamp stamp)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stamp | Stempel | Objek stempel yang. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.SetOrigin(140, 400);
stamp.SetImageSize(50, 50);
stamp.Opacity = 0.8f;
stamp.IsBackground = true;
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Lihat Juga

* kelas [Stempel](../../stamp/)
* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)