---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Text.TableAbsorber. Mewakili objek penyerap elemen tabel. Melakukan pencarian dan menyediakan akses ke hasil pencarian melalui koleksi TableList
type: docs
weight: 10790
url: /id/net/aspose.pdf.text/tableabsorber/
---
## Kelas TableAbsorber

Mewakili objek penyerap elemen tabel. Melakukan pencarian dan menyediakan akses ke hasil pencarian melalui koleksi [`TableList`](./tablelist/).

```csharp
public class TableAbsorber
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | Menginisialisasi instance baru dari `TableAbsorber`. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | Menginisialisasi instance baru dari `TableAbsorber` dengan opsi pencarian teks. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | Mengembalikan IList yang hanya baca yang berisi tabel yang ditemukan |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | Mendapatkan atau mengatur opsi pencarian teks. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Mengaktifkan mesin pengenalan tabel alternatif yang lebih unggul dalam banyak skenario dan mampu mengenali tabel tanpa batas. Belum mendukung pengeditan tabel dan mendapatkan gaya teks. Nilai default adalah false; |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Menghapus [`AbsorbedTable`](../absorbedtable/) dari halaman. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Mengganti [`AbsorbedTable`](../absorbedtable/) dengan [`Table`](../../aspose.pdf/table/) di halaman. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Mengekstrak tabel di dokumen yang ditentukan. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Mengekstrak tabel di halaman yang ditentukan |

## Contoh

Contoh ini menunjukkan cara menemukan tabel di halaman pertama dokumen PDF dan mengganti teks dalam sel tabel.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(pdfDocument.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)