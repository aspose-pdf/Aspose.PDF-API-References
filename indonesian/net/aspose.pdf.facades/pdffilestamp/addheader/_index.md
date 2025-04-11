---
title: PdfFileStamp.AddHeader
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileStamp. Menambahkan header ke halaman
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Menambahkan header ke halaman.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formattedText | FormattedText | Teks untuk header dan properti teks. |
| topMargin | Single | Margin di bagian atas halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### Lihat Juga

* kelas [FormattedText](../../formattedtext/)
* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Menambahkan header ke halaman-halaman file.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formattedText | FormattedText | Objek teks terformat yang berisi teks halaman dan propertinya. |
| topMargin | Single | Margin di bagian atas halaman. |
| leftMargin | Single | Margin di sisi kiri halaman. |
| rightMargin | Single | Margin di sisi kanan halaman. |

## Contoh

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### Lihat Juga

* kelas [FormattedText](../../formattedtext/)
* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Menambahkan gambar sebagai header ke halaman-halaman file.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageFile | String | Jalur ke file gambar. |
| topMargin | Single | Margin di bagian atas halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### Lihat Juga

* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Menambahkan gambar sebagai header di halaman-halaman.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageFile | String | Jalur ke file gambar. |
| topMargin | Single | Margin di bagian atas halaman. |
| leftMargin | Single | Margin di sisi kiri halaman. |
| rightMargin | Single | Margin di sisi kanan halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Lihat Juga

* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Menambahkan gambar sebagai header di halaman-halaman.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageStream | Stream | Stream dari gambar. |
| topMargin | Single | Margin di bagian atas halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Lihat Juga

* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Menambahkan gambar di bagian atas halaman.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream yang berisi data gambar. |
| topMargin | Single | Margin di bagian atas halaman. |
| leftMargin | Single | Margin di sisi kiri halaman. |
| rightMargin | Single | Margin di sisi kanan halaman. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### Lihat Juga

* kelas [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)