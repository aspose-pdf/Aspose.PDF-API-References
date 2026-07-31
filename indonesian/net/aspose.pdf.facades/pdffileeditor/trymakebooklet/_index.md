---
title: "PdfFileEditor.TryMakeBooklet"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileEditor. Membuat booklet dari file input ke file output"
type: docs
weight: 430
url: /id/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

Membuat buku kecil dari file input ke file output.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur dan nama file pdf input. |
| outputFile | String | Jalur dan nama file pdf output. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

Membuat buku kecil dari InputStream ke outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran pdf input. |
| outputStream | Stream | Aliran pdf output. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

Membuat buku kecil dari inputFile ke outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur dan nama file pdf input. |
| outputFile | String | Jalur dan nama file pdf output. |
| pageSize | PageSize | Ukuran halaman file pdf output. |

### Nilai Kembalian

True jika operasi berhasil.

## Catatan

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

Membuat buku kecil dari aliran input dan menyimpan hasil ke aliran output.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran PDF masukan. |
| outputStream | Stream | Aliran pdf output. |
| pageSize | PageSize | Ukuran halaman file pdf output. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

Membuat buku kecil khusus dari firstInputFile ke outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File masukan. |
| outputFile | String | Jalur dan nama file pdf output. |
| leftPages | Int32[] | Halaman kiri dari buklet. |
| rightPages | Int32[] | Halaman kanan dari buklet. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

Membuat buku kecil khusus dari firstInputStream ke outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran masukan. |
| outputStream | Stream | Aliran pdf output. |
| leftPages | Int32[] | Halaman kiri. |
| rightPages | Int32[] | Halaman kanan. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

Membuat buku kecil khusus dari firstInputFile ke outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File masukan. |
| outputFile | String | Jalur dan nama file pdf output. |
| pageSize | PageSize | Ukuran halaman file pdf output. |
| leftPages | Int32[] | Halaman kiri. |
| rightPages | Int32[] | Halaman kanan. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

Membuat buku kecil dari firstInputStream ke outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran masukan. |
| outputStream | Stream | Aliran pdf output. |
| pageSize | PageSize | Ukuran halaman file pdf output. |
| leftPages | Int32[] | Halaman kiri. |
| rightPages | Int32[] | Halaman kanan. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryMakeBooklet mirip dengan metode MakeBooklet, kecuali metode TryMakeBooklet tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


