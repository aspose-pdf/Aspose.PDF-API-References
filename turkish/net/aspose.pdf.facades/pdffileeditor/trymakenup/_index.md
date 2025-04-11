---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. firstInputFile'dan outputFile'a NUp belgesi oluşturur
type: docs
weight: 440
url: /tr/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

N-up belgesi oluşturur ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak dosyanın yolu. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Sonuç dosyasındaki sayfa boyutu. |
| response | HttpResponse | Sonucun kaydedileceği HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeNUp metodu, MakeNUp metoduna benzer, ancak TryMakeNUp metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

N-up belgesi oluşturur ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Kaynak belgenin akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Sonuç dosyasındaki sayfa boyutu. |
| response | HttpResponse | Sonucun kaydedileceği HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeNUp metodu, MakeNUp metoduna benzer, ancak TryMakeNUp metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

N-up belgesi oluşturur ve sonucu HttpResponse'ye kaydeder.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak dosya adı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| response | HttpResponse | Sonucun kaydedileceği HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeNUp metodu, MakeNUp metoduna benzer, ancak TryMakeNUp metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

N-up belgesi oluşturur ve sonucu HttpResponse'ye kaydeder.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Girdi belgesinin akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| response | HttpResponse | Sonucun kaydedileceği HttpResponse. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeNUp metodu, MakeNUp metoduna benzer, ancak TryMakeNUp metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

firstInputFile'dan outputFile'a N-Up belgesi oluşturur.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi pdf dosyasının yolu ve adı. |
| outputFile | String | Çıktı pdf dosyasının yolu ve adı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeNUp metodu, MakeNUp metoduna benzer, ancak TryMakeNUp metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

Girdi akışından N-Up belgesi oluşturur ve sonucu çıktı akışına kaydeder.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Girdi pdf akışı. |
| outputStream | Stream | Çıktı pdf akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeNUp metodu, MakeNUp metoduna benzer, ancak TryMakeNUp metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

İlk girdi akışından çıktı akışına N-Up belgesi oluşturur.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Girdi pdf akışı. |
| outputStream | Stream | Çıktı pdf akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Çıktı pdf dosyasının sayfa boyutu. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeNUp metodu, MakeNUp metoduna benzer, ancak TryMakeNUp metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

İki girdi PDF dosyasından outputFile'a N-Up belgesi oluşturur. outputFile'ın her sayfası, bir sayfası ilk girdi dosyasından ve diğer sayfası ikinci girdi dosyasından olmak üzere iki sayfa içerecektir. İki sayfa yatay olarak üst üste yerleştirilmiştir.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstInputFile | String | ilk girdi dosyası. |
| secondInputFile | String | ikinci girdi dosyası. |
| outputFile | String | Çıktı pdf dosyasının yolu ve adı. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false

## Açıklamalar

TryMakeNUp metodu, MakeNUp metoduna benzer, ancak TryMakeNUp metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

İki girdi PDF akışından outputStream'e N-Up belgesi oluşturur.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstInputStream | Stream | ilk girdi akışı. |
| secondInputStream | Stream | ikinci girdi akışı. |
| outputStream | Stream | Çıktı pdf akışı. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false

## Açıklamalar

TryMakeNUp metodu, MakeNUp metoduna benzer, ancak TryMakeNUp metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

Birden fazla girdi PDF dosyasından outputFile'a N-Up belgesi oluşturur. outputFile'ın her sayfası, aynı sayfa numarasına sahip girdi dosyalarındaki sayfaların kombinasyonunu içerecektir. Çoklu sayfalar, isSidewise true ise yatay olarak, false ise dikey olarak üst üste yerleştirilir.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFiles | String[] | Girdi Pdf dosyaları. |
| outputFile | String | Çıktı pdf dosyasının yolu ve adı. |
| isSidewise | Boolean | Üst üste yerleştirme şekli, yatay için true ve dikey için false. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeNUp metodu, MakeNUp metoduna benzer, ancak TryMakeNUp metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

Birden fazla girdi PDF akışından outputStream'e N-Up belgesi oluşturur. outputStream'in her sayfası, aynı sayfa numarasına sahip girdi akışlarındaki sayfaların kombinasyonunu içerecektir. Çoklu sayfalar, isSidewise true ise yatay olarak, false ise dikey olarak üst üste yerleştirilir.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStreams | Stream[] | Girdi Pdf akışları. |
| outputStream | Stream | Çıktı pdf akışı. |
| isSidewise | Boolean | Üst üste yerleştirme şekli, yatay için true ve dikey için false. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeNUp metodu, MakeNUp metoduna benzer, ancak TryMakeNUp metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

Girdi dosyasından outputFile'a N-Up belgesi oluşturur.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi pdf dosyasının yolu ve adı. |
| outputFile | String | Çıktı pdf dosyasının yolu ve adı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Çıktı pdf dosyasının sayfa boyutu. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryMakeNUp metodu, MakeNUp metoduna benzer, ancak TryMakeNUp metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)