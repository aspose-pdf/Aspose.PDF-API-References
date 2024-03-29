---
title: HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Referansı
description: Dönüştürülen PDF tarama görüntüleri içerebilir .png .jpeg vb. Bu numaralandırma PDFnin HTMLye dönüştürülmesi sırasında raster görüntülerin nasıl işlenebileceğinin yöntemlerini tanımlar
type: docs
weight: 3590
url: /tr/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

Dönüştürülen PDF, tarama görüntüleri içerebilir (.png, *.jpeg vb.) Bu numaralandırma, PDF'nin HTML'ye dönüştürülmesi sırasında raster görüntülerin nasıl işlenebileceğinin yöntemlerini tanımlar

```csharp
public enum RasterImagesSavingModes
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | Her farklı tarama dosyası için sarmalayıcı SVG görüntüsü oluşturulacak, ve tarama görüntüsü bu SVG görüntüsüne Base64 kodlu dizeler olarak gömülecek |
| AsExternalPngFilesReferencedViaSvg | `1` | farklı tarama görüntüleri PNG dosyaları olarak ayrılacak, ancak SVG görüntülerinin kaydırılması yoluyla referans alınacaktır, yani, her raster görüntü için bir PNG dosyası ve bir SVG oluşturulacak, ve bu tür SVG'lerin her biri, ilgili PNG dosyasına bağlantılar içerecektir |
| AsEmbeddedPartsOfPngPageBackground | `2` | Her sonuç sayfası için büyük bir PNG arka plan dosyası oluşturulacak. Raster görüntüler o dosyaya yerleştirilecek ve o görüntünün bölgeleri olarak işlenecek. Her görüntü için harici PNG dosyası oluşturulmayacak, sayfa başına yalnızca bir PNG dosyası dosyaların dönüştürme sonuç kümesinde bulunacaktır. |

### Ayrıca bakınız

* class [HtmlSaveOptions](../htmlsaveoptions)
* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
