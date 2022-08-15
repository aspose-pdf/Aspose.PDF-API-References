---
title: AddHeader
second_title: Aspose.PDF for .NET API Referansı
description: Sayfaya başlık ekler.
type: docs
weight: 160
url: /tr/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Sayfaya başlık ekler.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| formattedText | FormattedText | Metnin başlığı ve özellikleri için metin. |
| topMargin | Single | Sayfanın üst kısmındaki kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### Ayrıca bakınız

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Dosyanın sayfalarına başlık ekler.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| formattedText | FormattedText | Sayfa metnini ve özelliklerini içeren biçimlendirilmiş metin nesnesi. |
| topMargin | Single | Sayfanın üst kısmındaki kenar boşluğu. |
| leftMargin | Single | Sayfanın solundaki kenar boşluğu. |
| rightMargin | Single | Sayfanın sağındaki kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### Ayrıca bakınız

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Dosyanın sayfalarına başlık olarak resim ekler.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageFile | String | Görüntü dosyasının yolu. |
| topMargin | Single | Sayfanın üst kısmındaki kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### Ayrıca bakınız

* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Sayfalara üst bilgi olarak resim ekler.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageFile | String | Görüntü dosyasının yolu. |
| topMargin | Single | Sayfanın üst kısmındaki kenar boşluğu. |
| leftMargin | Single | Sayfanın sol tarafında kenar boşluğu. |
| rightMargin | Single | Sayfanın sağ tarafında kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Ayrıca bakınız

* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Sayfalara üst bilgi olarak resim ekler.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageStream | Stream | Görüntü akışı. |
| topMargin | Single | Sayfanın üst kısmındaki kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Ayrıca bakınız

* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Sayfanın en üstüne resim ekler.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Görüntü verilerini içeren akış. |
| topMargin | Single | Sayfanın üst kısmındaki kenar boşluğu. |
| leftMargin | Single | Sayfanın sol tarafında kenar boşluğu. |
| rightMargin | Single | Sayfanın sağ tarafında kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### Ayrıca bakınız

* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
