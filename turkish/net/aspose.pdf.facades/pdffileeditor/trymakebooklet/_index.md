---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Giriş dosyasından çıkış dosyasına broşür oluşturur
type: docs
weight: 430
url: /tr/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

Kaynak dosyadan broşür oluşturur ve sonucu HttpResponse nesnelerine kaydeder.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak dosya yolu. |
| pageSize | PageSize | İstenen sayfa boyutu. |
| leftPages | Int32[] | Sol tarafa yerleştirilecek sayfa numaralarının dizisi. |
| rightPages | Int32[] | Sağ tarafa yerleştirilecek sayfa numaralarının dizisi. |
| response | HttpResponse | Sonucun kaydedileceği HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeBooklet metodu, MakeBooklet metoduna benzer, ancak TryMakeBooklet metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

PDF dosyasından broşür oluşturur ve bunu HttpResponse'a kaydeder.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş belge akışı. |
| pageSize | PageSize | İstenen sayfa boyutu. |
| leftPages | Int32[] | Sol tarafa yerleştirilecek sayfa numaralarının dizisi. |
| rightPages | Int32[] | Sağ tarafa yerleştirilecek sayfa numaralarının dizisi. |
| response | HttpResponse | HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeBooklet metodu, MakeBooklet metoduna benzer, ancak TryMakeBooklet metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Kaynak dosyadan broşür oluşturur ve sonucu HttpResponse nesnelerine kaydeder.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak dosya yolu. |
| pageSize | PageSize | Çıkış dosyasındaki istenen sayfa boyutu. |
| response | HttpResponse | Sonucun kaydedileceği HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarılıysa true.

## Açıklamalar

TryMakeBooklet metodu, MakeBooklet metoduna benzer, ancak TryMakeBooklet metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Kaynak dosyadan broşür oluşturur ve sonucu HttpResponse'a kaydeder.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş belge akışı. |
| pageSize | PageSize | Çıkış dosyasındaki istenen sayfa boyutu. |
| response | HttpResponse | Sonucun kaydedileceği nesne. |

### Dönüş Değeri

Broşür başarıyla oluşturulduysa true.

## Açıklamalar

TryMakeBooklet metodu, MakeBooklet metoduna benzer, ancak TryMakeBooklet metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Giriş dosyasından çıkış dosyasına broşür oluşturur.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Giriş pdf dosya yolu ve adı. |
| outputFile | String | Çıkış pdf dosya yolu ve adı. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeBooklet metodu, MakeBooklet metoduna benzer, ancak TryMakeBooklet metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

InputStream'den outputStream'e broşür oluşturur.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş pdf akışı. |
| outputStream | Stream | çıkış pdf akışı. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeBooklet metodu, MakeBooklet metoduna benzer, ancak TryMakeBooklet metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

inputFile'dan outputFile'a broşür oluşturur.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Giriş pdf dosya yolu ve adı. |
| outputFile | String | Çıkış pdf dosya yolu ve adı. |
| pageSize | PageSize | Çıkış pdf dosyasının sayfa boyutu. |

### Dönüş Değeri

İşlem başarılıysa true.

## Açıklamalar

TryMakeBooklet metodu, MakeBooklet metoduna benzer, ancak TryMakeBooklet metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

Giriş akışından broşür oluşturur ve sonucu çıkış akışına kaydeder.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş PDF akışı. |
| outputStream | Stream | çıkış pdf akışı. |
| pageSize | PageSize | Çıkış pdf dosyasının sayfa boyutu. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeBooklet metodu, MakeBooklet metoduna benzer, ancak TryMakeBooklet metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

firstInputFile'dan outputFile'a özelleştirilmiş broşür oluşturur.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Giriş dosyası. |
| outputFile | String | Çıkış pdf dosya yolu ve adı. |
| leftPages | Int32[] | Broşürün sol sayfaları. |
| rightPages | Int32[] | Broşürün sağ sayfaları. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeBooklet metodu, MakeBooklet metoduna benzer, ancak TryMakeBooklet metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

firstInputStream'den outputStream'e özelleştirilmiş broşür oluşturur.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| outputStream | Stream | çıkış pdf akışı. |
| leftPages | Int32[] | Sol sayfalar. |
| rightPages | Int32[] | Sağ sayfalar. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeBooklet metodu, MakeBooklet metoduna benzer, ancak TryMakeBooklet metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

firstInputFile'dan outputFile'a özelleştirilmiş broşür oluşturur.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Giriş dosyası. |
| outputFile | String | Çıkış pdf dosya yolu ve adı. |
| pageSize | PageSize | Çıkış pdf dosyasının sayfa boyutu. |
| leftPages | Int32[] | Sol sayfalar. |
| rightPages | Int32[] | Sağ sayfalar. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeBooklet metodu, MakeBooklet metoduna benzer, ancak TryMakeBooklet metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

firstInputStream'den outputStream'e broşür oluşturur.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| outputStream | Stream | çıkış pdf akışı. |
| pageSize | PageSize | Çıkış pdf dosyasının sayfa boyutu. |
| leftPages | Int32[] | Sol sayfalar. |
| rightPages | Int32[] | Sağ sayfalar. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeBooklet metodu, MakeBooklet metoduna benzer, ancak TryMakeBooklet metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)