---
title: "PdfFileStamp.AddStamp"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileStamp. Menambahkan stamp ke file"
type: docs
weight: 140
url: /id/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## PdfFileStamp.AddStamp method

Menambahkan stempel ke file.

```csharp
public void AddStamp(Stamp stamp)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stempel | Stempel | Objek Stempel yang. |

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

* class [Stamp](../../stamp/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


