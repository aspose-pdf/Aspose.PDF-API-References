---
title: PdfFileEditor.SplitToPages
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. PDF dosyasını tek sayfalık belgelere böler
type: docs
weight: 370
url: /tr/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

PDF dosyasını tek sayfalık belgelere böler.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi PDF dosya adı. |

### Dönüş Değeri

Her bir akışın tek sayfalık bir PDF belgesini tamponladığı çıktı PDF akışları.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Pdf dosyasını tek sayfalık belgelere böler.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Girdi Pdf akışı. |

### Dönüş Değeri

Belgenin sayfalarını içeren bellek akışları dizisi.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Pdf dosyasını tek sayfalık belgelere böler ve belirtilen yola kaydeder. Yol, alan adı şablonu ile belirtilir.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi dosya adı. |
| fileNameTemplate | String | Sonuç dosya adı şablonu. Sayfa numarası ile değiştirilecek %NUM% içermelidir. Örneğin, c:/dir/page%NUM%.pdf belirtilirse, sonuç dosyalarının adları şu şekilde olacaktır: c:/dir/page1.pdf, c:/dir/page2.pdf vb. |

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Pdf dosyasını tek sayfalık belgelere böler ve belirtilen yola kaydeder. Yol, alan adı şablonu ile belirtilir.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Kaynak belgenin akışı. |
| fileNameTemplate | String | Sonuç dosya adı şablonu. Sayfa numarası ile değiştirilecek %NUM% içermelidir. Örneğin, c:/dir/page%NUM%.pdf belirtilirse, sonuç dosyalarının adları şu şekilde olacaktır: c:/dir/page1.pdf, c:/dir/page2.pdf vb. |

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)