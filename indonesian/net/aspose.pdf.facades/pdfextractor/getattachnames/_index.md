---
title: PdfExtractor.GetAttachNames
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfExtractor. Mengembalikan daftar lampiran dalam file PDF. Catatan ExtractAttachments harus dipanggil sebelum menggunakan metode ini
type: docs
weight: 160
url: /id/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## Metode PdfExtractor.GetAttachNames

Mengembalikan daftar lampiran dalam file PDF. Catatan: ExtractAttachments harus dipanggil sebelum menggunakan metode ini.

```csharp
public IList<string> GetAttachNames()
```

### Nilai Kembali

Daftar lampiran

## Contoh

Contoh menunjukkan cara mengekstrak nama lampiran dari file PDF.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### Lihat Juga

* kelas [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)