---
title: "Annotation"
linktitle: "Annotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir açıklama nesnesini temsil eden sınıf."
type: docs
weight: 60
url: /tr/java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class Annotation extends BaseParagraph
```

Bir açıklama nesnesini temsil eden sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Ek açıklama işleme için ziyaretçiyi kabul eder. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Parametreleri ve görünümü, matris dönüşümüne göre günceller. |
| [createAnnotation](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | Yalnızca dahili kullanım için |
| [flatten](#flatten--) | Ek açıklama içeriğini doğrudan sayfaya yerleştirir, ek açıklama nesnesi kaldırılacaktır. |
| [getActiveState](#getActiveState--) | Mevcut ek açıklama görünüm durumunu alır. |
| [getAlignment](#getAlignment--) | ff / * / * Mevcut durum adlarına göre "checked" durumunun adını döndürür. / * / * / * |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getAppearance](#getAppearance--) | Ek açıklamanın görünüm sözlüğünü alır. |
| [getAssignedPageIndex](#getAssignedPageIndex--) | Ek açıklamanın görünmesi gereken sayfanın indeksini (bir tabanlı) alır. |
| [getBorder](#getBorder--) | Ek açıklama kenarlık özelliklerini alır. {@code Border} |
| [getCharacteristics](#getCharacteristics--) | Ek açıklama özelliklerini alır. |
| [getColor](#getColor--) | Ek açıklama rengini alır. |
| [getContents](#getContents--) | Ek açıklama metnini alır. |
| [getEngineDict](#getEngineDict--) | Yalnızca dahili |
| [getEngineObj](#getEngineObj--) | Yalnızca dahili kullanım için |
| [getFlags](#getFlags--) | Ek açıklamanın bayraklarını alır. |
| [getFullName](#getFullName--) | Ek açıklamanın tam nitelikli adını alır. |
| [getHeight](#getHeight--) | Ek açıklamanın yüksekliğini alır. |
| [getHorizontalAlignment_Annotation_New](#getHorizontalAlignment_Annotation_New--) | Ek açıklama için metin hizalamasını alır veya ayarlar. |
| [getModified](#getModified--) | Ek açıklamanın son değiştirildiği tarih ve saati alır. |
| [getModifiedInternal](#getModifiedInternal--) | Ek açıklamanın son değiştirildiği tarih ve saati alır. |
| [getName](#getName--) | Sayfadaki ek açıklama adını alır. |
| [getNormalAppearance](#getNormalAppearance--) | Normal görünümü alır. |
| [getPage](#getPage--) | Bu ek açıklamanın ilişkili olduğu sayfa nesnesini alır. |
| [getPageIndex](#getPageIndex--) | Ek açıklamayı içeren sayfanın indeksini alır. |
| [getPageIndex](#getPageIndex-com.aspose.pdf.Annotation-) | Ek açıklamayı içeren sayfanın indeksini alır. |
| [getPdfActions](#getPdfActions--) | Ek açıklama eylemlerinin listesini alır. |
| [getRect](#getRect--) | Ek açıklama dikdörtgenini alır. |
| [getRectangle](#getRectangle-boolean-) | Sayfa dönüşünü dikkate alarak ek açıklamanın dikdörtgenini döndürür. |
| [getStates](#getStates--) | Ek açıklamanın görünüm sözlüğünü alır. |
| [getTextHorizontalAlignment](#getTextHorizontalAlignment--) | Ek açıklama için metin hizalamasını alır. |
| [getWidth](#getWidth--) | Ek açıklamanın genişliğini alır. |
| [initialize](#initialize-com.aspose.pdf.IDocument-) | Örnek başlatma |
| [isUpdateAppearanceOnConvert](#isUpdateAppearanceOnConvert--) | Doğru ise, ek açıklama görünümü PDF belgesi görüntüye dönüştürülmeden önce güncellenecektir. Bu, alanların doğru şekilde dönüştürülmesini sağlar ancak muhtemelen daha fazla zaman gerektirir. |
| [isUseFontSubset](#isUseFontSubset--) | Bu özellik doğru olarak ayarlanırsa, yazı tipleri belgeye alt küme olarak eklenecektir. Varsayılan değer doğrudur. |
| [setActiveState](#setActiveState-java.lang.String-) | Geçerli ek açıklama görünüm durumunu ayarlar. |
| [setAlignment](#setAlignment-com.aspose.pdf.TextAlignment-) | Ek açıklama hizalaması. Bu özellik artık kullanılmamaktadır. Bunun yerine getHorizontalAlignment_Annotation_New kullanın. |
| [setAssignedPageIndex](#setAssignedPageIndex-com.aspose.ms.System.Nullable-) | Ek açıklamanın görünmesi gereken sayfa indeksini (bir tabanlı) ayarlar. |
| [setBorder](#setBorder-com.aspose.pdf.Border-) | Ek açıklama kenarlık özelliklerini ayarlar. {@code Border} |
| [setColor](#setColor-com.aspose.pdf.Color-) | Ek açıklama rengini ayarlar. |
| [setContents](#setContents-java.lang.String-) | Ek açıklama metnini ayarlar. |
| [setFlags](#setFlags-int-) | Ek açıklamanın bayraklarını ayarlar. |
| [setHeight](#setHeight-double-) | Ek açıklamanın yüksekliğini ayarlar. |
| [setHorizontalAlignment_Annotation_New](#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-) | Ek açıklama için metin hizalamasını alır veya ayarlar. |
| [setModified](#setModified-java.util.Date-) | Ek açıklamanın son değiştirildiği tarih ve saati ayarlar. |
| [setModifiedInternal](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Ek açıklamanın son değiştirildiği tarih ve saati ayarlar. |
| [setName](#setName-java.lang.String-) | Sayfadaki ek açıklama adını ayarlar. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Ek açıklama dikdörtgenini ayarlar. |
| [setTextHorizontalAlignment](#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Ek açıklama için metin hizalamasını ayarlar. |
| [setUpdateAppearanceOnConvert](#setUpdateAppearanceOnConvert-boolean-) | Doğru ise, ek açıklama görünümü PDF belgesi görüntüye dönüştürülmeden önce güncellenecektir. Bu, alanların doğru şekilde dönüştürülmesini sağlar ancak muhtemelen daha fazla zaman gerektirir. |
| [setUseFontSubset](#setUseFontSubset-boolean-) | Bu özellik doğru olarak ayarlanırsa, yazı tipleri belgeye alt küme olarak eklenecektir. Varsayılan değer doğrudur. |
| [setWidth](#setWidth-double-) | Ek açıklamanın genişliğini ayarlar. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Ek açıklama işleme için ziyaretçiyi kabul eder.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Parametreleri ve görünümü, matris dönüşümüne göre günceller.

### createAnnotation {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
Yalnızca dahili kullanım için

### flatten {#flatten--}
```
public void flatten()
```

Ek açıklama içeriğini doğrudan sayfaya yerleştirir, ek açıklama nesnesi kaldırılacaktır.

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Mevcut ek açıklama görünüm durumunu alır.

**Returns:**
String değeri

### getAlignment {#getAlignment--}
```
@Deprecated public TextAlignment getAlignment()
```

ff / * / * Mevcut durum adlarına göre "checked" durumunun adını döndürür. / * / * / *

**Returns:**
Dize değeri /

### getAnnotationType {#getAnnotationType--}
```
public abstract AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
tam sayı değeri @see AnnotationType

### getAppearance {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```

Ek açıklamanın görünüm sözlüğünü alır.

**Returns:**
AppearanceDictionary nesnesi

### getAssignedPageIndex {#getAssignedPageIndex--}
```
public final com.aspose.ms.System.Nullable< Integer > getAssignedPageIndex()
```

Ek açıklamanın görünmesi gereken sayfanın indeksini (bir tabanlı) alır.

**Returns:**
Ek açıklamanın görünmesi gereken sayfa indeksi (bir tabanlı).

### getBorder {#getBorder--}
```
public Border getBorder()
```

Ek açıklama kenarlık özelliklerini alır. {@code Border}

**Returns:**
Border nesnesi

### getCharacteristics {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```

Ek açıklama özelliklerini alır.

**Returns:**
Characteristics nesnesi

### getColor {#getColor--}
```
public Color getColor()
```

Ek açıklama rengini alır.

**Returns:**
Color nesnesi

### getContents {#getContents--}
```
public String getContents()
```

Ek açıklama metnini alır.

**Returns:**
String değeri

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Yalnızca dahili

**Returns:**
IPdfDictionary nesnesi

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Yalnızca dahili kullanım için

**Returns:**
Dahili nesne

### getFlags {#getFlags--}
```
public int getFlags()
```

Ek açıklamanın bayraklarını alır.

**Returns:**
Ek açıklamanın bayrakları @see AnnotationFlags

### getFullName {#getFullName--}
```
public String getFullName()
```

Ek açıklamanın tam nitelikli adını alır.

**Returns:**
String değeri

### getHeight {#getHeight--}
```
public double getHeight()
```

Ek açıklamanın yüksekliğini alır.

**Returns:**
ek açıklamanın yüksekliği

### getHorizontalAlignment_Annotation_New {#getHorizontalAlignment_Annotation_New--}
```
@Deprecated public final HorizontalAlignment getHorizontalAlignment_Annotation_New()
```

Ek açıklama için metin hizalamasını alır veya ayarlar.

**Returns:**
ek açıklama için metin hizalaması. @see HorizontalAlignment @deprecated TextHorizontalAlignment özelliğini kullanın

### getModified {#getModified--}
```
public Date getModified()
```

Ek açıklamanın son değiştirildiği tarih ve saati alır.

**Returns:**
ek açıklamanın son değiştirildiği tarih ve saat.

### getModifiedInternal {#getModifiedInternal--}
```
public com.aspose.ms.System.DateTime getModifiedInternal()
```

Ek açıklamanın son değiştirildiği tarih ve saati alır.

**Returns:**
DateTime nesnesi

### getName {#getName--}
```
public String getName()
```

