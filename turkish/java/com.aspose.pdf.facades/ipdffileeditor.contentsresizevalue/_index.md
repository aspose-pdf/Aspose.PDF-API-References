---
title: "IPdfFileEditor.ContentsResizeValue"
linktitle: "IPdfFileEditor.ContentsResizeValue"
second_title: "Aspose.PDF for Java API Referansı"
description: "Kenar boşluğu veya içerik boyutunun, varsayılan uzay birimlerinin yüzdesi olarak belirtilen değeri. Bu sınıf ContentsResizeParameters içinde kullanılır."
type: docs
weight: 310
url: /tr/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue

```
public static class IPdfFileEditor.ContentsResizeValue extends Object
```

Kenar boşluğu veya içerik boyutunun, varsayılan uzay birimlerinin yüzdesi olarak belirtilen değeri. Bu sınıf ContentsResizeParameters içinde kullanılır.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [auto](#auto--) | Otomatik olarak hesaplanan değeri başlatır. |
| [getValue](#getValue--) | Belirtilen değeri alır. Değer birimlerini almak için Unit özelliğini kullan. |
| [isPercent](#isPercent--) | Değer yüzde olarak ifade edildiyse true, varsayılan birimlerde ifade edildiyse False döndürür. |
| [percents](#percents-double-) | Değeri yüzde olarak başlatır. |
| [setPercentValue](#setPercentValue-double-) | Değeri sayfa boyutunun yüzde olarak ayarlar. |
| [setUnitValue](#setUnitValue-double-) | Değeri varsayılan uzay birimlerinde ayarlar. |
| [units](#units-double-) | Değeri varsayılan uzay birimlerinde başlatır. |

### auto {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```

Otomatik olarak hesaplanan değeri başlatır.

**Returns:**
Yeni değer örneği.

### getValue {#getValue--}
```
public final double getValue()
```

Belirtilen değeri alır. Değer birimlerini almak için Unit özelliğini kullan.

**Returns:**
double değer

### isPercent {#isPercent--}
```
public final boolean isPercent()
```

Değer yüzde olarak ifade edildiyse true, varsayılan birimlerde ifade edildiyse False döndürür.

**Returns:**
boolean değer

### percents {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```

Değeri yüzde olarak başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Yüzde cinsinden değer. |

**Returns:**
Yeni değer örneği.

### setPercentValue {#setPercentValue-double-}
```
public final void setPercentValue(double value)
```

Değeri sayfa boyutunun yüzde olarak ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setUnitValue {#setUnitValue-double-}
```
public final void setUnitValue(double value)
```

Değeri varsayılan uzay birimlerinde ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### units {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```

Değeri varsayılan uzay birimlerinde başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Birim cinsinden değer. |

**Returns:**
Yeni değer örneği.
