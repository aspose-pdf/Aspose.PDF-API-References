---
title: "XYZExplicitDestination"
linktitle: "XYZExplicitDestination"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Pencerenin sol üst köşesinde konumlandırılmış (sol, üst) koordinatlarıyla sayfayı ve sayfa içeriğini gösteren açık hedefi temsil eder."
type: docs
weight: 5800
url: /tr/java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.XYZExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.XYZExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class XYZExplicitDestination extends ExplicitDestination
```

<p> Pencerenin sol üst köşesine konumlandırılmış (sol, üst) koordinatlarıyla sayfayı gösteren ve sayfa içeriğini zoom faktörüyle büyüten açık hedefi temsil eder. left, top veya zoom parametrelerinden herhangi biri için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir. 0 zoom değeri, null değerle aynı anlama gelir. </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p>

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | Uzak explicit destination oluşturur. |
| [XYZExplicitDestination](#XYZExplicitDestination-int-double-double-double-) | Uzak explicit destination oluşturur. |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | Örneği oluşturur ve DOM sayfa nesnesi ve görünür parametrelerle başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createDestination](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | Gerekirse sayfa dönüşünü dikkate alarak sayfanın belirtilen konumuna hedef oluşturur. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | Belirtilen sayfaya hedef oluşturur. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | Belirtilen sayfanın sol üst köşesine hedef oluşturur. |
| [getLeft](#getLeft--) | Pencerenin sol üst köşesinin sol yatay koordinatını alır. |
| [getTop](#getTop--) | Pencerenin sol üst köşesinin üst dikey koordinatını alır. |
| [getZoom](#getZoom--) | Yakınlaştırma faktörünü alır. |
| [toString](#toString--) | Nesnenin durumunu string değere dönüştürür. Örnek: "1 XYZ 100 200 3". |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
Uzak explicit destination oluşturur.

### XYZExplicitDestination {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```

Uzak explicit destination oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Uzak belgenin hedef sayfa numarası. |
| sol |  | Pencerenin sol üst köşesinin sol yatay koordinatı. |
| üst |  | Pencerenin sol üst köşesinin üst dikey koordinatı |
| zoom |  | Zoom faktörü. |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
Örneği oluşturur ve DOM sayfa nesnesi ve görünür parametrelerle başlatır.

### createDestination {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
Gerekirse sayfa dönüşünü dikkate alarak sayfanın belirtilen konumuna hedef oluşturur.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
Belirtilen sayfaya hedef oluşturur.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
Belirtilen sayfanın sol üst köşesine hedef oluşturur.

### getLeft {#getLeft--}
```
public double getLeft()
```

Pencerenin sol üst köşesinin sol yatay koordinatını alır.

**Returns:**
double

### getTop {#getTop--}
```
public double getTop()
```

Pencerenin sol üst köşesinin üst dikey koordinatını alır.

**Returns:**
double

### getZoom {#getZoom--}
```
public double getZoom()
```

Yakınlaştırma faktörünü alır.

**Returns:**
double

### toString {#toString--}
```
public String toString()
```

Nesnenin durumunu string değere dönüştürür. Örnek: "1 XYZ 100 200 3".

**Returns:**
Nesne durumunu temsil eden string değeri.
