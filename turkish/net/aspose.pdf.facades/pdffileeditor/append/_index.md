---
title: Append
second_title: Aspose.PDF for .NET API Referansı
description: portStreams içindeki belge dizisinden seçilen sayfaları ekler. Sonuç belgesi firstInputFile ve startPage - endPage aralığındaki tüm portStreams belge sayfalarını içerir.
type: docs
weight: 280
url: /tr/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

portStreams içindeki belge dizisinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage - endPage aralığındaki tüm portStreams belge sayfalarını içerir.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_4}

portFiles belgelerinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage - endPage aralığındaki tüm portFiles belge sayfalarını içerir.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
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

İşlem başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_3}

startPage ile endPage aralığındaki portFile'dan seçilen sayfaları, firstInputFile. 'nin sonundaki portFile'a ekler.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Pdf dosyasını girin. |
| portFile | String | Pdf dosyasından sayfalar. |
| startPage | Int32 | Sayfa portFile'da başlar. |
| endPage | Int32 | Sayfa portFile'da biter. |
| outputFile | String | Çıktı pdf belgesi. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

startPage ile endPage aralığında portStream'den seçilen sayfaları, firstInputStream'in sonunda portStream'e ekler.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Girdi dosyası Akış. |
| portStream | Stream | Pdf dosyasından sayfalar Akış. |
| startPage | Int32 | Sayfa, portFile Stream'de başlar. |
| endPage | Int32 | Sayfa, portFile Stream'de biter. |
| outputStream | Stream | Çıktı Pdf dosyası Akışı. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Append(Stream, Stream[], int, int, HttpResponse) {#append_2}

Belgeleri kaynak belgeye ekler ve sonucu yanıt nesnesine kaydeder.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

işlem başarılıysa true .

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, HttpResponse) {#append_5}

Belgeleri kaynak belgeye ekler ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
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

işlem başarılı olduysa true .

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
