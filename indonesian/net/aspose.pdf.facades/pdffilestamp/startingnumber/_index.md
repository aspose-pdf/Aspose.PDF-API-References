---
title: "PdfFileStamp.StartingNumber"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti PdfFileStamp. Mendapatkan atau mengatur nomor awal untuk halaman pertama dalam file masukan. Halaman berikutnya akan diberi nomor mulai dari nilai ini. Misalnya jika StartingNumber diatur ke 100, halaman dokumen akan memiliki nomor 100 101 102."
type: docs
weight: 100
url: /id/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber property

Mendapatkan atau mengatur nomor mulai untuk halaman pertama dalam file input. Halaman berikutnya akan diberi nomor mulai dari nilai ini. Misalnya jika StartingNumber diatur ke 100, halaman dokumen akan memiliki nomor 100, 101, 102...

```csharp
public int StartingNumber { get; set; }
```

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Lihat Juga

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


