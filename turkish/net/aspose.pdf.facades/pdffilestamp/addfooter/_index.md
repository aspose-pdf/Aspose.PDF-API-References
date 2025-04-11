---
title: PdfFileStamp.AddFooter
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp metodu. Belgenin sayfalarına alt bilgi ekler
type: docs
weight: 110
url: /tr/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

Belgenin sayfalarına alt bilgi ekler.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formattedText | FormattedText | Alt bilgi metnini ve metin özelliklerini içeren FormattedText nesnesi. |
| bottomMargin | Single | Sayfanın üstündeki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### Ayrıca Bakınız

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

Belgenin sayfalarına alt bilgi ekler.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formattedText | FormattedText | Alt bilgi metnini ve metin özelliklerini içeren FormattedText nesnesi. |
| bottomMargin | Single | Sayfanın altındaki kenar boşluğu. |
| leftMargin | Single | Sayfanın solundaki kenar boşluğu. |
| rightMargin | Single | Sayfanın sağındaki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### Ayrıca Bakınız

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

Sayfalara alt bilgi olarak resim ekler.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageFile | String | Resim dosyası adı ve yolu. |
| bottomMargin | Single | Sayfanın altındaki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### Ayrıca Bakınız

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

Sayfaların alt bilgisine resim ekler.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageFile | String | Resim dosyası adı ve yolu. |
| bottomMargin | Single | Sayfanın altındaki kenar boşluğu. |
| leftMargin | Single | Sayfanın solundaki kenar boşluğu. |
| rightMargin | Single | Sayfanın sağındaki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Ayrıca Bakınız

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

Sayfanın alt bilgisine resim ekler.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageStream | Stream | Resim verilerini içeren akış. |
| bottomMargin | Single | Sayfanın altındaki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Ayrıca Bakınız

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

Sayfanın alt bilgisine resim ekler.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageStream | Stream | Resim verilerini içeren akış. |
| bottomMargin | Single | Sayfanın altındaki kenar boşluğu. |
| leftMargin | Single | Sayfanın solundaki kenar boşluğu. |
| rightMargin | Single | Sayfanın sağındaki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### Ayrıca Bakınız

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)