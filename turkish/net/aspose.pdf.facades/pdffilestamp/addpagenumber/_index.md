---
title: PdfFileStamp.AddPageNumber
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp metodu. Dosyaya sayfa numarası ekleyin. Sayfa numarası metni, sayfa numarası ile değiştirilecek # işareti içerebilir. Sayfa numarası, sayfanın alt kısmında yatay olarak ortalanmış olarak yer alır.
type: docs
weight: 130
url: /tr/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## EkleSayfaNumarası(string) {#addpagenumber_4}

Dosyaya sayfa numarası ekler. Sayfa numarası metni, sayfa numarası ile değiştirilecek # işareti içerebilir. Sayfa numarası, sayfanın alt kısmında yatay olarak ortalanmış olarak yer alır.

```csharp
public void AddPageNumber(string formatString)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formatString | String | Sayfa numarası metni |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Ayrıca Bakınız

* sınıf [PdfFileStamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## EkleSayfaNumarası(FormattedText) {#addpagenumber}

Sayfaya sayfa numarası ekler. Sayfa numarası # işareti içerebilir ve bu sayfa numarası ile değiştirilecektir. Sayfa numarası, sayfanın alt kısmında yatay olarak ortalanmış olarak yer alır.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formattedText | FormattedText | Sayfa numarası için biçim dizesi olarak temsil edilen FormattedText. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Ayrıca Bakınız

* sınıf [FormattedText](../../formattedtext/)
* sınıf [PdfFileStamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## EkleSayfaNumarası(string, int, float, float, float, float) {#addpagenumber_6}

Belgenin sayfalarına sayfa numarası ekler.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formatString | String | Sayfa numarası için biçim dizesi. |
| position | Int32 | Sayfa numarasının sayfada yer alacağı konum. 0-alt orta, 1-alt sağ, 2-üst sağ, 3 - yanlar sağ, 4 - üst orta, 5 - alt sol, 6 - yanlar sol, 7 - üst sol. Aşağıdaki sabitleri kullanabilirsiniz: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Sayfanın sol kenarındaki kenar boşluğu. |
| rightMargin | Single | Sayfanın sağ kenarındaki kenar boşluğu. |
| topMargin | Single | Sayfanın üst kenarındaki kenar boşluğu. |
| bottomMargin | Single | Sayfanın alt kenarındaki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Ayrıca Bakınız

* sınıf [PdfFileStamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## EkleSayfaNumarası(string, float, float) {#addpagenumber_7}

Belirtilen konumda sayfa numarası ekler.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formatString | String | Biçim dizesi. Biçim dizesi, sayfa numarası ile değiştirilecek # işareti içerebilir. |
| x | Single | Sayfa numarasının X koordinatı. |
| y | Single | Sayfa numarasının Y koordinatı. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Ayrıca Bakınız

* sınıf [PdfFileStamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## EkleSayfaNumarası(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Belgenin sayfalarına sayfa numarası ekler.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formattedText | FormattedText | Sayfa numarası biçimini ve metin özelliklerini temsil eden FormattedText nesnesi. |
| position | Int32 | Sayfa numarasının sayfada yer alacağı konum. 0-alt orta, 1-alt sağ, 2-üst sağ, 3 - yanlar sağ, 4 - üst orta, 5 - alt sol, 6 - yanlar sol, 7 - üst sol. Aşağıdaki sabitleri kullanabilirsiniz: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Sayfanın sol kenarındaki kenar boşluğu. |
| rightMargin | Single | Sayfanın sağ kenarındaki kenar boşluğu. |
| topMargin | Single | Sayfanın üst kenarındaki kenar boşluğu. |
| bottomMargin | Single | Sayfanın alt kenarındaki kenar boşluğu. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Ayrıca Bakınız

* sınıf [FormattedText](../../formattedtext/)
* sınıf [PdfFileStamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## EkleSayfaNumarası(FormattedText, float, float) {#addpagenumber_3}

Belirtilen konumda sayfa numarası ekler.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formattedText | FormattedText | Sayfa numarası biçimini ve metin özelliklerini temsil eden biçimlendirilmiş metin. Biçim dizesi, sayfa numarası ile değiştirilecek # işareti içerebilir. |
| x | Single | Sayfa numarasının X koordinatı. |
| y | Single | Sayfa numarasının Y koordinatı. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Ayrıca Bakınız

* sınıf [FormattedText](../../formattedtext/)
* sınıf [PdfFileStamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## EkleSayfaNumarası(string, int) {#addpagenumber_5}

Sayfalara sayfa numarası ekler.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formatString | String | Sayfa numarasının biçimi. Bu metin, sayfa numarası ile değiştirilecek # işareti içerebilir. |
| position | Int32 | Sayfa numarasının sayfada yer alacağı konum. 0-alt orta, 1-alt sağ, 2-üst sağ, 3 - yanlar sağ, 4 - üst orta, 5 - alt sol, 6 - yanlar sol, 7 - üst sol. Aşağıdaki sabitleri kullanabilirsiniz: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Ayrıca Bakınız

* sınıf [PdfFileStamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## EkleSayfaNumarası(FormattedText, int) {#addpagenumber_1}

Sayfalara sayfa numarası ekler.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formattedText | FormattedText | Sayfa numarasının biçimini ve metin özelliklerini içeren FormattedText nesnesi. Bu metin, sayfa numarası ile değiştirilecek # işareti içerebilir. |
| position | Int32 | Sayfa numarasının sayfada yer alacağı konum. 0-alt orta, 1-alt sağ, 2-üst sağ, 3 - yanlar sağ, 4 - üst orta, 5 - alt sol, 6 - yanlar sol, 7 - üst sol. Aşağıdaki sabitleri kullanabilirsiniz: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Ayrıca Bakınız

* sınıf [FormattedText](../../formattedtext/)
* sınıf [PdfFileStamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)