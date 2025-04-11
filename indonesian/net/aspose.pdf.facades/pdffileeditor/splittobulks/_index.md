---
title: PdfFileEditor.SplitToBulks
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Memisahkan file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau beberapa halaman
type: docs
weight: 350
url: /id/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Memisahkan file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau beberapa halaman.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File PDF masukan. |
| numberOfPage | Int32[][] | Array yang berisi array elemen ganda, yang merupakan halaman awal dan akhir dokumen. |

### Return Value

Aliran PDF keluaran, setiap aliran menyimpan dokumen PDF.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Memisahkan file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau beberapa halaman.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran PDF masukan. |
| numberOfPage | Int32[][] | Halaman awal dan halaman akhir dari setiap dokumen. |

### Return Value

Aliran PDF keluaran, setiap aliran menyimpan dokumen PDF.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)