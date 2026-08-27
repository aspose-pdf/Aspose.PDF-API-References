---
title: "PdfFileEditor.TryConcatenate"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfFileEditor method. Menggabungkan dua file"
type: docs
weight: 390
url: /id/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

Menggabungkan dua file.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputFile | String | File pertama untuk digabungkan. |
| secInputFile | String | File kedua untuk digabungkan. |
| outputFile | String | File output. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melemparkan pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Menggabungkan dokumen.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | Document[] | Array dokumen sumber. |
| dest | Document | Dokumen tujuan. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melemparkan pengecualian jika operasi gagal.

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

Menggabungkan file menjadi satu file.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFiles | String[] | Array file untuk digabungkan. |
| outputFile | String | Nama file output. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melemparkan pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Menggabungkan file

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream[] | Array aliran yang akan digabungkan. |
| outputStream | Stream | Stream tempat file hasil akan disimpan. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melemparkan pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. contoh: document1 memiliki 5 halaman: p1, p2, p3, p4, p5. document2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan dua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputFile | String | File pertama. |
| secInputFile | String | File kedua. |
| blankPageFile | String | File PDF dengan halaman kosong. |
| outputFile | String | File hasil. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melemparkan pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. contoh: document1 memiliki 5 halaman: p1, p2, p3, p4, p5. document2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan dua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputStream | Stream | Aliran Pdf pertama. |
| secInputStream | Stream | Aliran Pdf kedua. |
| blankPageStream | Stream | Aliran Pdf dengan halaman kosong. |
| outputStream | Stream | Aliran Pdf keluaran. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melemparkan pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


