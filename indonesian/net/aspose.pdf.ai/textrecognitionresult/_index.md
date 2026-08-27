---
title: "Kelas TextRecognitionResult"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.TextRecognitionResult. Mewakili hasil OCR teragregasi untuk satu dokumen sumber"
type: docs
weight: 1180
url: /id/net/aspose.pdf.ai/textrecognitionresult/
---
## TextRecognitionResult class

Mewakili hasil OCR teragregasi untuk satu dokumen sumber.

```csharp
public class TextRecognitionResult
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextRecognitionResult](textrecognitionresult/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [OcrDetails](../../aspose.pdf.ai/textrecognitionresult/ocrdetails/) { get; set; } | Daftar yang berisi hasil OCR terperinci untuk setiap halaman dokumen. Untuk file gambar tunggal, daftar ini biasanya berisi satu entri OcrDetail dengan PageNumber = 1. |
| [OverallSuccess](../../aspose.pdf.ai/textrecognitionresult/overallsuccess/) { get; set; } | Menunjukkan apakah OCR berhasil untuk SEMUA halaman dalam dokumen ini. False jika ada OcrDetail dalam OcrDetails yang memiliki Success = false. |
| [SourceIdentifier](../../aspose.pdf.ai/textrecognitionresult/sourceidentifier/) { get; set; } | Pengidentifikasi untuk file sumber (mis., jalur lengkap atau nama unik). |
| [SummaryErrorMessage](../../aspose.pdf.ai/textrecognitionresult/summaryerrormessage/) { get; set; } | Pesan kesalahan terpusat jika OverallSuccess adalah false, atau ringkasan jika ada halaman yang gagal. Null jika OverallSuccess adalah true. |
| [TotalUsage](../../aspose.pdf.ai/textrecognitionresult/totalusage/) { get; set; } | Mendapatkan atau mengatur statistik penggunaan total untuk memproses dokumen ini (semua halaman). |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


