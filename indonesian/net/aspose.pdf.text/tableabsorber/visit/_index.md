---
title: TableAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Metode TableAbsorber. Mengekstrak tabel pada halaman yang ditentukan
type: docs
weight: 70
url: /id/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

Mengekstrak tabel pada halaman yang ditentukan

```csharp
public virtual void Visit(Page page)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| page | Page | Objek halaman dokumen Pdf. |

## Contoh

Contoh ini menunjukkan cara mengekstrak tabel pada halaman pertama dokumen PDF.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(doc.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
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

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| pdf | Document | Objek dokumen Pdf. |

## Contoh

Contoh ini menunjukkan cara mengekstrak tabel pada halaman pertama dokumen PDF.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(doc);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)