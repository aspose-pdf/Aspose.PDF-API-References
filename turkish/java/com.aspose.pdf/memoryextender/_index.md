---
title: "MemoryExtender"
linktitle: "MemoryExtender"
second_title: "Aspose.PDF for Java API Referansı"
description: "MemoryExtender sınıfını temsil eder. Sınırlı yığın belleğine sahip bir sistemde büyük dosyalar kullanılırken, geçici takas belleği olarak disk alanı kullanılabilir."
type: docs
weight: 3020
url: /tr/java/com.aspose.pdf/memoryextender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MemoryExtender

```
public class MemoryExtender extends Object
```

MemoryExtender sınıfını temsil eder. Sınırlı yığın belleğine sahip bir sistemde büyük dosyalar kullanılırken, geçici takas belleği olarak disk alanı kullanılabilir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MemoryExtender](#MemoryExtender--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCallBackPageImage](#getCallBackPageImage--) | Özel önbellek analizörünü al. |
| [getElementRenderingTimeout](#getElementRenderingTimeout--) | Sayfadan görüntüye dönüşümde kullanılan tek öğenin işlenmesi için azami süre. Varsayılan değer 10000 milisaniyedir. Yalnızca isSkipHeavyContentEnabled() == true olduğunda kullanılır. |
| [isEnabledMultiPageImageCache](#isEnabledMultiPageImageCache--) | EnabledMultiPageImageCache alanının durumunu al. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault--) | OptimizedMemoryStream'i varsayılan bellek depolama alanı olarak kullanma etkinleştirildi. 2 GB'den büyük belgelerle çalışmak için gereklidir. Varsayılan değer FALSE'tur. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault-boolean-) | OptimizedMemoryStream'i varsayılan bellek depolama alanı olarak kullanma etkinleştirildi. 2 GB'den büyük belgelerle çalışmak için gereklidir. Varsayılan değer FALSE'tur. |
| [isSkipHeavyContentEnabled](#isSkipHeavyContentEnabled--) | Yığın belleği yetersiz olduğunda yüksek bellek tüketen nesneleri atlama etkinleştirildi. Varsayılan değer FALSE'tur. |
| [isSwapEnabled](#isSwapEnabled--) | Disk alanını geçici takas belleği olarak kullanma etkinleştirildi. Varsayılan değer FALSE'tur. |
| [isTryToCreateFolderIfAbsent](#isTryToCreateFolderIfAbsent--) | Eksik klasörlerin otomatik olarak oluşturulup oluşturulmayacağını gösteren bir değer alır. <p>Eğer {@code true} olarak ayarlanırsa, yolla kaydeden Aspose yöntemleri hedef klasör yapısı mevcut değilse oluşturmaya çalışır. <p>Varsayılan değer {@code false}'tur. |
| [setCallBackPageImage](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | Yeni özel önbellek analizörünü uygula. |
| [setElementRenderingTimeout](#setElementRenderingTimeout-int-) | Sayfadan görüntüye dönüşümde kullanılan tek öğenin işlenmesi için azami süre. Varsayılan değer 10000 milisaniyedir. Yalnızca isSkipHeavyContentEnabled() == true olduğunda kullanılır. |
| [setEnableMultiPageCache](#setEnableMultiPageCache-boolean-) | EnabledMultiPageImageCache alanı için yeni durumu ayarla. |
| [setSkipHeavyContentEnabled](#setSkipHeavyContentEnabled-boolean-) | Yığın belleği yetersiz olduğunda yüksek bellek tüketen nesneleri atlamayı etkinleştirmek için bayrağı ayarla. |
| [setSwapEnabled](#setSwapEnabled-boolean-) | Disk alanının geçici takas belleği olarak kullanılmasını etkinleştirip etkinleştirmeyeceğini belirten bayrağı ayarlayın. |
| [setTryToCreateFolderIfAbsent](#setTryToCreateFolderIfAbsent-boolean-) | Eksik klasörlerin otomatik olarak oluşturulup oluşturulmayacağını gösteren bir değer ayarlar. <p>Eğer {@code true} olarak ayarlanırsa, yol ile kaydeden Aspose yöntemleri hedef klasör yapısı mevcut değilse oluşturmaya çalışacaktır. <p>Varsayılan değer {@code false}. |

### MemoryExtender {#MemoryExtender--}
```
public MemoryExtender()
```



### getCallBackPageImage {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```

Özel önbellek analizörünü al.

**Returns:**
CallBackPageImage nesnesi

### getElementRenderingTimeout {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```

Sayfadan görüntüye dönüşümde kullanılan tek öğenin işlenmesi için azami süre. Varsayılan değer 10000 milisaniyedir. Yalnızca isSkipHeavyContentEnabled() == true olduğunda kullanılır.

**Returns:**
int değer Milisaniye sayısı

### isEnabledMultiPageImageCache {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```

EnabledMultiPageImageCache alanının durumunu al.

**Returns:**
boolean değer

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```

OptimizedMemoryStream'i varsayılan bellek depolama alanı olarak kullanma etkinleştirildi. 2 GB'den büyük belgelerle çalışmak için gereklidir. Varsayılan değer FALSE'tur.

**Returns:**
boolean değer

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```

OptimizedMemoryStream'i varsayılan bellek depolama alanı olarak kullanma etkinleştirildi. 2 GB'den büyük belgelerle çalışmak için gereklidir. Varsayılan değer FALSE'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### isSkipHeavyContentEnabled {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```

Yığın belleği yetersiz olduğunda yüksek bellek tüketen nesneleri atlama etkinleştirildi. Varsayılan değer FALSE'tur.

**Returns:**
boolean değer

### isSwapEnabled {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```

Disk alanını geçici takas belleği olarak kullanma etkinleştirildi. Varsayılan değer FALSE'tur.

**Returns:**
boolean değer

### isTryToCreateFolderIfAbsent {#isTryToCreateFolderIfAbsent--}
```
public static boolean isTryToCreateFolderIfAbsent()
```

Eksik klasörlerin otomatik olarak oluşturulup oluşturulmayacağını gösteren bir değer alır. <p>Eğer {@code true} olarak ayarlanırsa, yolla kaydeden Aspose yöntemleri hedef klasör yapısı mevcut değilse oluşturmaya çalışır. <p>Varsayılan değer {@code false}'tur.

**Returns:**
boolean değer

### setCallBackPageImage {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
Yeni özel önbellek analizörünü uygula.

### setElementRenderingTimeout {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```

Sayfadan görüntüye dönüşümde kullanılan tek öğenin işlenmesi için azami süre. Varsayılan değer 10000 milisaniyedir. Yalnızca isSkipHeavyContentEnabled() == true olduğunda kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer Milisaniye sayısı |

### setEnableMultiPageCache {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```

EnabledMultiPageImageCache alanı için yeni durumu ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| enableMultiPageImageCache_ |  | boolean değer |

### setSkipHeavyContentEnabled {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```

Yığın belleği yetersiz olduğunda yüksek bellek tüketen nesneleri atlamayı etkinleştirmek için bayrağı ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSwapEnabled {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```

Disk alanının geçici takas belleği olarak kullanılmasını etkinleştirip etkinleştirmeyeceğini belirten bayrağı ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setTryToCreateFolderIfAbsent {#setTryToCreateFolderIfAbsent-boolean-}
```
public static void setTryToCreateFolderIfAbsent(boolean value)
```

Eksik klasörlerin otomatik olarak oluşturulup oluşturulmayacağını gösteren bir değer ayarlar. <p>Eğer {@code true} olarak ayarlanırsa, yol ile kaydeden Aspose yöntemleri hedef klasör yapısı mevcut değilse oluşturmaya çalışacaktır. <p>Varsayılan değer {@code false}.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
