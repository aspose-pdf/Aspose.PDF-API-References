---
title: "HtmlSaveOptions.RasterImagesSavingModes"
linktitle: "HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Aspose.PDF for Java API Referansı"
description: "Dönüştürülmüş PDF raster görüntüler (.png, *.jpeg vb.) içerebilir. Bu enum, raster görüntülerin PDF'ten HTML'e dönüşüm sırasında nasıl işleneceğini tanımlayan yöntemleri belirler."
type: docs
weight: 2140
url: /tr/java/com.aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes

```
public static final class HtmlSaveOptions.RasterImagesSavingModes extends com.aspose.ms.System.Enum
```

Dönüştürülmüş PDF raster görüntüler (.png, *.jpeg vb.) içerebilir. Bu enum, raster görüntülerin PDF'ten HTML'e dönüşüm sırasında nasıl işleneceğini tanımlayan yöntemleri belirler.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [AsEmbeddedPartsOfPngPageBackground](#AsEmbeddedPartsOfPngPageBackground) | Her sonuç sayfası için bir büyük PNG arka plan dosyası oluşturulacak. Raster görüntüler bu dosyaya gömülecek ve görüntünün bölgeleri olarak işlenecek. Her görüntü için dış PNG dosyaları oluşturulmayacak, yalnızca sayfa başına bir PNG dosyası dönüşüm sonuç dosyaları kümesinde bulunacak. |
| [AsExternalPngFilesReferencedViaSvg](#AsExternalPngFilesReferencedViaSvg) | Ayrı raster görüntüler PNG dosyaları olarak ayrı tutulacak ancak sarmalayıcı SVG görüntüleri aracılığıyla referans verilecek, yani her raster görüntü için bir PNG dosyası ve bir SVG oluşturulacak ve bu SVG'lerin her biri ilgili PNG dosyasına bağlantılar içerecek. |
| [AsPngImagesEmbeddedIntoSvg](#AsPngImagesEmbeddedIntoSvg) | Her ayrı raster dosya için bir sarmalayıcı SVG görüntüsü oluşturulacak ve raster görüntü Base64 kodlu dizgeler olarak o SVG görüntüsüne gömülecek. |
| [DontSave](#DontSave) | Sabit Düzen için görüntüleri kaydetme. |

### AsEmbeddedPartsOfPngPageBackground {#AsEmbeddedPartsOfPngPageBackground}
```
public static final int AsEmbeddedPartsOfPngPageBackground
```

Her sonuç sayfası için bir büyük PNG arka plan dosyası oluşturulacak. Raster görüntüler bu dosyaya gömülecek ve görüntünün bölgeleri olarak işlenecek. Her görüntü için dış PNG dosyaları oluşturulmayacak, yalnızca sayfa başına bir PNG dosyası dönüşüm sonuç dosyaları kümesinde bulunacak.

### AsExternalPngFilesReferencedViaSvg {#AsExternalPngFilesReferencedViaSvg}
```
public static final int AsExternalPngFilesReferencedViaSvg
```

Ayrı raster görüntüler PNG dosyaları olarak ayrı tutulacak ancak sarmalayıcı SVG görüntüleri aracılığıyla referans verilecek, yani her raster görüntü için bir PNG dosyası ve bir SVG oluşturulacak ve bu SVG'lerin her biri ilgili PNG dosyasına bağlantılar içerecek.

### AsPngImagesEmbeddedIntoSvg {#AsPngImagesEmbeddedIntoSvg}
```
public static final int AsPngImagesEmbeddedIntoSvg
```

Her ayrı raster dosya için bir sarmalayıcı SVG görüntüsü oluşturulacak ve raster görüntü Base64 kodlu dizgeler olarak o SVG görüntüsüne gömülecek.

### DontSave {#DontSave}
```
public static final int DontSave
```

Sabit Düzen için görüntüleri kaydetme.
