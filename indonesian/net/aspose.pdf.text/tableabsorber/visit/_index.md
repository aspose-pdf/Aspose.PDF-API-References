---
title: "TableAbsorber.Visit"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode TableAbsorber. Mengekstrak tabel pada halaman yang ditentukan"
type: docs
weight: 70
url: /id/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

Mengekstrak tabel pada halaman yang ditentukan

```csharp
public virtual void Visit(Page page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| halaman | Halaman | Objek halaman dokumen Pdf. |

## Contoh

Contoh ini menunjukkan cara mengekstrak tabel pada halaman pertama dokumen PDF.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TableAbsorber untuk menemukan tabel
TableAbsorber absorber = new TableAbsorber();

// Kunjungi halaman pertama dengan absorber
absorber.Visit(doc.Pages[1]);

// Dapatkan akses ke tabel pertama pada halaman, sel pertama mereka, dan fragmen teks di dalamnya
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Ubah teks fragmen teks pertama dalam sel
fragment.Text = "hi world";

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Mengekstrak tabel dalam dokumen yang ditentukan.

```csharp
public void Visit(Document pdf)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdf | Document | Objek Pdf pocument. |

## Contoh

Contoh ini menunjukkan cara mengekstrak tabel pada halaman pertama dokumen PDF.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TableAbsorber untuk menemukan tabel
TableAbsorber absorber = new TableAbsorber();

// Kunjungi halaman pertama dengan absorber
absorber.Visit(doc);

// Dapatkan akses ke tabel pertama pada halaman, sel pertama mereka, dan fragmen teks di dalamnya
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Ubah teks fragmen teks pertama dalam sel
fragment.Text = "hi world";

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


