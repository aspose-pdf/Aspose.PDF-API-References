---
title: PdfFileEditor.TryDelete
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Menghapus halaman yang ditentukan oleh array nomor dari file input dan menyimpannya sebagai file Pdf baru
type: docs
weight: 400
url: /id/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpannya sebagai file Pdf baru.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur file input. |
| pageNumber | Int32[] | Indeks halaman dari file input. |
| outputFile | String | Jalur file output. |

### Return Value

true jika operasi berhasil diselesaikan; jika tidak, false.

## Remarks

Metode TryDelete mirip dengan metode Delete, kecuali metode TryDelete tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpannya sebagai file Pdf baru.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream file input. |
| pageNumber | Int32[] | Indeks halaman dari file input. |
| outputStream | Stream | Stream file output. |

### Return Value

True untuk keberhasilan, atau false.

## Remarks

Metode TryDelete mirip dengan metode Delete, kecuali metode TryDelete tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryDelete(string, int[], HttpResponse) {#trydelete_3}

Menghapus halaman yang ditentukan dari dokumen dan menyimpan hasilnya ke dalam objek HttpResponse.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur file sumber. |
| pageNumber | Int32[] | Array nomor halaman yang harus dihapus. |
| response | HttpResponse | Objek respons di mana dokumen hasil akan disimpan. |

### Return Value

true jika operasi berhasil diselesaikan; jika tidak, false.

## Remarks

Metode TryDelete mirip dengan metode Delete, kecuali metode TryDelete tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

Menghapus halaman yang ditentukan dari dokumen dan menyimpan hasilnya ke dalam objek HttpResponse.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream dokumen sumber. |
| pageNumber | Int32[] | Array nomor halaman yang akan dihapus. |
| response | HttpResponse | Objek HttpResponse |

### Return Value

true jika operasi berhasil diselesaikan; jika tidak, false.

## Remarks

Metode TryDelete mirip dengan metode Delete, kecuali metode TryDelete tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)