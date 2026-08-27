---
title: "PdfFileEditor.TryInsert"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileEditor. Menyisipkan halaman dari file lain ke dalam file Pdf input"
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
| insertLocation | Int32 | Posisi sisipan dalam file input. |
| portFile | String | Halaman dari file Pdf. |
| pageNumber | Int32[] | Nomor halaman yang dipindahkan dalam portFile. |
| outputFile | String | File Pdf keluaran. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Catatan

Metode TryInsert mirip dengan metode Insert, kecuali metode TryInsert tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Lihat Juga

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
| inputStream | Stream | Aliran input file Pdf. |
| insertLocation | Int32 | Posisi sisipan dalam file input. |
| portStream | Stream | Aliran file Pdf untuk halaman. |
| pageNumber | Int32[] | Nomor halaman yang dipindahkan dalam portFile. |
| outputStream | Stream | Aliran Output. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryInsert mirip dengan metode Insert, kecuali metode TryInsert tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


