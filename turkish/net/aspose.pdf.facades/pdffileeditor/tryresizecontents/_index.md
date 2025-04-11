---
title: PdfFileEditor.TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Belgenin sayfalarının içeriğini yeniden boyutlandırır
type: docs
weight: 450
url: /tr/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültüldüğünde sayfanın etrafına boş kenar boşlukları eklenir. Sonuç HttpResponse nesnesine kaydedilir.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | String | Kaynak dosyanın yolu. |
| pages | Int32[] | Yeniden boyutlandırılacak sayfaların dizisi. |
| parameters | ContentsResizeParameters | Yeniden boyutlandırma parametreleri. |
| response | HttpResponse | Sonucun kaydedildiği HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryResizeContents metodu, ResizeContents metoduna benzer, ancak TryResizeContents metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültüldüğünde sayfanın etrafına boş kenar boşlukları eklenir. Sonuç HttpResponse nesnesine kaydedilir.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | Stream | Kaynak dosyanın akışı. |
| pages | Int32[] | Yeniden boyutlandırılacak sayfaların dizisi. |
| parameters | ContentsResizeParameters | Yeniden boyutlandırma parametreleri. |
| response | HttpResponse | Sonucun kaydedildiği HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryResizeContents metodu, ResizeContents metoduna benzer, ancak TryResizeContents metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Belgenin sayfalarının içeriğini yeniden boyutlandırır.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | Stream | Kaynak belge ile akış. |
| destination | Stream | Hedef belge ile akış. |
| pages | Int32[] | Sayfa indekslerinin dizisi. |
| parameters | ContentsResizeParameters | Yeniden boyutlandırma parametreleri. |

### Dönüş Değeri

Başarı durumunda true döner.

## Açıklamalar

TryResizeContents metodu, ResizeContents metoduna benzer, ancak TryResizeContents metodu işlem başarısız olursa bir istisna fırlatmaz.

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
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Ayrıca Bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. İçeriğin yeni boyutu varsayılan alan birimlerinde belirtilir.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | Stream | Kaynak belgeyi içeren akış. |
| destination | Stream | Sonuç belgesinin kaydedileceği akış. |
| pages | Int32[] | Sayfa indekslerinin dizisi. Null ise tüm belge sayfaları işlenecektir. |
| newWidth | Double | Sayfa içeriğinin varsayılan alan birimlerinde yeni genişliği. |
| newHeight | Double | Sayfa içeriğinin varsayılan alan birimlerinde yeni yüksekliği. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryResizeContents metodu, ResizeContents metoduna benzer, ancak TryResizeContents metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
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

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültüldüğünde sayfanın etrafına boş kenar boşlukları eklenir.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | String | Kaynak belge yolu. |
| destination | String | Hedef belge yolu. |
| pages | Int32[] | Sayfa indekslerinin dizisi (sayfa indeksi 1'den başlar). |
| parameters | ContentsResizeParameters | Sayfa yeniden boyutlandırma parametreleri. |

### Dönüş Değeri

Yeniden boyutlandırma başarılıysa true.

## Açıklamalar

TryResizeContents metodu, ResizeContents metoduna benzer, ancak TryResizeContents metodu işlem başarısız olursa bir istisna fırlatmaz.

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
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Ayrıca Bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)