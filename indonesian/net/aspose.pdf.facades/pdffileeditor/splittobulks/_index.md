---
title: "PdfFileEditor.SplitToBulks"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileEditor. Membagi file PDF menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau multi halaman."
type: docs
weight: 350
url: /id/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berisi satu halaman atau beberapa halaman.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File PDF input. |
| numberOfPage | Int32[][] | Array yang berisi array elemen double, yang merupakan halaman awal dan akhir dokumen. |

### Nilai Kembalian

Aliran PDF keluaran, setiap aliran menampung sebuah dokumen PDF.

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berisi satu halaman atau beberapa halaman.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran PDF masukan. |
| numberOfPage | Int32[][] | Halaman awal dan halaman akhir dari setiap dokumen. |

### Nilai Kembalian

Aliran PDF keluaran, setiap aliran menampung sebuah dokumen PDF.

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


