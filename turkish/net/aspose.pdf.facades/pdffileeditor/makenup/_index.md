---
title: MakeNUp
second_title: Aspose.PDF for .NET API Referansı
description: FirstInputFiledan outputFile. ye N-Up belgesi yapar
type: docs
weight: 340
url: /tr/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(string, string, int, int) {#makenup_8}

FirstInputFile'dan outputFile. 'ye N-Up belgesi yapar

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | pdf dosya yolunu ve adını girin. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |

### Geri dönüş değeri

boolean - Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Giriş akışından N-Up belgesi oluşturur ve sonucu çıkış akışına kaydeder.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | pdf akışını girin. |
| outputStream | Stream | Çıktı pdf akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |

### Geri dönüş değeri

boolean - Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

İlk giriş akışından çıkış akışına N-Up belge oluşturur.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | pdf akışını girin. |
| outputStream | Stream | Çıktı pdf akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Çıktı pdf dosyasının sayfa boyutu. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

İki giriş PDF dosyasından outputFile'a N-Up belgesi yapar. outputFile'ın her sayfası iki sayfa içerecektir, bir sayfa ilk giriş dosyasından ve diğeri ikinci giriş dosyasındandır. İki sayfa yatay olarak yığılmıştır.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstInputFile | String | ilk giriş dosyası. |
| secondInputFile | String | ikinci giriş dosyası. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |

### Geri dönüş değeri

boolean - Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

İki giriş PDF akışından outputStream. 'ye N-Up belge oluşturur

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstInputStream | Stream | ilk giriş akışı. |
| secondInputStream | Stream | ikinci giriş akışı. |
| outputStream | Stream | Çıktı pdf akışı. |

### Geri dönüş değeri

boolean - Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_11}

Çoklu giriş PDF dosyalarından outputFile'a N-Up belgesi yapar. outputFile'ın her sayfası, aynı sayfa numarasının giriş dosyalarındaki sayfalarıyla kombinasyon halinde olan çoklu sayfaları içerecektir. Çoklu sayfalar, isSidewise doğruysa yatay olarak ve isSidewise yanlışsa dikey olarak yığılır.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFiles | String[] | Pdf dosyalarını girin. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |
| isSidewise | Boolean | Yığılmış yol, yatay için doğru ve dikey için yanlış. |

### Geri dönüş değeri

boolean - Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_5}

Çoklu giriş PDF akışlarından outputStream'e N-Up belgesi oluşturur. outputStream'in her sayfası, aynı sayfa numarasının giriş akışlarındaki sayfalarıyla kombinasyon halinde olan birden çok sayfa içerecektir. Çoklu sayfalar, isSidewise doğruysa yatay olarak ve isSidewise yanlışsa dikey olarak yığılır.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStreams | Stream[] | Giriş Pdf akışları. |
| outputStream | Stream | Çıkış pdf akışı. |
| isSidewise | Boolean | Yığılmış yol, yatay için doğru ve dikey için yanlış. |

### Geri dönüş değeri

boolean - Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_9}

Girdi dosyasından çıktıFile. dosyasına N-Up belgesi yapar

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | pdf dosya yolunu ve adını girin. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Çıktı pdf dosyasının sayfa boyutu. |

### Geri dönüş değeri

boolean - Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, PageSize, HttpResponse) {#makenup}

N-yukarı belge oluşturur ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Kaynak belge akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Sonuç dosyasındaki sayfa boyutu. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, PageSize, HttpResponse) {#makenup_6}

N-yukarı belge oluşturur ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool MakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak dosyanın yolu. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Sonuç dosyasındaki sayfa boyutu. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, HttpResponse) {#makenup_7}

N-up belge oluşturur ve sonucu HttpResponse. içinde saklar

```csharp
public bool MakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak dosya adı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, HttpResponse) {#makenup_1}

N-yukarı belge oluşturur ve sonucu HttpResponse'da saklar.

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş belgesi akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| response | HttpResponse | HttpResponse sonucun saklanacağı yer. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
