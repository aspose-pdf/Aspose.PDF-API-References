---
title: PdfFileEditor.AddMargins
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları varsayılan alan birimlerinde belirtilir.
type: docs
weight: 220
url: /tr/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları varsayılan alan birimlerinde belirtilir.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | Stream | Kaynak belgeyi içeren akış. |
| destination | Stream | Sonuç belgesinin kaydedileceği akış. |
| pages | Int32[] | Sayfa indekslerinin dizisi. Null ise tüm belge sayfaları işlenecektir. |
| leftMargin | Double | Sol kenar boşluğu. |
| rightMargin | Double | Sağ kenar boşluğu. |
| topMargin | Double | Üst kenar boşluğu. |
| bottomMargin | Double | Alt kenar boşluğu. |

### Dönüş Değeri

İşlem başarılıysa true döner.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
    dest.Close();
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları varsayılan alan birimlerinde belirtilir.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | String | Kaynak belgeye giden yol. |
| destination | String | Sonuç belgesinin kaydedileceği yol. |
| pages | Int32[] | Sayfa indekslerinin dizisi. Null ise tüm belge sayfaları işlenecektir. |
| leftMargin | Double | Sol kenar boşluğu. |
| rightMargin | Double | Sağ kenar boşluğu. |
| topMargin | Double | Üst kenar boşluğu. |
| bottomMargin | Double | Alt kenar boşluğu. |

### Dönüş Değeri

Yeniden boyutlandırma başarılıysa true döner.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)