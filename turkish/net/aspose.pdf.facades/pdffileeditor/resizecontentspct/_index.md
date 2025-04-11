---
title: PdfFileEditor.ResizeContentsPct
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfa içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu yüzde olarak belirtilir.
type: docs
weight: 330
url: /tr/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfa içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu yüzde olarak belirtilir.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | Stream | Kaynak belgeyi içeren akış. |
| destination | Stream | Sonuç belgesinin kaydedileceği akış. |
| pages | Int32[] | Sayfa indekslerinin dizisi. Null ise tüm belge sayfaları işlenecektir. |
| newWidth | Double | Sayfa içeriğinin yeni genişliği yüzde olarak. |
| newHeight | Double | Sayfa içeriğinin yeni yüksekliği yüzde olarak. |

### Dönüş Değeri

Başarıyla yeniden boyutlandırıldıysa true.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfa içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu yüzde olarak belirtilir.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | String | Kaynak belgeye giden yol. |
| destination | String | Sonuç belgesinin kaydedileceği yol. |
| pages | Int32[] | Sayfa indekslerinin dizisi. Null ise tüm belge sayfaları işlenecektir. |
| newWidth | Double | Sayfa içeriğinin yeni genişliği yüzde olarak. |
| newHeight | Double | Sayfa içeriğinin yeni yüksekliği yüzde olarak. |

### Dönüş Değeri

Yeniden boyutlandırma başarılıysa true.

## Örnekler

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)