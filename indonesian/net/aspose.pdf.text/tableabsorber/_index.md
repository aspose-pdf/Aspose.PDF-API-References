---
title: "Kelas TableAbsorber"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Text.TableAbsorber class. Mewakili objek penyerap elemen tabel. Melakukan pencarian dan menyediakan akses ke hasil pencarian melalui koleksi TableList."
type: docs
weight: 10970
url: /id/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class

Mewakili objek absorber elemen tabel. Melakukan pencarian dan menyediakan akses ke hasil pencarian melalui koleksi [`TableList`](./tablelist/).

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
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | Mengembalikan IList read‑only yang berisi tabel yang ditemukan |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | Mendapatkan atau mengatur opsi pencarian teks. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Aktifkan mesin pengenalan tabel alternatif yang lebih unggul dalam banyak skenario dan mampu mengenali tabel tanpa batas. Belum mendukung penyuntingan tabel dan mendapatkan gaya teks. Nilai default adalah false; |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Menghapus sebuah [`AbsorbedTable`](../absorbedtable/) dari halaman. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Mengganti sebuah [`AbsorbedTable`](../absorbedtable/) dengan [`Table`](../../aspose.pdf/table/) pada halaman. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Mengekstrak tabel dalam dokumen yang ditentukan. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Mengekstrak tabel pada halaman yang ditentukan |

## Contoh

Contoh ini menunjukkan cara menemukan tabel pada halaman pertama dokumen PDF dan mengganti teks dalam sel tabel.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TableAbsorber untuk menemukan tabel
TableAbsorber absorber = new TableAbsorber();

// Kunjungi halaman pertama dengan absorber
absorber.Visit(pdfDocument.Pages[1]);

// Dapatkan akses ke tabel pertama pada halaman, sel pertama mereka, dan fragmen teks di dalamnya
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Ubah teks fragmen teks pertama dalam sel
fragment.Text = "hi world";

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


