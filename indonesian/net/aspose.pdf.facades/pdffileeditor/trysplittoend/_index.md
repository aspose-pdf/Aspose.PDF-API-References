---
title: PdfFileEditor.TrySplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Memisahkan dari lokasi dan menyimpan bagian belakang sebagai file baru
type: docs
weight: 470
url: /id/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Memisahkan dari lokasi, dan menyimpan bagian belakang sebagai file baru.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File Pdf sumber. |
| location | Int32 | Posisi pemisahan. |
| outputFile | String | Jalur file Pdf keluaran. |

### Return Value

True untuk berhasil, atau false.

## Remarks

Metode TrySplitToEnd mirip dengan metode SplitToEnd, kecuali metode TrySplitToEnd tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Memisahkan dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai file Stream baru.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream file Pdf sumber. |
| location | Int32 | Posisi pemisahan. |
| outputStream | Stream | Stream file Pdf keluaran. |

### Return Value

True untuk berhasil, atau false.

## Remarks

Stream TIDAK ditutup setelah operasi ini kecuali CloseConcatedStreams ditentukan. Metode TrySplitToEnd mirip dengan metode SplitToEnd, kecuali metode TrySplitToEnd tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

Memisahkan dari lokasi yang ditentukan, dan menyimpan bagian belakang ke dalam objek HttpResponse.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream dokumen sumber. |
| location | Int32 | Titik pemisahan. |
| response | HttpResponse | Objek HttpResponse. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TrySplitToEnd mirip dengan metode SplitToEnd, kecuali metode TrySplitToEnd tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

Memisahkan dari lokasi yang ditentukan, dan menyimpan bagian belakang ke dalam objek HttpResponse.

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | nama file sumber. |
| location | Int32 | Titik pemisahan. |
| response | HttpResponse | objek HttpResponse. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TrySplitToEnd mirip dengan metode SplitToEnd, kecuali metode TrySplitToEnd tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)