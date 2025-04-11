---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Membuat buku dari file input ke file output
type: docs
weight: 430
url: /id/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

Membuat buku dari file sumber dan menyimpan hasilnya ke objek HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur file sumber. |
| pageSize | PageSize | Ukuran halaman yang diinginkan. |
| leftPages | Int32[] | Array nomor halaman yang akan ditempatkan di kiri. |
| rightPages | Int32[] | Array nomor halaman yang akan ditempatkan di kanan. |
| response | HttpResponse | Objek HttpResponse tempat hasil akan disimpan. |

### Return Value

true jika operasi berhasil diselesaikan; jika tidak, false.

## Remarks

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Membuat buku dari file PDF dan menyimpannya ke HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran dokumen input. |
| pageSize | PageSize | Ukuran halaman yang diinginkan. |
| leftPages | Int32[] | Array nomor halaman yang akan ditempatkan di kiri. |
| rightPages | Int32[] | Array nomor halaman yang akan ditempatkan di kanan. |
| response | HttpResponse | Objek HttpResponse. |

### Return Value

true jika operasi berhasil diselesaikan; jika tidak, false.

## Remarks

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Membuat buku dari file sumber dan menyimpan hasilnya ke objek HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur file sumber. |
| pageSize | PageSize | Ukuran halaman yang diinginkan di file output. |
| response | HttpResponse | Objek HttpResponse tempat hasil akan disimpan. |

### Return Value

True jika operasi berhasil.

## Remarks

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Membuat buku dari file sumber dan menyimpan hasilnya ke HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran dokumen input. |
| pageSize | PageSize | Ukuran halaman yang diinginkan di file output. |
| response | HttpResponse | Objek tempat hasil akan disimpan. |

### Return Value

true jika buku berhasil dibangun.

## Remarks

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Membuat buku dari file input ke file output.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur dan nama file pdf input. |
| outputFile | String | Jalur dan nama file pdf output. |

### Return Value

true jika operasi berhasil diselesaikan; jika tidak, false.

## Remarks

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

Membuat buku dari InputStream ke outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran pdf input. |
| outputStream | Stream | aliran pdf output. |

### Return Value

true jika operasi berhasil diselesaikan; jika tidak, false.

## Remarks

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

Membuat buku dari inputFile ke outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur dan nama file pdf input. |
| outputFile | String | Jalur dan nama file pdf output. |
| pageSize | PageSize | Ukuran halaman dari file pdf output. |

### Return Value

True jika operasi berhasil.

## Remarks

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

Membuat buku dari aliran input dan menyimpan hasilnya ke aliran output.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran PDF input. |
| outputStream | Stream | aliran pdf output. |
| pageSize | PageSize | Ukuran halaman dari file pdf output. |

### Return Value

true jika operasi berhasil diselesaikan; jika tidak, false.

## Remarks

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

Membuat buku kustom dari firstInputFile ke outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File input. |
| outputFile | String | Jalur dan nama file pdf output. |
| leftPages | Int32[] | Halaman kiri dari buku. |
| rightPages | Int32[] | Halaman kanan dari buku. |

### Return Value

true jika operasi berhasil diselesaikan; jika tidak, false.

## Remarks

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

Membuat buku kustom dari firstInputStream ke outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran input. |
| outputStream | Stream | aliran pdf output. |
| leftPages | Int32[] | Halaman kiri. |
| rightPages | Int32[] | Halaman kanan. |

### Return Value

true jika operasi berhasil diselesaikan; jika tidak, false.

## Remarks

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

Membuat buku kustom dari firstInputFile ke outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File input. |
| outputFile | String | Jalur dan nama file pdf output. |
| pageSize | PageSize | Ukuran halaman dari file pdf output. |
| leftPages | Int32[] | Halaman kiri. |
| rightPages | Int32[] | Halaman kanan. |

### Return Value

true jika operasi berhasil diselesaikan; jika tidak, false.

## Remarks

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

Membuat buku dari firstInputStream ke outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran input. |
| outputStream | Stream | aliran pdf output. |
| pageSize | PageSize | Ukuran halaman dari file pdf output. |
| leftPages | Int32[] | Halaman kiri. |
| rightPages | Int32[] | Halaman kanan. |

### Return Value

true jika operasi berhasil diselesaikan; jika tidak, false.

## Remarks

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)