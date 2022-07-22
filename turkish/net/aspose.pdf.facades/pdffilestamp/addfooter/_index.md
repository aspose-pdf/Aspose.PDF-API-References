---
title: AddFooter
second_title: Aspose.PDF for .NET API Referansı
description: Belgenin sayfalarına altbilgi ekler.
type: docs
weight: 150
url: /tr/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

Belgenin sayfalarına altbilgi ekler.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| formattedText | FormattedText | Altbilgi metnini ve metin özelliklerini içeren FormattedText nesnesi. |
| bottomMargin | Single | Sayfanın üst kısmındaki kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### Ayrıca bakınız

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

Belgenin sayfalarına altbilgi ekler.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| formattedText | FormattedText | Altbilgi metni ve metin özelliklerini içeren FormattedText nesnesi. |
| bottomMargin | Single | Sayfanın alt kısmındaki kenar boşluğu. |
| leftMargin | Single | Sayfanın sol tarafında kenar boşluğu. |
| rightMargin | Single | Sayfanın sağ tarafında kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### Ayrıca bakınız

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

Belgenin sayfalarına alt bilgi olarak resim ekler.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageFile | String | Görüntü dosyası adı ve yolu. |
| bottomMargin | Single | Sayfanın alt kısmındaki kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### Ayrıca bakınız

* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

Sayfaların altbilgisi olarak resim ekler.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageFile | String | Iamge dosya adı ve yolu. |
| bottomMargin | Single | Sayfanın alt kısmındaki kenar boşluğu. |
| leftMargin | Single | Sayfanın sol tarafında kenar boşluğu. |
| rightMargin | Single | Sayfanın sağ tarafında kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Ayrıca bakınız

* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

Sayfanın altbilgisi olarak resim ekler.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageStream | Stream | Akış, görüntü verilerini içerir. |
| bottomMargin | Single | Sayfanın alt kısmındaki kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Ayrıca bakınız

* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

Sayfanın altbilgisi olarak resim ekler.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageStream | Stream | Akış, görüntü verilerini içerir. |
| bottomMargin | Single | Sayfanın alt kısmındaki kenar boşluğu. |
| leftMargin | Single | Sayfanın sol tarafında kenar boşluğu. |
| rightMargin | Single | Sayfanın sağ tarafında kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### Ayrıca bakınız

* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
