---
title: "FloatingBox"
linktitle: "FloatingBox"
second_title: "Aspose.PDF for Java API Referansı"
description: "Pdf belgesindeki bir FloatingBox'ı temsil eder. FloatingBox özel konumlandırılmıştır."
type: docs
weight: 1610
url: /tr/java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FloatingBox, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FloatingBox

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class FloatingBox extends BaseParagraph
```

Pdf belgesindeki bir FloatingBox'ı temsil eder. FloatingBox özel konumlandırılmıştır.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FloatingBox](#FloatingBox--) | Yeni bir {@code FloatingBox} sınıfı örneği başlatır. |
| [FloatingBox](#FloatingBox-float-float-) | Belirtilen genişlik ve yükseklik ile yeni bir {@code FloatingBox} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone](#deepClone--) | Yeni bir {@code FloatingBox} nesnesini klonlar. Yüzen kutudaki paragraflar klonlanmaz. |
| [getBackgroundColor](#getBackgroundColor--) | Yüzen kutunun arka plan rengini gösteren bir nesne alır. |
| [getBackgroundImage](#getBackgroundImage--) | Sayfa için arka plan görüntüsünü alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz). |
| [getBorder](#getBorder--) | Yüzen kutunun kenar bilgilerini gösteren bir nesne alır. |
| [getColumnInfo](#getColumnInfo--) | Bir sütun bilgisini alır |
| [getHeight](#getHeight--) | Yüzen kutunun yüksekliğini gösteren bir kayan nokta değeri alır. |
| [getLeft](#getLeft--) | Tablonun sol koordinatını alır. |
| [getPadding](#getPadding--) | Yüzen kutunun dolgu (padding) değerini gösteren bir nesne alır. |
| [getParagraphs](#getParagraphs--) | Hücredeki tüm paragrafları gösteren bir koleksiyon alır. |
| [getPositioningMode](#getPositioningMode--) | Sayfadaki FloatingBox konumunu belirlemek için varyantı belirtir. |
| [getTop](#getTop--) | Tablonun üst koordinatını alır. |
| [getWidth](#getWidth--) | Yüzen kutunun genişliğini gösteren bir kayan nokta değeri alır. |
| [isNeedRepeating](#isNeedRepeating--) | Paragrafın bir sonraki sayfada tekrarlanıp tekrarlanmayacağını gösteren bir boolean değer alır. Varsayılan değer true'tır. Bu öznitelik yalnızca paragrafın kendisi ve ReferenceParagraphID'sine başvuran nesne her ikisi de RepeatingRows içinde yer aldığında geçerlidir. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Yüzen kutunun arka plan rengini gösteren bir nesne ayarlar. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Sayfa için arka plan görüntüsünü alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz). |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Yüzen kutunun kenar bilgilerini gösteren bir nesne ayarlar. |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | Bir sütun bilgisini ayarlar |
| [setHeight](#setHeight-double-) | Yüzen kutunun yüksekliğini gösteren bir kayan nokta değeri ayarlar. |
| [setLeft](#setLeft-double-) | Tablonun sol koordinatını ayarlar. |
| [setNeedRepeating](#setNeedRepeating-boolean-) | Paragrafın bir sonraki sayfada tekrarlanıp tekrarlanmayacağını gösteren bir boolean değer ayarlar. Varsayılan değer true'tır. Bu öznitelik yalnızca paragrafın kendisi ve ReferenceParagraphID'sine başvuran nesne her ikisi de RepeatingRows içinde yer aldığında geçerlidir. |
| [setPadding](#setPadding-com.aspose.pdf.MarginInfo-) | Yüzen kutunun dolgu (padding) değerini gösteren bir nesne ayarlar. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Hücredeki tüm paragrafları gösteren bir koleksiyon ayarlar. |
| [setPositioningMode](#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-) | Sayfadaki FloatingBox konumunu belirlemek için varyantı belirtir. |
| [setTop](#setTop-double-) | Tablonun üst koordinatını ayarlar. |
| [setWidth](#setWidth-double-) | Yüzen kutunun genişliğini gösteren bir kayan nokta değeri ayarlar. |

### FloatingBox {#FloatingBox--}
```
public FloatingBox()
```

Yeni bir {@code FloatingBox} sınıfı örneği başlatır.

### FloatingBox {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```

