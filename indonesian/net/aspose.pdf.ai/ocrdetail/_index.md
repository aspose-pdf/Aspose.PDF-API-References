---
title: "Kelas OcrDetail"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.OcrDetail. Mewakili hasil OCR untuk satu halaman dokumen atau satu file gambar."
type: docs
weight: 860
url: /id/net/aspose.pdf.ai/ocrdetail/
---
## OcrDetail class

Mewakili hasil OCR untuk satu halaman dokumen atau satu file gambar.

```csharp
public class OcrDetail : IComparable<OcrDetail>
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [OcrDetail](ocrdetail/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ErrorMessage](../../aspose.pdf.ai/ocrdetail/errormessage/) { get; set; } | Pesan error yang menjelaskan mengapa OCR gagal untuk halaman ini, jika Success bernilai false. Null jika tidak. |
| [ExtractedText](../../aspose.pdf.ai/ocrdetail/extractedtext/) { get; set; } | Konten teks yang diekstrak dari halaman. Null jika Success bernilai false atau tidak ada teks yang ditemukan. |
| [PageNumber](../../aspose.pdf.ai/ocrdetail/pagenumber/) { get; set; } | Nomor halaman berbasis 1 dalam dokumen sumber. Untuk gambar satu halaman, nilai ini selalu 1. |
| [Success](../../aspose.pdf.ai/ocrdetail/success/) { get; set; } | Menunjukkan apakah ekstraksi OCR untuk halaman spesifik ini berhasil. |
| [Usage](../../aspose.pdf.ai/ocrdetail/usage/) { get; set; } | Mendapatkan atau mengatur statistik penggunaan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CompareTo](../../aspose.pdf.ai/ocrdetail/compareto/)(OcrDetail) | Membandingkan instance OcrDetail saat ini dengan objek OcrDetail lain berdasarkan properti PageNumber mereka. |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


