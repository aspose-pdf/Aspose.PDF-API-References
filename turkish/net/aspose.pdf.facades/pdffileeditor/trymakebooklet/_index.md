---
title: TryMakeBooklet
second_title: Aspose.PDF for .NET API Referansı
description: Kaynak dosyadan kitapçık yapar ve sonucu HttpResponse nesnelerine kaydeder.
type: docs
weight: 460
url: /tr/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, PageSize, int[], int[], HttpResponse) {#trymakebooklet_6}

Kaynak dosyadan kitapçık yapar ve sonucu HttpResponse nesnelerine kaydeder.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak dosya yolu. |
| pageSize | PageSize | İstenilen sayfa boyutu. |
| leftPages | Int32[] | Sola yerleştirilecek sayfa numaraları dizisi. |
| rightPages | Int32[] | Sağa yerleştirilecek sayfa numaraları dizisi. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeBooklet yöntemi, MakeBooklet yöntemine benzer, ancak TryMakeBooklet yöntemi, işlem başarısız olursa bir istisna atmaz.

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

PDF dosyasından kitapçık yapın ve onu HttpResponse. içine depolayın

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş belgesi akışı. |
| pageSize | PageSize | İstenilen sayfa boyutu. |
| leftPages | Int32[] | Sol tarafa yerleştirilecek sayfa numaraları dizisi. |
| rightPages | Int32[] | Sağda yer alacak sayfa numaraları dizisi. |
| response | HttpResponse | HttpResponse nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeBooklet yöntemi, MakeBooklet yöntemine benzer, ancak TryMakeBooklet yöntemi, işlem başarısız olursa bir istisna atmaz.

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Kaynak dosyadan kitapçık yapar ve sonucu HttpResponse nesnelerine kaydeder.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak dosya yolu. |
| pageSize | PageSize | Çıktı dosyasında istenen sayfa boyutu. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Geri dönüş değeri

İşlem başarılı olursa doğrudur.

### Notlar

TryMakeBooklet yöntemi, MakeBooklet yöntemine benzer, ancak TryMakeBooklet yöntemi, işlem başarısız olursa bir istisna atmaz.

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Kaynak dosyadan kitapçık yapar ve sonucu HttpResponse. içinde saklar

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş belgesi akışı. |
| pageSize | PageSize | Çıktı dosyasında istenen sayfa boyutu. |
| response | HttpResponse | Sonucun kaydedileceği nesneyi yanıtlayın. |

### Geri dönüş değeri

kitapçık başarıyla oluşturulduysa true .

### Notlar

TryMakeBooklet yöntemi, MakeBooklet yöntemine benzer, ancak TryMakeBooklet yöntemi, işlem başarısız olursa bir istisna atmaz.

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Girdi dosyasından çıktı dosyasına kitapçık yapar.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | pdf dosya yolunu ve adını girin. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeBooklet yöntemi, MakeBooklet yöntemine benzer, ancak TryMakeBooklet yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet_2}

InputStream'den outputStream. 'ye kitapçık yapar

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | pdf akışını girin. |
| outputStream | Stream | çıktı pdf akışı. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeBooklet yöntemi, MakeBooklet yöntemine benzer, ancak TryMakeBooklet yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_9}

inputFile'dan outputFile. 'ye kitapçık yapar

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | pdf dosya yolunu ve adını girin. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |
| pageSize | PageSize | Çıktı pdf dosyasının sayfa boyutu. |

### Geri dönüş değeri

İşlem başarılı olursa doğrudur.

### Notlar

TryMakeBooklet yöntemi, MakeBooklet yöntemine benzer, ancak TryMakeBooklet yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_3}

Giriş akışından kitapçık yapar ve sonucu çıkış akışına kaydeder.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | PDF akışını girin. |
| outputStream | Stream | çıktı pdf akışı. |
| pageSize | PageSize | Çıktı pdf dosyasının sayfa boyutu. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeBooklet yöntemi, MakeBooklet yöntemine benzer, ancak TryMakeBooklet yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_11}

FirstInputFile'dan outputFile'a özelleştirilmiş kitapçık yapar.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Giriş dosyası. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |
| leftPages | Int32[] | Kitapçığın sol sayfaları. |
| rightPages | Int32[] | Kitapçığın sağ sayfaları. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeBooklet yöntemi, MakeBooklet yöntemine benzer, ancak TryMakeBooklet yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_5}

FirstInputStream'den outputStream'e özelleştirilmiş kitapçık oluşturur.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| outputStream | Stream | çıkış pdf akışı. |
| leftPages | Int32[] | Sol sayfalar. |
| rightPages | Int32[] | Doğru sayfalar. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeBooklet yöntemi, MakeBooklet yöntemine benzer, ancak TryMakeBooklet yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_10}

FirstInputFile'dan outputFile'a özelleştirilmiş kitapçık yapar.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Giriş dosyası. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |
| pageSize | PageSize | Çıktı pdf dosyasının sayfa boyutu. |
| leftPages | Int32[] | Sol sayfalar. |
| rightPages | Int32[] | Doğru sayfalar. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeBooklet yöntemi, MakeBooklet yöntemine benzer, ancak TryMakeBooklet yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_4}

FirstInputStream'den outputStream'e kitapçık oluşturur.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| outputStream | Stream | çıkış pdf akışı. |
| pageSize | PageSize | Çıktı pdf dosyasının sayfa boyutu. |
| leftPages | Int32[] | Sol sayfalar. |
| rightPages | Int32[] | Doğru sayfalar. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeBooklet yöntemi, MakeBooklet yöntemine benzer, ancak TryMakeBooklet yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
