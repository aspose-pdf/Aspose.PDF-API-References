---
title: "FitBHExplicitDestination"
linktitle: "FitBHExplicitDestination"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfanın, dikey koordinat üstünün pencerenin üst kenarına konumlandırıldığı ve sayfa içeriğinin sadece büyütüldüğü açık hedefi temsil eder."
type: docs
weight: 1530
url: /tr/java/com.aspose.pdf/fitbhexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBHExplicitDestination extends ExplicitDestination
```

Sayfayı, dikey koordinat üst (top) pencerenin üst kenarına yerleştirilmiş ve sayfa içeriği, sınırlayıcı kutusunun tüm genişliğini pencereye sığacak şekilde yeterince büyütülmüş olarak gösteren açık hedefi temsil eder. Üst (top) için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-) | Uzak explicit destination oluşturur. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-int-double-) | Uzak explicit destination oluşturur. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Page-double-) | Örneği oluşturur ve DOM sayfa nesnesi ve üst parametresi ile başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTop](#getTop--) | Pencerenin üst kenarına konumlandırılan dikey koordinat üst değerini alır. |
| [toString](#toString--) | Nesnenin durumunu string değere dönüştürür. Örnek: "1 FitBH 100". |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-}
Uzak explicit destination oluşturur.

### FitBHExplicitDestination {#FitBHExplicitDestination-int-double-}
```
public FitBHExplicitDestination(int pageNumber, double top)
```

Uzak explicit destination oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Uzak belgenin hedef sayfa numarası. |
| üst |  | Pencerenin üst kenarına konumlandırılan dikey koordinat üst. |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Page-double-}
Örneği oluşturur ve DOM sayfa nesnesi ve üst parametresi ile başlatır.

### getTop {#getTop--}
```
public double getTop()
```

Pencerenin üst kenarına konumlandırılan dikey koordinat üst değerini alır.

**Returns:**
double değer

### toString {#toString--}
```
public String toString()
```

Nesnenin durumunu string değere dönüştürür. Örnek: "1 FitBH 100".

**Returns:**
Nesne durumunu temsil eden string değeri.
