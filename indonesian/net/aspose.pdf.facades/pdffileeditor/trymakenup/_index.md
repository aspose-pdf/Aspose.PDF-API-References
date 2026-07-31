---
title: "PdfFileEditor.TryMakeNUp"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileEditor. Membuat dokumen NUp dari firstInputFile ke outputFile"
type: docs
weight: 440
url: /id/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

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

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

Membuat dokumen N-Up dari aliran input dan menyimpan hasil ke aliran output.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran pdf input. |
| outputStream | Stream | Aliran pdf output. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

Membuat dokumen N-Up dari aliran input pertama ke aliran output.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran pdf input. |
| outputStream | Stream | Aliran pdf output. |
| x | Int32 | Jumlah kolom. |
| y | Int32 | Jumlah baris. |
| pageSize | PageSize | Ukuran halaman file pdf output. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

Membuat dokumen N-Up dari dua file PDF input ke outputFile. Setiap halaman outputFile akan berisi dua halaman, satu halaman berasal dari file input pertama dan satu lagi dari file input kedua. Kedua halaman ditumpuk secara horizontal.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputFile | String | file input pertama. |
| secondInputFile | String | file input kedua. |
| outputFile | String | Jalur dan nama file pdf output. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false

## Catatan

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

Membuat dokumen N-Up dari dua aliran PDF input ke outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstInputStream | Stream | aliran input pertama. |
| secondInputStream | Stream | aliran input kedua. |
| outputStream | Stream | Aliran pdf output. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false

## Catatan

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

Membuat dokumen N-Up dari beberapa file PDF input ke outputFile. Setiap halaman outputFile akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman dalam file input pada nomor halaman yang sama. Halaman‑multiple ditumpuk secara horizontal jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFiles | String[] | File Pdf input. |
| outputFile | String | Jalur dan nama file pdf output. |
| isSidewise | Boolean | Cara ditumpuk, true untuk secara horizontal dan false untuk secara vertikal. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

Membuat dokumen N-Up dari beberapa aliran PDF input ke outputStream. Setiap halaman outputStream akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman dalam aliran input pada nomor halaman yang sama. Halaman‑multiple ditumpuk secara horizontal jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStreams | Stream[] | Aliran Pdf input. |
| outputStream | Stream | Aliran pdf output. |
| isSidewise | Boolean | Cara ditumpuk, true untuk secara horizontal dan false untuk secara vertikal. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Lihat Juga

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
| pageSize | PageSize | Ukuran halaman file pdf output. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryMakeNUp mirip dengan metode MakeNUp, kecuali metode TryMakeNUp tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