Belirtilen genişlik ve yükseklik ile yeni bir {@code FloatingBox} sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik |  | Kutunun genişliği. |
| yükseklik |  | Kutunun yüksekliği. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Yeni bir {@code FloatingBox} nesnesini klonlar. Yüzen kutudaki paragraflar klonlanmaz.

**Returns:**
Yeni {@code FloatingBox} nesnesi.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Yüzen kutunun arka plan rengini gösteren bir nesne alır.

**Returns:**
Arka plan rengini gösteren nesne.

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Sayfa için arka plan görüntüsünü alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz).

**Returns:**
Görüntü örneği

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Yüzen kutunun kenar bilgilerini gösteren bir nesne alır.

**Returns:**
kenar bilgisini gösteren nesne.

### getColumnInfo {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```

Bir sütun bilgisini alır

**Returns:**
ColumnInfo nesnesi

### getHeight {#getHeight--}
```
public double getHeight()
```

Yüzen kutunun yüksekliğini gösteren bir kayan nokta değeri alır.

**Returns:**
yüksekliği gösteren değer.

### getLeft {#getLeft--}
```
public double getLeft()
```

Tablonun sol koordinatını alır.

**Returns:**
tablonun sol koordinatı.

### getPadding {#getPadding--}
```
public MarginInfo getPadding()
```

Yüzen kutunun dolgu (padding) değerini gösteren bir nesne alır.

**Returns:**
dolgu alanını gösteren nesne.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Hücredeki tüm paragrafları gösteren bir koleksiyon alır.

**Returns:**
tüm paragrafları gösteren koleksiyon.

### getPositioningMode {#getPositioningMode--}
```
public final ParagraphPositioningMode getPositioningMode()
```

Sayfadaki FloatingBox konumunu belirlemek için varyantı belirtir.

**Returns:**
ParagraphPositioningMode öğesi

### getTop {#getTop--}
```
public double getTop()
```

Tablonun üst koordinatını alır.

**Returns:**
tablonun üst koordinatı.

### getWidth {#getWidth--}
```
public double getWidth()
```

Yüzen kutunun genişliğini gösteren bir kayan nokta değeri alır.

**Returns:**
double değer

### isNeedRepeating {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```

Paragrafın bir sonraki sayfada tekrarlanıp tekrarlanmayacağını gösteren bir boolean değer alır. Varsayılan değer true'tır. Bu öznitelik yalnızca paragrafın kendisi ve ReferenceParagraphID'sine başvuran nesne her ikisi de RepeatingRows içinde yer aldığında geçerlidir.

**Returns:**
boolean değer

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Yüzen kutunun arka plan rengini gösteren bir nesne ayarlar.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Sayfa için arka plan görüntüsünü alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz).

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Yüzen kutunun kenar bilgilerini gösteren bir nesne ayarlar.

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
Bir sütun bilgisini ayarlar

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Yüzen kutunun yüksekliğini gösteren bir kayan nokta değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | yüksekliği gösteren değer. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Tablonun sol koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | tablonun sol koordinatı. |

### setNeedRepeating {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```

Paragrafın bir sonraki sayfada tekrarlanıp tekrarlanmayacağını gösteren bir boolean değer ayarlar. Varsayılan değer true'tır. Bu öznitelik yalnızca paragrafın kendisi ve ReferenceParagraphID'sine başvuran nesne her ikisi de RepeatingRows içinde yer aldığında geçerlidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setPadding {#setPadding-com.aspose.pdf.MarginInfo-}
Yüzen kutunun dolgu (padding) değerini gösteren bir nesne ayarlar.

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Hücredeki tüm paragrafları gösteren bir koleksiyon ayarlar.

### setPositioningMode {#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-}
Sayfadaki FloatingBox konumunu belirlemek için varyantı belirtir.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Tablonun üst koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | tablonun üst koordinatı. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Yüzen kutunun genişliğini gösteren bir kayan nokta değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |
