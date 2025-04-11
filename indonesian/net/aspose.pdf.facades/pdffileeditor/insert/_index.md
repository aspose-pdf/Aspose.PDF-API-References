---
title: PdfFileEditor.Insert
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Menyisipkan halaman dari file lain ke dalam file Pdf pada posisi tertentu
type: docs
weight: 290
url: /id/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

Menyisipkan halaman dari file lain ke dalam file Pdf pada posisi tertentu.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File Pdf masukan. |
| insertLocation | Int32 | Posisi dalam file masukan. |
| portFile | String | File Pdf yang dipindahkan. |
| startPage | Int32 | Posisi awal dalam portFile. |
| endPage | Int32 | Posisi akhir dalam portFile. |
| outputFile | String | File Pdf keluaran. |

### Return Value

True untuk berhasil, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Menyisipkan halaman dari file lain ke dalam file Pdf masukan.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream masukan dari file Pdf. |
| insertLocation | Int32 | Posisi sisip dalam file masukan. |
| portStream | Stream | Stream file Pdf untuk halaman. |
| startPage | Int32 | Dari halaman mana untuk memulai. |
| endPage | Int32 | Hingga halaman mana untuk diakhiri. |
| outputStream | Stream | Stream keluaran. |

### Return Value

True untuk berhasil, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

Menyisipkan halaman dari file lain ke dalam file Pdf masukan.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File Pdf masukan. |
| insertLocation | Int32 | Posisi sisip dalam file masukan. |
| portFile | String | Halaman dari file Pdf. |
| pageNumber | Int32[] | Nomor halaman yang dipindahkan dalam portFile. |
| outputFile | String | File Pdf keluaran. |

### Return Value

True untuk berhasil, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Menyisipkan halaman dari file lain ke dalam file Pdf masukan.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream masukan dari file Pdf. |
| insertLocation | Int32 | Posisi sisip dalam file masukan. |
| portStream | Stream | Stream file Pdf untuk halaman. |
| pageNumber | Int32[] | Nomor halaman yang dipindahkan dalam portFile. |
| outputStream | Stream | Stream keluaran. |

### Return Value

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)