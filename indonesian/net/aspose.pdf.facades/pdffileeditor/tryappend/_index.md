---
title: "PdfFileEditor.TryAppend"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "metode PdfFileEditor. Menambahkan halaman yang dipilih dari array dokumen dalam portStreams. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portStreams dalam rentang startPage hingga endPage."
type: docs
weight: 380
url: /id/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Menambahkan halaman, yang dipilih dari array dokumen di portStreams. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portStreams dalam rentang startPage hingga endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran Pdf masukan. |
| portStreams | Stream[] | Dokumen untuk menyalin halaman dari. |
| startPage | Int32 | Halaman mulai dalam dokumen portStreams. |
| endPage | Int32 | Halaman berakhir dalam dokumen portStreams. |
| outputStream | Stream | Aliran Pdf keluaran. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Catatan

Metode TryAppend mirip dengan metode Append, kecuali metode TryAppend tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Menambahkan halaman, yang dipilih dari dokumen portFiles. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portFiles dalam rentang startPage hingga endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File Pdf input. |
| portFiles | String[] | Dokumen untuk menyalin halaman dari. |
| startPage | Int32 | Halaman mulai dalam dokumen portFiles. |
| endPage | Int32 | Halaman berakhir dalam dokumen portFiles. |
| outputFile | String | Dokumen Pdf keluaran. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryAppend mirip dengan metode Append, kecuali metode TryAppend tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


