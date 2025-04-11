---
title: PdfFileStamp.AddHeader
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp metodu. Sayfaya başlık ekler
type: docs
weight: 120
url: /tr/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Sayfaya başlık ekler.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formattedText | FormattedText | Başlık için metin ve metnin özellikleri. |
| topMargin | Single | Sayfanın üst kısmındaki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### Ayrıca Bakınız

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Dosyanın sayfalarına başlık ekler.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formattedText | FormattedText | Sayfa metnini ve özelliklerini içeren biçimlendirilmiş metin nesnesi. |
| topMargin | Single | Sayfanın üst kısmındaki kenar boşluğu. |
| leftMargin | Single | Sayfanın solundaki kenar boşluğu. |
| rightMargin | Single | Sayfanın sağındaki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### Ayrıca Bakınız

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Dosyanın sayfalarına başlık olarak resim ekler.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageFile | String | Resim dosyasının yolu. |
| topMargin | Single | Sayfanın üst kısmındaki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### Ayrıca Bakınız

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Sayfalara başlık olarak resim ekler.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageFile | String | Resim dosyasının yolu. |
| topMargin | Single | Sayfanın üst kısmındaki kenar boşluğu. |
| leftMargin | Single | Sayfanın solundaki kenar boşluğu. |
| rightMargin | Single | Sayfanın sağındaki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Ayrıca Bakınız

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Sayfalara başlık olarak resim ekler.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageStream | Stream | Resmin akışı. |
| topMargin | Single | Sayfanın üst kısmındaki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Ayrıca Bakınız

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Sayfanın üst kısmına resim ekler.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Resim verilerini içeren akış. |
| topMargin | Single | Sayfanın üst kısmındaki kenar boşluğu. |
| leftMargin | Single | Sayfanın solundaki kenar boşluğu. |
| rightMargin | Single | Sayfanın sağındaki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### Ayrıca Bakınız

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)