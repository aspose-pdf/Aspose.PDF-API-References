---
title: PdfFileEditor.AddMarginsPct
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları, başlangıç sayfa boyutunun yüzdesi olarak belirtilir.
type: docs
weight: 230
url: /tr/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları, başlangıç sayfa boyutunun yüzdesi olarak belirtilir.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | Stream | Kaynak belgeyi içeren akış. |
| destination | Stream | Sonuç belgesinin kaydedileceği akış. |
| pages | Int32[] | Sayfa indekslerinin dizisi. Null ise tüm belge sayfaları işlenecektir. |
| leftMargin | Double | Başlangıç sayfa boyutunun yüzdesi olarak sol kenar boşluğu. |
| rightMargin | Double | Başlangıç sayfa boyutunun yüzdesi olarak sağ kenar boşluğu. |
| topMargin | Double | Başlangıç sayfa boyutunun yüzdesi olarak üst kenar boşluğu. |
| bottomMargin | Double | Başlangıç sayfa boyutunun yüzdesi olarak alt kenar boşluğu. |

### Dönüş Değeri

İşlem başarılı bir şekilde gerçekleştirildiyse true.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
    dest.Close();
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları, başlangıç sayfa boyutunun yüzdesi olarak belirtilir.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | String | Kaynak belgeye giden yol. |
| destination | String | Sonuç belgesinin kaydedileceği yol. |
| pages | Int32[] | Sayfa indekslerinin dizisi. Null ise tüm belge sayfaları işlenecektir. |
| leftMargin | Double | Başlangıç sayfa boyutunun yüzdesi olarak sol kenar boşluğu. |
| rightMargin | Double | Başlangıç sayfa boyutunun yüzdesi olarak sağ kenar boşluğu. |
| topMargin | Double | Başlangıç sayfa boyutunun yüzdesi olarak üst kenar boşluğu. |
| bottomMargin | Double | Başlangıç sayfa boyutunun yüzdesi olarak alt kenar boşluğu. |

### Dönüş Değeri

Yeniden boyutlandırma başarılıysa true

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)