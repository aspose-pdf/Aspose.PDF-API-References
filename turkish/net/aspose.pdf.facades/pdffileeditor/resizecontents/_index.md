---
title: PdfFileEditor.ResizeContents
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Belgenin sayfalarının içeriklerini yeniden boyutlandırır
type: docs
weight: 320
url: /tr/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

Belgenin sayfalarının içeriklerini yeniden boyutlandırır.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | Stream | Kaynak belge ile stream. |
| destination | Stream | Hedef belge ile stream. |
| pages | Int32[] | Sayfa indeksleri dizisi. |
| parameters | ContentsResizeParameters | Yeniden boyutlandırma parametreleri. |

### Dönüş Değeri

Başarılıysa true döner.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### Ayrıca Bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

Belge sayfalarının içeriklerini yeniden boyutlandırır. Sayfa içeriğini küçültür ve kenar boşlukları ekler. İçeriklerin yeni boyutu varsayılan alan birimlerinde belirtilir.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | Stream | Kaynak belgeyi içeren stream. |
| destination | Stream | Sonuç belgesinin kaydedileceği stream. |
| pages | Int32[] | Sayfa indeksleri dizisi. Null ise tüm belge sayfaları işlenecektir. |
| newWidth | Double | Sayfa içeriklerinin varsayılan alan birimlerinde yeni genişliği. |
| newHeight | Double | Sayfa içeriklerinin varsayılan alan birimlerinde yeni yüksekliği. |

### Dönüş Değeri

Yeniden boyutlandırma başarılıysa true döner.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

Belge sayfalarının içeriklerini yeniden boyutlandırır. Sayfa içeriğini küçültür ve kenar boşlukları ekler. İçeriklerin yeni boyutu varsayılan alan birimlerinde belirtilir.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | String | Kaynak belgeye giden yol. |
| destination | String | Sonuç belgesinin kaydedileceği yol. |
| pages | Int32[] | Sayfa indeksleri dizisi. Null ise tüm belge sayfaları işlenecektir. |
| newWidth | Double | Sayfa içeriklerinin varsayılan alan birimlerinde yeni genişliği. |
| newHeight | Double | Sayfa içeriklerinin varsayılan alan birimlerinde yeni yüksekliği. |

### Dönüş Değeri

Yeniden boyutlandırma başarılıysa true döner.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

Belgedeki sayfaların içeriklerini yeniden boyutlandırır. Sayfa küçültüldüğünde etrafına boş kenar boşlukları eklenir.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | String | Kaynak belge yolu. |
| destination | String | Hedef belge yolu. |
| pages | Int32[] | Sayfa indeksleri dizisi (sayfa indeksi 1'den başlar). |
| parameters | ContentsResizeParameters | Sayfa yeniden boyutlandırma parametreleri. |

### Dönüş Değeri

Yeniden boyutlandırma başarılıysa true döner.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### Ayrıca Bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

Belgenin sayfalarını yeniden boyutlandırır. Küçültülen sayfanın etrafına boş kenar boşlukları eklenir.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | Document | Kaynak belge. |
| pages | Int32[] | Sayfa indeksleri listesi. |
| parameters | ContentsResizeParameters | Yeniden boyutlandırma parametreleri. |

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### Ayrıca Bakınız

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

Belgenin sayfalarını yeniden boyutlandırır. Küçültülen sayfanın etrafına boş kenar boşlukları eklenir.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | Document | Kaynak belge. |
| parameters | ContentsResizeParameters | Yeniden boyutlandırma parametreleri. |

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### Ayrıca Bakınız

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)