---
title: PdfFileEditor.Insert
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Başka bir dosyadan sayfaları Pdf dosyasına bir konumda ekler
type: docs
weight: 290
url: /tr/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

Başka bir dosyadan sayfaları Pdf dosyasına bir konumda ekler.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi Pdf dosyası. |
| insertLocation | Int32 | Girdi dosyasındaki konum. |
| portFile | String | Taşınan Pdf dosyası. |
| startPage | Int32 | portFile'daki başlangıç konumu. |
| endPage | Int32 | portFile'daki bitiş konumu. |
| outputFile | String | Çıktı Pdf dosyası. |

### Dönüş Değeri

Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Başka bir dosyadan sayfaları girdi Pdf dosyasına ekler.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Pdf dosyasının Girdi Akışı. |
| insertLocation | Int32 | Girdi dosyasındaki ekleme konumu. |
| portStream | Stream | Sayfalar için Pdf dosyasının Akışı. |
| startPage | Int32 | Hangi sayfadan başlanacağı. |
| endPage | Int32 | Hangi sayfada sona ereceği. |
| outputStream | Stream | Çıktı Akışı. |

### Dönüş Değeri

Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

Başka bir dosyadan sayfaları girdi Pdf dosyasına ekler.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi Pdf dosyası. |
| insertLocation | Int32 | Girdi dosyasındaki ekleme konumu. |
| portFile | String | Pdf dosyasından sayfalar. |
| pageNumber | Int32[] | portFile'daki taşınan sayfa numarası. |
| outputFile | String | Çıktı Pdf dosyası. |

### Dönüş Değeri

Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Başka bir dosyadan sayfaları girdi Pdf dosyasına ekler.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Pdf dosyasının Girdi Akışı. |
| insertLocation | Int32 | Girdi dosyasındaki ekleme konumu. |
| portStream | Stream | Sayfalar için Pdf dosyasının Akışı. |
| pageNumber | Int32[] | portFile'daki taşınan sayfa numarası. |
| outputStream | Stream | Çıktı Akışı. |

### Dönüş Değeri

İşlem başarılıysa true.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)