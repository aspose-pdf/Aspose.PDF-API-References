---
title: PdfFileEditor.TryConcatenate
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. İki dosyayı birleştirir
type: docs
weight: 390
url: /tr/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

İki dosyayı birleştirir.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstInputFile | String | Birleştirilecek ilk dosya. |
| secInputFile | String | Birleştirilecek ikinci dosya. |
| outputFile | String | Çıktı dosyası. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryConcatenate metodu, Concatenate metoduna benzer, ancak TryConcatenate metodu işlem başarısız olursa bir istisna atmaz.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Belgeleri birleştirir.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | Document[] | Kaynak belgelerin dizisi. |
| dest | Document | Hedef belge. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryConcatenate metodu, Concatenate metoduna benzer, ancak TryConcatenate metodu işlem başarısız olursa bir istisna atmaz.

### Ayrıca Bakınız

* sınıf [Document](../../../aspose.pdf/document/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

Dosyaları tek bir dosyada birleştirir.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFiles | String[] | Birleştirilecek dosyaların dizisi. |
| outputFile | String | Çıktı dosyasının adı. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryConcatenate metodu, Concatenate metoduna benzer, ancak TryConcatenate metodu işlem başarısız olursa bir istisna atmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Dosyaları birleştirir.

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream[] | Birleştirilecek akışların dizisi. |
| outputStream | Stream | Sonuç dosyasının saklanacağı akış. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryConcatenate metodu, Concatenate metoduna benzer, ancak TryConcatenate metodu işlem başarısız olursa bir istisna atmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

İki Pdf belgesini yeni bir Pdf belgesine alternatif yollarla birleştirir ve boş yerleri boş sayfalarla doldurur. örn.: belge1'in 5 sayfası var: p1, p2, p3, p4, p5. belge2'nin 3 sayfası var: p1', p2', p3'. İki Pdf belgesini birleştirmek, sayfaları p1, p1', p2, p2', p3, p3', p4, boşsayfa, p5, boşsayfa olan sonuç belgesini üretecektir.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstInputFile | String | İlk dosya. |
| secInputFile | String | İkinci dosya. |
| blankPageFile | String | Boş sayfa içeren PDF dosyası. |
| outputFile | String | Sonuç dosyası. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryConcatenate metodu, Concatenate metoduna benzer, ancak TryConcatenate metodu işlem başarısız olursa bir istisna atmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

İki Pdf belgesini yeni bir Pdf belgesine alternatif yollarla birleştirir ve boş yerleri boş sayfalarla doldurur. örn.: belge1'in 5 sayfası var: p1, p2, p3, p4, p5. belge2'nin 3 sayfası var: p1', p2', p3'. İki Pdf belgesini birleştirmek, sayfaları p1, p1', p2, p2', p3, p3', p4, boşsayfa, p5, boşsayfa olan sonuç belgesini üretecektir.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstInputStream | Stream | İlk Pdf Akışı. |
| secInputStream | Stream | İkinci Pdf Akışı. |
| blankPageStream | Stream | Boş sayfa içeren Pdf Akışı. |
| outputStream | Stream | Çıktı Pdf Akışı. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryConcatenate metodu, Concatenate metoduna benzer, ancak TryConcatenate metodu işlem başarısız olursa bir istisna atmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)


## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Dosyaları birleştirir ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFiles | String[] | Birleştirilecek dosyaların dizisi. |
| response | HttpResponse | Yanıt nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryConcatenate metodu, Concatenate metoduna benzer, ancak TryConcatenate metodu işlem başarısız olursa bir istisna atmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Dosyaları birleştirir ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream[] | Birleştirilecek dosyaları içeren akışlar dizisi. |
| response | HttpResponse | Yanıt nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryConcatenate metodu, Concatenate metoduna benzer, ancak TryConcatenate metodu işlem başarısız olursa bir istisna atmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)