---
title: PdfPageEditor.GetPageSize
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor metodu. Belirtilen sayfanın boyutunu döndürür
type: docs
weight: 160
url: /tr/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize metodu

Belirtilen sayfanın boyutunu döndürür.

```csharp
public PageSize GetPageSize(int page)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Int32 | Sayfa indeksi. Belge sayfaları 1'den başlayarak numaralandırılır. |

### Dönüş Değeri

Sonuç, PageSize örneğidir. Sayfa genişliği ve yüksekliğini almak için döndürülen nesnenin Width ve Height özelliklerini kullanın.

## Örnekler

Aşağıdaki örnek, GetPageSize metodunun kullanımını göstermektedir:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfPageEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)