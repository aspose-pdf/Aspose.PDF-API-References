---
title: PdfFileEditor.SplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Memisahkan dari lokasi dan menyimpan bagian belakang sebagai file baru
type: docs
weight: 360
url: /id/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

Memisahkan dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai file Stream baru.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream file Pdf sumber. |
| location | Int32 | Posisi pemisahan. |
| outputStream | Stream | Stream file Pdf keluaran. |

### Return Value

True untuk sukses, atau false.

## Remarks

Stream TIDAK ditutup setelah operasi ini kecuali CloseConcatedStreams ditentukan.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

Memisahkan dari lokasi, dan menyimpan bagian belakang sebagai file baru.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File Pdf sumber. |
| location | Int32 | Posisi pemisahan. |
| outputFile | String | Jalur file Pdf keluaran. |

### Return Value

True untuk sukses, atau false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

Memisahkan dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai file Stream baru.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream file Pdf sumber. |
| location | Int32 | Posisi pemisahan. |
| outputStream | Stream | Stream file Pdf keluaran. |

### Return Value

True untuk sukses, atau false.

## Remarks

Stream TIDAK ditutup setelah operasi ini kecuali CloseConcatedStreams ditentukan.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)