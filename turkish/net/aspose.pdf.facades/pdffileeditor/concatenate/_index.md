---
title: Concatenate
second_title: Aspose.PDF for .NET API Referansı
description: İki dosyayı birleştirir.
type: docs
weight: 290
url: /tr/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_5}

İki dosyayı birleştirir.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstInputFile | String | Birleştirilecek ilk dosya. |
| secInputFile | String | Birleştirilecek ikinci dosya. |
| outputFile | String | Çıktı dosyası. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

İki dosyayı birleştirir.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstInputStream | Stream | İlk dosyanın akışı. |
| secInputStream | Stream | İkinci dosyanın akışı. |
| outputStream | Stream | Sonuç dosyasının depolanacağı akış. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

İşlem başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

Belgeleri birleştirir.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| src | Document[] | Kaynak belgeler dizisi. |
| dest | Document | Hedef belge. |

### Geri dönüş değeri

Birleştirme başarılıysa doğrudur.

### Ayrıca bakınız

* class [Document](../../../aspose.pdf/document)
* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_7}

Dosyaları tek bir dosyada birleştirir.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFiles | String[] | Birleştirilecek dosya dizisi. |
| outputFile | String | Çıktı dosyasının adı. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

Dosyaları birleştirir

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream[] | Birleştirilecek akış dizisi. |
| outputStream | Stream | Sonuç dosyasının depolanacağı akış. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_6}

İki Pdf belgesini alternatif yollarla sayfaları olan yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur. örneğin: belge1'in 5 sayfası vardır: p1, p2, p3, p4, p5. belge2'nin 3 sayfası vardır: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sayfalarla sonuç belgesini üretecektir:p1, p1', p2, p2', p3, p3', p4, boş sayfa, p5, boş sayfa .

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstInputFile | String | İlk dosya. |
| secInputFile | String | İkinci dosya. |
| blankPageFile | String | Boş sayfa içeren PDF dosyası. |
| outputFile | String | Sonuç dosyası. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

İki Pdf belgesini alternatif yollarla sayfaları olan yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur. örneğin: belge1'in 5 sayfası vardır: p1, p2, p3, p4, p5. belge2'nin 3 sayfası vardır: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sayfalarla sonuç belgesini üretecektir:p1, p1', p2, p2', p3, p3', p4, boş sayfa, p5, boş sayfa .

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstInputStream | Stream | İlk Pdf Akışı. |
| secInputStream | Stream | İkinci Pdf Akışı. |
| blankPageStream | Stream | Boş sayfa ile Pdf Akışı. |
| outputStream | Stream | Çıktı Pdf Akışı. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Concatenate(string[], HttpResponse) {#concatenate_8}

Dosyaları birleştirir ve reslt'yi HttpResposnse nesnesine kaydeder.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFiles | String[] | Birleştirilecek dosya dizisi. |
| response | HttpResponse | Yanıt nesnesi. |

### Geri dönüş değeri

birleştirme başarılıysa true .

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

Dosyaları birleştirir ve sonucu HttpResponse nesnesinde saklar.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream[] | Birleştirilecek dosyaları içeren akış dizisi. |
| response | HttpResponse | Yanıt nesnesi/ |

### Geri dönüş değeri

işlem başarılı olduysa true .

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
