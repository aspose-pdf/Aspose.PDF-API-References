---
title: "AbsorbedTable"
linktitle: "AbsorbedTable"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfada bulunan tabloyu temsil eder"
type: docs
weight: 30
url: /tr/java/com.aspose.pdf/absorbedtable/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedTable

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedTable >

```
public class AbsorbedTable extends Object implements ITableElement , Comparable < AbsorbedTable >
```

Sayfada bulunan tabloyu temsil eder

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedTable-) | Mevcut AbsorbedTable nesnesini başka bir AbsorbedTable nesnesiyle karşılaştırır ve mevcut nesnenin sıralama düzeninde diğer nesneden önce mi, sonra mı yoksa aynı konumda mı olduğunu belirten bir tam sayı döndürür. |
| [getPageNum](#getPageNum--) | Bu tabloyu içeren sayfanın numarasını alır |
| [getRectangle](#getRectangle--) | Sayfada tablonun konumunu tanımlayan dikdörtgeni alır |
| [getRowList](#getRowList--) | <p> Tablonun satırlarını içeren yalnızca okunabilir IList'i alır </p> |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedTable-}
Mevcut AbsorbedTable nesnesini başka bir AbsorbedTable nesnesiyle karşılaştırır ve mevcut nesnenin sıralama düzeninde diğer nesneden önce mi, sonra mı yoksa aynı konumda mı olduğunu belirten bir tam sayı döndürür.

### getPageNum {#getPageNum--}
```
public int getPageNum()
```

Bu tabloyu içeren sayfanın numarasını alır

**Returns:**
int değer

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Sayfada tablonun konumunu tanımlayan dikdörtgeni alır

**Returns:**
Rectangle nesnesi

### getRowList {#getRowList--}
```
public List < AbsorbedRow > getRowList()
```

<p> Tablonun satırlarını içeren yalnızca okunabilir IList'i alır </p>

**Returns:**
{@code IGenericList<AbsorbedRow>} nesnesi
