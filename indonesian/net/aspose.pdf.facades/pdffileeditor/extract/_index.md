---
title: "PdfFileEditor.Extract"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfFileEditor method. Mengekstrak halaman dari file masukan dan menyimpannya sebagai file Pdf baru."
type: docs
weight: 280
url: /id/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

Mengekstrak halaman dari file input, menyimpan sebagai file Pdf baru.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur file Pdf input. |
| startPage | Int32 | Nomor halaman mulai. |
| endPage | Int32 | Nomor halaman akhir. |
| outputFile | String | Jalur file Pdf keluaran. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file PDF baru.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Path file input. |
| pageNumber | Int32[] | Indeks halaman di luar file input. |
| outputFile | String | Path file output. |

### Nilai Kembalian

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Mengekstrak halaman dari file input, menyimpan sebagai file Pdf baru.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran file masukan. |
| startPage | Int32 | Nomor halaman mulai. |
| endPage | Int32 | Nomor halaman akhir. |
| outputStream | Stream | Aliran file Pdf keluaran. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file Pdf baru.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran file masukan. |
| pageNumber | Int32[] | Indeks halaman di luar file input. |
| outputStream | Stream | Aliran file output. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


