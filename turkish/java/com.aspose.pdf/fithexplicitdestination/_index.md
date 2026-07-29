---
title: "FitHExplicitDestination"
linktitle: "FitHExplicitDestination"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfanın, dikey koordinat üstünün pencerenin üst kenarına konumlandırıldığı ve sayfa içeriğinin sadece büyütüldüğü açık hedefi temsil eder."
type: docs
weight: 1560
url: /tr/java/com.aspose.pdf/fithexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitHExplicitDestination extends ExplicitDestination
```

Sayfayı, dikey koordinat üst (top) pencerenin üst kenarına yerleştirilmiş ve sayfa içeriği, sayfanın tüm genişliğini pencereye sığacak şekilde yeterince büyütülmüş olarak gösteren açık hedefi temsil eder. Üst (top) için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Document-int-double-) | Uzak explicit destination oluşturur. |
| [FitHExplicitDestination](#FitHExplicitDestination-int-double-) | Uzak explicit destination oluşturur. |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Page-double-) | Örneği oluşturur ve DOM sayfa nesnesi ve üst parametresi ile başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTop](#getTop--) | Pencerenin üst kenarına konumlandırılan dikey koordinat üst değerini alır. |
| [toString](#toString--) | Nesne durumunu dize değerine dönüştürür. Örnek: "1 FitH 100". |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Document-int-double-}
Uzak explicit destination oluşturur.

### FitHExplicitDestination {#FitHExplicitDestination-int-double-}
```
public FitHExplicitDestination(int pageNumber, double top)
```

Uzak explicit destination oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Uzak belgenin hedef sayfa numarası. |
| üst |  | Pencerenin üst kenarına konumlandırılan dikey koordinat üst. |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Page-double-}
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

Nesne durumunu dize değerine dönüştürür. Örnek: "1 FitH 100".

**Returns:**
Nesne durumunu temsil eden string değeri.
