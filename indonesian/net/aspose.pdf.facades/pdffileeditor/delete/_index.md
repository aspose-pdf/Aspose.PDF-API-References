---
title: PdfFileEditor.Delete
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Menghapus halaman yang ditentukan oleh array nomor dari file input dan menyimpannya sebagai file Pdf baru
type: docs
weight: 270
url: /id/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpannya sebagai file Pdf baru.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur file input. |
| pageNumber | Int32[] | Indeks halaman dari file input. |
| outputFile | String | Jalur file output. |

### Return Value

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpannya sebagai file Pdf baru.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream file input. |
| pageNumber | Int32[] | Indeks halaman dari file input. |
| outputStream | Stream | Stream file output. |

### Return Value

True untuk keberhasilan, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)