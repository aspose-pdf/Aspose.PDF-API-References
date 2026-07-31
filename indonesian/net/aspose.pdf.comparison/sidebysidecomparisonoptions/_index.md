---
title: "Kelas SideBySideComparisonOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Comparison.SideBySideComparisonOptions. Mewakili kelas opsi untuk membandingkan dokumen dengan output berdampingan"
type: docs
weight: 3400
url: /id/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class

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
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Dapatkan dan atur properti yang menentukan apakah penanda perubahan tambahan ditampilkan. Jika diatur, menampilkan tanda perubahan yang tidak ada pada halaman saat ini tetapi ada pada halaman lain. Jika perubahan terletak di antara kata-kata, tanda tersebut mungkin tidak diposisikan secara tepat relatif terhadap karakter spasi. Nilai default adalah `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Dapatkan dan atur area perbandingan. Digunakan untuk halaman atau dokumen pertama dalam metode perbandingan. Opsi ini tidak dapat diatur bersama dengan opsi [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) dan [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Dapatkan dan atur area perbandingan. Digunakan untuk halaman atau dokumen kedua dalam metode perbandingan. Opsi ini tidak dapat diatur bersama dengan opsi [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) dan [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Mendapatkan dan mengatur mode perbandingan. Nilai default adalah !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Dapatkan dan atur area pengecualian. Digunakan untuk halaman atau dokumen pertama dalam metode perbandingan. Opsi ini dapat diatur bersama dengan [`ExcludeTables`](./excludetables/). Opsi ini tidak dapat diatur bersama dengan opsi [`ComparisonArea1`](./comparisonarea1/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Dapatkan dan atur area pengecualian. Digunakan untuk halaman atau dokumen kedua dalam metode perbandingan. Opsi ini dapat diatur bersama dengan [`ExcludeTables`](./excludetables/). Opsi ini tidak dapat diatur bersama dengan opsi [`ComparisonArea2`](./comparisonarea2/). |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Dapatkan dan atur opsi yang menentukan apakah tabel dikecualikan dari perbandingan. Opsi ini tidak dapat diatur bersama dengan [`ComparisonArea1`](./comparisonarea1/) dan [`ComparisonArea2`](./comparisonarea2/). Nilai default adalah `false`. |

### Lihat Juga

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


