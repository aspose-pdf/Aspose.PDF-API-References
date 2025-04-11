---
title: PdfFileEditor.TryConcatenate
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Menggabungkan dua file
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
| outputFile | String | File keluaran. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### See Also

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

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melempar pengecualian jika operasi gagal.

### See Also

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
| outputFile | String | Nama file keluaran. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### See Also

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
| inputStream | Stream[] | Array stream yang akan digabungkan. |
| outputStream | Stream | Stream tempat file hasil akan disimpan. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. Misalnya: dokumen1 memiliki 5 halaman: p1, p2, p3, p4, p5. dokumen2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan kedua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman: p1, p1', p2, p2', p3, p3', p4, halaman kosong, p5, halaman kosong.

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

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. Misalnya: dokumen1 memiliki 5 halaman: p1, p2, p3, p4, p5. dokumen2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan kedua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman: p1, p1', p2, p2', p3, p3', p4, halaman kosong, p5, halaman kosong.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputStream | Stream | Stream Pdf pertama. |
| secInputStream | Stream | Stream Pdf kedua. |
| blankPageStream | Stream | Stream Pdf dengan halaman kosong. |
| outputStream | Stream | Stream Pdf keluaran. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Menggabungkan file dan menyimpan hasilnya ke dalam objek HttpResponse.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFiles | String[] | Array file untuk digabungkan. |
| response | HttpResponse | Objek respons. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Menggabungkan file dan menyimpan hasilnya ke dalam objek HttpResponse.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream[] | Array stream yang berisi file untuk digabungkan. |
| response | HttpResponse | Objek respons. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryConcatenate mirip dengan metode Concatenate, kecuali metode TryConcatenate tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)