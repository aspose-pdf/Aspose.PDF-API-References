---
title: "FreeTextAnnotation"
linktitle: "FreeTextAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfada metni doğrudan gösteren bir serbest metin açıklamasını temsil eder. Normal bir metin açıklamasının aksine, serbest metin açıklamasının açık veya kapalı bir durumu yoktur; bunun yerine."
type: docs
weight: 1790
url: /tr/java/com.aspose.pdf/freetextannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FreeTextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FreeTextAnnotation extends MarkupAnnotation
```

Sayfada doğrudan metin gösteren bir serbest metin açıklamasını temsil eder. Normal bir metin açıklamasının aksine, serbest metin açıklamasının açık ya da kapalı durumu yoktur; bir açılır pencerede gösterilmek yerine metin her zaman görünür.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | Generator ile kullanılacak yapıcı. |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | Belirtilen sayfada yeni bir FreeText açıklaması oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Açıklamayı işlemek için ziyaretçi nesnesini kabul eder. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getCallout](#getCallout--) | Çağrı çizgisini belirten nokta dizisi. |
| [getDefaultAppearance](#getDefaultAppearance--) | Metni biçimlendirmek için kullanılacak varsayılan görünüm dizesini alır. |
| [getDefaultAppearanceObject](#getDefaultAppearanceObject--) | FreeText açıklamasının varsayılan görünümünü temsil eden nesne. |
| [getDefaultStyle](#getDefaultStyle--) | Varsayılan stil dizesini alır. |
| [getEndingStyle](#getEndingStyle--) | Çizgi bitiş noktasının çizgi bitiş stilini alır. |
| [getIntent](#getIntent--) | Serbest metin açıklamasının amacını alır. |
| [getJustification](#getJustification--) | Açıklamanın metnini görüntülerken kullanılacak hizalama (justification) biçimini belirten kodu alır. |
| [getRotate](#getRotate--) | Açıklama dönüş açısı. |
| [getStartingStyle](#getStartingStyle--) | Çizgi bitiş noktasının çizgi bitiş stilini alır veya ayarlar. OThis özelliği artık kullanılmamaktadır, lütfen EndingStyle kullanın. |
| [getTextRectangle](#getTextRectangle--) | Açıklamanın Rect girdisi ile o dikdörtgenin içinde bulunan bir dikdörtgen arasındaki sayısal farkları tanımlayan dikdörtgen. İç dikdörtgen, açıklamanın metninin görüntülenmesi gereken yerdir. |
| [getTextStyle](#getTextStyle--) | Görünümdeki metnin stilini alır veya ayarlar. Metin stili değiştiğinde, metnin görünümü güncellenir. |
| [isValidXml](#isValidXml-java.lang.String-) |  |
| [setCallout](#setCallout-com.aspose.pdf.Point:A-) | Çağrı çizgisini belirten nokta dizisi. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Metni biçimlendirmek için kullanılacak varsayılan görünüm dizesini ayarlar. |
| [setDefaultStyle](#setDefaultStyle-java.lang.String-) | Varsayılan stil dizesini ayarlar. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Çizgi bitiş noktasının çizgi bitiş stilini ayarlar. |
| [setIntent](#setIntent-com.aspose.pdf.FreeTextIntent-) | Serbest metin açıklamasının amacını ayarlar. |
| [setJustification](#setJustification-com.aspose.pdf.Justification-) | Açıklamanın metnini görüntülerken kullanılacak hizalama (justification) biçimini belirten kodu ayarlar. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Açıklama dönüş açısı. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Çizgi bitiş noktasının çizgi bitiş stilini alır veya ayarlar. OThis özelliği artık kullanılmamaktadır, lütfen EndingStyle kullanın. |
| [setTextRectangle](#setTextRectangle-com.aspose.pdf.Rectangle-) | Açıklamanın Rect girdisi ile o dikdörtgenin içinde bulunan bir dikdörtgen arasındaki sayısal farkları tanımlayan dikdörtgen. İç dikdörtgen, açıklamanın metninin görüntülenmesi gereken yerdir. |
| [setTextStyle](#setTextStyle-int-int-int-) | textStyle parametresi tarafından belirlenen biçimlendirmeyi, fromInd indeksinden toInd indeksine kadar olan metin parçacığı için ayarlar. |
| [setTextStyle](#setTextStyle-int-java.lang.String-double-java.awt.Color-) | textStyle parametresi tarafından belirlenen biçimlendirmeyi tüm ek açıklama metni için ayarlar. |
| [setTextStyle](#setTextStyle-com.aspose.pdf.TextStyle-) | Metnin görünümündeki stili ayarlar. Metin stili değiştiğinde, metin görünümü güncellenir. |
| [updateAppearance](#updateAppearance--) | Metin değiştirildikten/taşındıktan sonra Görünümü günceller. |

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
Generator ile kullanılacak yapıcı.

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
Belirtilen sayfada yeni bir FreeText açıklaması oluşturur.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Açıklamayı işlemek için ziyaretçi nesnesini kabul eder.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
int değer

### getCallout {#getCallout--}
```
public final Point [] getCallout()
```

Çağrı çizgisini belirten nokta dizisi.

**Returns:**
Point dizisi

### getDefaultAppearance {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```