Sayfadaki ek açıklama adını alır.

**Returns:**
String değeri

### getNormalAppearance {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```

Normal görünümü alır.

**Returns:**
XForm nesnesi

### getPage {#getPage--}
```
public Page getPage()
```

Bu ek açıklamanın ilişkili olduğu sayfa nesnesini alır.

**Returns:**
Page nesnesi

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Ek açıklamayı içeren sayfanın indeksini alır.

**Returns:**
int değer

### getPageIndex {#getPageIndex-com.aspose.pdf.Annotation-}
Ek açıklamayı içeren sayfanın indeksini alır.

**Returns:**
int değer

### getPdfActions {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```

Ek açıklama eylemlerinin listesini alır.

**Returns:**
PdfActionCollection örneği

### getRect {#getRect--}
```
public Rectangle getRect()
```

Ek açıklama dikdörtgenini alır.

**Returns:**
Rectangle nesnesi

### getRectangle {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```

Sayfa dönüşünü dikkate alarak ek açıklamanın dikdörtgenini döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| considerRotation |  | Eğer true ise, sayfa dönüşü dikkate alınır. |

**Returns:**
Rectangle nesnesi

### getStates {#getStates--}
```
public AppearanceDictionary getStates()
```

Ek açıklamanın görünüm sözlüğünü alır.

**Returns:**
AppearanceDictionary nesnesi

### getTextHorizontalAlignment {#getTextHorizontalAlignment--}
```
public HorizontalAlignment getTextHorizontalAlignment()
```

Ek açıklama için metin hizalamasını alır.

**Returns:**
ek açıklama için metin hizalaması. @see HorizontalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Ek açıklamanın genişliğini alır.

**Returns:**
double değer, ek açıklamanın genişliği.

### initialize {#initialize-com.aspose.pdf.IDocument-}
Örnek başlatma

### isUpdateAppearanceOnConvert {#isUpdateAppearanceOnConvert--}
```
public static boolean isUpdateAppearanceOnConvert()
```

Doğru ise, ek açıklama görünümü PDF belgesi görüntüye dönüştürülmeden önce güncellenecektir. Bu, alanların doğru şekilde dönüştürülmesini sağlar ancak muhtemelen daha fazla zaman gerektirir.

**Returns:**
boolean değer

### isUseFontSubset {#isUseFontSubset--}
```
public static boolean isUseFontSubset()
```

Bu özellik doğru olarak ayarlanırsa, yazı tipleri belgeye alt küme olarak eklenecektir. Varsayılan değer doğrudur.

**Returns:**
boolean değer

### setActiveState {#setActiveState-java.lang.String-}
Geçerli ek açıklama görünüm durumunu ayarlar.

### setAlignment {#setAlignment-com.aspose.pdf.TextAlignment-}
Ek açıklama hizalaması. Bu özellik artık kullanılmamaktadır. Bunun yerine getHorizontalAlignment_Annotation_New kullanın.

### setAssignedPageIndex {#setAssignedPageIndex-com.aspose.ms.System.Nullable-}
Ek açıklamanın görünmesi gereken sayfa indeksini (bir tabanlı) ayarlar.

### setBorder {#setBorder-com.aspose.pdf.Border-}
Ek açıklama kenarlık özelliklerini ayarlar. {@code Border}

### setColor {#setColor-com.aspose.pdf.Color-}
Ek açıklama rengini ayarlar.

### setContents {#setContents-java.lang.String-}
Ek açıklama metnini ayarlar.

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Ek açıklamanın bayraklarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ek açıklamanın bayrakları @see AnnotationFlags |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Ek açıklamanın yüksekliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ek açıklamanın yüksekliği |

### setHorizontalAlignment_Annotation_New {#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-}
Ek açıklama için metin hizalamasını alır veya ayarlar.

### setModified {#setModified-java.util.Date-}
Ek açıklamanın son değiştirildiği tarih ve saati ayarlar.

### setModifiedInternal {#setModifiedInternal-com.aspose.ms.System.DateTime-}
Ek açıklamanın son değiştirildiği tarih ve saati ayarlar.

### setName {#setName-java.lang.String-}
Sayfadaki ek açıklama adını ayarlar.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Ek açıklama dikdörtgenini ayarlar.

### setTextHorizontalAlignment {#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Ek açıklama için metin hizalamasını ayarlar.

### setUpdateAppearanceOnConvert {#setUpdateAppearanceOnConvert-boolean-}
```
public static void setUpdateAppearanceOnConvert(boolean value)
```

Doğru ise, ek açıklama görünümü PDF belgesi görüntüye dönüştürülmeden önce güncellenecektir. Bu, alanların doğru şekilde dönüştürülmesini sağlar ancak muhtemelen daha fazla zaman gerektirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUseFontSubset {#setUseFontSubset-boolean-}
```
public static void setUseFontSubset(boolean value)
```

Bu özellik doğru olarak ayarlanırsa, yazı tipleri belgeye alt küme olarak eklenecektir. Varsayılan değer doğrudur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Ek açıklamanın genişliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ek açıklamanın genişliği. |
