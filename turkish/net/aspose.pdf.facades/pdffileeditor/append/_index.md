---
title: PdfFileEditor.Append
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. portStreams içindeki belgeler dizisinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage ile endPage aralığındaki tüm portStreams belgelerinin sayfalarını içerir.
type: docs
weight: 250
url: /tr/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

portStreams içindeki belgeler dizisinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage ile endPage aralığındaki tüm portStreams belgelerinin sayfalarını içerir.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

portFiles belgelerinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage ile endPage aralığındaki tüm portFiles belgelerinin sayfalarını içerir.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
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

İşlem başarılıysa true.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

startPage ile endPage aralığında portFile'dan seçilen sayfaları, firstInputFile'ın sonuna portFile'da ekler.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi Pdf dosyası. |
| portFile | String | Pdf dosyasından sayfalar. |
| startPage | Int32 | portFile'da sayfanın başladığı yer. |
| endPage | Int32 | portFile'da sayfanın bittiği yer. |
| outputFile | String | Çıktı Pdf belgesi. |

### Dönüş Değeri

İşlem başarılıysa true.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

startPage ile endPage aralığında portStream'dan seçilen sayfaları, firstInputStream'ın sonuna portStream'da ekler.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Girdi dosyası Akışı. |
| portStream | Stream | Pdf dosyası Akışından sayfalar. |
| startPage | Int32 | portFile Akışında sayfanın başladığı yer. |
| endPage | Int32 | portFile Akışında sayfanın bittiği yer. |
| outputStream | Stream | Çıktı Pdf dosyası Akışı. |

### Dönüş Değeri

Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)