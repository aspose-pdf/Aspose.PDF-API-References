---
title: PdfFileEditor.SplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Belirtilen yerden ayırır ve arka kısmı yeni bir dosya olarak kaydeder
type: docs
weight: 360
url: /tr/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

Belirtilen yerden ayırır ve arka kısmı yeni bir dosya Akışı olarak kaydeder.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Akış | Kaynak Pdf dosyası Akışı. |
| location | Int32 | Ayırma pozisyonu. |
| outputStream | Akış | Çıktı Pdf dosyası Akışı. |

### Dönüş Değeri

Başarı için doğru, ya da yanlış.

## Açıklamalar

Bu işlemden sonra akışlar KAPATILMAZ, CloseConcatedStreams belirtilmedikçe.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

Belirtilen yerden ayırır ve arka kısmı yeni bir dosya olarak kaydeder.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | Dize | Kaynak Pdf dosyası. |
| location | Int32 | Ayırma pozisyonu. |
| outputFile | Dize | Çıktı Pdf dosyası yolu. |

### Dönüş Değeri

Başarı için doğru, ya da yanlış.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

Belirtilen yerden ayırır ve arka kısmı yeni bir dosya Akışı olarak kaydeder.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Akış | Kaynak Pdf dosyası Akışı. |
| location | Int32 | Ayırma pozisyonu. |
| outputStream | Akış | Çıktı Pdf dosyası Akışı. |

### Dönüş Değeri

Başarı için doğru, ya da yanlış.

## Açıklamalar

Bu işlemden sonra akışlar KAPATILMAZ, CloseConcatedStreams belirtilmedikçe.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)