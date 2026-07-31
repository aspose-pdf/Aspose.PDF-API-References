---
title: "PdfFileEditor.TrySplitToEnd"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileEditor. Membagi dari lokasi dan menyimpan bagian belakang sebagai file baru."
type: docs
weight: 470
url: /id/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Membagi dari lokasi, dan menyimpan bagian belakang sebagai file baru.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File Pdf sumber. |
| lokasi | Int32 | Posisi pemisahan. |
| outputFile | String | Jalur file Pdf keluaran. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Catatan

Metode TrySplitToEnd mirip dengan metode SplitToEnd, kecuali metode TrySplitToEnd tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai Stream file baru.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran file Pdf sumber. |
| lokasi | Int32 | Posisi pemisahan. |
| outputStream | Stream | Aliran file Pdf keluaran. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Catatan

Aliran tidak DITUTUP setelah operasi ini kecuali CloseConcatedStreams ditentukan. Metode TrySplitToEnd mirip dengan metode SplitToEnd, kecuali metode TrySplitToEnd tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


