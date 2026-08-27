---
title: "Kelas Table"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Table kelas. Mewakili tabel yang dapat ditambahkan ke halaman"
type: docs
weight: 10460
url: /id/net/aspose.pdf/table/
---
## Table class

Mewakili tabel yang dapat ditambahkan ke halaman.

```csharp
public sealed class Table : BaseParagraph
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Table](table/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | Mendapatkan atau mengatur perataan tabel. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | Mendapatkan atau mengatur warna latar belakang tabel |
| [Border](../../aspose.pdf/table/border/) { get; set; } | Mendapatkan atau mengatur batas. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Mendapatkan atau mengatur teks jeda untuk tabel |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Mendapatkan atau mengatur tabel vertikal rusak; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Mendapatkan atau mengatur penyesuaian kolom tabel. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Mendapatkan lebar kolom tabel. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Mendapatkan atau mengatur gaya sudut batas. |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Mendapatkan batas sel default; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Mendapatkan atau mengatur padding sel default. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Mendapatkan atau mengatur status teks sel default. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Mendapatkan batas sel default; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal paragraf |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk pdf generator). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Mendapatkan atau mengatur batas yang termasuk dalam lebar kolom. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Mendapatkan atau mengatur apakah tabel terputus - akan dipotong untuk halaman berikutnya. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Defaultnya false. (untuk pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf menjadi inline. Defaultnya false. (untuk pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Defaultnya false. (untuk pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Defaultnya false. (untuk pdf generation) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Mendapatkan atau mengatur koordinat kiri tabel. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan PDF) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Mendapatkan atau mengatur jumlah kolom maksimum untuk tabel |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Mendapatkan jumlah baris pertama yang diulang untuk beberapa halaman |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Mendapatkan gaya untuk baris yang diulang |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Mendapatkan baris-baris tabel. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Mendapatkan atau mengatur koordinat atas tabel. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai integer yang menunjukkan urutan Z grafik. Grafik dengan ZIndex lebih besar akan ditempatkan di atas grafik dengan ZIndex lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Gandakan tabel. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Dapatkan tinggi. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Dapatkan lebar. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Mengimpor array satu dimensi data ke dalam tabel. Impor menempatkan satu sel per setiap item array dan dimulai dari baris serta kolom yang ditentukan dalam parameter. Selama impor, jika terdeteksi bahwa baris yang diperlukan masih belum ada (misalnya tabel target terlalu kecil untuk menampung semua data), baris yang diperlukan akan dibuat |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Mengimpor data dari System.Data.DataTable ke Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Mengimpor objek DataTable ke dalam tabel. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Mengimpor objek DataTable, tetapi tidak sebagai keseluruhan. Hanya baris dan kolom yang ditentukan yang diimpor. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Mengimpor data objek DataView ke dalam tabel. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Atur tinggi. |

### Lihat Juga

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


