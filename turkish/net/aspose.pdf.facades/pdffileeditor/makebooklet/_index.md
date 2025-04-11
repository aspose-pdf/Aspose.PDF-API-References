---
title: PdfFileEditor.MakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Giriş dosyasından çıkış dosyasına broşür oluşturur
type: docs
weight: 300
url: /tr/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_4}

Giriş dosyasından çıkış dosyasına broşür oluşturur.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Giriş pdf dosya yolu ve adı. |
| outputFile | String | Çıkış pdf dosya yolu ve adı. |

### Dönüş Değeri

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet}

Giriş akışından çıkış akışına broşür oluşturur.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş pdf akışı. |
| outputStream | Stream | çıkış pdf akışı. |

### Dönüş Değeri

İşlem başarılıysa true.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_5}

GirişFile'dan çıkışFile'a broşür oluşturur.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Giriş pdf dosya yolu ve adı. |
| outputFile | String | Çıkış pdf dosya yolu ve adı. |
| pageSize | PageSize | Çıkış pdf dosyasının sayfa boyutu. |

### Dönüş Değeri

İşlem başarılıysa true.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_1}

Giriş akışından broşür oluşturur ve sonucu çıkış akışına kaydeder.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş PDF akışı. |
| outputStream | Stream | çıkış pdf akışı. |
| pageSize | PageSize | Çıkış pdf dosyasının sayfa boyutu. |

### Dönüş Değeri

İşlem başarılıysa true.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_7}

İlkInputFile'dan çıkışFile'a özelleştirilmiş broşür oluşturur.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Giriş dosyası. |
| outputFile | String | Çıkış pdf dosya yolu ve adı. |
| leftPages | Int32[] | Broşürün sol sayfaları. |
| rightPages | Int32[] | Broşürün sağ sayfaları. |

### Dönüş Değeri

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_3}

İlkInputStream'den çıkışStream'e özelleştirilmiş broşür oluşturur.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| outputStream | Stream | çıkış pdf akışı. |
| leftPages | Int32[] | Sol sayfalar. |
| rightPages | Int32[] | Sağ sayfalar. |

### Dönüş Değeri

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_6}

İlkInputFile'dan çıkışFile'a özelleştirilmiş broşür oluşturur.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
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

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_2}

İlkInputStream'den çıkışStream'e broşür oluşturur.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
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

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

Kaynak dosyasından broşür oluşturur ve sonucu HttpResponse nesnelerine kaydeder.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak dosya yolu. |
| pageSize | PageSize | İstenen sayfa boyutu. |
| leftPages | Int32[] | Sol tarafa yerleştirilecek sayfa numaralarının dizisi. |
| rightPages | Int32[] | Sağ tarafa yerleştirilecek sayfa numaralarının dizisi. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarılıysa true.

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

PDF dosyasından broşür oluşturur ve bunu HttpResponse'ye kaydeder.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş belge akışı. |
| pageSize | PageSize | İstenen sayfa boyutu. |
| leftPages | Int32[] | Sol tarafa yerleştirilecek sayfa numaralarının dizisi. |
| rightPages | Int32[] | Sağ tarafa yerleştirilecek sayfa numaralarının dizisi. |
| response | HttpResponse | HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarılıysa true.

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

Kaynak dosyasından broşür oluşturur ve sonucu HttpResponse nesnelerine kaydeder.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak dosya yolu. |
| pageSize | PageSize | Çıkış dosyasında istenen sayfa boyutu. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarılıysa true.

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

Kaynak dosyasından broşür oluşturur ve sonucu HttpResponse'ye kaydeder.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş belge akışı. |
| pageSize | PageSize | Çıkış dosyasında istenen sayfa boyutu. |
| response | HttpResponse | Sonucun kaydedileceği Respose nesnesi. |

### Dönüş Değeri

Broşür başarıyla oluşturulduysa true.

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)