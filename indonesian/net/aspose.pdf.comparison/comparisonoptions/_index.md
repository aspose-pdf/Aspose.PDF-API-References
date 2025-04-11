---
title: Class ComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Comparison.ComparisonOptions. Mewakili kelas opsi perbandingan dokumen PDF
type: docs
weight: 3150
url: /id/net/aspose.pdf.comparison/comparisonoptions/
---
## Kelas ComparisonOptions

Mewakili kelas opsi perbandingan dokumen PDF.

```csharp
public class ComparisonOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | Mendapatkan dan mengatur urutan operasi edit. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | Mendapatkan dan mengatur area yang dikecualikan. Digunakan untuk halaman atau dokumen pertama dalam metode perbandingan. Opsi ini dapat diatur bersama dengan [`ExcludeTables`](./excludetables/). Opsi ini tidak dapat diatur bersama dengan opsi [`ExtractionArea`](./extractionarea/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | Mendapatkan dan mengatur area yang dikecualikan. Digunakan untuk halaman atau dokumen kedua dalam metode perbandingan. Opsi ini dapat diatur bersama dengan [`ExcludeTables`](./excludetables/). Opsi ini tidak dapat diatur bersama dengan opsi [`ExtractionArea`](./extractionarea/). |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | Mendapatkan dan mengatur opsi yang menentukan apakah tabel dikecualikan dari perbandingan. Opsi ini tidak dapat diatur bersama dengan opsi [`ExtractionArea`](./extractionarea/). Nilai default adalah `false`. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | Mendapatkan dan mengatur area persegi panjang di mana teks halaman akan dibandingkan. Opsi ini tidak dapat diatur bersama dengan opsi [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) dan [`ExcludeAreas2`](./excludeareas2/). |

### Lihat Juga

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)