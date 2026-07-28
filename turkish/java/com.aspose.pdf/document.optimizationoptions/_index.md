---
title: "Document.OptimizationOptions"
linktitle: "Document.OptimizationOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Belge optimizasyon algoritmasını tanımlayan sınıf. Bu sınıfın bir örneği OptimizeResources() metodunun parametresi olarak kullanılabilir. @deprecated Bu sınıf artık kullanılmıyor. Lütfen."
type: docs
weight: 1110
url: /tr/java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions com.aspose.pdf.Document.OptimizationOptions, com.aspose.pdf.optimization.OptimizationOptions, com.aspose.pdf.Document.OptimizationOptions

```
@Deprecated public static class Document.OptimizationOptions extends OptimizationOptions
```

Belge optimizasyon algoritmasını tanımlayan sınıf. Bu sınıfın bir örneği OptimizeResources() metodunun parametresi olarak kullanılabilir. @deprecated Bu sınıf artık kullanılmamaktadır. Lütfen com.aspose.pdf.optimization.OptimizationOptions kullanın.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) | Kullanımdan kaldırıldı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [all](#all--) | Tüm seçenekler etkinleştirilmiş bir optimizasyon stratejisi oluşturur. |
| [getMaximumImageDimension](#getMaximumImageDimension--) | Maksimum görüntü boyutunu belirtir. Mevcut görüntünün genişliği veya yüksekliği bu değerden büyükse, görüntü boyutu orantılı olarak küçültülür. |
| [getResolution](#getResolution--) | CompressIamges bayrağı kullanıldığında yeni görüntü dpi değerini belirtir. |
| [setMaximumImageDimension](#setMaximumImageDimension-int-) | Maksimum görüntü boyutunu belirtir. Mevcut görüntünün genişliği veya yüksekliği bu değerden büyükse, görüntü boyutu orantılı olarak küçültülür. |
| [setResolution](#setResolution-int-) | CompressIamges bayrağı kullanıldığında yeni görüntü dpi değerini belirtir. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```

Kullanımdan kaldırıldı.

### all {#all--}
```
public static Document.OptimizationOptions all()
```

Tüm seçenekler etkinleştirilmiş bir optimizasyon stratejisi oluşturur.

**Returns:**
OptimizationOptions nesnesi.

### getMaximumImageDimension {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```

Maksimum görüntü boyutunu belirtir. Mevcut görüntünün genişliği veya yüksekliği bu değerden büyükse, görüntü boyutu orantılı olarak küçültülür.

**Returns:**
görüntü maksimum boyutu

### getResolution {#getResolution--}
```
public int getResolution()
```

CompressIamges bayrağı kullanıldığında yeni görüntü dpi değerini belirtir.

**Returns:**
görüntü çözünürlüğü

### setMaximumImageDimension {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```

Maksimum görüntü boyutunu belirtir. Mevcut görüntünün genişliği veya yüksekliği bu değerden büyükse, görüntü boyutu orantılı olarak küçültülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boyut |  | görüntü maksimum boyutu |

### setResolution {#setResolution-int-}
```
public void setResolution(int dpi)
```

CompressIamges bayrağı kullanıldığında yeni görüntü dpi değerini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dpi |  | görüntü çözünürlüğü |
