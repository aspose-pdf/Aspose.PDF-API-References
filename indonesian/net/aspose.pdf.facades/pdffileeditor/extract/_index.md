---
title: PdfFileEditor.Extract
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Mengekstrak halaman dari file input dan menyimpannya sebagai file Pdf baru
type: docs
weight: 280
url: /id/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Ekstrak(string, int, int, string) {#extract_2}

Mengekstrak halaman dari file input, menyimpannya sebagai file Pdf baru.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur file Pdf input. |
| startPage | Int32 | Nomor halaman awal. |
| endPage | Int32 | Nomor halaman akhir. |
| outputFile | String | Jalur file Pdf output. |

### Nilai Kembali

True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Ekstrak(string, int[], string) {#extract_3}

Mengekstrak halaman yang ditentukan oleh array nomor, menyimpannya sebagai file PDF baru.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur file input. |
| pageNumber | Int32[] | Indeks halaman dari file input. |
| outputFile | String | Jalur file output. |

### Nilai Kembali

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Ekstrak(Stream, int, int, Stream) {#extract}

Mengekstrak halaman dari file input, menyimpannya sebagai file Pdf baru.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream file input. |
| startPage | Int32 | Nomor halaman awal. |
| endPage | Int32 | Nomor halaman akhir. |
| outputStream | Stream | Stream file Pdf output. |

### Nilai Kembali

True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Ekstrak(Stream, int[], Stream) {#extract_1}

Mengekstrak halaman yang ditentukan oleh array nomor, menyimpannya sebagai file Pdf baru.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream file input. |
| pageNumber | Int32[] | Indeks halaman dari file input. |
| outputStream | Stream | Stream file output. |

### Nilai Kembali

True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)