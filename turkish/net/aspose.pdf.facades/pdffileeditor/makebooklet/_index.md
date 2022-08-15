---
title: MakeBooklet
second_title: Aspose.PDF for .NET API Referansı
description: Girdi dosyasından çıktı dosyasına kitapçık yapar.
type: docs
weight: 330
url: /tr/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_8}

Girdi dosyasından çıktı dosyasına kitapçık yapar.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | pdf dosya yolunu ve adını girin. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |

### Geri dönüş değeri

boolean - Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet_2}

InputStream'den outputStream. 'ye kitapçık yapar

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | pdf akışını girin. |
| outputStream | Stream | çıktı pdf akışı. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_9}

inputFile'dan outputFile. 'ye kitapçık yapar

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | pdf dosya yolunu ve adını girin. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |
| pageSize | PageSize | Çıktı pdf dosyasının sayfa boyutu. |

### Geri dönüş değeri

İşlem başarılı olursa doğrudur.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_3}

Giriş akışından kitapçık yapar ve sonucu çıkış akışına kaydeder.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | PDF akışını girin. |
| outputStream | Stream | çıktı pdf akışı. |
| pageSize | PageSize | Çıktı pdf dosyasının sayfa boyutu. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_11}

FirstInputFile'dan outputFile'a özelleştirilmiş kitapçık yapar.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Giriş dosyası. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |
| leftPages | Int32[] | Kitapçığın sol sayfaları. |
| rightPages | Int32[] | Kitapçığın sağ sayfaları. |

### Geri dönüş değeri

boolean - Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_5}

FirstInputStream'den outputStream'e özelleştirilmiş kitapçık oluşturur.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| outputStream | Stream | çıkış pdf akışı. |
| leftPages | Int32[] | Sol sayfalar. |
| rightPages | Int32[] | Doğru sayfalar. |

### Geri dönüş değeri

boolean - Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_10}

FirstInputFile'dan outputFile'a özelleştirilmiş kitapçık yapar.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
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

boolean - Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_4}

FirstInputStream'den outputStream'e kitapçık oluşturur.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
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

boolean - Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

Kaynak dosyadan kitapçık yapar ve sonucu HttpResponse nesnelerine kaydeder.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
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

İşlem başarılı olduysa doğrudur.

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

PDF dosyasından kitapçık yapın ve onu HttpResponse. içine depolayın

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş belgesi akışı. |
| pageSize | PageSize | İstenilen sayfa boyutu. |
| leftPages | Int32[] | Sol tarafa yerleştirilecek sayfa numaraları dizisi. |
| rightPages | Int32[] | Sağda yer alacak sayfa numaraları dizisi. |
| response | HttpResponse | HttpResponse nesnesi. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

Kaynak dosyadan kitapçık yapar ve sonucu HttpResponse nesnelerine kaydeder.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak dosya yolu. |
| pageSize | PageSize | Çıktı dosyasında istenen sayfa boyutu. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Geri dönüş değeri

İşlem başarılı olursa doğrudur.

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

Kaynak dosyadan kitapçık yapar ve sonucu HttpResponse. içinde saklar

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş belgesi akışı. |
| pageSize | PageSize | Çıktı dosyasında istenen sayfa boyutu. |
| response | HttpResponse | Sonucun kaydedileceği nesneyi yanıtlayın. |

### Geri dönüş değeri

kitapçık başarıyla oluşturulduysa true .

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
