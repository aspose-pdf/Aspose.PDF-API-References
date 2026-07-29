---
title: "AbsorbedCell"
linktitle: "AbsorbedCell"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfada bulunan tablonun hücresini temsil eder"
type: docs
weight: 10
url: /tr/java/com.aspose.pdf/absorbedcell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedCell

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedCell >

```
public class AbsorbedCell extends Object implements ITableElement , Comparable < AbsorbedCell >
```

Sayfada bulunan tablonun hücresini temsil eder

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedCell-) | Mevcut AbsorbedCell nesnesini başka bir AbsorbedCell nesnesiyle karşılaştırır ve mevcut nesnenin diğer nesneye göre sıralama düzeninde önce mi, sonra mı yoksa aynı konumda mı olduğunu belirten bir tam sayı döndürür. |
| [getBorderInfo](#getBorderInfo--) | FlowEngine.TableAbsorber.UseFlowEngine özelliği true olarak ayarlandığında hücre için kenar bilgilerini döndürür. |
| [getColSpan](#getColSpan--) | TableAbsorber.UseFlowEngine özelliği true olarak ayarlandığında hücrenin kapsaması gereken sütun sayısını döndürür. |
| [getRectangle](#getRectangle--) | Sayfadaki hücrenin konumunu tanımlayan dikdörtgeni alır |
| [getTextFragments](#getTextFragments--) | Hücrede bulunan metni tanımlayan {@code TextFragment} nesnelerinin koleksiyonunu alır |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedCell-}
Mevcut AbsorbedCell nesnesini başka bir AbsorbedCell nesnesiyle karşılaştırır ve mevcut nesnenin diğer nesneye göre sıralama düzeninde önce mi, sonra mı yoksa aynı konumda mı olduğunu belirten bir tam sayı döndürür.

### getBorderInfo {#getBorderInfo--}
```
public final BorderInfo getBorderInfo()
```

FlowEngine.TableAbsorber.UseFlowEngine özelliği true olarak ayarlandığında hücre için kenar bilgilerini döndürür.

**Returns:**
BorderInfo örneği

### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

TableAbsorber.UseFlowEngine özelliği true olarak ayarlandığında hücrenin kapsaması gereken sütun sayısını döndürür.

**Returns:**
int değer

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Sayfadaki hücrenin konumunu tanımlayan dikdörtgeni alır

**Returns:**
Rectangle nesnesi

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

Hücrede bulunan metni tanımlayan {@code TextFragment} nesnelerinin koleksiyonunu alır

**Returns:**
TextFragmentCollection nesnesi
