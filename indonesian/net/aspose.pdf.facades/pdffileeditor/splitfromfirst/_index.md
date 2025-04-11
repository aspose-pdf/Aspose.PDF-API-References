---
title: PdfFileEditor.SplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Memisahkan file Pdf dari halaman pertama ke lokasi yang ditentukan dan menyimpan bagian depan sebagai file baru
type: docs
weight: 340
url: /id/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Memisahkan file Pdf dari halaman pertama ke lokasi yang ditentukan, dan menyimpan bagian depan sebagai file baru.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File Pdf sumber. |
| location | Int32 | Titik pemisahan. |
| outputFile | String | File Pdf keluaran. |

### Return Value

True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

Memisahkan dari awal ke lokasi yang ditentukan, dan menyimpan bagian depan dalam Stream keluaran.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream file Pdf sumber. |
| location | Int32 | Titik pemisahan. |
| outputStream | Stream | Stream file keluaran. |

### Return Value

True untuk sukses, atau false.

## Catatan

Stream TIDAK ditutup setelah operasi ini.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)