---
title: PdfFileEditor.MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. İki giriş PDF akışından outputStream'e NUp belgesi oluşturur
type: docs
weight: 310
url: /tr/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

firstInputFile'dan outputFile'a N-Up belgesi oluşturur.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Giriş pdf dosya yolu ve adı. |
| outputFile | String | Çıkış pdf dosya yolu ve adı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |

### Dönüş Değeri

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Giriş akışından N-Up belgesi oluşturur ve sonucu çıkış akışına kaydeder.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş pdf akışı. |
| outputStream | Stream | Çıkış pdf akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |

### Dönüş Değeri

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

İlk giriş akışından çıkış akışına N-Up belgesi oluşturur.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş pdf akışı. |
| outputStream | Stream | Çıkış pdf akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Çıkış pdf dosyasının sayfa boyutu. |

### Dönüş Değeri

İşlem başarılıysa true.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

İki giriş PDF dosyasından outputFile'a N-Up belgesi oluşturur. outputFile'ın her sayfası, bir sayfası ilk giriş dosyasından ve diğer sayfası ikinci giriş dosyasından olmak üzere iki sayfa içerecektir. İki sayfa yatay olarak üst üste yerleştirilmiştir.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstInputFile | String | ilk giriş dosyası. |
| secondInputFile | String | ikinci giriş dosyası. |
| outputFile | String | Çıkış pdf dosya yolu ve adı. |

### Dönüş Değeri

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

İki giriş PDF akışından outputStream'e N-Up belgesi oluşturur.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstInputStream | Stream | ilk giriş akışı. |
| secondInputStream | Stream | ikinci giriş akışı. |
| outputStream | Stream | Çıkış pdf akışı. |

### Dönüş Değeri

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

Birden fazla giriş PDF dosyasından outputFile'a N-Up belgesi oluşturur. outputFile'ın her sayfası, aynı sayfa numarasındaki giriş dosyalarındaki sayfaların kombinasyonunu içerecektir. Eğer isSidewise true ise çoklu sayfalar yatay olarak, false ise dikey olarak üst üste yerleştirilir.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFiles | String[] | Giriş Pdf dosyaları. |
| outputFile | String | Çıkış pdf dosya yolu ve adı. |
| isSidewise | Boolean | Üst üste yerleştirme şekli, yatay için true ve dikey için false. |

### Dönüş Değeri

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

Birden fazla giriş PDF akışından outputStream'e N-Up belgesi oluşturur. outputStream'in her sayfası, aynı sayfa numarasındaki giriş akışlarındaki sayfaların kombinasyonunu içerecektir. Çoklu sayfalar isSidewise true ise yatay olarak, false ise dikey olarak üst üste yerleştirilir.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStreams | Stream[] | Giriş Pdf akışları. |
| outputStream | Stream | Çıkış pdf akışı. |
| isSidewise | Boolean | Üst üste yerleştirme şekli, yatay için true ve dikey için false. |

### Dönüş Değeri

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

Giriş dosyasından outputFile'a N-Up belgesi oluşturur.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Giriş pdf dosya yolu ve adı. |
| outputFile | String | Çıkış pdf dosya yolu ve adı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Çıkış pdf dosyasının sayfa boyutu. |

### Dönüş Değeri

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

firstInputFile'dan outputFile'a N-Up belgesi oluşturur.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Giriş pdf dosya yolu ve adı. |
| outputFile | String | Çıkış pdf dosya yolu ve adı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |

### Dönüş Değeri

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

Giriş akışından N-Up belgesi oluşturur ve sonucu çıkış akışına kaydeder.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş pdf akışı. |
| outputStream | Stream | Çıkış pdf akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |

### Dönüş Değeri

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

İlk giriş akışından çıkış akışına N-Up belgesi oluşturur.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş pdf akışı. |
| outputStream | Stream | Çıkış pdf akışı. |
| x | Int32 | Sütun sayısı. |
| y | Int32 | Satır sayısı. |
| pageSize | PageSize | Çıkış pdf dosyasının sayfa boyutu. |

### Dönüş Değeri

İşlem başarılıysa true.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

İki giriş PDF dosyasından outputFile'a N-Up belgesi oluşturur. outputFile'ın her sayfası, bir sayfası ilk giriş dosyasından ve diğer sayfası ikinci giriş dosyasından olmak üzere iki sayfa içerecektir. İki sayfa yatay olarak üst üste yerleştirilmiştir.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstInputFile | String | ilk giriş dosyası. |
| secondInputFile | String | ikinci giriş dosyası. |
| outputFile | String | Çıkış pdf dosya yolu ve adı. |

### Dönüş Değeri

boolean - Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)