---
title: PdfFileEditor.MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Membuat dokumen NUp dari dua aliran PDF input ke outputStream
type: docs
weight: 310
url: /id/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

Membuat dokumen N-Up dari firstInputFile ke outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur dan nama file pdf input. |
| outputFile | String | Jalur dan nama file pdf output. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |

### Return Value

boolean - True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Membuat dokumen N-Up dari aliran input dan menyimpan hasilnya ke aliran output.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran pdf input. |
| outputStream | Stream | Aliran pdf output. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |

### Return Value

boolean - True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

Membuat dokumen N-Up dari aliran input pertama ke aliran output.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran pdf input. |
| outputStream | Stream | Aliran pdf output. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |
| pageSize | PageSize | Ukuran halaman dari file pdf output. |

### Return Value

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

Membuat dokumen N-Up dari dua file PDF input ke outputFile. Setiap halaman dari outputFile akan berisi dua halaman, satu halaman dari file input pertama dan satu lagi dari file input kedua. Dua halaman tersebut ditumpuk secara horizontal.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputFile | String | file input pertama. |
| secondInputFile | String | file input kedua. |
| outputFile | String | Jalur dan nama file pdf output. |

### Return Value

boolean - True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

Membuat dokumen N-Up dari dua aliran PDF input ke outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputStream | Stream | aliran input pertama. |
| secondInputStream | Stream | aliran input kedua. |
| outputStream | Stream | Aliran pdf output. |

### Return Value

boolean - True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

Membuat dokumen N-Up dari beberapa file PDF input ke outputFile. Setiap halaman dari outputFile akan berisi beberapa halaman, yang merupakan kombinasi dari halaman di file input dengan nomor halaman yang sama. Halaman-halaman tersebut ditumpuk secara horizontal jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFiles | String[] | File Pdf input. |
| outputFile | String | Jalur dan nama file pdf output. |
| isSidewise | Boolean | Cara penumpukan, true untuk horizontal dan false untuk vertikal. |

### Return Value

boolean - True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

Membuat dokumen N-Up dari beberapa aliran PDF input ke outputStream. Setiap halaman dari outputStream akan berisi beberapa halaman, yang merupakan kombinasi dari halaman di aliran input dengan nomor halaman yang sama. Halaman-halaman tersebut ditumpuk secara horizontal jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStreams | Stream[] | Aliran Pdf input. |
| outputStream | Stream | Aliran pdf output. |
| isSidewise | Boolean | Cara penumpukan, true untuk horizontal dan false untuk vertikal. |

### Return Value

boolean - True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

Membuat dokumen N-Up dari file input ke outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur dan nama file pdf input. |
| outputFile | String | Jalur dan nama file pdf output. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |
| pageSize | PageSize | Ukuran halaman dari file pdf output. |

### Return Value

boolean - True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

Membuat dokumen N-Up dari firstInputFile ke outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur dan nama file pdf input. |
| outputFile | String | Jalur dan nama file pdf output. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |

### Return Value

boolean - True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

Membuat dokumen N-Up dari aliran input dan menyimpan hasilnya ke aliran output.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran pdf input. |
| outputStream | Stream | Aliran pdf output. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |

### Return Value

boolean - True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

Membuat dokumen N-Up dari aliran input pertama ke aliran output.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran pdf input. |
| outputStream | Stream | Aliran pdf output. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |
| pageSize | PageSize | Ukuran halaman dari file pdf output. |

### Return Value

True jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

Membuat dokumen N-Up dari dua file PDF input ke outputFile. Setiap halaman dari outputFile akan berisi dua halaman, satu halaman dari file input pertama dan satu lagi dari file input kedua. Dua halaman tersebut ditumpuk secara horizontal.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputFile | String | file input pertama. |
| secondInputFile | String | file input kedua. |
| outputFile | String | Jalur dan nama file pdf output. |

### Return Value

boolean - True untuk sukses, atau false.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)