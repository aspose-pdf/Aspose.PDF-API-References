---
title: "PdfFileStamp.AddPageNumber"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileStamp. Menambahkan nomor halaman ke file. Teks nomor halaman dapat berisi tanda  yang akan diganti dengan nomor halaman. Nomor halaman ditempatkan di bagian bawah halaman dan dipusatkan secara horizontal."
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Menambahkan nomor halaman ke file. Teks nomor halaman dapat berisi tanda # yang akan diganti dengan nomor halaman. Nomor halaman ditempatkan di bagian bawah halaman secara horizontal di tengah.

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

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Menambahkan nomor halaman ke halaman. Nomor halaman dapat berisi tanda # yang akan diganti dengan nomor halaman. Nomor halaman ditempatkan di bagian bawah halaman secara horizontal di tengah.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formattedText | FormattedText | String format untuk nomor halaman direpresentasikan sebagai FormattedText. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Lihat Juga

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
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
| posisi | Int32 | Posisi di mana nomor halaman akan ditempatkan pada halaman. 0‑tengah bawah, 1‑kanan bawah, 2‑kanan atas, 3‑sisi kanan, 4‑tengah atas,5‑kiri bawah,6‑sisi kiri,7‑kiri atas. Anda dapat menggunakan konstanta berikut: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margin pada tepi kiri halaman. |
| rightMargin | Single | Margin pada tepi kanan halaman. |
| topMargin | Single | Margin pada tepi atas halaman. |
| bottomMargin | Single | Margin pada tepi bawah halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Lihat Juga

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Menambahkan nomor halaman pada posisi yang ditentukan di halaman.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formatString | String | String format. String format dapat berisi tanda # yang akan diganti dengan nomor halaman. |
| x | Single | Koordinat X nomor halaman. |
| y | Single | Koordinat Y nomor halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Lihat Juga

* class [PdfFileStamp](../)
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
| posisi | Int32 | Posisi di mana nomor halaman akan ditempatkan pada halaman. 0‑tengah bawah, 1‑kanan bawah, 2‑kanan atas, 3‑sisi kanan, 4‑tengah atas,5‑kiri bawah,6‑sisi kiri,7‑kiri atas. Anda dapat menggunakan konstanta berikut: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margin pada tepi kiri halaman. |
| rightMargin | Single | Margin pada tepi kanan halaman. |
| topMargin | Single | Margin pada tepi atas halaman. |
| bottomMargin | Single | Margin pada tepi bawah halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Lihat Juga

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Menambahkan nomor halaman pada posisi yang ditentukan di halaman.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formattedText | FormattedText | Teks terformat yang mewakili format nomor halaman dan properti teks. String format dapat berisi tanda # yang akan digantikan dengan nomor halaman. |
| x | Single | Koordinat X nomor halaman. |
| y | Single | Koordinat Y nomor halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Lihat Juga

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
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
| formatString | String | Format nomor halaman. Teks ini dapat berisi # yang akan digantikan dengan nomor halaman. |
| posisi | Int32 | Posisi di mana nomor halaman akan ditempatkan pada halaman. 0‑tengah bawah, 1‑kanan bawah, 2‑kanan atas, 3‑sisi kanan, 4‑tengah atas,5‑kiri bawah,6‑sisi kiri,7‑kiri atas. Anda dapat menggunakan konstanta berikut: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Lihat Juga

* class [PdfFileStamp](../)
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
| formattedText | FormattedText | Objek FormattedText yang berisi format nomor halaman dan properti teks. Teks ini dapat berisi # yang akan digantikan dengan nomor halaman. |
| posisi | Int32 | Posisi di mana nomor halaman akan ditempatkan pada halaman. 0‑tengah bawah, 1‑kanan bawah, 2‑kanan atas, 3‑sisi kanan, 4‑tengah atas,5‑kiri bawah,6‑sisi kiri,7‑kiri atas. Anda dapat menggunakan konstanta berikut: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Lihat Juga

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


