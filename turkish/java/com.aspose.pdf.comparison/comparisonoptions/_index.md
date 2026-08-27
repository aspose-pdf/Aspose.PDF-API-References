---
title: "ComparisonOptions"
linktitle: "ComparisonOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belge karşılaştırma seçenekleri sınıfını temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.pdf.comparison/comparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.ComparisonOptions

```
public class ComparisonOptions extends Object
```

PDF belge karşılaştırma seçenekleri sınıfını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ComparisonOptions](#ComparisonOptions--) | Bir {@link ComparisonOptions} sınıf örneği oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEditOperationsOrder](#getEditOperationsOrder--) | Düzenleme işlemleri sırasını alır ve ayarlar. |
| [getExcludeAreas1](#getExcludeAreas1--) | Dışlama alanlarını al ve ayarla. Karşılaştırma yönteminde ilk sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) seçeneği ile birlikte ayarlanamaz. |
| [getExcludeAreas2](#getExcludeAreas2--) | Dışlama alanlarını al ve ayarla. Karşılaştırma yönteminde ikinci sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) seçeneği ile birlikte ayarlanamaz. |
| [getExtractionArea](#getExtractionArea--) | Sayfaların metninin karşılaştırılacağı dikdörtgen alanı al ve ayarla. Bu seçenek {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) ve { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) seçenekleri ile birlikte ayarlanamaz. |
| [isExcludeTables](#isExcludeTables--) | Tabloların karşılaştırmadan dışlanıp dışlanmayacağını belirleyen seçeneği al ve ayarla. Bu seçenek {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) seçeneği ile birlikte ayarlanamaz. Varsayılan değer {@code false}. |
| [setEditOperationsOrder](#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-) | Düzenleme işlemleri sırasını alır ve ayarlar. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Dışlama alanlarını al ve ayarla. Karşılaştırma yönteminde ilk sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) seçeneği ile birlikte ayarlanamaz. |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Dışlama alanlarını al ve ayarla. Karşılaştırma yönteminde ikinci sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) seçeneği ile birlikte ayarlanamaz. |
| [setExcludeTables](#setExcludeTables-boolean-) | Tabloların karşılaştırmadan dışlanıp dışlanmayacağını belirleyen seçeneği al ve ayarla. Bu seçenek {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) seçeneği ile birlikte ayarlanamaz. Varsayılan değer {@code false}. |
| [setExtractionArea](#setExtractionArea-com.aspose.pdf.Rectangle-) | Sayfaların metninin karşılaştırılacağı dikdörtgen alanı al ve ayarla. Bu seçenek {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) ve { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) seçenekleri ile birlikte ayarlanamaz. |

### ComparisonOptions {#ComparisonOptions--}
```
public ComparisonOptions()
```

Bir {@link ComparisonOptions} sınıf örneği oluşturur.

### getEditOperationsOrder {#getEditOperationsOrder--}
```
public final EditOperationsOrder getEditOperationsOrder()
```

Düzenleme işlemleri sırasını alır ve ayarlar.

**Returns:**
EditOperationsOrder öğesi

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Dışlama alanlarını al ve ayarla. Karşılaştırma yönteminde ilk sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) seçeneği ile birlikte ayarlanamaz.

**Returns:**
Rectangle örneklerinin dizisi

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Dışlama alanlarını al ve ayarla. Karşılaştırma yönteminde ikinci sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) seçeneği ile birlikte ayarlanamaz.

**Returns:**
Rectangle örneklerinin dizisi

### getExtractionArea {#getExtractionArea--}
```
public final Rectangle getExtractionArea()
```

Sayfaların metninin karşılaştırılacağı dikdörtgen alanı al ve ayarla. Bu seçenek {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) ve { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) seçenekleri ile birlikte ayarlanamaz.

**Returns:**
Dikdörtgen örneği

### isExcludeTables {#isExcludeTables--}
```
public final boolean isExcludeTables()
```

Tabloların karşılaştırmadan dışlanıp dışlanmayacağını belirleyen seçeneği al ve ayarla. Bu seçenek {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) seçeneği ile birlikte ayarlanamaz. Varsayılan değer {@code false}.

**Returns:**
boolean değer

### setEditOperationsOrder {#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-}
Düzenleme işlemleri sırasını alır ve ayarlar.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Dışlama alanlarını al ve ayarla. Karşılaştırma yönteminde ilk sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) seçeneği ile birlikte ayarlanamaz.

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Dışlama alanlarını al ve ayarla. Karşılaştırma yönteminde ikinci sayfa veya belge için kullanılır. Bu seçenek {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) ile birlikte ayarlanabilir. Bu seçenek {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) seçeneği ile birlikte ayarlanamaz.

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Tabloların karşılaştırmadan dışlanıp dışlanmayacağını belirleyen seçeneği al ve ayarla. Bu seçenek {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) seçeneği ile birlikte ayarlanamaz. Varsayılan değer {@code false}.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setExtractionArea {#setExtractionArea-com.aspose.pdf.Rectangle-}
Sayfaların metninin karşılaştırılacağı dikdörtgen alanı al ve ayarla. Bu seçenek {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) ve { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) seçenekleri ile birlikte ayarlanamaz.
