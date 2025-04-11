---
title: PdfFileEditor.SplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Pdf dosyasını ilk sayfadan belirtilen konuma böler ve ön kısmı yeni bir dosya olarak kaydeder
type: docs
weight: 340
url: /tr/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Pdf dosyasını ilk sayfadan belirtilen konuma böler ve ön kısmı yeni bir dosya olarak kaydeder.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak Pdf dosyası. |
| location | Int32 | Bölme noktası. |
| outputFile | String | Çıktı Pdf dosyası. |

### Dönüş Değeri

Başarı için true, ya da başarısızlık için false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

Başlangıçtan belirtilen konuma böler ve ön kısmı çıktı Stream'inde kaydeder.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Kaynak Pdf dosyası Stream'i. |
| location | Int32 | Bölme noktası. |
| outputStream | Stream | Çıktı dosyası Stream'i. |

### Dönüş Değeri

Başarı için true, ya da başarısızlık için false.

## Açıklamalar

Bu işlemden sonra akışlar KAPANMAZ.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)