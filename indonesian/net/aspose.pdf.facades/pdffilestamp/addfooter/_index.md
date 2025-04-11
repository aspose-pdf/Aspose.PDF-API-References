---
title: PdfFileStamp.AddFooter
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileStamp. Menambahkan footer ke halaman dokumen
type: docs
weight: 110
url: /id/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

Menambahkan footer ke halaman dokumen.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formattedText | FormattedText | Objek FormattedText yang berisi teks footer dan properti teks. |
| bottomMargin | Single | Margin di bagian atas halaman. |

## Contoh

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### Lihat Juga

* kelas [FormattedText](../../formattedtext/)
* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

Menambahkan footer ke halaman dokumen.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formattedText | FormattedText | Objek FormattedText yang berisi teks footer dan properti teks. |
| bottomMargin | Single | Margin di bagian bawah halaman. |
| leftMargin | Single | Margin di sisi kiri halaman. |
| rightMargin | Single | Margin di sisi kanan halaman. |

## Contoh

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### Lihat Juga

* kelas [FormattedText](../../formattedtext/)
* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

Menambahkan gambar sebagai footer ke halaman dokumen.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageFile | String | Nama dan jalur file gambar. |
| bottomMargin | Single | Margin di bagian bawah halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### Lihat Juga

* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

Menambahkan gambar sebagai footer dari halaman.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageFile | String | Nama dan jalur file gambar. |
| bottomMargin | Single | Margin di bagian bawah halaman. |
| leftMargin | Single | Margin di sisi kiri halaman. |
| rightMargin | Single | Margin di sisi kanan halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Lihat Juga

* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

Menambahkan gambar sebagai footer dari halaman.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageStream | Stream | Stream yang berisi data gambar. |
| bottomMargin | Single | Margin di bagian bawah halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Lihat Juga

* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

Menambahkan gambar sebagai footer dari halaman.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageStream | Stream | Stream yang berisi data gambar. |
| bottomMargin | Single | Margin di bagian bawah halaman. |
| leftMargin | Single | Margin di sisi kiri halaman. |
| rightMargin | Single | Margin di sisi kanan halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### Lihat Juga

* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)