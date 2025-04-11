---
title: PdfFileEditor.Delete
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Girdi dosyasından numara dizisi ile belirtilen sayfaları siler ve yeni bir Pdf dosyası olarak kaydeder.
type: docs
weight: 270
url: /tr/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Girdi dosyasından numara dizisi ile belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi dosyası yolu. |
| pageNumber | Int32[] | Girdi dosyasındaki sayfanın indeksi. |
| outputFile | String | Çıktı dosyası yolu. |

### Dönüş Değeri

İşlem başarılıysa true döner.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Girdi dosyasından numara dizisi ile belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Girdi dosyası Akışı. |
| pageNumber | Int32[] | Girdi dosyasındaki sayfanın indeksi. |
| outputStream | Stream | Çıktı dosyası akışı. |

### Dönüş Değeri

Başarı için true, ya da false.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)