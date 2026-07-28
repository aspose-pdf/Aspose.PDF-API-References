---
title: "FitVExplicitDestination"
linktitle: "FitVExplicitDestination"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfayı, yatay koordinat solun pencerenin sol kenarında konumlandırıldığı ve sayfa içeriğinin sadece büyütüldüğü şekilde gösteren açık hedefi temsil eder."
type: docs
weight: 1580
url: /tr/java/com.aspose.pdf/fitvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitVExplicitDestination extends ExplicitDestination
```

Sayfayı, yatay koordinat sol (left) pencerenin sol kenarına yerleştirilmiş ve sayfa içeriği, sayfanın tüm yüksekliğini pencereye sığacak şekilde yeterince büyütülmüş olarak gösteren açık hedefi temsil eder. Sol (left) için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Document-int-double-) | Uzak explicit destination oluşturur. |
| [FitVExplicitDestination](#FitVExplicitDestination-int-double-) | Uzak explicit destination oluşturur. |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Page-double-) | Örneği oluşturur ve DOM sayfa nesnesi ile left parametresiyle başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLeft](#getLeft--) | Pencerenin sol kenarında konumlandırılmış yatay koordinatı alır. |
| [toString](#toString--) | Nesne durumunu dize değerine dönüştürür. Örnek: "1 FitV 100". |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Document-int-double-}
Uzak explicit destination oluşturur.

### FitVExplicitDestination {#FitVExplicitDestination-int-double-}
```
public FitVExplicitDestination(int pageNumber, double left)
```

Uzak explicit destination oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Uzak belgenin hedef sayfa numarası. |
| sol |  | Pencerenin sol kenarında konumlandırılmış yatay koordinat. |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Page-double-}
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

Nesne durumunu dize değerine dönüştürür. Örnek: "1 FitV 100".

**Returns:**
Nesne durumunu temsil eden string değeri.
