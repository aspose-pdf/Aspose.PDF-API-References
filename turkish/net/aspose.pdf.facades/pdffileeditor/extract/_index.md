---
title: PdfFileEditor.Extract
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Girdi dosyalarından sayfaları çıkarır ve yeni bir Pdf dosyası olarak kaydeder
type: docs
weight: 280
url: /tr/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

Girdi dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi Pdf dosyası yolu. |
| startPage | Int32 | Başlangıç sayfa numarası. |
| endPage | Int32 | Bitiş sayfa numarası. |
| outputFile | String | Çıktı Pdf dosyası yolu. |

### Dönüş Değeri

Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

Numara dizisi ile belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi dosyası yolu. |
| pageNumber | Int32[] | Girdi dosyasındaki sayfa indeksi. |
| outputFile | String | Çıktı dosyası yolu. |

### Dönüş Değeri

İşlem başarılıysa true.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Girdi dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Girdi dosyası Akışı. |
| startPage | Int32 | Başlangıç sayfa numarası. |
| endPage | Int32 | Bitiş sayfa numarası. |
| outputStream | Stream | Çıktı Pdf dosyası Akışı. |

### Dönüş Değeri

Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Numara dizisi ile belirtilen sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Girdi dosyası Akışı. |
| pageNumber | Int32[] | Girdi dosyasındaki sayfa indeksi. |
| outputStream | Stream | Çıktı dosyası akışı. |

### Dönüş Değeri

Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)