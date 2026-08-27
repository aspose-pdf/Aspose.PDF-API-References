---
title: "PdfExtractor.GetAttachNames"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfExtractor. Mengembalikan daftar lampiran dalam file PDF. Catatan: ExtractAttachments harus dipanggil sebelum menggunakan metode ini."
type: docs
weight: 160
url: /id/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames method

Mengembalikan daftar lampiran dalam file PDF. Catatan: ExtractAttachments harus dipanggil sebelum menggunakan metode ini.

```csharp
public IList<string> GetAttachNames()
```

### Nilai Kembalian

Daftar lampiran

## Contoh

Contoh ini menunjukkan cara mengekstrak nama lampiran dari file PDF.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### Lihat Juga

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


