---
title: TryResizeContents
second_title: Aspose.PDF for .NET API Referansı
description: Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse sayfanın etrafına boş kenar boşlukları eklenir. Sonuç HttpResponse nesnesinde saklanır.
type: docs
weight: 480
url: /tr/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents_3}

Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse, sayfanın etrafına boş kenar boşlukları eklenir. Sonuç, HttpResponse nesnesinde saklanır.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| source | String | Kaynak dosyanın yolu. |
| pages | Int32[] | Yeniden boyutlandırılacak sayfa dizisi. |
| parameters | ContentsResizeParameters | Parametreleri yeniden boyutlandırın. |
| response | HttpResponse | Sonucun kaydedildiği HttpResponse nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryResizeContents yöntemi, ResizeContents yöntemine benzer, ancak TryResizeContents yöntemi, işlem başarısız olursa bir istisna atmaz.

### Ayrıca bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse, sayfanın etrafına boş kenar boşlukları eklenir. Sonuç, HttpResponse nesnesinde saklanır.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| source | Stream | Kaynak dosya akışı. |
| pages | Int32[] | Yeniden boyutlandırılacak sayfa dizisi. |
| parameters | ContentsResizeParameters | Parametreleri yeniden boyutlandırın. |
| response | HttpResponse | Sonucun kaydedildiği HttpResponse nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryResizeContents yöntemi, ResizeContents yöntemine benzer, ancak TryResizeContents yöntemi, işlem başarısız olursa bir istisna atmaz.

### Ayrıca bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Belgenin sayfalarının içeriğini yeniden boyutlandırır.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
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

### Notlar

TryResizeContents yöntemi, ResizeContents yöntemine benzer, ancak TryResizeContents yöntemi, işlem başarısız olursa bir istisna atmaz.

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
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Ayrıca bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_2}

Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu varsayılan alan birimlerinde belirtilir.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
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

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryResizeContents yöntemi, ResizeContents yöntemine benzer, ancak TryResizeContents yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
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

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_4}

Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse, sayfanın etrafına boş kenar boşlukları eklenir.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
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

### Notlar

TryResizeContents yöntemi, ResizeContents yöntemine benzer, ancak TryResizeContents yöntemi, işlem başarısız olursa bir istisna atmaz.

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
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Ayrıca bakınız

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
