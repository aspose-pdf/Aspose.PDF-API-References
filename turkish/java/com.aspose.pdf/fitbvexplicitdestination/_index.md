---
title: "FitBVExplicitDestination"
linktitle: "FitBVExplicitDestination"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfayı, yatay koordinat solun pencerenin sol kenarında konumlandırıldığı ve sayfa içeriğinin sadece büyütüldüğü şekilde gösteren açık hedefi temsil eder."
type: docs
weight: 1540
url: /tr/java/com.aspose.pdf/fitbvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBVExplicitDestination extends ExplicitDestination
```

Sayfayı, yatay koordinat sol (left) pencerenin sol kenarına yerleştirilmiş ve sayfa içeriği, sınırlayıcı kutusunun tüm yüksekliğini pencereye sığacak şekilde yeterince büyütülmüş olarak gösteren açık hedefi temsil eder. Sol (left) için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FitBVExplicitDestination](#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-) | Uzak explicit destination oluşturur. |
| [FitBVExplicitDestination](#FitBVExplicitDestination-int-double-) | Uzak explicit destination oluşturur. |
| [FitBVExplicitDestination](#FitBVExplicitDestination-com.aspose.pdf.Page-double-) | Örneği oluşturur ve DOM sayfa nesnesi ile left parametresiyle başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLeft](#getLeft--) | Pencerenin sol kenarında konumlandırılmış yatay koordinatı alır. |
| [toString](#toString--) | Nesne durumunu string değere dönüştürür. Örnek: "1 FitBV 100". |

### FitBVExplicitDestination {#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-}
Uzak explicit destination oluşturur.

### FitBVExplicitDestination {#FitBVExplicitDestination-int-double-}
```
public FitBVExplicitDestination(int pageNumber, double left)
```

Uzak explicit destination oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Uzak belgenin hedef sayfa numarası. |
| sol |  | Pencerenin sol kenarında konumlandırılmış yatay koordinat. |

### FitBVExplicitDestination {#FitBVExplicitDestination-com.aspose.pdf.Page-double-}
Örneği oluşturur ve DOM sayfa nesnesi ile left parametresiyle başlatır.

### getLeft {#getLeft--}
```
public double getLeft()
```

Pencerenin sol kenarında konumlandırılmış yatay koordinatı alır.

**Returns:**
double değer

### toString {#toString--}
```
public String toString()
```

Nesne durumunu string değere dönüştürür. Örnek: "1 FitBV 100".

**Returns:**
Nesne durumunu temsil eden string değeri.
