---
title: TryMakeNUp
second_title: Aspose.PDF for .NET API Referansı
description: N-yukarı belge oluşturur ve sonucu HttpResponse nesnesine kaydeder.
type: docs
weight: 470
url: /tr/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, int, int, PageSize, HttpResponse) {#trymakenup_6}

N-yukarı belge oluşturur ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak dosyanın yolu. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Sonuç dosyasındaki sayfa boyutu. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeNUp yöntemi, MakeNUp yöntemine benzer, ancak TryMakeNUp yöntemi, işlem başarısız olursa bir istisna atmaz.

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

N-yukarı belge oluşturur ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Kaynak belge akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Sonuç dosyasındaki sayfa boyutu. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeNUp yöntemi, MakeNUp yöntemine benzer, ancak TryMakeNUp yöntemi, işlem başarısız olursa bir istisna atmaz.

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

N-up belge oluşturur ve sonucu HttpResponse. içinde saklar

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak dosya adı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeNUp yöntemi, MakeNUp yöntemine benzer, ancak TryMakeNUp yöntemi, işlem başarısız olursa bir istisna atmaz.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

N-yukarı belge oluşturur ve sonucu HttpResponse'da saklar.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş belgesi akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| response | HttpResponse | HttpResponse sonucun saklanacağı yer. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeNUp yöntemi, MakeNUp yöntemine benzer, ancak TryMakeNUp yöntemi, işlem başarısız olursa bir istisna atmaz.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

FirstInputFile'dan outputFile. 'ye N-Up belgesi yapar

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | pdf dosya yolunu ve adını girin. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeNUp yöntemi, MakeNUp yöntemine benzer, ancak TryMakeNUp yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup_2}

Giriş akışından N-Up belgesi oluşturur ve sonucu çıkış akışına kaydeder.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | pdf akışını girin. |
| outputStream | Stream | Çıktı pdf akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeNUp yöntemi, MakeNUp yöntemine benzer, ancak TryMakeNUp yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_3}

İlk giriş akışından çıkış akışına N-Up belge oluşturur.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | pdf akışını girin. |
| outputStream | Stream | Çıktı pdf akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Çıktı pdf dosyasının sayfa boyutu. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeNUp yöntemi, MakeNUp yöntemine benzer, ancak TryMakeNUp yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_10}

İki giriş PDF dosyasından outputFile'a N-Up belgesi yapar. outputFile'ın her sayfası iki sayfa içerecektir, bir sayfa ilk giriş dosyasından ve diğeri ikinci giriş dosyasındandır. İki sayfa yatay olarak yığılmıştır.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstInputFile | String | ilk giriş dosyası. |
| secondInputFile | String | ikinci giriş dosyası. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde, yanlış

### Notlar

TryMakeNUp yöntemi, MakeNUp yöntemine benzer, ancak TryMakeNUp yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_4}

İki giriş PDF akışından outputStream. 'ye N-Up belge oluşturur

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstInputStream | Stream | ilk giriş akışı. |
| secondInputStream | Stream | ikinci giriş akışı. |
| outputStream | Stream | Çıktı pdf akışı. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde, yanlış

### Notlar

TryMakeNUp yöntemi, MakeNUp yöntemine benzer, ancak TryMakeNUp yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_11}

Çoklu giriş PDF dosyalarından outputFile'a N-Up belgesi yapar. outputFile'ın her sayfası, aynı sayfa numarasının giriş dosyalarındaki sayfalarıyla kombinasyon halinde olan çoklu sayfaları içerecektir. Çoklu sayfalar, isSidewise doğruysa yatay olarak ve isSidewise yanlışsa dikey olarak yığılır.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFiles | String[] | Pdf dosyalarını girin. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |
| isSidewise | Boolean | Yığılmış yol, yatay için doğru ve dikey için yanlış. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeNUp yöntemi, MakeNUp yöntemine benzer, ancak TryMakeNUp yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_5}

Çoklu giriş PDF akışlarından outputStream'e N-Up belgesi oluşturur. outputStream'in her sayfası, aynı sayfa numarasının giriş akışlarındaki sayfalarıyla kombinasyon halinde olan birden çok sayfa içerecektir. Çoklu sayfalar, isSidewise doğruysa yatay olarak ve isSidewise yanlışsa dikey olarak yığılır.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStreams | Stream[] | Giriş Pdf akışları. |
| outputStream | Stream | Çıkış pdf akışı. |
| isSidewise | Boolean | Yığılmış yol, yatay için doğru ve dikey için yanlış. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeNUp yöntemi, MakeNUp yöntemine benzer, ancak TryMakeNUp yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_9}

Girdi dosyasından çıktıFile. dosyasına N-Up belgesi yapar

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | pdf dosya yolunu ve adını girin. |
| outputFile | String | Çıktı pdf dosya yolu ve adı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Çıktı pdf dosyasının sayfa boyutu. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryMakeNUp yöntemi, MakeNUp yöntemine benzer, ancak TryMakeNUp yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
