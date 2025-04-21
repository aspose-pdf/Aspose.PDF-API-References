---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes enum. Dönüştürülen PDF, raster görüntüler içerebilir - .png, .jpeg vb. Bu enum, PDF'nin HTML'ye dönüştürülmesi sırasında raster görüntülerin nasıl işleneceğini tanımlar.
type: docs
weight: 5720
url: /tr/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumerasyonu

Dönüştürülen PDF, raster görüntüler içerebilir (.png, *.jpeg vb.). Bu enum, PDF'nin HTML'ye dönüştürülmesi sırasında raster görüntülerin nasıl işleneceğini tanımlar.

```csharp
public enum RasterImagesSavingModes
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | Her bir ayrı raster dosya için sarıcı SVG görüntüsü oluşturulacak ve raster görüntü, o SVG görüntüsüne Base64 kodlu dizeler olarak gömülecektir. |
| AsExternalPngFilesReferencedViaSvg | `1` | Ayrı raster görüntüler PNG dosyaları olarak ayrı tutulacak, ancak sarıcı SVG görüntüleri aracılığıyla referans verilecektir; yani her raster görüntü için bir PNG dosyası ve bir SVG oluşturulacak ve bu SVG'ler ilgili PNG dosyasına bağlantılar içerecektir. |
| AsEmbeddedPartsOfPngPageBackground | `2` | Her sonuç sayfası için bir büyük PNG arka plan dosyası oluşturulacaktır. Raster görüntüler bu dosyaya gömülecek ve o görüntünün bölgeleri olarak işlenecektir. Her görüntü için dış PNG dosyaları oluşturulmayacak, yalnızca sayfa başına bir PNG dosyası dönüşüm sonuç dosyası setinde bulunacaktır. |
| DontSave | `3` | Sabit Düzen için görüntüleri kaydetmeyin. |

### Ayrıca Bakınız

* sınıf [HtmlSaveOptions](../htmlsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)