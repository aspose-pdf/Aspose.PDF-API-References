---
title: "GraphicalPdfComparer"
linktitle: "GraphicalPdfComparer"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgelerini grafiksel olarak karşılaştırmak için bir sınıfı temsil eder. Özellikle grafiksel küçük değişiklikleri aramak için kullanılmalıdır. Metin içeriği değişikliklerini karşılaştırmak için başka bir sınıf kullanın."
type: docs
weight: 10
url: /tr/java/com.aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.GraphicalPdfComparer

```
public class GraphicalPdfComparer extends Object
```

PDF belgelerini grafiksel olarak karşılaştırmak için bir sınıfı temsil eder. Öncelikle grafiksel doğadaki küçük değişiklikleri aramak için kullanılmalıdır. Metin içeriği değişikliklerini karşılaştırmak için diğer PDF karşılaştırma sınıflarını kullanın.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GraphicalPdfComparer](#GraphicalPdfComparer--) | {@link GraphicalPdfComparer} sınıfının bir örneğini oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [compareDocumentsToImages](#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Belgeleri grafiksel olarak karşılaştırır. |
| [compareDocumentsToPdf](#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-) | Belgeleri grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir PDF belgesine yerleştirilir. |
| [comparePagesToImage](#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Sayfaları grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir görüntüye yerleştirilir. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-) | Sayfaları grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir PDF belgesine yerleştirilir. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Sayfaları grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir PDF belgesine yerleştirilir. |
| [getColor](#getColor--) | Değişiklik bayrağı rengini alır ve ayarlar. Varsayılan renk kırmızıdır. |
| [getDifference](#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-) | Sayfa görüntüleri arasındaki farkları alır. Sonuç, karşılaştırılan ilk sayfanın bir görüntüsü ve farkların bir dizisini içerir. |
| [getResolution](#getResolution--) | Oluşturulan görüntülerin çözünürlüğünü alır ve ayarlar. Varsayılan değer 150dpi'dir. |
| [getThreshold](#getThreshold--) | Yüzde olarak eşik değerini alır ve ayarlar. Bu değer, sizin için önemsiz olan küçük değişiklikleri yok saymanıza olanak tanır. Varsayılan değer %0'dır. |
| [setColor](#setColor-com.aspose.pdf.Color-) | Değişiklik bayrağı rengini alır ve ayarlar. Varsayılan renk kırmızıdır. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Oluşturulan görüntülerin çözünürlüğünü alır ve ayarlar. Varsayılan değer 150dpi'dir. |
| [setThreshold](#setThreshold-double-) | Yüzde olarak eşik değerini alır ve ayarlar. Bu değer, sizin için önemsiz olan küçük değişiklikleri yok saymanıza olanak tanır. Varsayılan değer %0'dır. |

### GraphicalPdfComparer {#GraphicalPdfComparer--}
```
public GraphicalPdfComparer()
```

{@link GraphicalPdfComparer} sınıfının bir örneğini oluşturur.

### compareDocumentsToImages {#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
Belgeleri grafiksel olarak karşılaştırır.

### compareDocumentsToPdf {#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-}
Belgeleri grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir PDF belgesine yerleştirilir.

### comparePagesToImage {#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Sayfaları grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir görüntüye yerleştirilir.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-}
Sayfaları grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir PDF belgesine yerleştirilir.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Sayfaları grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir PDF belgesine yerleştirilir.

### getColor {#getColor--}
```
public final Color getColor()
```

Değişiklik bayrağı rengini alır ve ayarlar. Varsayılan renk kırmızıdır.

**Returns:**
Renk örneği

### getDifference {#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-}
Sayfa görüntüleri arasındaki farkları alır. Sonuç, karşılaştırılan ilk sayfanın bir görüntüsü ve farkların bir dizisini içerir.

### getResolution {#getResolution--}
```
public final Resolution getResolution()
```

Oluşturulan görüntülerin çözünürlüğünü alır ve ayarlar. Varsayılan değer 150dpi'dir.

**Returns:**
Çözünürlük örneği

### getThreshold {#getThreshold--}
```
public final double getThreshold()
```

Yüzde olarak eşik değerini alır ve ayarlar. Bu değer, sizin için önemsiz olan küçük değişiklikleri yok saymanıza olanak tanır. Varsayılan değer %0'dır.

**Returns:**
double değer

### setColor {#setColor-com.aspose.pdf.Color-}
Değişiklik bayrağı rengini alır ve ayarlar. Varsayılan renk kırmızıdır.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Oluşturulan görüntülerin çözünürlüğünü alır ve ayarlar. Varsayılan değer 150dpi'dir.

### setThreshold {#setThreshold-double-}
```
public final void setThreshold(double value)
```

Yüzde olarak eşik değerini alır ve ayarlar. Bu değer, sizin için önemsiz olan küçük değişiklikleri yok saymanıza olanak tanır. Varsayılan değer %0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |
