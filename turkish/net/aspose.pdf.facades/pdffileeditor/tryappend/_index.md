---
title: TryAppend
second_title: Aspose.PDF for .NET API Referansı
description: portStreams içindeki belge dizisinden seçilen sayfaları ekler. Sonuç belgesi firstInputFile ve startPage - endPage aralığındaki tüm portStreams belge sayfalarını içerir.
type: docs
weight: 410
url: /tr/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

portStreams içindeki belge dizisinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage - endPage aralığındaki tüm portStreams belge sayfalarını içerir.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş Pdf akışı. |
| portStreams | Stream[] | Sayfaların kopyalanacağı belgeler. |
| startPage | Int32 | Sayfa, portStreams belgelerinde başlar. |
| endPage | Int32 | Sayfa, portStreams belgelerinde biter. |
| outputStream | Stream | Çıktı pdf akışı. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Notlar

TryAppend yöntemi, İşlem başarısız olursa TryAppend yönteminin bir istisna oluşturmaması dışında, Append yöntemine benzer.

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_2}

portFiles belgelerinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage - endPage aralığındaki tüm portFiles belge sayfalarını içerir.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Pdf dosyasını girin. |
| portFiles | String[] | Sayfaların kopyalanacağı belgeler. |
| startPage | Int32 | Sayfa, portFiles belgelerinde başlar. |
| endPage | Int32 | PortFiles belgelerinde sayfa biter. |
| outputFile | String | Çıktı pdf belgesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryAppend yöntemi, İşlem başarısız olursa TryAppend yönteminin bir istisna oluşturmaması dışında, Append yöntemine benzer.

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Belgeleri kaynak belgeye ekler ve sonucu yanıt nesnesine kaydeder.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Kaynak belgeyi içeren akış. |
| portStreams | Stream[] | Eklenecek belgelerle akış dizisi. |
| startPage | Int32 | Eklenen sayfanın başlangıç sayfası. |
| endPage | Int32 | Eklenen sayfaların bitiş sayfası. |
| response | HttpResponse | Belgenin kaydedileceği yanıt nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryAppend yöntemi, İşlem başarısız olursa TryAppend yönteminin bir istisna oluşturmaması dışında, Append yöntemine benzer.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Belgeleri kaynak belgeye ekler ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak belgeyi içeren dosyanın adı. |
| portFiles | String[] | Eklenen belgeleri içeren dosya adları dizisi. |
| startPage | Int32 | Eklenen sayfaların başlangıç sayfası. |
| endPage | Int32 | Eklenen sayfaların bitiş sayfası. |
| response | HttpResponse | Belgenin kaydedileceği yanıt nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryAppend yöntemi, İşlem başarısız olursa TryAppend yönteminin bir istisna oluşturmaması dışında, Append yöntemine benzer.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
