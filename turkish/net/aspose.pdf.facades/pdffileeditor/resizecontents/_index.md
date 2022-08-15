---
title: ResizeContents
second_title: Aspose.PDF for .NET API Referansı
description: Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse sayfanın etrafına boş kenar boşlukları eklenir.
type: docs
weight: 350
url: /tr/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_4}

Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse, sayfanın etrafına boş kenar boşlukları eklenir.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| source | String | Kaynak belge yolu. |
| destination | String | Hedef belge yolu. |
| pages | Int32[] | Sayfa dizinleri dizisi (sayfa dizini 1'den başlar). |
| parameters | ContentsResizeParameters | Sayfa yeniden boyutlandırma parametreleri. |

### Geri dönüş değeri

yeniden boyutlandırma başarılı olduysa true .

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //sol kenar boşluğu = sayfa genişliğinin %10'u
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //yeni içerik genişliği otomatik olarak genişlik - sol kenar boşluğu - sağ kenar boşluğu (%100 - %10 - %10 = %80) olarak hesaplanır
    null,
    //sağ kenar boşluğu sayfanın %10'udur 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //üst kenar boşluğu = yüksekliğin %10'u
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //yeni içerik yüksekliği otomatik olarak hesaplanır (genişliğe benzer)
    null,
    //alt marj %10
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### Ayrıca bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_7}

Belgenin sayfalarını yeniden boyutlandırır. Küçülen sayfanın çevresine boş kenar boşlukları eklendi.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| source | Document | Kaynak dosyası. |
| pages | Int32[] | Sayfa dizinlerinin listesi. |
| parameters | ContentsResizeParameters | Parametreleri yeniden boyutlandırın. |

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //sol kenar boşluğu = sayfa genişliğinin %10'u
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //yeni içerik genişliği otomatik olarak genişlik - sol kenar boşluğu - sağ kenar boşluğu (%100 - %10 - %10 = %80) olarak hesaplanır
    null,
    //sağ kenar boşluğu sayfanın %10'udur 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //üst kenar boşluğu = yüksekliğin %10'u
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //yeni içerik yüksekliği otomatik olarak hesaplanır (genişliğe benzer)
    null,
    //alt marj %10
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### Ayrıca bakınız

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_6}

Belgenin sayfalarını yeniden boyutlandırır. Küçülen sayfanın çevresine boş kenar boşlukları eklendi.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| source | Document | Kaynak dosyası. |
| parameters | ContentsResizeParameters | Parametreleri yeniden boyutlandırın. |

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //sol kenar boşluğu = sayfa genişliğinin %10'u
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //yeni içerik genişliği otomatik olarak genişlik - sol kenar boşluğu - sağ kenar boşluğu (%100 - %10 - %10 = %80) olarak hesaplanır
    null,
    //sağ kenar boşluğu sayfanın %10'udur 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //üst kenar boşluğu = yüksekliğin %10'u
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //yeni içerik yüksekliği otomatik olarak hesaplanır (genişliğe benzer)
    null,
    //alt marj %10
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### Ayrıca bakınız

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents_1}

Belgenin sayfalarının içeriğini yeniden boyutlandırır.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| source | Stream | Kaynak belge ile akış. |
| destination | Stream | Hedef belgeyle akış yapın. |
| pages | Int32[] | Sayfa dizinleri dizisi. |
| parameters | ContentsResizeParameters | Parametreleri yeniden boyutlandırın. |

### Geri dönüş değeri

Başarılı olursa true döndürür.

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //sol kenar boşluğu = sayfa genişliğinin %10'u
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //yeni içerik genişliği otomatik olarak genişlik - sol kenar boşluğu - sağ kenar boşluğu (%100 - %10 - %10 = %80) olarak hesaplanır
    null,
    //sağ kenar boşluğu sayfanın %10'udur 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //üst kenar boşluğu = yüksekliğin %10'u
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //yeni içerik yüksekliği otomatik olarak hesaplanır (genişliğe benzer)
    null,
    //alt marj %10
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### Ayrıca bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_2}

Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu varsayılan alan birimlerinde belirtilir.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| source | Stream | Kaynak belgeyi içeren akış. |
| destination | Stream | Ortaya çıkan belgenin kaydedileceği akış. |
| pages | Int32[] | Sayfa dizinleri dizisi. Null ise tüm belge sayfaları işlenir. |
| newWidth | Double | Varsayılan alan birimlerinde yeni sayfa içeriği genişliği. |
| newHeight | Double | Varsayılan alan birimlerinde sayfa içeriğinin yeni yüksekliği. |

### Geri dönüş değeri

Yeniden boyutlandırma başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
// belgenin tüm sayfalarını yeniden boyutlandır
null, 
//yeni içerik genişliği = 200
200, 
//yeni içerik yüksekliği = 300
300);
// sayfanın dinlenme alanı boş olacak
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_5}

Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu varsayılan alan birimlerinde belirtilir.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| source | String | Kaynak belgeye giden yol. |
| destination | String | Ortaya çıkan belgenin kaydedileceği yol. |
| pages | Int32[] | Sayfa dizinleri dizisi. Null ise tüm belge sayfaları işlenir. |
| newWidth | Double | Varsayılan alan birimlerinde yeni sayfa içeriği genişliği. |
| newHeight | Double | Varsayılan alan birimlerinde sayfa içeriğinin yeni yüksekliği. |

### Geri dönüş değeri

yeniden boyutlandırma başarılı olduysa true .

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
// belgenin tüm sayfalarını yeniden boyutlandır
null, 
//yeni içerik genişliği = 200
200, 
//yeni içerik yüksekliği = 300
300);
// sayfanın dinlenme alanı boş olacak
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## ResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#resizecontents_3}

Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse, sayfanın etrafına boş kenar boşlukları eklenir. Sonuç, HttpResponse nesnesinde saklanır.

```csharp
public bool ResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| source | String | Kaynak dosyanın yolu. |
| pages | Int32[] | Yeniden boyutlandırılacak sayfa dizisi. |
| parameters | ContentsResizeParameters | Parametreleri yeniden boyutlandırın. |
| response | HttpResponse | Sonucun kaydedildiği HttpResponse nesnesi. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Ayrıca bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## ResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#resizecontents}

Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse, sayfanın etrafına boş kenar boşlukları eklenir. Sonuç, HttpResponse nesnesinde saklanır.

```csharp
public bool ResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| source | Stream | Kaynak dosya akışı. |
| pages | Int32[] | Yeniden boyutlandırılacak sayfa dizisi. |
| parameters | ContentsResizeParameters | Parametreleri yeniden boyutlandırın. |
| response | HttpResponse | Sonucun kaydedildiği HttpResponse nesnesi. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Ayrıca bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
