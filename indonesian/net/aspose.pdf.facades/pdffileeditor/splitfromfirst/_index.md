---
title: "PdfFileEditor.SplitFromFirst"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileEditor. Membagi file Pdf dari halaman pertama hingga lokasi yang ditentukan dan menyimpan bagian depan sebagai file baru"
type: docs
weight: 340
url: /id/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Membagi file Pdf dari halaman pertama hingga lokasi yang ditentukan, dan menyimpan bagian depan sebagai file baru.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File Pdf sumber. |
| lokasi | Int32 | Titik pemisahan. |
| outputFile | String | File Pdf keluaran. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

Membagi dari awal hingga lokasi yang ditentukan, dan menyimpan bagian depan ke Stream output.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran file Pdf sumber. |
| lokasi | Int32 | Titik pemisahan. |
| outputStream | Stream | Stream file output. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Catatan

Aliran TIDAK ditutup setelah operasi ini.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


