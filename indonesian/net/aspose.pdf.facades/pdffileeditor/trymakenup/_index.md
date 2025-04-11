---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Membuat dokumen NUp dari firstInputFile ke outputFile
type: docs
weight: 440
url: /id/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

Membuat dokumen N-up dan menyimpan hasilnya ke dalam objek HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur ke file sumber. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |
| pageSize | PageSize | Ukuran halaman dalam file hasil. |
| response | HttpResponse | Objek HttpResponse di mana hasil akan disimpan. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Membuat dokumen N-up dan menyimpan hasilnya ke dalam objek HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream dari dokumen sumber. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |
| pageSize | PageSize | Ukuran halaman dalam file hasil. |
| response | HttpResponse | Objek HttpResponse di mana hasil akan disimpan. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Membuat dokumen N-up dan menyimpan hasilnya ke dalam HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Nama file sumber. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |
| response | HttpResponse | Objek HttpResponse di mana hasil akan disimpan. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Membuat dokumen N-up dan menyimpan hasilnya ke dalam HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream dari dokumen input. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |
| response | HttpResponse | HttpResponse di mana hasil akan disimpan. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Membuat dokumen N-Up dari firstInputFile ke outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur dan nama file pdf input. |
| outputFile | String | Jalur dan nama file pdf output. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

Membuat dokumen N-Up dari stream input dan menyimpan hasilnya ke dalam stream output.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream pdf input. |
| outputStream | Stream | Stream pdf output. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

Membuat dokumen N-Up dari stream input pertama ke stream output.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream pdf input. |
| outputStream | Stream | Stream pdf output. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |
| pageSize | PageSize | Ukuran halaman dari file pdf output. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

Membuat dokumen N-Up dari dua file PDF input ke outputFile. Setiap halaman dari outputFile akan berisi dua halaman, satu halaman dari file input pertama dan satu halaman dari file input kedua. Dua halaman tersebut ditumpuk secara horizontal.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputFile | String | file input pertama. |
| secondInputFile | String | file input kedua. |
| outputFile | String | Jalur dan nama file pdf output. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false

## Remarks

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

Membuat dokumen N-Up dari dua stream PDF input ke outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputStream | Stream | stream input pertama. |
| secondInputStream | Stream | stream input kedua. |
| outputStream | Stream | Stream pdf output. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false

## Remarks

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

Membuat dokumen N-Up dari beberapa file PDF input ke outputFile. Setiap halaman dari outputFile akan berisi beberapa halaman, yang merupakan kombinasi dari halaman-halaman dalam file input dengan nomor halaman yang sama. Beberapa halaman ditumpuk secara horizontal jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFiles | String[] | File Pdf input. |
| outputFile | String | Jalur dan nama file pdf output. |
| isSidewise | Boolean | Cara penumpukan, true untuk horizontal dan false untuk vertikal. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

Membuat dokumen N-Up dari beberapa stream PDF input ke outputStream. Setiap halaman dari outputStream akan berisi beberapa halaman, yang merupakan kombinasi dari halaman-halaman dalam stream input dengan nomor halaman yang sama. Beberapa halaman ditumpuk secara horizontal jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStreams | Stream[] | Stream Pdf input. |
| outputStream | Stream | Stream pdf output. |
| isSidewise | Boolean | Cara penumpukan, true untuk horizontal dan false untuk vertikal. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

Membuat dokumen N-Up dari file input ke outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur dan nama file pdf input. |
| outputFile | String | Jalur dan nama file pdf output. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |
| pageSize | PageSize | Ukuran halaman dari file pdf output. |

### Return Value

true jika operasi selesai dengan sukses; jika tidak, false.

## Remarks

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)