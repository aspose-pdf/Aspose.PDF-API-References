---
title: "PdfFileEditor.Concatenate"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfFileEditor method. Menggabungkan dua file"
type: docs
weight: 260
url: /id/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_4}

Menggabungkan dua file.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputFile | String | File pertama untuk digabungkan. |
| secInputFile | String | File kedua untuk digabungkan. |
| outputFile | String | File output. |

### Nilai Kembalian

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

Menggabungkan dua file.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputStream | Stream | Stream file pertama. |
| secInputStream | Stream | Stream file kedua. |
| outputStream | Stream | Stream tempat file hasil akan disimpan. |

### Nilai Kembalian

True jika operasi berhasil.

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

Menggabungkan dokumen.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | Document[] | Array dokumen sumber. |
| dest | Document | Dokumen tujuan. |

### Nilai Kembalian

True jika penggabungan berhasil.

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_6}

Menggabungkan file menjadi satu file.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFiles | String[] | Array file untuk digabungkan. |
| outputFile | String | Nama file output. |

### Nilai Kembalian

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

Menggabungkan file

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream[] | Array aliran yang akan digabungkan. |
| outputStream | Stream | Stream tempat file hasil akan disimpan. |

### Nilai Kembalian

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. contoh: document1 memiliki 5 halaman: p1, p2, p3, p4, p5. document2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan dua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputFile | String | File pertama. |
| secInputFile | String | File kedua. |
| blankPageFile | String | File PDF dengan halaman kosong. |
| outputFile | String | File hasil. |

### Nilai Kembalian

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. contoh: document1 memiliki 5 halaman: p1, p2, p3, p4, p5. document2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan dua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputStream | Stream | Aliran Pdf pertama. |
| secInputStream | Stream | Aliran Pdf kedua. |
| blankPageStream | Stream | Aliran Pdf dengan halaman kosong. |
| outputStream | Stream | Aliran Pdf keluaran. |

### Nilai Kembalian

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


