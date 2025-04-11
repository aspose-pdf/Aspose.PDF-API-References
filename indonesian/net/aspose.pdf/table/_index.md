---
title: Class Table
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Table. Mewakili tabel yang dapat ditambahkan ke halaman
type: docs
weight: 10280
url: /id/net/aspose.pdf/table/
---
## Kelas Tabel

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
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Mendapatkan atau mengatur teks pemisah untuk tabel |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Mendapatkan atau mengatur tabel yang terputus secara vertikal; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Mendapatkan atau mengatur penyesuaian kolom tabel. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Mendapatkan lebar kolom tabel. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Mendapatkan atau mengatur gaya sudut batas |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Mendapatkan batas sel default; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Mendapatkan atau mengatur padding sel default. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Mendapatkan atau mengatur status teks sel default. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Mendapatkan batas sel default; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal paragraf |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk generator pdf). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Mendapatkan atau mengatur batas yang termasuk dalam lebar kolom. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Mendapatkan atau mengatur apakah tabel terputus - akan dipotong untuk halaman berikutnya. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false. (untuk generasi pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur apakah paragraf adalah inline. Default adalah false. (untuk generasi pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan di halaman baru. Default adalah false. (untuk generasi pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap di halaman yang sama bersama dengan paragraf berikutnya. Default adalah false. (untuk generasi pdf) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Mendapatkan atau mengatur koordinat kiri tabel. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk generasi pdf) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Mendapatkan atau mengatur jumlah kolom maksimum untuk tabel |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Mendapatkan jumlah baris pertama yang diulang untuk beberapa halaman |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Mendapatkan gaya untuk baris yang diulang |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Mendapatkan baris tabel. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Mendapatkan atau mengatur koordinat atas tabel. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Mengkloning tabel. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Mendapatkan tinggi. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Mendapatkan lebar. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Mengimpor array data satu dimensi ke dalam tabel. Impor dilakukan satu sel untuk setiap item array dan dimulai dari baris dan kolom yang ditentukan dalam parameter. Selama impor, jika terdeteksi bahwa baris yang diperlukan masih tidak ada (yaitu tabel target terlalu kecil untuk menyerap semua data), baris yang diperlukan akan dibuat |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Mengimpor data dari System.Data.DataTable ke dalam Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Mengimpor objek DataTable ke dalam tabel. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Mengimpor objek DataTable, tetapi tidak sebagai entitas keseluruhan. Hanya baris dan kolom yang ditentukan yang diimpor. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Mengimpor data objek DataView ke dalam tabel. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Mengatur tinggi. |

### Lihat Juga

* kelas [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)