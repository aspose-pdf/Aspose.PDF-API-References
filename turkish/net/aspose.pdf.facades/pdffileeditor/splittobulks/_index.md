---
title: PdfFileEditor.SplitToBulks
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfa veya çok sayfa olabilir.
type: docs
weight: 350
url: /tr/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfa veya çok sayfa olabilir.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Girdi PDF dosyası. |
| numberOfPage | Int32[][] | Belgenin başlangıç ve bitiş sayfalarını içeren çift elemanlardan oluşan dizi. |

### Dönüş Değeri

Çıktı PDF akışları, her akış bir PDF belgesini tamponlar.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfa veya çok sayfa olabilir.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Girdi PDF akışı. |
| numberOfPage | Int32[][] | Her belgenin başlangıç sayfası ve bitiş sayfası. |

### Dönüş Değeri

Çıktı PDF akışları, her akış bir PDF belgesini tamponlar.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)