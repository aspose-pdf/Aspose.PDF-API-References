---
title: "Damga"
linktitle: "Damga"
second_title: "Aspose.PDF for Java API Referansı"
description: "Alt sınıflar olarak gelen çeşitli damga türleri için soyut bir sınıf."
type: docs
weight: 4620
url: /tr/java/com.aspose.pdf/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp

```
public abstract class Stamp extends Object
```

Alt sınıflar olarak gelen çeşitli damga türleri için soyut bir sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Stamp](#Stamp--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBottomMargin](#getBottomMargin--) | Damganın alt kenar boşluğunu alır. |
| [getHeight](#getHeight--) | Sayfada damganın istenen yüksekliğini alır. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Sayfada damganın yatay hizalamasını alır. |
| [getLeftMargin](#getLeftMargin--) | Damganın sol kenar boşluğunu alır. |
| [getOpacity](#getOpacity--) | Damganın opaklığını gösteren bir değeri alır. Değer 0.0 ile 1.0 arasındadır. Varsayılan değer 1.0'dır. |
| [getOutlineOpacity](#getOutlineOpacity--) | Damganın kenar çizgi opaklığını gösteren bir değeri alır. Değer 0.0 ile 1.0 arasındadır. Varsayılan değer 1.0'dır. |
| [getOutlineWidth](#getOutlineWidth--) | Damganın kenar çizgi genişliğinin değerini alır. Varsayılan değer 1.0'dır. |
| [getRightMargin](#getRightMargin--) | Damganın sağ kenar boşluğunu alır. |
| [getRotate](#getRotate--) | Damga içeriğinin dönüşünü {@code Rotation} değerlerine göre alır. Not: Bu özellik, 90 derece katları (0, 90, 180, 270 derece) olan açıları ayarlamak içindir. Rastgele açı ayarlamak için RotateAngle özelliğini kullanın. Eğer ArbitraryAngle ile ayarlanan açı 90'ın katı değilse Rotate özelliği Rotation.None döndürür. |
| [getRotateAngle](#getRotateAngle--) | Damganın derece cinsinden dönüş açısını alır. Bu özellik, rastgele bir dönüş açısı ayarlamayı sağlar. |
| [getStampId](#getStampId--) | Damga kimliğini alır. |
| [getTopMargin](#getTopMargin--) | Damganın üst kenar boşluğunu alır. |
| [getVerticalAlignment](#getVerticalAlignment--) | Sayfada damganın dikey hizalamasını alır. |
| [getWidth](#getWidth--) | Sayfada damganın istenen genişliğini alır. |
| [getXIndent](#getXIndent--) | Sol taraftan başlayarak damganın yatay koordinatını al. |
| [getYIndent](#getYIndent--) | Alt taraftan başlayarak damganın dikey koordinatını al. |
| [getZoom](#getZoom--) | Damganın yakınlaştırma faktörünü alır. Damgayı ölçeklendirmeyi sağlar. Lütfen ZoomX ve ZoomY özellik çiftinin her eksen için ayrı ayrı yakınlaştırma faktörü ayarlamaya izin verdiğini unutmayın. Bu özelliğin ayarlanması hem ZoomX hem de ZoomY özelliklerini değiştirir. ZoomX ve ZoomY farklı ise Zoom özelliği ZoomX değerini döndürür. |
| [getZoomX](#getZoomX--) | Damganın yatay yakınlaştırma faktörünü alır. Damgayı yatay olarak ölçeklendirmeyi sağlar. |
| [getZoomY](#getZoomY--) | Damganın dikey yakınlaştırma faktörünü alır. Damgayı dikey olarak ölçeklendirmeyi sağlar. |
| [isBackground](#isBackground--) | İçeriğin arka plan olarak damgalandığını gösteren bir bool değer alır. Değer true ise damga içeriği altta yer alır. Varsayılan olarak değer false'tur, damga içeriği üstte yer alır. |
| [put](#put-com.aspose.pdf.Page-) | Sayfaya damga ekler. |
| [setBackground](#setBackground-boolean-) | İçeriğin arka plan olarak damgalandığını gösteren bir bool değer ayarlar. Değer true ise damga içeriği altta yer alır. Varsayılan olarak değer false'tur, damga içeriği üstte yer alır. |
| [setBottomMargin](#setBottomMargin-double-) | Damganın alt kenar boşluğunu ayarlar. |
| [setHeight](#setHeight-double-) | Sayfada damganın istenen yüksekliğini ayarlar. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Sayfada damganın yatay hizalamasını ayarlar. |
| [setLeftMargin](#setLeftMargin-double-) | Damganın sol kenar boşluğunu ayarlar. |
| [setOpacity](#setOpacity-double-) | Damganın opaklığını göstermek için bir değer ayarlar. Değer 0.0 ile 1.0 arasındadır. Varsayılan değer 1.0'dır. |
| [setOutlineOpacity](#setOutlineOpacity-double-) | Damganın kontur opaklığını göstermek için bir değer ayarlar. Değer 0.0 ile 1.0 arasındadır. Varsayılan değer 1.0'dır. |
| [setOutlineWidth](#setOutlineWidth-double-) | Damganın kontur genişliğinin değerini ayarlar. Varsayılan değer 1.0'dır. |
| [setRightMargin](#setRightMargin-double-) | Damganın sağ kenar boşluğunu ayarlar. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Damga içeriğinin dönüşünü {@code Rotation} değerlerine göre ayarlar. Not: Bu özellik, 90 derecenin katları (0, 90, 180, 270 derece) olan açıları ayarlamak içindir. İstediğiniz açıyı ayarlamak için RotateAngle özelliğini kullanın. Eğer ArbitraryAngle ile ayarlanan açı 90'ın katı değilse Rotate özelliği Rotation.None döndürür. |
| [setRotateAngle](#setRotateAngle-double-) | Damganın dönüş açısını derece cinsinden ayarlar. Bu özellik, istediğiniz dönüş açısını ayarlamaya izin verir. |
| [setStampId](#setStampId-int-) | Damga kimliğini ayarlar. |
| [setTopMargin](#setTopMargin-double-) | Damganın üst kenar boşluğunu ayarlar. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Sayfada damganın dikey hizalamasını ayarlar. |
| [setWidth](#setWidth-double-) | Sayfada damganın istenen genişliğini ayarlar. |
| [setXIndent](#setXIndent-double-) | Sol taraftan başlayarak damganın yatay koordinatını ayarlar. |
| [setYIndent](#setYIndent-double-) | Alt taraftan başlayarak damganın dikey koordinatını ayarlar. |
| [setZoom](#setZoom-double-) | Damganın yakınlaştırma faktörünü alır. Damgayı ölçeklendirmeyi sağlar. Lütfen ZoomX ve ZoomY özellik çiftinin her eksen için ayrı ayrı yakınlaştırma faktörü ayarlamaya izin verdiğini unutmayın. Bu özelliğin ayarlanması hem ZoomX hem de ZoomY özelliklerini değiştirir. ZoomX ve ZoomY farklı ise Zoom özelliği ZoomX değerini döndürür. |
| [setZoomX](#setZoomX-double-) | Damganın yatay yakınlaştırma faktörünü ayarlar. Damgayı yatay olarak ölçeklendirmeye izin verir. |
| [setZoomY](#setZoomY-double-) | Damganın dikey yakınlaştırma faktörünü ayarlar. Damgayı dikey olarak ölçeklendirmeye izin verir. |

### Stamp {#Stamp--}
```
public Stamp()
```



### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Damganın alt kenar boşluğunu alır.

**Returns:**
double değer

### getHeight {#getHeight--}
```
public double getHeight()
```

Sayfada damganın istenen yüksekliğini alır.

**Returns:**
double değer

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Sayfada damganın yatay hizalamasını alır.

**Returns:**
HorizontalAlignment değeri @see HorizontalAlignment

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Damganın sol kenar boşluğunu alır.

**Returns:**
double değer

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Damganın opaklığını gösteren bir değeri alır. Değer 0.0 ile 1.0 arasındadır. Varsayılan değer 1.0'dır.

**Returns:**
double değer

### getOutlineOpacity {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```

Damganın kenar çizgi opaklığını gösteren bir değeri alır. Değer 0.0 ile 1.0 arasındadır. Varsayılan değer 1.0'dır.

**Returns:**
double değer

### getOutlineWidth {#getOutlineWidth--}
```
public double getOutlineWidth()
```

Damganın kenar çizgi genişliğinin değerini alır. Varsayılan değer 1.0'dır.

**Returns:**
double değer

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Damganın sağ kenar boşluğunu alır.

**Returns:**
double değer

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Damga içeriğinin dönüşünü {@code Rotation} değerlerine göre alır. Not: Bu özellik, 90 derece katları (0, 90, 180, 270 derece) olan açıları ayarlamak içindir. Rastgele açı ayarlamak için RotateAngle özelliğini kullanın. Eğer ArbitraryAngle ile ayarlanan açı 90'ın katı değilse Rotate özelliği Rotation.None döndürür.

**Returns:**
Dönüş değeri @see Rotation

### getRotateAngle {#getRotateAngle--}
```
public double getRotateAngle()
```

Damganın derece cinsinden dönüş açısını alır. Bu özellik, rastgele bir dönüş açısı ayarlamayı sağlar.

**Returns:**
double değer

### getStampId {#getStampId--}
```
public int getStampId()
```

Damga kimliğini alır.

**Returns:**
Damganın tanımlayıcısı.

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Damganın üst kenar boşluğunu alır.

**Returns:**
double değer

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Sayfada damganın dikey hizalamasını alır.

**Returns:**
DikeyHizalama değeri @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Sayfada damganın istenen genişliğini alır.

**Returns:**
double değer

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Sol taraftan başlayarak damganın yatay koordinatını al.

**Returns:**
double değer

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Alt taraftan başlayarak damganın dikey koordinatını al.

**Returns:**
double değer

### getZoom {#getZoom--}
```
public double getZoom()
```

Damganın yakınlaştırma faktörünü alır. Damgayı ölçeklendirmeyi sağlar. Lütfen ZoomX ve ZoomY özellik çiftinin her eksen için ayrı ayrı yakınlaştırma faktörü ayarlamaya izin verdiğini unutmayın. Bu özelliğin ayarlanması hem ZoomX hem de ZoomY özelliklerini değiştirir. ZoomX ve ZoomY farklı ise Zoom özelliği ZoomX değerini döndürür.

**Returns:**
double değer

### getZoomX {#getZoomX--}
```
public double getZoomX()
```

Damganın yatay yakınlaştırma faktörünü alır. Damgayı yatay olarak ölçeklendirmeyi sağlar.

**Returns:**
double değer

### getZoomY {#getZoomY--}
```
public double getZoomY()
```

Damganın dikey yakınlaştırma faktörünü alır. Damgayı dikey olarak ölçeklendirmeyi sağlar.

**Returns:**
double değer

### isBackground {#isBackground--}
```
public boolean isBackground()
```

İçeriğin arka plan olarak damgalandığını gösteren bir bool değer alır. Değer true ise damga içeriği altta yer alır. Varsayılan olarak değer false'tur, damga içeriği üstte yer alır.

**Returns:**
boolean değer

### put {#put-com.aspose.pdf.Page-}
Sayfaya damga ekler.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

İçeriğin arka plan olarak damgalandığını gösteren bir bool değer ayarlar. Değer true ise damga içeriği altta yer alır. Varsayılan olarak değer false'tur, damga içeriği üstte yer alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Damganın alt kenar boşluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Sayfada damganın istenen yüksekliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Sayfada damganın yatay hizalamasını ayarlar.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Damganın sol kenar boşluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Damganın opaklığını göstermek için bir değer ayarlar. Değer 0.0 ile 1.0 arasındadır. Varsayılan değer 1.0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setOutlineOpacity {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```

Damganın kontur opaklığını göstermek için bir değer ayarlar. Değer 0.0 ile 1.0 arasındadır. Varsayılan değer 1.0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setOutlineWidth {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```

Damganın kontur genişliğinin değerini ayarlar. Varsayılan değer 1.0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Damganın sağ kenar boşluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Damga içeriğinin dönüşünü {@code Rotation} değerlerine göre ayarlar. Not: Bu özellik, 90 derecenin katları (0, 90, 180, 270 derece) olan açıları ayarlamak içindir. İstediğiniz açıyı ayarlamak için RotateAngle özelliğini kullanın. Eğer ArbitraryAngle ile ayarlanan açı 90'ın katı değilse Rotate özelliği Rotation.None döndürür.

### setRotateAngle {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```

Damganın dönüş açısını derece cinsinden ayarlar. Bu özellik, istediğiniz dönüş açısını ayarlamaya izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | dönüş açısı |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Damga kimliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Damga kimliğinin yeni değeri. |

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Damganın üst kenar boşluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Sayfada damganın dikey hizalamasını ayarlar.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Sayfada damganın istenen genişliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Sol taraftan başlayarak damganın yatay koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Alt taraftan başlayarak damganın dikey koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setZoom {#setZoom-double-}
```
public void setZoom(double value)
```

Damganın yakınlaştırma faktörünü alır. Damgayı ölçeklendirmeyi sağlar. Lütfen ZoomX ve ZoomY özellik çiftinin her eksen için ayrı ayrı yakınlaştırma faktörü ayarlamaya izin verdiğini unutmayın. Bu özelliğin ayarlanması hem ZoomX hem de ZoomY özelliklerini değiştirir. ZoomX ve ZoomY farklı ise Zoom özelliği ZoomX değerini döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setZoomX {#setZoomX-double-}
```
public void setZoomX(double value)
```

Damganın yatay yakınlaştırma faktörünü ayarlar. Damgayı yatay olarak ölçeklendirmeye izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setZoomY {#setZoomY-double-}
```
public void setZoomY(double value)
```

Damganın dikey yakınlaştırma faktörünü ayarlar. Damgayı dikey olarak ölçeklendirmeye izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |
