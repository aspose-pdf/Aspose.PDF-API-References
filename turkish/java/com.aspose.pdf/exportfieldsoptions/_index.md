---
title: "ExportFieldsOptions"
linktitle: "ExportFieldsOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Form alanlarını dışa aktarma seçenekleri için temel sınıfı temsil eder."
type: docs
weight: 1310
url: /tr/java/com.aspose.pdf/exportfieldsoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExportFieldsOptions

```
public abstract class ExportFieldsOptions extends Object
```

Form alanlarını dışa aktarma seçenekleri için temel sınıfı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ExportFieldsOptions](#ExportFieldsOptions--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getExportPasswordValue](#getExportPasswordValue--) | Parola değerinin dışa aktarılıp aktarılmayacağını gösteren bir değeri alır veya ayarlar. Değer: {@code true} parola değeri dışa aktarılacaksa; aksi takdirde {@code false}. |
| [getFieldSelector](#getFieldSelector--) | Belirli bir alanın dışa aktarılıp aktarılmayacağını belirleyen bir temsilci alır. Temsilci {@code null} ise, tüm alanlar dışa aktarılır (varsayılan davranış). |
| [setExportPasswordValue](#setExportPasswordValue-boolean-) | Parola değerinin dışa aktarılıp aktarılmayacağını gösteren bir değeri alır veya ayarlar. Değer: {@code true} parola değeri dışa aktarılacaksa; aksi takdirde {@code false}. |
| [setFieldSelector](#setFieldSelector-com.aspose.ms.System.Predicate-) | Belirli bir alanın dışa aktarılıp aktarılmayacağını belirleyen bir temsilci ayarlar. |

### ExportFieldsOptions {#ExportFieldsOptions--}
```
public ExportFieldsOptions()
```



### getExportPasswordValue {#getExportPasswordValue--}
```
public final boolean getExportPasswordValue()
```

Parola değerinin dışa aktarılıp aktarılmayacağını gösteren bir değeri alır veya ayarlar. Değer: {@code true} parola değeri dışa aktarılacaksa; aksi takdirde {@code false}.

**Returns:**
boolean değer

### getFieldSelector {#getFieldSelector--}
```
public final com.aspose.ms.System.Predicate< Field > getFieldSelector()
```

Belirli bir alanın dışa aktarılıp aktarılmayacağını belirleyen bir temsilci alır. Temsilci {@code null} ise, tüm alanlar dışa aktarılır (varsayılan davranış).

**Returns:**
belirli bir alanın dışa aktarılıp aktarılmayacağını belirleyen bir temsilci.

### setExportPasswordValue {#setExportPasswordValue-boolean-}
```
public final void setExportPasswordValue(boolean value)
```

Parola değerinin dışa aktarılıp aktarılmayacağını gösteren bir değeri alır veya ayarlar. Değer: {@code true} parola değeri dışa aktarılacaksa; aksi takdirde {@code false}.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setFieldSelector {#setFieldSelector-com.aspose.ms.System.Predicate-}
Belirli bir alanın dışa aktarılıp aktarılmayacağını belirleyen bir temsilci ayarlar.
