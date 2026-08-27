---
title: "PdfFileEditor.Delete"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileEditor. Menghapus halaman yang ditentukan oleh array nomor dari file input dan menyimpannya sebagai file Pdf baru"
type: docs
weight: 270
url: /id/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Path file input. |
| pageNumber | Int32[] | Indeks halaman di luar file input. |
| outputFile | String | Path file output. |

### Nilai Kembalian

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran file masukan. |
| pageNumber | Int32[] | Indeks halaman di luar file input. |
| outputStream | Stream | Aliran file output. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


