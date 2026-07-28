---
title: "EpubLoadOptions"
linktitle: "EpubLoadOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "EPUB dosyasını pdf belgesine yükleme/içe aktarma seçeneklerini içerir."
type: docs
weight: 1220
url: /tr/java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.EpubLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.EpubLoadOptions

```
public final class EpubLoadOptions extends LoadOptions
```

EPUB dosyasını pdf belgesine yükleme/içe aktarma seçeneklerini içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EpubLoadOptions](#EpubLoadOptions--) | EPUB dosyasını pdf belgesine dönüştürmek için varsayılan yükleme seçeneklerini oluşturur. Varsayılan pdf sayfa boyutu - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](#EpubLoadOptions-java.awt.geom.Dimension2D-) | EPUB dosyasını pdf belgesine dönüştürmek için varsayılan yükleme seçeneklerini oluşturur. Varsayılan pdf sayfa boyutu - A4 300dpi 2480 X 3508. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCustomCss](#getCustomCss--) | Epub belgesi açılırken uygulanacak özel Css'yi alır veya ayarlar. |
| [getEngineType](#getEngineType--) | EPUB'tan PDF'ye dönüşüm için motor tipini seçin. Varsayılan EngineType.NEW'dir. |
| [getMargin](#getMargin--) | Kenar boşluğu bilgilerini temsil eden nesneye referans alır. |
| [getMarginsAreaUsageMode](#getMarginsAreaUsageMode--) | Kenar boşluğu alanının kullanım modunu temsil eder - içe aktarılan belgenin CSS talimatlarının (varsa) kenar boşluğu kullanımına ilişkin işlenmesini tanımlar. |
| [getPageSize](#getPageSize--) | İçe aktarma için çıktı sayfa boyutunu alır. |
| [getPageSizeAdjustmentMode](#getPageSizeAdjustmentMode--) | DİKKAT! Özellik uygulanmış ancak örnek belge için OSHARED katmanında ortaya çıkan engelleyici bir sorun nedeniyle henüz genel API'ye eklenmemiştir. Dönüşüm sırasında sayfa boyutunun kullanım modunu temsil eder. HTML, EPUB vb. formatlar genellikle akış tasarımına sahiptir, bu nedenle gerekli sayfa boyutuna sığdırılmasına izin verir. Ancak bazen içerik, gerekli sayfa boyutuna yerleştirilemeyecek şekilde yatay konumlar veya boyutlar belirler. Bu gibi durumlarda ne yapılması gerektiği tanımlanabilir (ör. içerik boyutu, sonuç PDF belgesinin başlangıç sayfa boyutuna uymadığında). |
| [setCustomCss](#setCustomCss-java.lang.String-) | Epub belgesi açılırken uygulanacak özel Css'yi alır veya ayarlar. |
| [setEngineType](#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-) | EPUB'tan PDF'ye dönüşüm için motor tipini seçin. Varsayılan EngineType.NEW'dir. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Kenar boşluğu bilgilerini temsil eden nesneye referans alır. |
| [setMarginsAreaUsageMode](#setMarginsAreaUsageMode-int-) | Kenar boşluğu alanının kullanım modunu temsil eder - içe aktarılan belgenin CSS talimatlarının (varsa) kenar boşluğu kullanımına ilişkin işlenmesini tanımlar. |
| [setPageSizeAdjustmentMode](#setPageSizeAdjustmentMode-int-) | DİKKAT! Özellik uygulanmış ancak örnek belge için OSHARED katmanında ortaya çıkan engelleyici bir sorun nedeniyle henüz genel API'ye eklenmemiştir. Dönüşüm sırasında sayfa boyutunun kullanım modunu temsil eder. HTML, EPUB vb. formatlar genellikle akış tasarımına sahiptir, bu nedenle gerekli sayfa boyutuna sığdırılmasına izin verir. Ancak bazen içerik, gerekli sayfa boyutuna yerleştirilemeyecek şekilde yatay konumlar veya boyutlar belirler. Bu gibi durumlarda ne yapılması gerektiği tanımlanabilir (ör. içerik boyutu, sonuç PDF belgesinin başlangıç sayfa boyutuna uymadığında). |

### EpubLoadOptions {#EpubLoadOptions--}
```
public EpubLoadOptions()
```

EPUB dosyasını pdf belgesine dönüştürmek için varsayılan yükleme seçeneklerini oluşturur. Varsayılan pdf sayfa boyutu - A4 300dpi 2480 X 3508.

### EpubLoadOptions {#EpubLoadOptions-java.awt.geom.Dimension2D-}
EPUB dosyasını pdf belgesine dönüştürmek için varsayılan yükleme seçeneklerini oluşturur. Varsayılan pdf sayfa boyutu - A4 300dpi 2480 X 3508.

### getCustomCss {#getCustomCss--}
```
public final String getCustomCss()
```

Epub belgesi açılırken uygulanacak özel Css'yi alır veya ayarlar.

**Returns:**
String değeri

### getEngineType {#getEngineType--}
```
public EpubLoadOptions.EngineType getEngineType()
```

EPUB'tan PDF'ye dönüşüm için motor tipini seçin. Varsayılan EngineType.NEW'dir.

**Returns:**
EngineType öğesi

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Kenar boşluğu bilgilerini temsil eden nesneye referans alır.

**Returns:**
MarginInfo nesnesi

### getMarginsAreaUsageMode {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```

Kenar boşluğu alanının kullanım modunu temsil eder - içe aktarılan belgenin CSS talimatlarının (varsa) kenar boşluğu kullanımına ilişkin işlenmesini tanımlar.

**Returns:**
MarginsAreaUsageModes değeri @see MarginsAreaUsageModes

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

İçe aktarma için çıktı sayfa boyutunu alır.

**Returns:**
Dimension2D nesnesi

### getPageSizeAdjustmentMode {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```

DİKKAT! Özellik uygulanmış ancak örnek belge için OSHARED katmanında ortaya çıkan engelleyici bir sorun nedeniyle henüz genel API'ye eklenmemiştir. Dönüşüm sırasında sayfa boyutunun kullanım modunu temsil eder. HTML, EPUB vb. formatlar genellikle akış tasarımına sahiptir, bu nedenle gerekli sayfa boyutuna sığdırılmasına izin verir. Ancak bazen içerik, gerekli sayfa boyutuna yerleştirilemeyecek şekilde yatay konumlar veya boyutlar belirler. Bu gibi durumlarda ne yapılması gerektiği tanımlanabilir (ör. içerik boyutu, sonuç PDF belgesinin başlangıç sayfa boyutuna uymadığında).

**Returns:**
PageSizeAdjustmentModes değeri @see PageSizeAdjustmentModes

### setCustomCss {#setCustomCss-java.lang.String-}
Epub belgesi açılırken uygulanacak özel Css'yi alır veya ayarlar.

### setEngineType {#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-}
EPUB'tan PDF'ye dönüşüm için motor tipini seçin. Varsayılan EngineType.NEW'dir.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Kenar boşluğu bilgilerini temsil eden nesneye referans alır.

### setMarginsAreaUsageMode {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```

Kenar boşluğu alanının kullanım modunu temsil eder - içe aktarılan belgenin CSS talimatlarının (varsa) kenar boşluğu kullanımına ilişkin işlenmesini tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| marginsAreaUsageMode |  | MarginsAreaUsageModes değeri @see MarginsAreaUsageModes |

### setPageSizeAdjustmentMode {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```

DİKKAT! Özellik uygulanmış ancak örnek belge için OSHARED katmanında ortaya çıkan engelleyici bir sorun nedeniyle henüz genel API'ye eklenmemiştir. Dönüşüm sırasında sayfa boyutunun kullanım modunu temsil eder. HTML, EPUB vb. formatlar genellikle akış tasarımına sahiptir, bu nedenle gerekli sayfa boyutuna sığdırılmasına izin verir. Ancak bazen içerik, gerekli sayfa boyutuna yerleştirilemeyecek şekilde yatay konumlar veya boyutlar belirler. Bu gibi durumlarda ne yapılması gerektiği tanımlanabilir (ör. içerik boyutu, sonuç PDF belgesinin başlangıç sayfa boyutuna uymadığında).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageSizeAdjustmentMode |  | PageSizeAdjustmentModes değeri @see PageSizeAdjustmentModes |
