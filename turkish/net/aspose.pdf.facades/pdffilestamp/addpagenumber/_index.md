---
title: AddPageNumber
second_title: Aspose.PDF for .NET API Referansı
description: Dosyaya sayfa numarası ekleyin. Sayfa numarası metni sayfa numarası ile değiştirilecek olan  işareti içerebilir. Sayfa numarası sayfanın alt kısmına yatay olarak ortalanır.
type: docs
weight: 170
url: /tr/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Dosyaya sayfa numarası ekleyin. Sayfa numarası metni, sayfa numarası ile değiştirilecek olan # işareti içerebilir. Sayfa numarası, sayfanın alt kısmına yatay olarak ortalanır.

```csharp
public void AddPageNumber(string formatString)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| formatString | String | Sayfa numarası metni |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Ayrıca bakınız

* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Sayfaya sayfa numarası ekler. Sayfa numarası, sayfa numarası ile değiştirilecek # işareti içerebilir. Sayfa numarası, sayfanın altına yatay olarak ortalanır.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| formattedText | FormattedText | Sayfa numarası için format dizesi FormattedText olarak temsil edilir. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Ayrıca bakınız

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Belgenin sayfalarına sayfa numarası ekler.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| formatString | String | Sayfa numarası için biçim dizesi. |
| position | Int32 | Sayfa numarasının sayfada yer alacağı konum. 0 alt orta, 1 sağ alt, 2 sağ üst, 3 - sağ taraf, 4 - orta üst,5 - sol alt,6 - sol taraf,7 - sol üst. Aşağıdaki sabitleri kullanabilirsiniz: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Sayfanın sol kenarındaki kenar boşluğu. |
| rightMargin | Single | Sayfanın sağ kenarındaki kenar boşluğu. |
| topMargin | Single | Sayfanın üst kenarındaki kenar boşluğu. |
| bottomMargin | Single | Sayfanın alt kenarındaki kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Ayrıca bakınız

* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Sayfada belirtilen konuma sayfa numarası ekler.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| formatString | String | Biçim dizesi. Biçim dizesi, sayfa numarasıyla değiştirilecek olan # işareti içerebilir. |
| x | Single | Sayfa numarasının X koordinatı. |
| y | Single | Sayfa numarasının Y koordinatı. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Ayrıca bakınız

* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Belgenin sayfalarına sayfa numarası ekler.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| formattedText | FormattedText | Metnin sayfa numarası biçimini ve özelliklerini temsil eden FormattedText nesnesi. |
| position | Int32 | Sayfa numarasının sayfada yer alacağı konum. 0 alt orta, 1 sağ alt, 2 sağ üst, 3 - sağ taraf, 4 - orta üst,5 - sol alt,6 - sol taraf,7 - sol üst. Aşağıdaki sabitleri kullanabilirsiniz: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Sayfanın sol kenarındaki kenar boşluğu. |
| rightMargin | Single | Sayfanın sağ kenarındaki kenar boşluğu. |
| topMargin | Single | Sayfanın üst kenarındaki kenar boşluğu. |
| bottomMargin | Single | Sayfanın alt kenarındaki kenar boşluğu. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Ayrıca bakınız

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Sayfada belirtilen konuma sayfa numarası ekler.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| formattedText | FormattedText | Sayfa numarası biçimini ve metnin özelliklerini temsil eden biçimlendirilmiş metin. Biçim dizesi, sayfa numarasıyla değiştirilecek # işareti içerebilir. |
| x | Single | Sayfa numarasının X koordinatı. |
| y | Single | Sayfa numarasının Y koordinatı. |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Ayrıca bakınız

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Sayfalara sayfa numarası ekler.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| formatString | String | Sayfa numarasının biçimi. Bu metin, sayfa numarası ile değiştirilecek olan # içerebilir. |
| position | Int32 | Sayfa numarasının sayfada yer alacağı konum. 0 alt orta, 1 sağ alt, 2 sağ üst, 3 - sağ taraf, 4 - orta üst,5 - sol alt,6 - sol taraf,7 - sol üst. Aşağıdaki sabitleri kullanabilirsiniz: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Ayrıca bakınız

* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Sayfalara sayfa numarası ekler.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| formattedText | FormattedText | Sayfa numarasının biçimini ve metin özelliklerini içeren FormattedText nesnesi. Bu metin, sayfa numarası ile değiştirilecek olan # içerebilir. |
| position | Int32 | Sayfa numarasının sayfada yer alacağı konum. 0 alt orta, 1 sağ alt, 2 sağ üst, 3 - sağ taraf, 4 - orta üst,5 - sol alt,6 - sol taraf,7 - sol üst. Aşağıdaki sabitleri kullanabilirsiniz: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Ayrıca bakınız

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* ad alanı [Aspose.Pdf.Facades](../../pdffilestamp)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
