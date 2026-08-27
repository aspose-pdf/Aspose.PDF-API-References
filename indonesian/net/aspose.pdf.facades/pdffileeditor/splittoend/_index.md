---
title: "PdfFileEditor.SplitToEnd"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileEditor. Membagi dari lokasi dan menyimpan bagian belakang sebagai file baru."
type: docs
weight: 360
url: /id/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai Stream file baru.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran file Pdf sumber. |
| lokasi | Int32 | Posisi pemisahan. |
| outputStream | Stream | Aliran file Pdf keluaran. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Catatan

Aliran TIDAK ditutup setelah operasi ini kecuali CloseConcatedStreams ditentukan.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

Membagi dari lokasi, dan menyimpan bagian belakang sebagai file baru.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File Pdf sumber. |
| lokasi | Int32 | Posisi pemisahan. |
| outputFile | String | Jalur file Pdf keluaran. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai Stream file baru.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran file Pdf sumber. |
| lokasi | Int32 | Posisi pemisahan. |
| outputStream | Stream | Aliran file Pdf keluaran. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Catatan

Aliran TIDAK ditutup setelah operasi ini kecuali CloseConcatedStreams ditentukan.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


