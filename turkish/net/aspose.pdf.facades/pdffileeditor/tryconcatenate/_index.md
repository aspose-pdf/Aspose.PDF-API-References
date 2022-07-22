---
title: TryConcatenate
second_title: Aspose.PDF for .NET API Referansı
description: İki dosyayı birleştirir.
type: docs
weight: 420
url: /tr/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_4}

İki dosyayı birleştirir.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstInputFile | String | Birleştirilecek ilk dosya. |
| secInputFile | String | Birleştirilecek ikinci dosya. |
| outputFile | String | Çıktı dosyası. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryConcatenate yöntemi, işlem başarısız olursa TryConcatenate yönteminin bir istisna oluşturmaması dışında, Concatenate yöntemine benzer.

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Belgeleri birleştirir.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| src | Document[] | Kaynak belgeler dizisi. |
| dest | Document | Hedef belge. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryConcatenate yöntemi, Concatenate yöntemine benzer, , işlem başarısız olursa TryConcatenate yönteminin bir istisna oluşturmaması dışında.

### Ayrıca bakınız

* class [Document](../../../aspose.pdf/document)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_6}

Dosyaları tek bir dosyada birleştirir.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFiles | String[] | Birleştirilecek dosya dizisi. |
| outputFile | String | Çıktı dosyasının adı. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryConcatenate yöntemi, Concatenate yöntemine benzer, , işlem başarısız olursa TryConcatenate yönteminin bir istisna oluşturmaması dışında.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Dosyaları birleştirir

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream[] | Birleştirilecek akış dizisi. |
| outputStream | Stream | Sonuç dosyasının depolanacağı akış. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryConcatenate yöntemi, Concatenate yöntemine benzer, , işlem başarısız olursa TryConcatenate yönteminin bir istisna oluşturmaması dışında.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_5}

İki Pdf belgesini alternatif yollarla sayfaları olan yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur. örneğin: belge1'in 5 sayfası vardır: p1, p2, p3, p4, p5. belge2'nin 3 sayfası vardır: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sayfalarla sonuç belgesini üretecektir:p1, p1', p2, p2', p3, p3', p4, boş sayfa, p5, boş sayfa .

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstInputFile | String | İlk dosya. |
| secInputFile | String | İkinci dosya. |
| blankPageFile | String | Boş sayfa içeren PDF dosyası. |
| outputFile | String | Sonuç dosyası. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryConcatenate yöntemi, Concatenate yöntemine benzer, ancak TryConcatenate yönteminin işlem başarısız olursa bir istisna oluşturmaması dışında.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

İki Pdf belgesini alternatif yollarla sayfaları olan yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur. örneğin: belge1'in 5 sayfası vardır: p1, p2, p3, p4, p5. belge2'nin 3 sayfası vardır: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sayfalarla sonuç belgesini üretecektir:p1, p1', p2, p2', p3, p3', p4, boş sayfa, p5, boş sayfa .

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstInputStream | Stream | İlk Pdf Akışı. |
| secInputStream | Stream | İkinci Pdf Akışı. |
| blankPageStream | Stream | Boş sayfa ile Pdf Akışı. |
| outputStream | Stream | Çıktı Pdf Akışı. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryConcatenate yöntemi, Concatenate yöntemine benzer, ancak TryConcatenate yönteminin işlem başarısız olursa bir istisna oluşturmaması dışında.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Dosyaları birleştirir ve reslt'yi HttpResposnse nesnesine kaydeder.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFiles | String[] | Birleştirilecek dosya dizisi. |
| response | HttpResponse | Yanıt nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryConcatenate yöntemi, işlem başarısız olursa TryConcatenate yönteminin bir istisna oluşturmaması dışında, Concatenate yöntemine benzer.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Dosyaları birleştirir ve sonucu HttpResponse nesnesinde saklar.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream[] | Birleştirilecek dosyaları içeren akış dizisi. |
| response | HttpResponse | Yanıt nesnesi/ |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryConcatenate yöntemi, işlem başarısız olursa TryConcatenate yönteminin bir istisna oluşturmaması dışında, Concatenate yöntemine benzer.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
