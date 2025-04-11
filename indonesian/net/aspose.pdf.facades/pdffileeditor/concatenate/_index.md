---
title: PdfFileEditor.Concatenate
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Menggabungkan dua file
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
| outputFile | String | File keluaran. |

### Return Value

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
| firstInputStream | Stream | Stream dari file pertama. |
| secInputStream | Stream | Stream dari file kedua. |
| outputStream | Stream | Stream tempat file hasil akan disimpan. |

### Return Value

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

### Return Value

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
| outputFile | String | Nama file keluaran. |

### Return Value

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
| inputStream | Stream[] | Array stream yang akan digabungkan. |
| outputStream | Stream | Stream tempat file hasil akan disimpan. |

### Return Value

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

Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. misalnya: dokumen1 memiliki 5 halaman: p1, p2, p3, p4, p5. dokumen2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan kedua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman: p1, p1', p2, p2', p3, p3', p4, halaman kosong, p5, halaman kosong.

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

### Return Value

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

Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. misalnya: dokumen1 memiliki 5 halaman: p1, p2, p3, p4, p5. dokumen2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan kedua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman: p1, p1', p2, p2', p3, p3', p4, halaman kosong, p5, halaman kosong.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputStream | Stream | Stream Pdf pertama. |
| secInputStream | Stream | Stream Pdf kedua. |
| blankPageStream | Stream | Stream Pdf dengan halaman kosong. |
| outputStream | Stream | Stream Pdf keluaran. |

### Return Value

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


## Concatenate(string[], HttpResponse) {#concatenate_8}

Menggabungkan file dan menyimpan hasilnya ke dalam objek HttpResponse.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFiles | String[] | Array file untuk digabungkan. |
| response | HttpResponse | Objek respons. |

### Return Value

true jika penggabungan berhasil.

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

Menggabungkan file dan menyimpan hasilnya ke dalam objek HttpResponse.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream[] | Array stream yang berisi file untuk digabungkan. |
| response | HttpResponse | Objek respons. |

### Return Value

true jika operasi berhasil.

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)