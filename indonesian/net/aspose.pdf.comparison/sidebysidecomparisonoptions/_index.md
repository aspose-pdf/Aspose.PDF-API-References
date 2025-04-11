---
title: Class SideBySideComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Comparison.SideBySideComparisonOptions. Mewakili kelas opsi untuk membandingkan dokumen dengan output berdampingan
type: docs
weight: 3290
url: /id/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## Kelas SideBySideComparisonOptions

Mewakili kelas opsi untuk membandingkan dokumen dengan output berdampingan.

```csharp
public class SideBySideComparisonOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Mendapatkan dan mengatur properti yang menentukan apakah penanda perubahan tambahan ditampilkan. Jika diatur, menampilkan penanda perubahan yang tidak ada di halaman saat ini tetapi ada di halaman lain. Jika perubahan terjadi di antara kata-kata, penanda mungkin tidak diposisikan tepat relatif terhadap karakter spasi. Nilai default adalah `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Mendapatkan dan mengatur area perbandingan. Digunakan untuk halaman atau dokumen pertama dalam metode perbandingan. Opsi ini tidak dapat diatur bersamaan dengan opsi [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) dan [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Mendapatkan dan mengatur area perbandingan. Digunakan untuk halaman atau dokumen kedua dalam metode perbandingan. Opsi ini tidak dapat diatur bersamaan dengan opsi [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) dan [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Mendapatkan dan mengatur mode perbandingan. Nilai default adalah !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Mendapatkan dan mengatur area yang dikecualikan. Digunakan untuk halaman atau dokumen pertama dalam metode perbandingan. Opsi ini dapat diatur bersamaan dengan [`ExcludeTables`](./excludetables/). Opsi ini tidak dapat diatur bersamaan dengan opsi [`ComparisonArea1`](./comparisonarea1/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Mendapatkan dan mengatur area yang dikecualikan. Digunakan untuk halaman atau dokumen kedua dalam metode perbandingan. Opsi ini dapat diatur bersamaan dengan [`ExcludeTables`](./excludetables/). Opsi ini tidak dapat diatur bersamaan dengan opsi [`ComparisonArea2`](./comparisonarea2/). |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Mendapatkan dan mengatur opsi yang menentukan apakah tabel dikecualikan dari perbandingan. Opsi ini tidak dapat diatur bersama dengan [`ComparisonArea1`](./comparisonarea1/) dan [`ComparisonArea2`](./comparisonarea2/). Nilai default adalah `false`. |

### Lihat Juga

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)