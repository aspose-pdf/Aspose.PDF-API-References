---
title: "ImageCompressionOptions"
linktitle: "ImageCompressionOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sınıf, görüntü sıkıştırması için ayarlanmış seçenekleri içerir."
type: docs
weight: 10
url: /tr/java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.ImageCompressionOptions

```
public class ImageCompressionOptions extends Object
```

Sınıf, görüntü sıkıştırması için ayarlanmış seçenekleri içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageCompressionOptions](#ImageCompressionOptions--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEncoding](#getEncoding--) | Görüntüleri depolamak için kullanılan kodlamayı alır veya ayarlar. |
| [getImageQuality](#getImageQuality--) | CompressImages bayrağı kullanıldığında görüntü sıkıştırma seviyesini belirtir. |
| [getMaxResolution](#getMaxResolution--) | Görüntülerin maksimum çözünürlüğünü belirtir. Görüntünün çözünürlüğü daha yüksekse ölçeklendirilecektir. |
| [getResizeImages](#getResizeImages--) | Bu bayrak true olarak ayarlanmış ve CompressImages true ise, görüntü çözünürlüğü belirtilen MaxResolution parametresinden büyükse görüntüler yeniden boyutlandırılacaktır. |
| [getVersion](#getVersion--) | Sıkıştırma algoritmasının sürümü. Olası değerler şunlardır: 1. standart sıkıştırma, 2. hızlı (geliştirilmiş sıkıştırma, standarttan daha hızlıdır ancak tüm görüntüler için uygulanabilir olmayabilir), 3. karışık (daha hızlı algoritma ile sıkıştırılamayan görüntülere standart sıkıştırma uygulanır, bu en iyi sıkıştırmayı sağlayabilir ancak \"fast\" algoritmadan daha yavaştır). \"Fast\" sürümü görüntü yeniden boyutlandırma için uygulanamaz (standart yöntem kullanılacaktır). Varsayılan \"Standard\". |
| [isCompressImages](#isCompressImages--) | Bu bayrak true olarak ayarlanırsa, görüntüler belgede sıkıştırılacaktır. Sıkıştırma seviyesi ImageQuality özelliği ile belirtilir. |
| [setCompressImages](#setCompressImages-boolean-) | Bu bayrak true olarak ayarlanırsa, görüntüler belgede sıkıştırılacaktır. Sıkıştırma seviyesi ImageQuality özelliği ile belirtilir. |
| [setEncoding](#setEncoding-int-) | Görüntüleri depolamak için kullanılan kodlamayı alır veya ayarlar. |
| [setImageQuality](#setImageQuality-int-) | CompressImages bayrağı kullanıldığında görüntü sıkıştırma seviyesini belirtir. |
| [setMaxResolution](#setMaxResolution-int-) | Görüntülerin maksimum çözünürlüğünü belirtir. Görüntünün çözünürlüğü daha yüksekse ölçeklendirilecektir. |
| [setResizeImages](#setResizeImages-boolean-) | Bu bayrak true olarak ayarlanmış ve CompressImages true ise, görüntü çözünürlüğü belirtilen MaxResolution parametresinden büyükse görüntüler yeniden boyutlandırılacaktır. |
| [setVersion](#setVersion-int-) | Sıkıştırma algoritmasının sürümü. Olası değerler şunlardır: 1. standart sıkıştırma, 2. hızlı (geliştirilmiş sıkıştırma, standarttan daha hızlıdır ancak tüm görüntüler için uygulanabilir olmayabilir), 3. karışık (daha hızlı algoritma ile sıkıştırılamayan görüntülere standart sıkıştırma uygulanır, bu en iyi sıkıştırmayı sağlayabilir ancak \"fast\" algoritmadan daha yavaştır). \"Fast\" sürümü görüntü yeniden boyutlandırma için uygulanamaz (standart yöntem kullanılacaktır). Varsayılan \"Standard\". |

### ImageCompressionOptions {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```



### getEncoding {#getEncoding--}
```
public final int getEncoding()
```

Görüntüleri depolamak için kullanılan kodlamayı alır veya ayarlar.

**Returns:**
ImageEncoding öğesi

### getImageQuality {#getImageQuality--}
```
public final int getImageQuality()
```

CompressImages bayrağı kullanıldığında görüntü sıkıştırma seviyesini belirtir.

**Returns:**
int değer

### getMaxResolution {#getMaxResolution--}
```
public final int getMaxResolution()
```

Görüntülerin maksimum çözünürlüğünü belirtir. Görüntünün çözünürlüğü daha yüksekse ölçeklendirilecektir.

**Returns:**
int değer

### getResizeImages {#getResizeImages--}
```
public final boolean getResizeImages()
```

Bu bayrak true olarak ayarlanmış ve CompressImages true ise, görüntü çözünürlüğü belirtilen MaxResolution parametresinden büyükse görüntüler yeniden boyutlandırılacaktır.

**Returns:**
boolean değer

### getVersion {#getVersion--}
```
public final int getVersion()
```

Sıkıştırma algoritmasının sürümü. Olası değerler şunlardır: 1. standart sıkıştırma, 2. hızlı (geliştirilmiş sıkıştırma, standarttan daha hızlıdır ancak tüm görüntüler için uygulanabilir olmayabilir), 3. karışık (daha hızlı algoritma ile sıkıştırılamayan görüntülere standart sıkıştırma uygulanır, bu en iyi sıkıştırmayı sağlayabilir ancak \"fast\" algoritmadan daha yavaştır). \"Fast\" sürümü görüntü yeniden boyutlandırma için uygulanamaz (standart yöntem kullanılacaktır). Varsayılan \"Standard\".

**Returns:**
int değer

### isCompressImages {#isCompressImages--}
```
public final boolean isCompressImages()
```

Bu bayrak true olarak ayarlanırsa, görüntüler belgede sıkıştırılacaktır. Sıkıştırma seviyesi ImageQuality özelliği ile belirtilir.

**Returns:**
boolean değer

### setCompressImages {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```

Bu bayrak true olarak ayarlanırsa, görüntüler belgede sıkıştırılacaktır. Sıkıştırma seviyesi ImageQuality özelliği ile belirtilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setEncoding {#setEncoding-int-}
```
public final void setEncoding(int value)
```

Görüntüleri depolamak için kullanılan kodlamayı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ImageEncoding öğesi |

### setImageQuality {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```

CompressImages bayrağı kullanıldığında görüntü sıkıştırma seviyesini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setMaxResolution {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```

Görüntülerin maksimum çözünürlüğünü belirtir. Görüntünün çözünürlüğü daha yüksekse ölçeklendirilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setResizeImages {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```

Bu bayrak true olarak ayarlanmış ve CompressImages true ise, görüntü çözünürlüğü belirtilen MaxResolution parametresinden büyükse görüntüler yeniden boyutlandırılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setVersion {#setVersion-int-}
```
public final void setVersion(int value)
```

Sıkıştırma algoritmasının sürümü. Olası değerler şunlardır: 1. standart sıkıştırma, 2. hızlı (geliştirilmiş sıkıştırma, standarttan daha hızlıdır ancak tüm görüntüler için uygulanabilir olmayabilir), 3. karışık (daha hızlı algoritma ile sıkıştırılamayan görüntülere standart sıkıştırma uygulanır, bu en iyi sıkıştırmayı sağlayabilir ancak \"fast\" algoritmadan daha yavaştır). \"Fast\" sürümü görüntü yeniden boyutlandırma için uygulanamaz (standart yöntem kullanılacaktır). Varsayılan \"Standard\".

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |
