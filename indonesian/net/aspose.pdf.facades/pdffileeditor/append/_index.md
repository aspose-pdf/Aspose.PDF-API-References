---
title: PdfFileEditor.Append
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Menambahkan halaman yang dipilih dari array dokumen dalam portStreams. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portStreams dalam rentang startPage hingga endPage
type: docs
weight: 250
url: /id/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Menambahkan halaman, yang dipilih dari array dokumen dalam portStreams. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portStreams dalam rentang startPage hingga endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream Pdf input. |
| portStreams | Stream[] | Dokumen untuk menyalin halaman dari. |
| startPage | Int32 | Halaman mulai dalam dokumen portStreams. |
| endPage | Int32 | Halaman berakhir dalam dokumen portStreams. |
| outputStream | Stream | Stream Pdf output. |

### Return Value

True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

Menambahkan halaman, yang dipilih dari dokumen portFiles. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portFiles dalam rentang startPage hingga endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File Pdf input. |
| portFiles | String[] | Dokumen untuk menyalin halaman dari. |
| startPage | Int32 | Halaman mulai dalam dokumen portFiles. |
| endPage | Int32 | Halaman berakhir dalam dokumen portFiles. |
| outputFile | String | Dokumen Pdf output. |

### Return Value

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

Menambahkan halaman, yang dipilih dari portFile dalam rentang dari startPage hingga endPage, di portFile di akhir firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File Pdf input. |
| portFile | String | Halaman dari file Pdf. |
| startPage | Int32 | Halaman mulai dalam portFile. |
| endPage | Int32 | Halaman berakhir dalam portFile. |
| outputFile | String | Dokumen Pdf output. |

### Return Value

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Menambahkan halaman, yang dipilih dari portStream dalam rentang dari startPage hingga endPage, di portStream di akhir firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream file input. |
| portStream | Stream | Halaman dari Stream file Pdf. |
| startPage | Int32 | Halaman mulai dalam Stream portFile. |
| endPage | Int32 | Halaman berakhir dalam Stream portFile. |
| outputStream | Stream | Stream file Pdf output. |

### Return Value

True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)