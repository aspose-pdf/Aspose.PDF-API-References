---
title: "FitRExplicitDestination"
linktitle: "FitRExplicitDestination"
second_title: "Aspose.PDF for Java API Referansı"
description: "Koordinatları sol, alt, sağ ve ... ile belirtilen dikdörtgene sığacak şekilde sayfanın içeriğini yeterince büyüterek gösteren açık bir hedefi temsil eder."
type: docs
weight: 1570
url: /tr/java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitRExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitRExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitRExplicitDestination extends ExplicitDestination
```

Sayfanın içeriğini, sol, alt, sağ ve üst (left, bottom, right, top) koordinatlarıyla belirtilen dikdörtgeni pencereye hem yatay hem de dikey olarak tamamen sığacak şekilde yeterince büyütülmüş olarak gösteren açık hedefi temsil eder. Gereken yatay ve dikey büyütme faktörleri farklıysa, ikisinden küçüğünü kullanarak, diğer boyutta dikdörtgeni pencere içinde ortalar. Parametrelerden herhangi biri için null değer, öngörülemeyen davranışlara yol açabilir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | Uzak explicit destination oluşturur. |
| [FitRExplicitDestination](#FitRExplicitDestination-int-double-double-double-double-) | Uzak explicit destination oluşturur. |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | Örneği oluşturur ve DOM sayfa nesnesi ve görünür parametrelerle başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBottom](#getBottom--) | Görünür dikdörtgenin alt dikey koordinatını alır. |
| [getLeft](#getLeft--) | Görünür dikdörtgenin sol yatay koordinatını alır. |
| [getRight](#getRight--) | Görünür dikdörtgenin sağ yatay koordinatını alır. |
| [getTop](#getTop--) | Görünür dikdörtgenin üst dikey koordinatını alır. |
| [toString](#toString--) | Nesne durumunu string değerine dönüştürür. Örnek: "1 FitR 100 200 300 400". |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
Uzak explicit destination oluşturur.

### FitRExplicitDestination {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```

Uzak explicit destination oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Uzak belgenin hedef sayfa numarası. |
| sol |  | Görünür dikdörtgenin sol yatay koordinatı. |
| alt |  | Görünür dikdörtgenin alt dikey koordinatı. |
| sağ |  | Görünür dikdörtgenin sağ yatay koordinatı. |
| üst |  | Görünür dikdörtgenin üst dikey koordinatı. |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
Örneği oluşturur ve DOM sayfa nesnesi ve görünür parametrelerle başlatır.

### getBottom {#getBottom--}
```
public double getBottom()
```

Görünür dikdörtgenin alt dikey koordinatını alır.

**Returns:**
double değer

### getLeft {#getLeft--}
```
public double getLeft()
```

Görünür dikdörtgenin sol yatay koordinatını alır.

**Returns:**
double değer

### getRight {#getRight--}
```
public double getRight()
```

Görünür dikdörtgenin sağ yatay koordinatını alır.

**Returns:**
double değer

### getTop {#getTop--}
```
public double getTop()
```

Görünür dikdörtgenin üst dikey koordinatını alır.

**Returns:**
double değer

### toString {#toString--}
```
public String toString()
```

Nesne durumunu string değerine dönüştürür. Örnek: "1 FitR 100 200 300 400".

**Returns:**
Nesne durumunu temsil eden string değeri.
