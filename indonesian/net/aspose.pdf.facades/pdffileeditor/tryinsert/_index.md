---
title: PdfFileEditor.TryInsert
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Menyisipkan halaman dari file lain ke dalam file Pdf input
type: docs
weight: 420
url: /id/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

Menyisipkan halaman dari file lain ke dalam file Pdf input.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File Pdf input. |
| insertLocation | Int32 | Posisi penyisipan dalam file input. |
| portFile | String | Halaman dari file Pdf. |
| pageNumber | Int32[] | Nomor halaman yang dipindahkan dalam portFile. |
| outputFile | String | File Pdf output. |

### Return Value

True untuk berhasil, atau false.

## Remarks

Metode TryInsert mirip dengan metode Insert, kecuali metode TryInsert tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Menyisipkan halaman dari file lain ke dalam file Pdf input.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream dari file Pdf input. |
| insertLocation | Int32 | Posisi penyisipan dalam file input. |
| portStream | Stream | Stream dari file Pdf untuk halaman. |
| pageNumber | Int32[] | Nomor halaman yang dipindahkan dalam portFile. |
| outputStream | Stream | Stream output. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryInsert mirip dengan metode Insert, kecuali metode TryInsert tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Menyisipkan konten file ke dalam file sumber dan menyimpan hasilnya ke dalam objek HttpResponse.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Nama file sumber. |
| insertLocation | Int32 | Nomor halaman di mana file kedua akan disisipkan. |
| portFile | String | Jalur ke file yang akan disisipkan. |
| pageNumber | Int32[] | Array nomor halaman dalam file sumber yang akan disisipkan. |
| response | HttpResponse | Objek respons di mana hasil akan disimpan. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryInsert mirip dengan metode Insert, kecuali metode TryInsert tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Menyisipkan dokumen ke dalam dokumen lain dan menyimpan hasilnya ke dalam objek respons.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream dengan dokumen sumber |
| insertLocation | Int32 | Lokasi di mana dokumen lain akan disisipkan. |
| portStream | Stream | Dokumen yang akan disisipkan. |
| pageNumber | Int32[] | Array nomor halaman dalam dokumen kedua yang akan disisipkan. |
| response | HttpResponse | Objek respons di mana hasil akan disimpan. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryInsert mirip dengan metode Insert, kecuali metode TryInsert tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)