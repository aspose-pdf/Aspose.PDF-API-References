---
title: "PclLoadOptions"
linktitle: "PclLoadOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "PCL dosyasını pdf belgesine yükleme (import) seçeneklerini temsil eder."
type: docs
weight: 3530
url: /tr/java/com.aspose.pdf/pclloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PclLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PclLoadOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

PCL dosyasını pdf belgesine yükleme (import) seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PclLoadOptions](#PclLoadOptions--) | {@code PclLoadOptions} nesnesini oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar. |
| [getConversionEngine](#getConversionEngine--) | Dönüşüm için kullanılacak dönüştürme motorunu tanımlar. |
| [getExceptions](#getExceptions--) | Dönüşüm hatalarının listesi. |
| [isSupressErrors](#isSupressErrors--) | PCL dönüşüm hatalarının bastırılıp bastırılmayacağını gösteren boolean değeri alır veya ayarlar. |
| [setBatchSize](#setBatchSize-int-) | Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar. |
| [setConversionEngine](#setConversionEngine-int-) | Dönüşüm için kullanılacak dönüştürme motorunu tanımlar. |
| [setSupressErrors](#setSupressErrors-boolean-) | PCL dönüşüm hatalarının bastırılıp bastırılmayacağını gösteren boolean değeri alır veya ayarlar. |

### PclLoadOptions {#PclLoadOptions--}
```
public PclLoadOptions()
```

{@code PclLoadOptions} nesnesini oluşturur.

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar.

**Returns:**
int değer

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Dönüşüm için kullanılacak dönüştürme motorunu tanımlar.

**Returns:**
ConversionEngines öğesi @see ConversionEngines

### getExceptions {#getExceptions--}
```
public List < Exception > getExceptions()
```

Dönüşüm hatalarının listesi.

**Returns:**
Exceptions listesi

### isSupressErrors {#isSupressErrors--}
```
public boolean isSupressErrors()
```

PCL dönüşüm hatalarının bastırılıp bastırılmayacağını gösteren boolean değeri alır veya ayarlar.

**Returns:**
boolean değer

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Dönüşüm için kullanılacak dönüştürme motorunu tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| conversionEngine |  | ConversionEngines öğesi @see ConversionEngines |

### setSupressErrors {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```

PCL dönüşüm hatalarının bastırılıp bastırılmayacağını gösteren boolean değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| supressErrors |  | boolean değer |
