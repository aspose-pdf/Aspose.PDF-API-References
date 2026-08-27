---
title: "LineAnnotation"
linktitle: "LineAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Çizgi açıklamasını temsil eden sınıf."
type: docs
weight: 2710
url: /tr/java/com.aspose.pdf/lineannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.LineAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class LineAnnotation extends MarkupAnnotation
```

Çizgi açıklamasını temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Generator ile kullanılmak için yapıcı. |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Belirtilen sayfada yeni bir Line annotation oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Açıklama işleme için ziyaretçiyi kabul eder. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Matris dönüşümüne göre Başlangıç ve Bitiş noktalarını günceller. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getCaptionOffset](#getCaptionOffset--) | Altyazı metni ofsetini normal konumundan alır. |
| [getCaptionPosition](#getCaptionPosition--) | Açıklama altyazı konumunu alır. |
| [getEnding](#getEnding--) | Çizgi bitiş noktasını alır. |
| [getEndingStyle](#getEndingStyle--) | Çizgi bitiş noktasının bitiş stilini alır. |
| [getIntent](#getIntent--) | Line annotation'ın amacını alır. |
| [getInteriorColor](#getInteriorColor--) | Açıklamanın iç renk değerini alır. |
| [getLeaderLine](#getLeaderLine--) | Lider çizgi uzunluğunu alır. |
| [getLeaderLineExtension](#getLeaderLineExtension--) | Lider çizgi uzantısının uzunluğunu alır. |
| [getLeaderLineOffset](#getLeaderLineOffset--) | Lider çizgi ofsetini alır. |
| [getMeasure](#getMeasure--) | Bu açıklama için belirtilen ölçü birimleri. |
| [getShowCaption](#getShowCaption--) | İçeriğin altyazı olarak gösterilmesi gerektiğini belirleyen boolean bayrağı alır. |
| [getStarting](#getStarting--) | Çizginin başlangıç noktasını alır. |
| [getStartingStyle](#getStartingStyle--) | Çizgi başlangıç noktası için çizgi bitiş stilini alır. |
| [setCaptionOffset](#setCaptionOffset-com.aspose.pdf.Point-) | Altyazı metni ofsetini normal konumundan ayarlar. |
| [setCaptionPosition](#setCaptionPosition-com.aspose.pdf.CaptionPosition-) | Açıklama altyazı konumunu ayarlar. |
| [setEnding](#setEnding-com.aspose.pdf.Point-) | Çizgi bitiş noktasını ayarlar. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Çizgi bitiş noktasının bitiş stilini ayarlar. |
| [setIntent](#setIntent-com.aspose.pdf.LineIntent-) | Line annotation'ın amacını ayarlar. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Açıklamanın iç renk değerini ayarlar. |
| [setLeaderLine](#setLeaderLine-double-) | Lider çizgi uzunluğunu ayarlar. |
| [setLeaderLineExtension](#setLeaderLineExtension-double-) | Lider çizgi uzantısının uzunluğunu ayarlar. |
| [setLeaderLineOffset](#setLeaderLineOffset-double-) | Lider çizgi ofsetini ayarlar. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Bu açıklama için belirtilen ölçü birimleri. |
| [setShowCaption](#setShowCaption-boolean-) | İçeriğin başlık olarak gösterilmesi gerektiğini belirleyen boolean bayrağı ayarlar. |
| [setStarting](#setStarting-com.aspose.pdf.Point-) | Çizginin başlangıç noktasını ayarlar. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Çizgi başlangıç noktası için çizgi bitiş stilini ayarlar. |

### LineAnnotation {#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Generator ile kullanılmak için yapıcı.

### LineAnnotation {#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Belirtilen sayfada yeni bir Line annotation oluşturur.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Açıklama işleme için ziyaretçiyi kabul eder.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Matris dönüşümüne göre Başlangıç ve Bitiş noktalarını günceller.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
AnnotationType öğesi @see AnnotationType

### getCaptionOffset {#getCaptionOffset--}
```
public Point getCaptionOffset()
```

Altyazı metni ofsetini normal konumundan alır.

**Returns:**
Nokta nesnesi

### getCaptionPosition {#getCaptionPosition--}
```
public CaptionPosition getCaptionPosition()
```

Açıklama altyazı konumunu alır.

**Returns:**
CaptionPosition öğesi @see CaptionPosition

### getEnding {#getEnding--}
```
public Point getEnding()
```

Çizgi bitiş noktasını alır.

**Returns:**
Nokta değeri

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Çizgi bitiş noktasının bitiş stilini alır.

**Returns:**
LineEnding öğesi @see LineEnding

### getIntent {#getIntent--}
```
public LineIntent getIntent()
```

Line annotation'ın amacını alır.

**Returns:**
LineIntent öğesi @see LineIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Açıklamanın iç renk değerini alır.

**Returns:**
Color nesnesi

### getLeaderLine {#getLeaderLine--}
```
public double getLeaderLine()
```

Lider çizgi uzunluğunu alır.

**Returns:**
double değer

### getLeaderLineExtension {#getLeaderLineExtension--}
```
public double getLeaderLineExtension()
```

Lider çizgi uzantısının uzunluğunu alır.

**Returns:**
double değer

### getLeaderLineOffset {#getLeaderLineOffset--}
```
public double getLeaderLineOffset()
```

Lider çizgi ofsetini alır.

**Returns:**
double değer

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Bu açıklama için belirtilen ölçü birimleri.

**Returns:**
Measure nesnesi

### getShowCaption {#getShowCaption--}
```
public boolean getShowCaption()
```

İçeriğin altyazı olarak gösterilmesi gerektiğini belirleyen boolean bayrağı alır.

**Returns:**
boolean değer

### getStarting {#getStarting--}
```
public Point getStarting()
```

Çizginin başlangıç noktasını alır.

**Returns:**
Nokta değeri

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Çizgi başlangıç noktası için çizgi bitiş stilini alır.

**Returns:**
LineEnding öğesi @see LineEnding

### setCaptionOffset {#setCaptionOffset-com.aspose.pdf.Point-}
Altyazı metni ofsetini normal konumundan ayarlar.

### setCaptionPosition {#setCaptionPosition-com.aspose.pdf.CaptionPosition-}
Açıklama altyazı konumunu ayarlar.

### setEnding {#setEnding-com.aspose.pdf.Point-}
Çizgi bitiş noktasını ayarlar.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Çizgi bitiş noktasının bitiş stilini ayarlar.

### setIntent {#setIntent-com.aspose.pdf.LineIntent-}
Line annotation'ın amacını ayarlar.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Açıklamanın iç renk değerini ayarlar.

### setLeaderLine {#setLeaderLine-double-}
```
public void setLeaderLine(double value)
```

Lider çizgi uzunluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setLeaderLineExtension {#setLeaderLineExtension-double-}
```
public void setLeaderLineExtension(double value)
```

Lider çizgi uzantısının uzunluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setLeaderLineOffset {#setLeaderLineOffset-double-}
```
public void setLeaderLineOffset(double value)
```

Lider çizgi ofsetini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Bu açıklama için belirtilen ölçü birimleri.

### setShowCaption {#setShowCaption-boolean-}
```
public void setShowCaption(boolean value)
```

İçeriğin başlık olarak gösterilmesi gerektiğini belirleyen boolean bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setStarting {#setStarting-com.aspose.pdf.Point-}
Çizginin başlangıç noktasını ayarlar.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Çizgi başlangıç noktası için çizgi bitiş stilini ayarlar.
