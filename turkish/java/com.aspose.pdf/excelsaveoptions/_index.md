---
title: "ExcelSaveOptions"
linktitle: "ExcelSaveOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Excel formatına dışa aktarma için kaydetme seçenekleri."
type: docs
weight: 1260
url: /tr/java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.ExcelSaveOptions

```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

Excel formatına dışa aktarma için kaydetme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ExcelSaveOptions](#ExcelSaveOptions--) | Yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat](#getFormat--) | / * / * (virtual) ölçekleme yazı tipi boyutuna Excel tablosuna dönüştürme sırasında uygulanacak faktörü alır veya ayarlar. / * eski motor. Daha düşük bir değer ayarlanması, bazı / * belgeler. Varsayılan değer 0.9; değeri sıfıra ayarlamak, algoritmanın ölçeklemeyi otomatik seçmesini sağlar. / * / * / * |
| [getMinimizeTheNumberOfWorksheets](#getMinimizeTheNumberOfWorksheets--) | Sonuç çalışma kitabındaki sayfa sayısını azaltmanız gerekiyorsa true ayarlayın. Varsayılan değer false'tur; bu, her PDF sayfasının ayrı bir çalışma sayfası olarak kaydedilmesi anlamına gelir. |
| [isInsertBlankColumnAtFirst](#isInsertBlankColumnAtFirst--) | Çalışma sayfasının ilk sütunu olarak boş bir sütun eklemeyi bastırmanız gerekiyorsa false olarak ayarlayın. Varsayılan değer true'tır; bu, boş sütunun ekleneceği anlamına gelir. |
| [isUniformWorksheets](#isUniformWorksheets--) | Belge boyunca aynı sütun bölünmesini kullanmak için true olarak ayarlayın. Varsayılan değer false'tur; bu, sütun bölünmesinin her sayfa için bağımsız olacağı anlamına gelir. |
| [setFormat](#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-) | Çıktı biçimi |
| [setInsertBlankColumnAtFirst](#setInsertBlankColumnAtFirst-boolean-) | Çalışma sayfasının ilk sütunu olarak boş bir sütun eklemeyi bastırmanız gerekiyorsa false olarak ayarlayın. Varsayılan değer true'tır; bu, boş sütunun ekleneceği anlamına gelir. |
| [setMinimizeTheNumberOfWorksheets](#setMinimizeTheNumberOfWorksheets-boolean-) | Sonuç çalışma kitabındaki sayfa sayısını azaltmanız gerekiyorsa true ayarlayın. Varsayılan değer false'tur; bu, her PDF sayfasının ayrı bir çalışma sayfası olarak kaydedilmesi anlamına gelir. |
| [setUniformWorksheets](#setUniformWorksheets-boolean-) | Dönüşüm için kullanılacak dönüştürme motorunu tanımlar. |

### ExcelSaveOptions {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
```

Yapıcı

### getFormat {#getFormat--}
```
public ExcelSaveOptions.ExcelFormat getFormat()
```

/ * / * (virtual) ölçekleme yazı tipi boyutuna Excel tablosuna dönüştürme sırasında uygulanacak faktörü alır veya ayarlar. / * eski motor. Daha düşük bir değer ayarlanması, bazı / * belgeler. Varsayılan değer 0.9; değeri sıfıra ayarlamak, algoritmanın ölçeklemeyi otomatik seçmesini sağlar. / * / * / *

**Returns:**
double değer /

### getMinimizeTheNumberOfWorksheets {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```

Sonuç çalışma kitabındaki sayfa sayısını azaltmanız gerekiyorsa true ayarlayın. Varsayılan değer false'tur; bu, her PDF sayfasının ayrı bir çalışma sayfası olarak kaydedilmesi anlamına gelir.

**Returns:**
boolean değer

### isInsertBlankColumnAtFirst {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```

Çalışma sayfasının ilk sütunu olarak boş bir sütun eklemeyi bastırmanız gerekiyorsa false olarak ayarlayın. Varsayılan değer true'tır; bu, boş sütunun ekleneceği anlamına gelir.

**Returns:**
boolean değer

### isUniformWorksheets {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```

Belge boyunca aynı sütun bölünmesini kullanmak için true olarak ayarlayın. Varsayılan değer false'tur; bu, sütun bölünmesinin her sayfa için bağımsız olacağı anlamına gelir.

**Returns:**
boolean değer

### setFormat {#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-}
Çıktı biçimi

### setInsertBlankColumnAtFirst {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```

Çalışma sayfasının ilk sütunu olarak boş bir sütun eklemeyi bastırmanız gerekiyorsa false olarak ayarlayın. Varsayılan değer true'tır; bu, boş sütunun ekleneceği anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMinimizeTheNumberOfWorksheets {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```

Sonuç çalışma kitabındaki sayfa sayısını azaltmanız gerekiyorsa true ayarlayın. Varsayılan değer false'tur; bu, her PDF sayfasının ayrı bir çalışma sayfası olarak kaydedilmesi anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUniformWorksheets {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```

Dönüşüm için kullanılacak dönüştürme motorunu tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  |  |
