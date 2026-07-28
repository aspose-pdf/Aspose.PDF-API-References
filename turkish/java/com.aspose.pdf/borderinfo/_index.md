---
title: "BorderInfo"
linktitle: "BorderInfo"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu sınıf, grafik öğeleri için kenarı temsil eder."
type: docs
weight: 370
url: /tr/java/com.aspose.pdf/borderinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BorderInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class BorderInfo extends Object implements com.aspose.ms.System.ICloneable
```

Bu sınıf, grafik öğeleri için kenarı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BorderInfo](#BorderInfo--) | Yeni bir {@code BorderInfo} sınıfı örneği başlatır. |
| [BorderInfo](#BorderInfo-int-) | Yeni bir {@code BorderInfo} sınıfı örneği başlatır. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.Color-) | Yeni bir {@code BorderInfo} sınıfı örneği başlatır. |
| [BorderInfo](#BorderInfo-int-float-) | Yeni bir {@code BorderInfo} sınıfı örneği başlatır. |
| [BorderInfo](#BorderInfo-int-float-com.aspose.pdf.Color-) | Yeni bir {@code BorderInfo} sınıfı örneği başlatır. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.GraphInfo-) | Yeni bir {@code BorderInfo} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone](#deepClone--) | Yeni bir BorderInfo nesnesini klonlar. |
| [getBottom](#getBottom--) | Sınırın alt kısmını gösteren nesneyi alır. |
| [getLeft](#getLeft--) | Sınırın sol kısmını gösteren {@code GraphInfo} nesnesini alır. |
| [getRight](#getRight--) | Sınırın sağ kısmını gösteren {@code GraphInfo} nesnesini alır. |
| [getRoundedBorderRadius](#getRoundedBorderRadius--) | Yuvarlatılmış sınır yarıçapını alır. |
| [getTop](#getTop--) | Sınırın üst kısmını gösteren {@code GraphInfo} nesnesini alır. |
| [setBottom](#setBottom-com.aspose.pdf.GraphInfo-) | Sınırın alt kısmını gösteren nesneyi ayarlar. |
| [setLeft](#setLeft-com.aspose.pdf.GraphInfo-) | Sınırın sol kısmını gösteren {@code GraphInfo} nesnesini ayarlar. |
| [setRight](#setRight-com.aspose.pdf.GraphInfo-) | Sınırın sağ kısmını gösteren {@code GraphInfo} nesnesini ayarlar. |
| [setRoundedBorderRadius](#setRoundedBorderRadius-double-) | Yuvarlatılmış sınır yarıçapını ayarlar. |
| [setTop](#setTop-com.aspose.pdf.GraphInfo-) | Sınırın üst kısmını gösteren {@code GraphInfo} nesnesini ayarlar. |

### BorderInfo {#BorderInfo--}
```
public BorderInfo()
```

Yeni bir {@code BorderInfo} sınıfı örneği başlatır.

### BorderInfo {#BorderInfo-int-}
```
public BorderInfo(int borderSide)
```

Yeni bir {@code BorderInfo} sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| borderSide |  | Sınır kenarları bilgisini gösterir. Örneğin: (BorderSide.Left \ | BorderSide.Top). |

### BorderInfo {#BorderInfo-int-com.aspose.pdf.Color-}
Yeni bir {@code BorderInfo} sınıfı örneği başlatır.

### BorderInfo {#BorderInfo-int-float-}
```
public BorderInfo(int borderSide, float borderWidth)
```

Yeni bir {@code BorderInfo} sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| borderSide |  | Sınır kenarları bilgisini gösterir. Örneğin: (BorderSide.Left \ | BorderSide.Top). |
| borderWidth |  | Sınırın genişliği. |

### BorderInfo {#BorderInfo-int-float-com.aspose.pdf.Color-}
Yeni bir {@code BorderInfo} sınıfı örneği başlatır.

### BorderInfo {#BorderInfo-int-com.aspose.pdf.GraphInfo-}
Yeni bir {@code BorderInfo} sınıfı örneği başlatır.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Yeni bir BorderInfo nesnesini klonlar.

**Returns:**
Yeni BorderInfo nesnesi.

### getBottom {#getBottom--}
```
public GraphInfo getBottom()
```

Sınırın alt kısmını gösteren nesneyi alır.

**Returns:**
alt

### getLeft {#getLeft--}
```
public GraphInfo getLeft()
```

Sınırın sol kısmını gösteren {@code GraphInfo} nesnesini alır.

**Returns:**
kenarın solunu gösteren nesne.

### getRight {#getRight--}
```
public GraphInfo getRight()
```

Sınırın sağ kısmını gösteren {@code GraphInfo} nesnesini alır.

**Returns:**
kenarın sağını gösteren nesne.

### getRoundedBorderRadius {#getRoundedBorderRadius--}
```
public double getRoundedBorderRadius()
```

Yuvarlatılmış sınır yarıçapını alır.

**Returns:**
değer

### getTop {#getTop--}
```
public GraphInfo getTop()
```

Sınırın üst kısmını gösteren {@code GraphInfo} nesnesini alır.

**Returns:**
üst kenarı gösteren nesne

### setBottom {#setBottom-com.aspose.pdf.GraphInfo-}
Sınırın alt kısmını gösteren nesneyi ayarlar.

### setLeft {#setLeft-com.aspose.pdf.GraphInfo-}
Sınırın sol kısmını gösteren {@code GraphInfo} nesnesini ayarlar.

### setRight {#setRight-com.aspose.pdf.GraphInfo-}
Sınırın sağ kısmını gösteren {@code GraphInfo} nesnesini ayarlar.

### setRoundedBorderRadius {#setRoundedBorderRadius-double-}
```
public void setRoundedBorderRadius(double value)
```

Yuvarlatılmış sınır yarıçapını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setTop {#setTop-com.aspose.pdf.GraphInfo-}
Sınırın üst kısmını gösteren {@code GraphInfo} nesnesini ayarlar.
