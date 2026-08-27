---
title: "IPdfFileEditor.ContentsResizeParameters"
linktitle: "IPdfFileEditor.ContentsResizeParameters"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfa yeniden boyutlandırma parametrelerini belirten sınıf. Aşağıdaki parametrelerin ayarlanmasına izin verir: Sonuç sayfasının boyutu (genişlik, yükseklik) varsayılan uzay birimlerinde veya başlangıç sayfalarının yüzdesi olarak."
type: docs
weight: 300
url: /tr/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters

```
public static class IPdfFileEditor.ContentsResizeParameters extends Object
```

Sayfa yeniden boyutlandırma parametrelerini belirlemek için sınıf. Aşağıdaki parametrelerin ayarlanmasına izin verir: Sonuç sayfasının boyutu (genişlik, yükseklik) varsayılan uzay birimlerinde veya başlangıç sayfasının boyutunun yüzdesi olarak; Sol, üst, alt ve sağ kenar boşlukları varsayılan uzay birimlerinde veya başlangıç sayfasının boyutunun yüzdesi olarak; Bazı değerler otomatik hesaplama için null bırakılabilir. Bu değerler, açıkça belirtilen değerlerin hesaplanmasından sonra sayfanın kalan boyutundan hesaplanır. Örneğin: sayfa genişliği = 100 ve yeni sayfa genişliği 60 birim olarak belirtilirse, sol ve sağ kenar boşlukları otomatik olarak hesaplanır: (100 - 60) / 2 = 15. Bu sınıf ResizeContents metodunda kullanılır.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ContentsResizeParameters](#ContentsResizeParameters--) | Tüm değerlerin \"auto\" olarak ayarlandığı yeniden boyutlandırma parametrelerini oluşturur. Gerekirse daha sonra kenar boşlukları ve içerik boyutu belirtilebilir. |
| [ContentsResizeParameters](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Tüm değerlerin \"auto\" olarak ayarlandığı yeniden boyutlandırma parametrelerini oluşturur. Gerekirse daha sonra kenar boşlukları ve içerik boyutu belirtilebilir. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [contentSize](#contentSize-double-double-) | Belirtilen içerik boyutuyla yeniden boyutlandırma parametreleri oluşturur. |
| [contentSizePercent](#contentSizePercent-double-double-) | İlk sayfa boyutunun yüzdesi olarak belirtilen içerik boyutuyla yeniden boyutlandırma parametreleri oluşturur. Kenar boşlukları otomatik olarak hesaplanır. |
| [getBottomMargin](#getBottomMargin--) | Sonuç sayfasındaki alt kenar boşluğunu alır veya ayarlar. |
| [getContentsHeight](#getContentsHeight--) | Sonuç sayfasındaki kaynak sayfanın içerik yüksekliğini alır veya ayarlar. |
| [getContentsWidth](#getContentsWidth--) | Sonuç sayfasındaki kaynak sayfanın içerik genişliğini alır veya ayarlar. |
| [getLeftMargin](#getLeftMargin--) | Sonuç sayfasındaki sol kenar boşluğunu alır veya ayarlar. |
| [getRightMargin](#getRightMargin--) | Sonuç sayfasındaki sağ kenar boşluğunu alır veya ayarlar. |
| [getTopMargin](#getTopMargin--) | Sonuç sayfasındaki üst kenar boşluğunu alır veya ayarlar. |
| [isChangeMediaBox](#isChangeMediaBox--) | Bir PDF sayfasının MediaBox'ını yeniden boyutlandırma işlemi sırasında ayarlayıp ayarlamayacağını alır. Varsayılan değer {@code false}dır. Bu parametrenin ayarlanması, yeniden boyutlandırma sırasında MediaBox'ın CropBox değerine uymasını sağlar. |
| [margins](#margins-double-double-double-double-) | Belirtilen kenar boşlukları değeriyle yeniden boyutlandırma parametreleri oluşturur. İçerik boyutu otomatik olarak hesaplanır. |
| [marginsPercent](#marginsPercent-double-double-double-double-) | Yeniden boyutlandırma parametrelerini oluşturur. Kenar boşlukları, başlangıç sayfa boyutunun yüzde cinsinden belirtilir. |
| [pageResize](#pageResize-double-double-) | Sayfa yeniden boyutlandırması için yeniden boyutlandırma parametrelerini oluşturur. |
| [pageResizePct](#pageResizePct-double-double-) | Sayfa yeniden boyutlandırması için yeniden boyutlandırma parametrelerini oluşturur. Yeni boyutlar yüzde olarak belirtilir. |
| [setBottomMargin](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Sonuç sayfasındaki alt kenar boşluğunu alır veya ayarlar. |
| [setChangeMediaBox](#setChangeMediaBox-boolean-) | PDF sayfasının MediaBox'ını yeniden boyutlandırma işlemi sırasında ayarlayıp ayarlamama durumunu belirler. Varsayılan değer {@code false}'dur. Bu parametrenin ayarlanması, yeniden boyutlandırma sırasında MediaBox'ın CropBox değerine uymasını sağlar. |
| [setContentsHeight](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Sonuç sayfasındaki kaynak sayfanın içerik yüksekliğini alır veya ayarlar. |
| [setContentsWidth](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Sonuç sayfasındaki kaynak sayfanın içerik genişliğini alır veya ayarlar. |
| [setLeftMargin](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Sonuç sayfasındaki sol kenar boşluğunu alır veya ayarlar. |
| [setRightMargin](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Sonuç sayfasındaki sağ kenar boşluğunu alır veya ayarlar. |
| [setTopMargin](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Sonuç sayfasındaki üst kenar boşluğunu alır veya ayarlar. |

### ContentsResizeParameters {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```

Tüm değerlerin \"auto\" olarak ayarlandığı yeniden boyutlandırma parametrelerini oluşturur. Gerekirse daha sonra kenar boşlukları ve içerik boyutu belirtilebilir.

### ContentsResizeParameters {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Tüm değerlerin \"auto\" olarak ayarlandığı yeniden boyutlandırma parametrelerini oluşturur. Gerekirse daha sonra kenar boşlukları ve içerik boyutu belirtilebilir.

### contentSize {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```

Belirtilen içerik boyutuyla yeniden boyutlandırma parametreleri oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik |  | İçeriklerin yeni genişliği. |
| yükseklik |  | contetns'in yeni yüksekliği. |

**Returns:**
Yeni yeniden boyutlandırma parametrelerini döndürür.

### contentSizePercent {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```

İlk sayfa boyutunun yüzdesi olarak belirtilen içerik boyutuyla yeniden boyutlandırma parametreleri oluşturur. Kenar boşlukları otomatik olarak hesaplanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik |  | Yeni içerik genişliği yüzde olarak. |
| yükseklik |  | Yeni içerik yüksekliği yüzde olarak. |

**Returns:**
Yeni yeniden boyutlandırma parametreleri.

### getBottomMargin {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```

Sonuç sayfasındaki alt kenar boşluğunu alır veya ayarlar.

**Returns:**
ContentsResizeValue nesnesi

### getContentsHeight {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```

Sonuç sayfasındaki kaynak sayfanın içerik yüksekliğini alır veya ayarlar.

**Returns:**
ContentsResizeValue nesnesi

### getContentsWidth {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```

Sonuç sayfasındaki kaynak sayfanın içerik genişliğini alır veya ayarlar.

**Returns:**
ContentsResizeValue nesnesi

### getLeftMargin {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```

Sonuç sayfasındaki sol kenar boşluğunu alır veya ayarlar.

**Returns:**
ContentsResizeValue nesnesi

### getRightMargin {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```

Sonuç sayfasındaki sağ kenar boşluğunu alır veya ayarlar.

**Returns:**
ContentsResizeValue nesnesi

### getTopMargin {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```

Sonuç sayfasındaki üst kenar boşluğunu alır veya ayarlar.

**Returns:**
ContentsResizeValue nesnesi

### isChangeMediaBox {#isChangeMediaBox--}
```
public final boolean isChangeMediaBox()
```

Bir PDF sayfasının MediaBox'ını yeniden boyutlandırma işlemi sırasında ayarlayıp ayarlamayacağını alır. Varsayılan değer {@code false}dır. Bu parametrenin ayarlanması, yeniden boyutlandırma sırasında MediaBox'ın CropBox değerine uymasını sağlar.

**Returns:**
PDF sayfasının MediaBox'ını yeniden boyutlandırma işlemi sırasında ayarlayıp ayarlamama.

### margins {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```

Belirtilen kenar boşlukları değeriyle yeniden boyutlandırma parametreleri oluşturur. İçerik boyutu otomatik olarak hesaplanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol |  | Sol kenar boşluğu. |
| sağ |  | Sağ kenar boşluğu. |
| üst |  | Üst kenar boşluğu. |
| alt |  | Alt kenar boşluğu. |

**Returns:**
Oluşturulan yeniden boyutlandırma parametreleri.

### marginsPercent {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```

Yeniden boyutlandırma parametrelerini oluşturur. Kenar boşlukları, başlangıç sayfa boyutunun yüzde cinsinden belirtilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol |  | Sol kenar boşluğu (sayfa genişliğinin yüzde cinsinden). |
| sağ |  | Sağ kenar boşluğu (sayfa yüksekliğinin yüzde cinsinden). |
| üst |  | Üst kenar boşluğu (sayfa yüksekliğinin yüzde cinsinden). |
| alt |  | Alt kenar boşluğu (sayfa yüksekliğinin yüzde cinsinden). |

**Returns:**
Yeni yeniden boyutlandırma parametrelerini döndürür.

### pageResize {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```

Sayfa yeniden boyutlandırması için yeniden boyutlandırma parametrelerini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik |  | Yeni sayfa genişliği birim olarak. |
| yükseklik |  | Yeni sayfa yüksekliği birim olarak. |

**Returns:**
Yeni yeniden boyutlandırma paramteres.

### pageResizePct {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```

Sayfa yeniden boyutlandırması için yeniden boyutlandırma parametrelerini oluşturur. Yeni boyutlar yüzde olarak belirtilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| widthPct |  | Yeni sayfa genişliği yüzde olarak. |
| heightPct |  | Yeni sayfa yüksekliği yüzde olarak. |

**Returns:**
Yeni yeniden boyutlandırma paramteres.

### setBottomMargin {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Sonuç sayfasındaki alt kenar boşluğunu alır veya ayarlar.

### setChangeMediaBox {#setChangeMediaBox-boolean-}
```
public final void setChangeMediaBox(boolean value)
```

PDF sayfasının MediaBox'ını yeniden boyutlandırma işlemi sırasında ayarlayıp ayarlamama durumunu belirler. Varsayılan değer {@code false}'dur. Bu parametrenin ayarlanması, yeniden boyutlandırma sırasında MediaBox'ın CropBox değerine uymasını sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | PDF sayfasının MediaBox'ını yeniden boyutlandırma işlemi sırasında ayarlayıp ayarlamama. |

### setContentsHeight {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Sonuç sayfasındaki kaynak sayfanın içerik yüksekliğini alır veya ayarlar.

### setContentsWidth {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Sonuç sayfasındaki kaynak sayfanın içerik genişliğini alır veya ayarlar.

### setLeftMargin {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Sonuç sayfasındaki sol kenar boşluğunu alır veya ayarlar.

### setRightMargin {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Sonuç sayfasındaki sağ kenar boşluğunu alır veya ayarlar.

### setTopMargin {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Sonuç sayfasındaki üst kenar boşluğunu alır veya ayarlar.
