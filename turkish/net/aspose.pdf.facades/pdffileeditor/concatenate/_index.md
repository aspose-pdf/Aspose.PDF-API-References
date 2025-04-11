---
title: PdfFileEditor.Concatenate
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. İki dosyayı birleştirir
type: docs
weight: 260
url: /tr/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Birleştir(string, string, string) {#concatenate_4}

İki dosyayı birleştirir.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstInputFile | String | Birleştirilecek ilk dosya. |
| secInputFile | String | Birleştirilecek ikinci dosya. |
| outputFile | String | Çıktı dosyası. |

### Dönüş Değeri

İşlem başarılıysa doğru.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Birleştir(Stream, Stream, Stream) {#concatenate_1}

İki dosyayı birleştirir.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstInputStream | Stream | İlk dosyanın akışı. |
| secInputStream | Stream | İkinci dosyanın akışı. |
| outputStream | Stream | Sonuç dosyasının saklanacağı akış. |

### Dönüş Değeri

İşlem başarılıysa doğru.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Birleştir(Document[], Document) {#concatenate}

Belgeleri birleştirir.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | Document[] | Kaynak belgelerin dizisi. |
| dest | Document | Hedef belge. |

### Dönüş Değeri

Birleştirme başarılıysa doğru.

### Ayrıca Bakınız

* sınıf [Document](../../../aspose.pdf/document/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Birleştir(string[], string) {#concatenate_6}

Dosyaları tek bir dosyada birleştirir.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFiles | String[] | Birleştirilecek dosyaların dizisi. |
| outputFile | String | Çıktı dosyasının adı. |

### Dönüş Değeri

İşlem başarılıysa doğru.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Birleştir(Stream[], Stream) {#concatenate_3}

Dosyaları birleştirir.

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream[] | Birleştirilecek akışların dizisi. |
| outputStream | Stream | Sonuç dosyasının saklanacağı akış. |

### Dönüş Değeri

İşlem başarılıysa doğru.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Birleştir(string, string, string, string) {#concatenate_5}

İki Pdf belgesini yeni bir Pdf belgesinde sayfaları alternatif yollarla birleştirir ve boş yerleri boş sayfalarla doldurur. örneğin: belge1'in 5 sayfası var: p1, p2, p3, p4, p5. belge2'nin 3 sayfası var: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sayfaları içeren sonuç belgesini üretecektir: p1, p1', p2, p2', p3, p3', p4, boşsayfa, p5, boşsayfa.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstInputFile | String | İlk dosya. |
| secInputFile | String | İkinci dosya. |
| blankPageFile | String | Boş sayfa içeren PDF dosyası. |
| outputFile | String | Sonuç dosyası. |

### Dönüş Değeri

İşlem başarılıysa doğru.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Birleştir(Stream, Stream, Stream, Stream) {#concatenate_2}

İki Pdf belgesini yeni bir Pdf belgesinde sayfaları alternatif yollarla birleştirir ve boş yerleri boş sayfalarla doldurur. örneğin: belge1'in 5 sayfası var: p1, p2, p3, p4, p5. belge2'nin 3 sayfası var: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sayfaları içeren sonuç belgesini üretecektir: p1, p1', p2, p2', p3, p3', p4, boşsayfa, p5, boşsayfa.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstInputStream | Stream | İlk Pdf Akışı. |
| secInputStream | Stream | İkinci Pdf Akışı. |
| blankPageStream | Stream | Boş sayfa içeren Pdf Akışı. |
| outputStream | Stream | Çıktı Pdf Akışı. |

### Dönüş Değeri

İşlem başarılıysa doğru.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)


## Birleştir(string[], HttpResponse) {#concatenate_8}

Dosyaları birleştirir ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFiles | String[] | Birleştirilecek dosyaların dizisi. |
| response | HttpResponse | Yanıt nesnesi. |

### Dönüş Değeri

Birleştirme başarılıysa doğru.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Birleştir(Stream[], HttpResponse) {#concatenate_4}

Dosyaları birleştirir ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream[] | Birleştirilecek dosyaları içeren akışlar dizisi. |
| response | HttpResponse | Yanıt nesnesi. |

### Dönüş Değeri

İşlem başarılıysa doğru.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)