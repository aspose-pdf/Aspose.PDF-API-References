---
title: "SideBySideComparisonOptions"
linktitle: "SideBySideComparisonOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Yan yana çıktı ile belgeleri karşılaştırmak için bir seçenek sınıfını temsil eder."
type: docs
weight: 60
url: /tr/java/com.aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget, com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions

```
public class SideBySideComparisonOptions extends IVentureLicenseTarget
```

Yan yana çıktı ile belgeleri karşılaştırmak için bir seçenek sınıfını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SideBySideComparisonOptions](#SideBySideComparisonOptions--) | Bir {@link SideBySideComparisonOptions} sınıf örneği oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAdditionalChangeMarks](#getAdditionalChangeMarks--) | Ek değişiklik işaretçilerinin gösterilip gösterilmeyeceğini belirleyen özelliği alır ve ayarlar. Ayarlanırsa, mevcut sayfada olmayan ancak başka bir sayfada bulunan değişiklik işaretlerini gösterir. Değişiklik kelimeler arasında konumlanıyorsa, işaret boşluk karakterine göre tam olarak konumlanmayabilir. Varsayılan değer {@code false}'dur. |
| [getComparisonArea1](#getComparisonArea1--) | Karşılaştırma alanını alır ve ayarlar. Karşılaştırma yönteminde ilk sayfa veya belge için kullanılır. Bu seçenek, {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) ve {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) seçenekleriyle birlikte ayarlanamaz. |
| [getComparisonArea2](#getComparisonArea2--) | Karşılaştırma alanını alır ve ayarlar. Karşılaştırma yönteminde ikinci sayfa veya belge için kullanılır. Bu seçenek, {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) ve {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) seçenekleriyle birlikte ayarlanamaz. |
| [getComparisonMode](#getComparisonMode--) | Bir karşılaştırma modunu alır ve ayarlar. Varsayılan değer {@link ComparisonMode#IgnoreSpaces}'dır. |
| [getDeleteColor](#getDeleteColor--) | Yan yana karşılaştırma sırasında silinen içeriği işaretlemek için kullanılan rengi alır. Bu özellik, karşılaştırma sonucundaki silme işlemlerinin görsel temsilini tanımlar. |
| [getExcludeAreas1](#getExcludeAreas1--) | Hariç tutma alanlarını al ve ayarla. Karşılaştırma yönteminde ilk sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) seçeneğiyle birlikte ayarlanamaz. |
| [getExcludeAreas2](#getExcludeAreas2--) | Hariç tutma alanlarını al ve ayarla. Karşılaştırma yönteminde ikinci sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) seçeneğiyle birlikte ayarlanamaz. |
| [getExcludeTables](#getExcludeTables--) | Tabloların karşılaştırmadan hariç tutulup tutulmayacağını belirleyen seçeneği al ve ayarla. Bu seçenek {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) ve {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) ile birlikte ayarlanamaz. Varsayılan değer {@code false}'dur. |
| [getInsertColor](#getInsertColor--) | Yan yana karşılaştırma sırasında eklenen içeriği işaretlemek için kullanılan rengi alır. Bu özellik, karşılaştırma sonucundaki ekleme işlemlerinin görsel temsilini tanımlar. |
| [setAdditionalChangeMarks](#setAdditionalChangeMarks-boolean-) | Ek değişiklik işaretçilerinin gösterilip gösterilmeyeceğini belirleyen özelliği alır ve ayarlar. Ayarlanırsa, mevcut sayfada olmayan ancak başka bir sayfada bulunan değişiklik işaretlerini gösterir. Değişiklik kelimeler arasında konumlanıyorsa, işaret boşluk karakterine göre tam olarak konumlanmayabilir. Varsayılan değer {@code false}'dur. |
| [setComparisonArea1](#setComparisonArea1-com.aspose.pdf.Rectangle-) | Karşılaştırma alanını alır ve ayarlar. Karşılaştırma yönteminde ilk sayfa veya belge için kullanılır. Bu seçenek, {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) ve {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) seçenekleriyle birlikte ayarlanamaz. |
| [setComparisonArea2](#setComparisonArea2-com.aspose.pdf.Rectangle-) | Karşılaştırma alanını alır ve ayarlar. Karşılaştırma yönteminde ikinci sayfa veya belge için kullanılır. Bu seçenek, {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) ve {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) seçenekleriyle birlikte ayarlanamaz. |
| [setComparisonMode](#setComparisonMode-int-) | Bir karşılaştırma modunu alır ve ayarlar. Varsayılan değer {@link ComparisonMode#IgnoreSpaces}'dır. |
| [setDeleteColor](#setDeleteColor-com.aspose.pdf.Color-) | Yan yana karşılaştırma sırasında silinen içeriği işaretlemek için kullanılan rengi ayarlar. Bu özellik, karşılaştırma sonucundaki silme işlemlerinin görsel temsilini tanımlar. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Hariç tutma alanlarını al ve ayarla. Karşılaştırma yönteminde ilk sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) seçeneğiyle birlikte ayarlanamaz. |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Hariç tutma alanlarını al ve ayarla. Karşılaştırma yönteminde ikinci sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) seçeneğiyle birlikte ayarlanamaz. |
| [setExcludeTables](#setExcludeTables-boolean-) | Tabloların karşılaştırmadan hariç tutulup tutulmayacağını belirleyen seçeneği al ve ayarla. Bu seçenek {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) ve {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) ile birlikte ayarlanamaz. Varsayılan değer {@code false}'dur. |
| [setInsertColor](#setInsertColor-com.aspose.pdf.Color-) | Yan yana karşılaştırma sırasında eklenen içeriği işaretlemek için kullanılan rengi ayarlar. Bu özellik, karşılaştırma sonucundaki ekleme işlemlerinin görsel temsilini tanımlar. |
| [setVentureLicense](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |

### SideBySideComparisonOptions {#SideBySideComparisonOptions--}
```
public SideBySideComparisonOptions()
```

Bir {@link SideBySideComparisonOptions} sınıf örneği oluşturur.

### getAdditionalChangeMarks {#getAdditionalChangeMarks--}
```
public final boolean getAdditionalChangeMarks()
```

Ek değişiklik işaretçilerinin gösterilip gösterilmeyeceğini belirleyen özelliği alır ve ayarlar. Ayarlanırsa, mevcut sayfada olmayan ancak başka bir sayfada bulunan değişiklik işaretlerini gösterir. Değişiklik kelimeler arasında konumlanıyorsa, işaret boşluk karakterine göre tam olarak konumlanmayabilir. Varsayılan değer {@code false}'dur.

**Returns:**
boolean değer

### getComparisonArea1 {#getComparisonArea1--}
```
public final Rectangle getComparisonArea1()
```

Karşılaştırma alanını alır ve ayarlar. Karşılaştırma yönteminde ilk sayfa veya belge için kullanılır. Bu seçenek, {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) ve {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) seçenekleriyle birlikte ayarlanamaz.

**Returns:**
Dikdörtgen örneği

### getComparisonArea2 {#getComparisonArea2--}
```
public final Rectangle getComparisonArea2()
```

Karşılaştırma alanını alır ve ayarlar. Karşılaştırma yönteminde ikinci sayfa veya belge için kullanılır. Bu seçenek, {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) ve {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) seçenekleriyle birlikte ayarlanamaz.

**Returns:**
Dikdörtgen örneği

### getComparisonMode {#getComparisonMode--}
```
public final int getComparisonMode()
```

Bir karşılaştırma modunu alır ve ayarlar. Varsayılan değer {@link ComparisonMode#IgnoreSpaces}'dır.

**Returns:**
ComparisonMode öğesi

### getDeleteColor {#getDeleteColor--}
```
public final Color getDeleteColor()
```

Yan yana karşılaştırma sırasında silinen içeriği işaretlemek için kullanılan rengi alır. Bu özellik, karşılaştırma sonucundaki silme işlemlerinin görsel temsilini tanımlar.

**Returns:**
yan yana karşılaştırma sırasında silinen içeriği işaretlemek için kullanılan renk.

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Hariç tutma alanlarını al ve ayarla. Karşılaştırma yönteminde ilk sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) seçeneğiyle birlikte ayarlanamaz.

**Returns:**
Rectangle örneklerinin dizisi

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Hariç tutma alanlarını al ve ayarla. Karşılaştırma yönteminde ikinci sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) seçeneğiyle birlikte ayarlanamaz.

**Returns:**
Rectangle örneklerinin dizisi

### getExcludeTables {#getExcludeTables--}
```
public final boolean getExcludeTables()
```

Tabloların karşılaştırmadan hariç tutulup tutulmayacağını belirleyen seçeneği al ve ayarla. Bu seçenek {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) ve {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) ile birlikte ayarlanamaz. Varsayılan değer {@code false}'dur.

**Returns:**
boolean değer

### getInsertColor {#getInsertColor--}
```
public final Color getInsertColor()
```

Yan yana karşılaştırma sırasında eklenen içeriği işaretlemek için kullanılan rengi alır. Bu özellik, karşılaştırma sonucundaki ekleme işlemlerinin görsel temsilini tanımlar.

**Returns:**
yan yana karşılaştırma sırasında eklenen içeriği işaretlemek için kullanılan renk.

### setAdditionalChangeMarks {#setAdditionalChangeMarks-boolean-}
```
public final void setAdditionalChangeMarks(boolean value)
```

Ek değişiklik işaretçilerinin gösterilip gösterilmeyeceğini belirleyen özelliği alır ve ayarlar. Ayarlanırsa, mevcut sayfada olmayan ancak başka bir sayfada bulunan değişiklik işaretlerini gösterir. Değişiklik kelimeler arasında konumlanıyorsa, işaret boşluk karakterine göre tam olarak konumlanmayabilir. Varsayılan değer {@code false}'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setComparisonArea1 {#setComparisonArea1-com.aspose.pdf.Rectangle-}
Karşılaştırma alanını alır ve ayarlar. Karşılaştırma yönteminde ilk sayfa veya belge için kullanılır. Bu seçenek, {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) ve {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) seçenekleriyle birlikte ayarlanamaz.

### setComparisonArea2 {#setComparisonArea2-com.aspose.pdf.Rectangle-}
Karşılaştırma alanını alır ve ayarlar. Karşılaştırma yönteminde ikinci sayfa veya belge için kullanılır. Bu seçenek, {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) ve {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) seçenekleriyle birlikte ayarlanamaz.

### setComparisonMode {#setComparisonMode-int-}
```
public final void setComparisonMode(int value)
```

Bir karşılaştırma modunu alır ve ayarlar. Varsayılan değer {@link ComparisonMode#IgnoreSpaces}'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ComparisonMode öğesi |

### setDeleteColor {#setDeleteColor-com.aspose.pdf.Color-}
Yan yana karşılaştırma sırasında silinen içeriği işaretlemek için kullanılan rengi ayarlar. Bu özellik, karşılaştırma sonucundaki silme işlemlerinin görsel temsilini tanımlar.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Hariç tutma alanlarını al ve ayarla. Karşılaştırma yönteminde ilk sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) seçeneğiyle birlikte ayarlanamaz.

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Hariç tutma alanlarını al ve ayarla. Karşılaştırma yönteminde ikinci sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) seçeneğiyle birlikte ayarlanamaz.

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Tabloların karşılaştırmadan hariç tutulup tutulmayacağını belirleyen seçeneği al ve ayarla. Bu seçenek {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) ve {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) ile birlikte ayarlanamaz. Varsayılan değer {@code false}'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setInsertColor {#setInsertColor-com.aspose.pdf.Color-}
Yan yana karşılaştırma sırasında eklenen içeriği işaretlemek için kullanılan rengi ayarlar. Bu özellik, karşılaştırma sonucundaki ekleme işlemlerinin görsel temsilini tanımlar.

### setVentureLicense {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