Metni biçimlendirmek için kullanılacak varsayılan görünüm dizesini alır.

**Returns:**
String değeri

### getDefaultAppearanceObject {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```

FreeText açıklamasının varsayılan görünümünü temsil eden nesne.

**Returns:**
DefaultAppearance nesnesi

### getDefaultStyle {#getDefaultStyle--}
```
public String getDefaultStyle()
```

Varsayılan stil dizesini alır.

**Returns:**
String değeri

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Çizgi bitiş noktasının çizgi bitiş stilini alır.

**Returns:**
LineEnding değeri @see LineEnding

### getIntent {#getIntent--}
```
public FreeTextIntent getIntent()
```

Serbest metin açıklamasının amacını alır.

**Returns:**
int değeri @see FreeTextIntent

### getJustification {#getJustification--}
```
public Justification getJustification()
```

Açıklamanın metnini görüntülerken kullanılacak hizalama (justification) biçimini belirten kodu alır.

**Returns:**
int değeri @see Justification

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Açıklama dönüş açısı.

**Returns:**
Rotation öğesi @see Rotation

### getStartingStyle {#getStartingStyle--}
```
public final LineEnding getStartingStyle()
```

Çizgi bitiş noktasının çizgi bitiş stilini alır veya ayarlar. OThis özelliği artık kullanılmamaktadır, lütfen EndingStyle kullanın.

**Returns:**
LineEnding öğesi

### getTextRectangle {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```

Açıklamanın Rect girdisi ile o dikdörtgenin içinde bulunan bir dikdörtgen arasındaki sayısal farkları tanımlayan dikdörtgen. İç dikdörtgen, açıklamanın metninin görüntülenmesi gereken yerdir.

**Returns:**
Dikdörtgen örneği

### getTextStyle {#getTextStyle--}
```
public TextStyle getTextStyle()
```

Görünümdeki metnin stilini alır veya ayarlar. Metin stili değiştiğinde, metnin görünümü güncellenir.

**Returns:**
TextStyle değeri

### isValidXml {#isValidXml-java.lang.String-}


### setCallout {#setCallout-com.aspose.pdf.Point:A-}
Çağrı çizgisini belirten nokta dizisi.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Metni biçimlendirmek için kullanılacak varsayılan görünüm dizesini ayarlar.

### setDefaultStyle {#setDefaultStyle-java.lang.String-}
Varsayılan stil dizesini ayarlar.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Çizgi bitiş noktasının çizgi bitiş stilini ayarlar.

### setIntent {#setIntent-com.aspose.pdf.FreeTextIntent-}
Serbest metin açıklamasının amacını ayarlar.

### setJustification {#setJustification-com.aspose.pdf.Justification-}
Açıklamanın metnini görüntülerken kullanılacak hizalama (justification) biçimini belirten kodu ayarlar.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Açıklama dönüş açısı.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Çizgi bitiş noktasının çizgi bitiş stilini alır veya ayarlar. OThis özelliği artık kullanılmamaktadır, lütfen EndingStyle kullanın.

### setTextRectangle {#setTextRectangle-com.aspose.pdf.Rectangle-}
Açıklamanın Rect girdisi ile o dikdörtgenin içinde bulunan bir dikdörtgen arasındaki sayısal farkları tanımlayan dikdörtgen. İç dikdörtgen, açıklamanın metninin görüntülenmesi gereken yerdir.

### setTextStyle {#setTextStyle-int-int-int-}
```
public final void setTextStyle(int fromInd, int toInd, int textStyles)
```

textStyle parametresi tarafından belirlenen biçimlendirmeyi, fromInd indeksinden toInd indeksine kadar olan metin parçacığı için ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fromInd |  | Metin parçacığının başlangıç indeksi (0'dan). |
| toInd |  | Metin parçacığının bitiş indeksi (0'dan sayılarak, bu indeks dahil değildir). |
| textStyles |  | Metin parçacığına uygulanan stil(ler). |

### setTextStyle {#setTextStyle-int-java.lang.String-double-java.awt.Color-}
textStyle parametresi tarafından belirlenen biçimlendirmeyi tüm ek açıklama metni için ayarlar.

### setTextStyle {#setTextStyle-com.aspose.pdf.TextStyle-}
Metnin görünümündeki stili ayarlar. Metin stili değiştiğinde, metin görünümü güncellenir.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Metin değiştirildikten/taşındıktan sonra Görünümü günceller.
