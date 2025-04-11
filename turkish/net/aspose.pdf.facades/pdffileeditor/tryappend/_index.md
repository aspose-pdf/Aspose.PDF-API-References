---
title: PdfFileEditor.TryAppend
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor yöntemi. portStreams içindeki belgeler dizisinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage ile endPage aralığındaki tüm portStreams belgelerinin sayfalarını içerir.
type: docs
weight: 380
url: /tr/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

portStreams içindeki belgeler dizisinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage ile endPage aralığındaki tüm portStreams belgelerinin sayfalarını içerir.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Girdi Pdf akışı. |
| portStreams | Stream[] | Sayfaların kopyalanacağı belgeler. |
| startPage | Int32 | portStreams belgelerinde sayfanın başladığı yer. |
| endPage | Int32 | portStreams belgelerinde sayfanın bittiği yer. |
| outputStream | Stream | Çıktı Pdf akışı. |

### Dönüş Değeri

Başarı için true, aksi takdirde false.

## Açıklamalar

TryAppend yöntemi, Append yöntemine benzer, ancak TryAppend yöntemi işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

portFiles belgelerinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage ile endPage aralığındaki tüm portFiles belgelerinin sayfalarını içerir.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi Pdf dosyası. |
| portFiles | String[] | Sayfaların kopyalanacağı belgeler. |
| startPage | Int32 | portFiles belgelerinde sayfanın başladığı yer. |
| endPage | Int32 | portFiles belgelerinde sayfanın bittiği yer. |
| outputFile | String | Çıktı Pdf belgesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryAppend yöntemi, Append yöntemine benzer, ancak TryAppend yöntemi işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)


## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Kaynak belgeye belgeleri ekler ve sonucu yanıt nesnesine kaydeder.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Kaynak belgeyi içeren akış. |
| portStreams | Stream[] | Eklenecek belgelerle birlikte akışlar dizisi. |
| startPage | Int32 | Eklenen sayfanın başlangıç sayfası. |
| endPage | Int32 | Eklenen sayfaların bitiş sayfası. |
| response | HttpResponse | Belgenin kaydedileceği yanıt nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryAppend yöntemi, Append yöntemine benzer, ancak TryAppend yöntemi işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Kaynak belgeye belgeleri ekler ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak belgeyi içeren dosyanın adı. |
| portFiles | String[] | Eklenen belgeleri içeren dosya adları dizisi. |
| startPage | Int32 | Eklenen sayfaların başlangıç sayfası. |
| endPage | Int32 | Eklenen sayfaların bitiş sayfası. |
| response | HttpResponse | Belgenin kaydedileceği yanıt nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryAppend yöntemi, Append yöntemine benzer, ancak TryAppend yöntemi işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)