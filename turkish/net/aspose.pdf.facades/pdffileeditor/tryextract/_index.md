---
title: PdfFileEditor.TryExtract
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Girdi dosyalarından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder
type: docs
weight: 410
url: /tr/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

Girdi dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi Pdf dosyası yolu. |
| startPage | Int32 | Başlangıç sayfa numarası. |
| endPage | Int32 | Bitiş sayfa numarası. |
| outputFile | String | Çıktı Pdf dosyası yolu. |

### Dönüş Değeri

Başarı için true, aksi takdirde false.

## Açıklamalar

TryExtract metodu, Extract metoduna benzer, ancak TryExtract metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Numara dizisi ile belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi dosyası yolu. |
| pageNumber | Int32[] | Girdi dosyasındaki sayfa indeksleri. |
| outputFile | String | Çıktı dosyası yolu. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryExtract metodu, Extract metoduna benzer, ancak TryExtract metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Numara dizisi ile belirtilen sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Girdi dosyası Akışı. |
| pageNumber | Int32[] | Girdi dosyasındaki sayfa indeksleri. |
| outputStream | Stream | Çıktı dosyası akışı. |

### Dönüş Değeri

Başarı için true, aksi takdirde false.

## Açıklamalar

TryExtract metodu, Extract metoduna benzer, ancak TryExtract metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)


## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Kaynak belgenin akışı. |
| pageNumber | Int32[] | Çıkarılacak sayfa numaralarının dizisi. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryExtract metodu, Extract metoduna benzer, ancak TryExtract metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak dosya yolu. |
| pageNumber | Int32[] | Çıkarılacak sayfa numaralarının dizisi. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryExtract metodu, Extract metoduna benzer, ancak TryExtract metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)