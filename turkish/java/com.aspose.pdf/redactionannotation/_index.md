---
title: "RedactionAnnotation"
linktitle: "RedactionAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Redact açıklamasını temsil eder."
type: docs
weight: 4120
url: /tr/java/com.aspose.pdf/redactionannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.RedactionAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class RedactionAnnotation extends MarkupAnnotation
```

Redact açıklamasını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.IDocument-) | RedactionAnnotation için yapıcı. Generator içinde kullanmak için. |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | RedactAnnotation için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Açıklamayı işlemek için ziyaretçi nesnesini kabul eder. |
| [flatten](#flatten--) | Açıklamayı düzleştirir, yani açıklamayı kaldırır ve içeriğini ekler. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getBorderColor](#getBorderColor--) | Redaction aktif olmadığında çizilen kenarın rengini alır. |
| [getDefaultAppearance](#getDefaultAppearance--) | Metni biçimlendirmek için kullanılacak varsayılan görünüm dizesini alır veya ayarlar. |
| [getFillColor](#getFillColor--) | Açıklamayı doldurmak için rengi alır. |
| [getFontSize](#getFontSize--) | OverlayText için yazı tipi boyutunu alır. |
| [getOverlayText](#getOverlayText--) | Kırpma açıklaması üzerine yazdırılacak metni alır. |
| [getQuadPoint](#getQuadPoint--) | Kaldırılması amaçlanan içerik bölgesinin koordinatlarını belirten 8xN sayı dizisi. |
| [getQuadPoints](#getQuadPoints--) | n dörtgenin koordinatlarını belirten nokta dizisini alır. Her dörtgen, açıklamanın altındaki metinde bir kelimeyi veya ardışık kelimeler grubunu kapsar. |
| [getTextAlignment](#getTextAlignment--) | Kaplama Metninin hizalamasını alır. |
| [isRepeat](#isRepeat--) | Doğru ise kaplama metni açıklama üzerinde tekrarlanır. |
| [redact](#redact--) | Açıklamayı düzleştirir ve sayfa içeriklerini kırpar (yani kırpılmış açıklamanın altındaki metin ve görüntü içeriğini kaldırır). |
| [redactExact](#redactExact--) | Açıklamayı düzleştirir ve sayfa içeriklerini kırpar (yani kırpılmış açıklamanın tam altındaki metin ve görüntü içeriğini kaldırır). |
| [setBorderColor](#setBorderColor-com.aspose.pdf.Color-) | Kırpma etkin olmadığında çizilen kenarlığın rengini ayarlar. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Metni biçimlendirmek için kullanılacak varsayılan görünüm dizesini alır veya ayarlar. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | Açıklamayı doldurmak için rengi ayarlar. |
| [setFontSize](#setFontSize-float-) | Kaplama Metni için yazı tipi boyutunu ayarlar. Varsayılan değer 10'dur. |
| [setOverlayText](#setOverlayText-java.lang.String-) | Kırpma açıklaması üzerine yazdırılacak metni ayarlar. |
| [setQuadPoint](#setQuadPoint-com.aspose.pdf.Point:A-) | Kaldırılması amaçlanan içerik bölgesinin koordinatlarını belirten 8xN sayı dizisi. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | n dörtgenin koordinatlarını belirten nokta dizisini ayarlar. Her dörtgen, açıklamanın altındaki metinde bir kelimeyi veya ardışık kelimeler grubunu kapsar. |
| [setRepeat](#setRepeat-boolean-) | Doğru ise kaplama metni açıklama üzerinde tekrarlanır. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Kaplama Metninin hizalamasını ayarlar. |

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.IDocument-}
RedactionAnnotation için yapıcı. Generator içinde kullanmak için.

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
RedactAnnotation için yapıcı.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Açıklamayı işlemek için ziyaretçi nesnesini kabul eder.

### flatten {#flatten--}
```
public void flatten()
```

Açıklamayı düzleştirir, yani açıklamayı kaldırır ve içeriğini ekler.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
AnnotationType öğesi @see AnnotationType

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

Redaction aktif olmadığında çizilen kenarın rengini alır.

**Returns:**
Renk değeri

### getDefaultAppearance {#getDefaultAppearance--}
```
public final String getDefaultAppearance()
```

Metni biçimlendirmek için kullanılacak varsayılan görünüm dizesini alır veya ayarlar.

**Returns:**
String değeri

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

Açıklamayı doldurmak için rengi alır.

**Returns:**
renk değeri

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

OverlayText için yazı tipi boyutunu alır.

**Returns:**
int değer

### getOverlayText {#getOverlayText--}
```
public String getOverlayText()
```

Kırpma açıklaması üzerine yazdırılacak metni alır.

**Returns:**
string value

### getQuadPoint {#getQuadPoint--}
```
public Point [] getQuadPoint()
```

Kaldırılması amaçlanan içerik bölgesinin koordinatlarını belirten 8xN sayı dizisi.

**Returns:**
nokta dizisi

### getQuadPoints {#getQuadPoints--}
```
@Deprecated public Point [] getQuadPoints()
```

n dörtgenin koordinatlarını belirten nokta dizisini alır. Her dörtgen, açıklamanın altındaki metinde bir kelimeyi veya ardışık kelimeler grubunu kapsar.

**Returns:**
Point değerlerinin dizisi

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Kaplama Metninin hizalamasını alır.

**Returns:**
HorizontalAlignment değeri @see HorizontalAlignment

### isRepeat {#isRepeat--}
```
public boolean isRepeat()
```

Doğru ise kaplama metni açıklama üzerinde tekrarlanır.

**Returns:**
boolean değer

### redact {#redact--}
```
public void redact()
```

Açıklamayı düzleştirir ve sayfa içeriklerini kırpar (yani kırpılmış açıklamanın altındaki metin ve görüntü içeriğini kaldırır).

### redactExact {#redactExact--}
```
public void redactExact()
```

Açıklamayı düzleştirir ve sayfa içeriklerini kırpar (yani kırpılmış açıklamanın tam altındaki metin ve görüntü içeriğini kaldırır).

### setBorderColor {#setBorderColor-com.aspose.pdf.Color-}
Kırpma etkin olmadığında çizilen kenarlığın rengini ayarlar.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Metni biçimlendirmek için kullanılacak varsayılan görünüm dizesini alır veya ayarlar.

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
Açıklamayı doldurmak için rengi ayarlar.

### setFontSize {#setFontSize-float-}
```
public final void setFontSize(float fontSize)
```

Kaplama Metni için yazı tipi boyutunu ayarlar. Varsayılan değer 10'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontSize |  | int değer |

### setOverlayText {#setOverlayText-java.lang.String-}
Kırpma açıklaması üzerine yazdırılacak metni ayarlar.

### setQuadPoint {#setQuadPoint-com.aspose.pdf.Point:A-}
Kaldırılması amaçlanan içerik bölgesinin koordinatlarını belirten 8xN sayı dizisi.

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
n dörtgenin koordinatlarını belirten nokta dizisini ayarlar. Her dörtgen, açıklamanın altındaki metinde bir kelimeyi veya ardışık kelimeler grubunu kapsar.

### setRepeat {#setRepeat-boolean-}
```
public void setRepeat(boolean value)
```

Doğru ise kaplama metni açıklama üzerinde tekrarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Kaplama Metninin hizalamasını ayarlar.
