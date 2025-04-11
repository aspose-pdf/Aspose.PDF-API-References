---
title: PdfFileStamp.AddPageNumber
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileStamp. Tambahkan nomor halaman ke file. Teks nomor halaman dapat mengandung tanda # yang akan diganti dengan nomor halaman. Nomor halaman ditempatkan di bagian bawah halaman yang terpusat secara horizontal
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Tambahkan nomor halaman ke file. Teks nomor halaman dapat mengandung tanda # yang akan diganti dengan nomor halaman. Nomor halaman ditempatkan di bagian bawah halaman yang terpusat secara horizontal.

```csharp
public void AddPageNumber(string formatString)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formatString | String | Teks nomor halaman |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Lihat Juga

* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Menambahkan nomor halaman ke halaman. Nomor halaman dapat mengandung tanda # yang akan diganti dengan nomor halaman. Nomor halaman ditempatkan di bagian bawah halaman yang terpusat secara horizontal.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formattedText | FormattedText | String format untuk nomor halaman yang direpresentasikan sebagai FormattedText. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Lihat Juga

* kelas [FormattedText](../../formattedtext/)
* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Menambahkan nomor halaman ke halaman-halaman dokumen.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formatString | String | String format untuk nomor halaman. |
| position | Int32 | Posisi di mana nomor halaman akan ditempatkan di halaman. 0-tengah bawah, 1-kanan bawah, 2-kanan atas, 3 - sisi kanan, 4 - tengah atas, 5 - kiri bawah, 6 - sisi kiri, 7 - kiri atas. Anda dapat menggunakan konstanta berikut: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margin di tepi kiri halaman. |
| rightMargin | Single | Margin di tepi kanan halaman. |
| topMargin | Single | Margin di tepi atas halaman. |
| bottomMargin | Single | Margin di tepi bawah halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Lihat Juga

* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Menambahkan nomor halaman di posisi yang ditentukan di halaman.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formatString | String | String format. String format dapat mengandung tanda # yang akan diganti dengan nomor halaman. |
| x | Single | Koordinat X dari nomor halaman. |
| y | Single | Koordinat Y dari nomor halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Lihat Juga

* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Menambahkan nomor halaman ke halaman-halaman dokumen.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formattedText | FormattedText | Objek FormattedText yang merepresentasikan format nomor halaman dan properti teks. |
| position | Int32 | Posisi di mana nomor halaman akan ditempatkan di halaman. 0-tengah bawah, 1-kanan bawah, 2-kanan atas, 3 - sisi kanan, 4 - tengah atas, 5 - kiri bawah, 6 - sisi kiri, 7 - kiri atas. Anda dapat menggunakan konstanta berikut: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margin di tepi kiri halaman. |
| rightMargin | Single | Margin di tepi kanan halaman. |
| topMargin | Single | Margin di tepi atas halaman. |
| bottomMargin | Single | Margin di tepi bawah halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Lihat Juga

* kelas [FormattedText](../../formattedtext/)
* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Menambahkan nomor halaman di posisi yang ditentukan di halaman.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formattedText | FormattedText | Teks terformat yang merepresentasikan format nomor halaman dan properti teks. String format dapat mengandung tanda # yang akan diganti dengan nomor halaman. |
| x | Single | Koordinat X dari nomor halaman. |
| y | Single | Koordinat Y dari nomor halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Lihat Juga

* kelas [FormattedText](../../formattedtext/)
* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Menambahkan nomor halaman ke halaman-halaman.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formatString | String | Format nomor halaman. Teks ini dapat mengandung # yang akan diganti dengan nomor halaman. |
| position | Int32 | Posisi di mana nomor halaman akan ditempatkan di halaman. 0-tengah bawah, 1-kanan bawah, 2-kanan atas, 3 - sisi kanan, 4 - tengah atas, 5 - kiri bawah, 6 - sisi kiri, 7 - kiri atas. Anda dapat menggunakan konstanta berikut: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Lihat Juga

* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Menambahkan nomor halaman ke halaman-halaman.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formattedText | FormattedText | Objek FormattedText yang berisi format nomor halaman dan properti teks. Teks ini dapat mengandung # yang akan diganti dengan nomor halaman. |
| position | Int32 | Posisi di mana nomor halaman akan ditempatkan di halaman. 0-tengah bawah, 1-kanan bawah, 2-kanan atas, 3 - sisi kanan, 4 - tengah atas, 5 - kiri bawah, 6 - sisi kiri, 7 - kiri atas. Anda dapat menggunakan konstanta berikut: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Lihat Juga

* kelas [FormattedText](../../formattedtext/)
* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)