---
title: "OptimizationOptions"
linktitle: "OptimizationOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Belge optimizasyon algoritmasını tanımlayan sınıf. Bu sınıfın bir örneği, OptimizeResources() yönteminin parametresi olarak kullanılabilir."
type: docs
weight: 40
url: /tr/java/com.aspose.pdf.optimization/optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions

```
public class OptimizationOptions extends Object
```

Belge optimizasyon algoritmasını tanımlayan sınıf. Bu sınıfın bir örneği, OptimizeResources() yönteminin parametresi olarak kullanılabilir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [all](#all--) | Tüm seçenekler etkinleştirilmiş bir optimizasyon stratejisi oluşturur. Lütfen yalnızca belgenin işlevselliğini değiştirmeyen seçeneklerin etkinleştirildiğini unutmayın. Örneğin, görüntü sıkıştırma ve yazı tipi gömme kaldırma etkin olmayacaktır (ve manuel olarak eklenebilir). |
| [getCompressAllContentStreams](#getCompressAllContentStreams--) | Eğer {@link} olarak ayarlanırsa, tüm sıkıştırılmamış sayfa içerik akışları {@code Document#OptimizeResources()} sırasında FlateDecode filtresi kullanılarak sıkıştırılır. Varsayılan {@link} geriye dönük uyumluluğu korumaktır. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Belgedeki görüntülerin sıkıştırılıp sıkıştırılmayacağını ve sıkıştırma parametrelerini tanımlayan seçenekler kümesi. |
| [getImageEncoding](#getImageEncoding--) | Kullanılacak görüntü kodlayıcı. |
| [getImageQuality](#getImageQuality--) | CompressIamges bayrağı kullanıldığında görüntü sıkıştırma seviyesini belirtir. |
| [getMaxResoultion](#getMaxResoultion--) | Görüntülerin maksimum çözünürlüğünü belirtir. Görüntü daha yüksek bir çözünürlüğe sahipse ölçeklendirilir. |
| [isAllowReusePageContent](#isAllowReusePageContent--) | Doğruysa, belge eşit sayfalar için optimize edildiğinde sayfa içerikleri yeniden kullanılacaktır. |
| [isCompressImages](#isCompressImages--) | Bu bayrak true olarak ayarlanırsa, görüntüler belgede sıkıştırılır. sıkıştırma seviyesi ImageQuality özelliği ile belirtilir. |
| [isCompressObjects](#isCompressObjects--) | Bu bayrak {@code } olarak ayarlanırsa, Pdf nesneleri Objest Streams içine paketlenir ve pdf dosya boyutunu azaltmak için sıkıştırılır. |
| [isLinkDuplicateStreams](#isLinkDuplicateStreams--) | Bu bayrak true olarak ayarlanırsa, Resource streams analiz edilir. Eğer yinelenen akışlar bulunursa (yani akış içeriği eşitse), bu akışlar tek bir nesne olarak depolanır. Bu, bazı durumlarda belge boyutunun azalmasını sağlar (örneğin, aynı belge birden çok kez birleştirildiğinde). |
| [isRemovePrivateInfo](#isRemovePrivateInfo--) | Özel bilgileri kaldır (sayfa parça bilgisi). |
| [isRemoveUnusedObjects](#isRemoveUnusedObjects--) | Bu bayrak true olarak ayarlanırsa, tüm belge nesneleri kontrol edilir ve kullanılmayan nesneler (yani herhangi bir referansı olmayan nesneler) belgeden kaldırılır. |
| [isRemoveUnusedStreams](#isRemoveUnusedStreams--) | Bu bayrak true olarak ayarlanırsa, her kaynak kullanımına göre kontrol edilir. Eğer kaynak hiç kullanılmazsa, kaynak kaldırılır. Bu, örneğin sayfalar belgeden çıkarıldığında belge boyutunun azalmasını sağlayabilir. |
| [isResizeImages](#isResizeImages--) | Bu bayrak true olarak ayarlanırsa ve CompressImages true ise, görüntü çözünürlüğü belirtilen MaxResolution parametresinden büyükse görüntüler yeniden boyutlandırılır. |
| [isSubsetFonts](#isSubsetFonts--) | Fontlar true olarak ayarlanırsa alt kümelere dönüştürülür. |
| [isUnembedFonts](#isUnembedFonts--) | Fontların gömülmemesini sağlamak için true olarak ayarlayın. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Doğruysa, belge eşit sayfalar için optimize edildiğinde sayfa içerikleri yeniden kullanılacaktır. |
| [setCompressAllContentStreams](#setCompressAllContentStreams-boolean-) | Eğer {@link} olarak ayarlanırsa, tüm sıkıştırılmamış sayfa içerik akışları {@code Document#OptimizeResources()} sırasında FlateDecode filtresi kullanılarak sıkıştırılır. Varsayılan {@link} geriye dönük uyumluluğu korumaktır. |
| [setCompressImages](#setCompressImages-boolean-) | Bu bayrak true olarak ayarlanırsa, görüntüler belgede sıkıştırılır. sıkıştırma seviyesi ImageQuality özelliği ile belirtilir. |
| [setCompressObjects](#setCompressObjects-boolean-) | Bu bayrak {@code } olarak ayarlanırsa, Pdf nesneleri Objest Streams içine paketlenir ve pdf dosya boyutunu azaltmak için sıkıştırılır. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Belgedeki görüntülerin sıkıştırılıp sıkıştırılmayacağını ve sıkıştırma parametrelerini tanımlayan seçenekler kümesi. |
| [setImageEncoding](#setImageEncoding-int-) | Kullanılacak görüntü kodlayıcı. |
| [setImageQuality](#setImageQuality-int-) | CompressIamges bayrağı kullanıldığında görüntü sıkıştırma seviyesini belirtir. |
| [setLinkDuplicateStreams](#setLinkDuplicateStreams-boolean-) | Bu bayrak true olarak ayarlanırsa, Resource streams analiz edilir. Eğer yinelenen akışlar bulunursa (yani akış içeriği eşitse), bu akışlar tek bir nesne olarak depolanır. Bu, bazı durumlarda belge boyutunun azalmasını sağlar (örneğin, aynı belge birden çok kez birleştirildiğinde). |
| [setMaxResoultion](#setMaxResoultion-int-) | Görüntülerin maksimum çözünürlüğünü belirtir. Görüntü daha yüksek bir çözünürlüğe sahipse ölçeklendirilir. |
| [setRemovePrivateInfo](#setRemovePrivateInfo-boolean-) | Özel bilgileri kaldır (sayfa parça bilgisi). |
| [setRemoveUnusedObjects](#setRemoveUnusedObjects-boolean-) | Bu bayrak true olarak ayarlanırsa, tüm belge nesneleri kontrol edilir ve kullanılmayan nesneler (yani herhangi bir referansı olmayan nesneler) belgeden kaldırılır. |
| [setRemoveUnusedStreams](#setRemoveUnusedStreams-boolean-) | Bu bayrak true olarak ayarlanırsa, her kaynak kullanımına göre kontrol edilir. Eğer kaynak hiç kullanılmazsa, kaynak kaldırılır. Bu, örneğin sayfalar belgeden çıkarıldığında belge boyutunun azalmasını sağlayabilir. |
| [setResizeImages](#setResizeImages-boolean-) | Bu bayrak true olarak ayarlanırsa ve CompressImages true ise, görüntü çözünürlüğü belirtilen MaxResolution parametresinden büyükse görüntüler yeniden boyutlandırılır. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Fontlar true olarak ayarlanırsa alt kümelere dönüştürülür. |
| [setUnembedFonts](#setUnembedFonts-boolean-) | Fontların gömülmemesini sağlamak için true olarak ayarlayın. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```



### all {#all--}
```
public static OptimizationOptions all()
```

Tüm seçenekler etkinleştirilmiş bir optimizasyon stratejisi oluşturur. Lütfen yalnızca belgenin işlevselliğini değiştirmeyen seçeneklerin etkinleştirildiğini unutmayın. Örneğin, görüntü sıkıştırma ve yazı tipi gömme kaldırma etkin olmayacaktır (ve manuel olarak eklenebilir).

**Returns:**
OptimizationOptions nesnesi.

### getCompressAllContentStreams {#getCompressAllContentStreams--}
```
public final boolean getCompressAllContentStreams()
```

Eğer {@link} olarak ayarlanırsa, tüm sıkıştırılmamış sayfa içerik akışları {@code Document#OptimizeResources()} sırasında FlateDecode filtresi kullanılarak sıkıştırılır. Varsayılan {@link} geriye dönük uyumluluğu korumaktır.

**Returns:**
boolean değer

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Belgedeki görüntülerin sıkıştırılıp sıkıştırılmayacağını ve sıkıştırma parametrelerini tanımlayan seçenekler kümesi.

**Returns:**
ImageCompressionOptions örneği

### getImageEncoding {#getImageEncoding--}
```
public final int getImageEncoding()
```

Kullanılacak görüntü kodlayıcı.

**Returns:**
ImageEncoding öğesi

### getImageQuality {#getImageQuality--}
```
@Deprecated public final int getImageQuality()
```

CompressIamges bayrağı kullanıldığında görüntü sıkıştırma seviyesini belirtir.

**Returns:**
int değer @deprecated Lütfen ImageCompressionOptions.ImageQuality kullanın.

### getMaxResoultion {#getMaxResoultion--}
```
public final int getMaxResoultion()
```

Görüntülerin maksimum çözünürlüğünü belirtir. Görüntü daha yüksek bir çözünürlüğe sahipse ölçeklendirilir.

**Returns:**
int değer

### isAllowReusePageContent {#isAllowReusePageContent--}
```
public final boolean isAllowReusePageContent()
```

Doğruysa, belge eşit sayfalar için optimize edildiğinde sayfa içerikleri yeniden kullanılacaktır.

**Returns:**
boolean değer

### isCompressImages {#isCompressImages--}
```
@Deprecated public final boolean isCompressImages()
```

Bu bayrak true olarak ayarlanırsa, görüntüler belgede sıkıştırılır. sıkıştırma seviyesi ImageQuality özelliği ile belirtilir.

**Returns:**
boolean değer @deprecated Lütfen ImageCompressionOptions.CompressImages kullanın.

### isCompressObjects {#isCompressObjects--}
```
public final boolean isCompressObjects()
```

Bu bayrak {@code } olarak ayarlanırsa, Pdf nesneleri Objest Streams içine paketlenir ve pdf dosya boyutunu azaltmak için sıkıştırılır.

**Returns:**
boolean değer

### isLinkDuplicateStreams {#isLinkDuplicateStreams--}
```
public final boolean isLinkDuplicateStreams()
```

Bu bayrak true olarak ayarlanırsa, Resource streams analiz edilir. Eğer yinelenen akışlar bulunursa (yani akış içeriği eşitse), bu akışlar tek bir nesne olarak depolanır. Bu, bazı durumlarda belge boyutunun azalmasını sağlar (örneğin, aynı belge birden çok kez birleştirildiğinde).

**Returns:**
boolean değer

### isRemovePrivateInfo {#isRemovePrivateInfo--}
```
public final boolean isRemovePrivateInfo()
```

Özel bilgileri kaldır (sayfa parça bilgisi).

**Returns:**
boolean değer

### isRemoveUnusedObjects {#isRemoveUnusedObjects--}
```
public final boolean isRemoveUnusedObjects()
```

Bu bayrak true olarak ayarlanırsa, tüm belge nesneleri kontrol edilir ve kullanılmayan nesneler (yani herhangi bir referansı olmayan nesneler) belgeden kaldırılır.

**Returns:**
boolean değer

### isRemoveUnusedStreams {#isRemoveUnusedStreams--}
```
public final boolean isRemoveUnusedStreams()
```

Bu bayrak true olarak ayarlanırsa, her kaynak kullanımına göre kontrol edilir. Eğer kaynak hiç kullanılmazsa, kaynak kaldırılır. Bu, örneğin sayfalar belgeden çıkarıldığında belge boyutunun azalmasını sağlayabilir.

**Returns:**
boolean değer

### isResizeImages {#isResizeImages--}
```
@Deprecated public final boolean isResizeImages()
```

Bu bayrak true olarak ayarlanırsa ve CompressImages true ise, görüntü çözünürlüğü belirtilen MaxResolution parametresinden büyükse görüntüler yeniden boyutlandırılır.

**Returns:**
boolean değer @deprecated Lütfen ImageCompressionOptions.ResizeImages kullanın.

### isSubsetFonts {#isSubsetFonts--}
```
public final boolean isSubsetFonts()
```

Fontlar true olarak ayarlanırsa alt kümelere dönüştürülür.

**Returns:**
boolean değer

### isUnembedFonts {#isUnembedFonts--}
```
public final boolean isUnembedFonts()
```

Fontların gömülmemesini sağlamak için true olarak ayarlayın.

**Returns:**
boolean değer

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```

Doğruysa, belge eşit sayfalar için optimize edildiğinde sayfa içerikleri yeniden kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setCompressAllContentStreams {#setCompressAllContentStreams-boolean-}
```
public final void setCompressAllContentStreams(boolean value)
```

Eğer {@link} olarak ayarlanırsa, tüm sıkıştırılmamış sayfa içerik akışları {@code Document#OptimizeResources()} sırasında FlateDecode filtresi kullanılarak sıkıştırılır. Varsayılan {@link} geriye dönük uyumluluğu korumaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setCompressImages {#setCompressImages-boolean-}
```
@Deprecated public final void setCompressImages(boolean value)
```

Bu bayrak true olarak ayarlanırsa, görüntüler belgede sıkıştırılır. sıkıştırma seviyesi ImageQuality özelliği ile belirtilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer @deprecated Lütfen ImageCompressionOptions.CompressImages kullanın. |

### setCompressObjects {#setCompressObjects-boolean-}
```
public final void setCompressObjects(boolean value)
```

Bu bayrak {@code } olarak ayarlanırsa, Pdf nesneleri Objest Streams içine paketlenir ve pdf dosya boyutunu azaltmak için sıkıştırılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Belgedeki görüntülerin sıkıştırılıp sıkıştırılmayacağını ve sıkıştırma parametrelerini tanımlayan seçenekler kümesi.

### setImageEncoding {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```

Kullanılacak görüntü kodlayıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ImageEncoding öğesi |

### setImageQuality {#setImageQuality-int-}
```
@Deprecated public final void setImageQuality(int value)
```

CompressIamges bayrağı kullanıldığında görüntü sıkıştırma seviyesini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer @deprecated Lütfen ImageCompressionOptions.ImageQuality kullanın. |

### setLinkDuplicateStreams {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```

Bu bayrak true olarak ayarlanırsa, Resource streams analiz edilir. Eğer yinelenen akışlar bulunursa (yani akış içeriği eşitse), bu akışlar tek bir nesne olarak depolanır. Bu, bazı durumlarda belge boyutunun azalmasını sağlar (örneğin, aynı belge birden çok kez birleştirildiğinde).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMaxResoultion {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```

Görüntülerin maksimum çözünürlüğünü belirtir. Görüntü daha yüksek bir çözünürlüğe sahipse ölçeklendirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setRemovePrivateInfo {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```

Özel bilgileri kaldır (sayfa parça bilgisi).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRemoveUnusedObjects {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```

Bu bayrak true olarak ayarlanırsa, tüm belge nesneleri kontrol edilir ve kullanılmayan nesneler (yani herhangi bir referansı olmayan nesneler) belgeden kaldırılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRemoveUnusedStreams {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```

Bu bayrak true olarak ayarlanırsa, her kaynak kullanımına göre kontrol edilir. Eğer kaynak hiç kullanılmazsa, kaynak kaldırılır. Bu, örneğin sayfalar belgeden çıkarıldığında belge boyutunun azalmasını sağlayabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setResizeImages {#setResizeImages-boolean-}
```
@Deprecated public final void setResizeImages(boolean value)
```

Bu bayrak true olarak ayarlanırsa ve CompressImages true ise, görüntü çözünürlüğü belirtilen MaxResolution parametresinden büyükse görüntüler yeniden boyutlandırılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer @deprecated Lütfen ImageCompressionOptions.ResizeImages kullanın. |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Fontlar true olarak ayarlanırsa alt kümelere dönüştürülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUnembedFonts {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```

Fontların gömülmemesini sağlamak için true olarak ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
