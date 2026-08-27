---
title: "Annotation"
linktitle: "Annotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar ett annoteringsobjekt."
type: docs
weight: 60
url: /sv/java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class Annotation extends BaseParagraph
```

Klass som representerar ett annoteringsobjekt.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökare för annoteringsbearbetning. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Uppdatera parametrar och utseende enligt matrisomvandlingen. |
| [createAnnotation](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | Endast för internt bruk |
| [flatten](#flatten--) | Placera annoteringsinnehåll direkt på sidan, annoteringsobjektet kommer att tas bort. |
| [getActiveState](#getActiveState--) | Hämtar aktuellt annoteringsutseende. |
| [getAlignment](#getAlignment--) | ff / * / * Returnerar namn på "checked"-tillstånd enligt befintliga tillståndsnamn. / * / * / * |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getAppearance](#getAppearance--) | Hämtar utseendedictionary för annoteringen. |
| [getAssignedPageIndex](#getAssignedPageIndex--) | Hämtar sidindex (enbaserat) där annoteringen ska visas. |
| [getBorder](#getBorder--) | Hämtar annoteringens kantkarakteristik. {@code Border} |
| [getCharacteristics](#getCharacteristics--) | Hämtar annoteringens egenskaper. |
| [getColor](#getColor--) | Hämtar annoteringens färg. |
| [getContents](#getContents--) | Hämtar annoteringstext. |
| [getEngineDict](#getEngineDict--) | Endast intern |
| [getEngineObj](#getEngineObj--) | Endast för intern användning |
| [getFlags](#getFlags--) | Hämta flaggor för annoteringen. |
| [getFullName](#getFullName--) | Hämtar fullständigt kvalificerat namn för annoteringen. |
| [getHeight](#getHeight--) | Hämtar annoteringens höjd. |
| [getHorizontalAlignment_Annotation_New](#getHorizontalAlignment_Annotation_New--) | Hämtar eller anger textjustering för annoteringen. |
| [getModified](#getModified--) | Hämtar datum och tid då annotationen senast ändrades. |
| [getModifiedInternal](#getModifiedInternal--) | Hämtar datum och tid då annotationen senast ändrades. |
| [getName](#getName--) | Hämtar annoteringens namn på sidan. |
| [getNormalAppearance](#getNormalAppearance--) | Hämtar normal visning. |
| [getPage](#getPage--) | Hämtar sidobjektet som denna annotation är associerad med. |
| [getPageIndex](#getPageIndex--) | Hämtar sidans index som innehåller annotationen. |
| [getPageIndex](#getPageIndex-com.aspose.pdf.Annotation-) | Hämtar sidans index som innehåller annotationen. |
| [getPdfActions](#getPdfActions--) | Hämtar lista över annoteringsåtgärder. |
| [getRect](#getRect--) | Hämtar annoteringsrektangel. |
| [getRectangle](#getRectangle-boolean-) | Returnerar annoteringens rektangel med hänsyn till sidrotation. |
| [getStates](#getStates--) | Hämtar visningsordbok för annotationen. |
| [getTextHorizontalAlignment](#getTextHorizontalAlignment--) | Hämtar textjustering för annotationen. |
| [getWidth](#getWidth--) | Hämtar bredden på annotationen. |
| [initialize](#initialize-com.aspose.pdf.IDocument-) | Instansinitialisering |
| [isUpdateAppearanceOnConvert](#isUpdateAppearanceOnConvert--) | Om true uppdateras annoteringens utseende innan PDF-dokumentet konverteras till bild. Detta gör att fält konverteras korrekt men kan kräva mer tid. |
| [isUseFontSubset](#isUseFontSubset--) | Om den här egenskapen är satt till true kommer typsnitt att läggas till dokumentet som delmängder. Standardvärdet är true. |
| [setActiveState](#setActiveState-java.lang.String-) | Ställer in aktuellt annoteringsutseende. |
| [setAlignment](#setAlignment-com.aspose.pdf.TextAlignment-) | Annoteringsjustering. Denna egenskap är föråldrad. Använd getHorizontalAlignment_Annotation_New istället. |
| [setAssignedPageIndex](#setAssignedPageIndex-com.aspose.ms.System.Nullable-) | Ställer in sidindex (en-baserat) där annotationen ska visas. |
| [setBorder](#setBorder-com.aspose.pdf.Border-) | Ställer in annoteringens kantkaraktäristik. {@code Border} |
| [setColor](#setColor-com.aspose.pdf.Color-) | Ställer in annoteringens färg. |
| [setContents](#setContents-java.lang.String-) | Ställer in annoteringstext. |
| [setFlags](#setFlags-int-) | Ställ in flaggor för annotationen. |
| [setHeight](#setHeight-double-) | Ställer in höjden på annotationen. |
| [setHorizontalAlignment_Annotation_New](#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-) | Hämtar eller anger textjustering för annoteringen. |
| [setModified](#setModified-java.util.Date-) | Ställer in datum och tid då annotationen senast ändrades. |
| [setModifiedInternal](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Ställer in datum och tid då annotationen senast ändrades. |
| [setName](#setName-java.lang.String-) | Ställer in annoteringens namn på sidan. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Ställer in annoteringsrektangel. |
| [setTextHorizontalAlignment](#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Ställer in textjustering för annotationen. |
| [setUpdateAppearanceOnConvert](#setUpdateAppearanceOnConvert-boolean-) | Om true uppdateras annoteringens utseende innan PDF-dokumentet konverteras till bild. Detta gör att fält konverteras korrekt men kan kräva mer tid. |
| [setUseFontSubset](#setUseFontSubset-boolean-) | Om den här egenskapen är satt till true kommer typsnitt att läggas till dokumentet som delmängder. Standardvärdet är true. |
| [setWidth](#setWidth-double-) | Ställer in bredden på annotationen. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökare för annoteringsbearbetning.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Uppdatera parametrar och utseende enligt matrisomvandlingen.

### createAnnotation {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
Endast för internt bruk

### flatten {#flatten--}
```
public void flatten()
```

Placera annoteringsinnehåll direkt på sidan, annoteringsobjektet kommer att tas bort.

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Hämtar aktuellt annoteringsutseende.

**Returns:**
String värde

### getAlignment {#getAlignment--}
```
@Deprecated public TextAlignment getAlignment()
```

ff / * / * Returnerar namn på "checked"-tillstånd enligt befintliga tillståndsnamn. / * / * / *

**Returns:**
Strängvärde /

### getAnnotationType {#getAnnotationType--}
```
public abstract AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
int‑värde @see AnnotationType

### getAppearance {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```

Hämtar utseendedictionary för annoteringen.

**Returns:**
AppearanceDictionary‑objekt

### getAssignedPageIndex {#getAssignedPageIndex--}
```
public final com.aspose.ms.System.Nullable< Integer > getAssignedPageIndex()
```

Hämtar sidindex (enbaserat) där annoteringen ska visas.

**Returns:**
sidindex (en‑baserad) där annotationen ska visas.

### getBorder {#getBorder--}
```
public Border getBorder()
```

Hämtar annoteringens kantkarakteristik. {@code Border}

**Returns:**
Border‑objekt

### getCharacteristics {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```

Hämtar annoteringens egenskaper.

**Returns:**
Characteristics‑objekt

### getColor {#getColor--}
```
public Color getColor()
```

Hämtar annoteringens färg.

**Returns:**
Color‑objekt

### getContents {#getContents--}
```
public String getContents()
```

Hämtar annoteringstext.

**Returns:**
String värde

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Endast intern

**Returns:**
IPdfDictionary‑objekt

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Endast för intern användning

**Returns:**
Intern objekt

### getFlags {#getFlags--}
```
public int getFlags()
```

Hämta flaggor för annoteringen.

**Returns:**
Flaggor för annotationen @see AnnotationFlags

### getFullName {#getFullName--}
```
public String getFullName()
```

Hämtar fullständigt kvalificerat namn för annoteringen.

**Returns:**
String värde

### getHeight {#getHeight--}
```
public double getHeight()
```

Hämtar annoteringens höjd.

**Returns:**
höjd på annotationen

### getHorizontalAlignment_Annotation_New {#getHorizontalAlignment_Annotation_New--}
```
@Deprecated public final HorizontalAlignment getHorizontalAlignment_Annotation_New()
```

Hämtar eller anger textjustering för annoteringen.

**Returns:**
textjustering för annotationen. @see HorizontalAlignment @deprecated Använd egenskapen TextHorizontalAlignment

### getModified {#getModified--}
```
public Date getModified()
```

Hämtar datum och tid då annotationen senast ändrades.

**Returns:**
datum och tid då annotationen senast ändrades.

### getModifiedInternal {#getModifiedInternal--}
```
public com.aspose.ms.System.DateTime getModifiedInternal()
```

Hämtar datum och tid då annotationen senast ändrades.

**Returns:**
DateTime‑objekt

### getName {#getName--}
```
public String getName()
```

Hämtar annoteringens namn på sidan.

**Returns:**
String värde

### getNormalAppearance {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```

Hämtar normal visning.

**Returns:**
XForm‑objekt

### getPage {#getPage--}
```
public Page getPage()
```

Hämtar sidobjektet som denna annotation är associerad med.

**Returns:**
Page‑objekt

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Hämtar sidans index som innehåller annotationen.

**Returns:**
int‑värde

### getPageIndex {#getPageIndex-com.aspose.pdf.Annotation-}
Hämtar sidans index som innehåller annotationen.

**Returns:**
int‑värde

### getPdfActions {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```

Hämtar lista över annoteringsåtgärder.

**Returns:**
PdfActionCollection‑instans

### getRect {#getRect--}
```
public Rectangle getRect()
```

Hämtar annoteringsrektangel.

**Returns:**
Rectangle‑objekt

### getRectangle {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```

Returnerar annoteringens rektangel med hänsyn till sidrotation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| considerRotation |  | Om true, tas sidrotation i beaktande. |

**Returns:**
Rectangle‑objekt

### getStates {#getStates--}
```
public AppearanceDictionary getStates()
```

Hämtar visningsordbok för annotationen.

**Returns:**
AppearanceDictionary‑objekt

### getTextHorizontalAlignment {#getTextHorizontalAlignment--}
```
public HorizontalAlignment getTextHorizontalAlignment()
```

Hämtar textjustering för annotationen.

**Returns:**
textjustering för annotationen. @see HorizontalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Hämtar bredden på annotationen.

**Returns:**
double‑värde, bredd på annotationen.

### initialize {#initialize-com.aspose.pdf.IDocument-}
Instansinitialisering

### isUpdateAppearanceOnConvert {#isUpdateAppearanceOnConvert--}
```
public static boolean isUpdateAppearanceOnConvert()
```

Om true uppdateras annoteringens utseende innan PDF-dokumentet konverteras till bild. Detta gör att fält konverteras korrekt men kan kräva mer tid.

**Returns:**
booleskt värde

### isUseFontSubset {#isUseFontSubset--}
```
public static boolean isUseFontSubset()
```

Om den här egenskapen är satt till true kommer typsnitt att läggas till dokumentet som delmängder. Standardvärdet är true.

**Returns:**
booleskt värde

### setActiveState {#setActiveState-java.lang.String-}
Ställer in aktuellt annoteringsutseende.

### setAlignment {#setAlignment-com.aspose.pdf.TextAlignment-}
Annoteringsjustering. Denna egenskap är föråldrad. Använd getHorizontalAlignment_Annotation_New istället.

### setAssignedPageIndex {#setAssignedPageIndex-com.aspose.ms.System.Nullable-}
Ställer in sidindex (en-baserat) där annotationen ska visas.

### setBorder {#setBorder-com.aspose.pdf.Border-}
Ställer in annoteringens kantkaraktäristik. {@code Border}

### setColor {#setColor-com.aspose.pdf.Color-}
Ställer in annoteringens färg.

### setContents {#setContents-java.lang.String-}
Ställer in annoteringstext.

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Ställ in flaggor för annotationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flaggor för annotationen @see AnnotationFlags |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Ställer in höjden på annotationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | höjd på annotationen |

### setHorizontalAlignment_Annotation_New {#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-}
Hämtar eller anger textjustering för annoteringen.

### setModified {#setModified-java.util.Date-}
Ställer in datum och tid då annotationen senast ändrades.

### setModifiedInternal {#setModifiedInternal-com.aspose.ms.System.DateTime-}
Ställer in datum och tid då annotationen senast ändrades.

### setName {#setName-java.lang.String-}
Ställer in annoteringens namn på sidan.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Ställer in annoteringsrektangel.

### setTextHorizontalAlignment {#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Ställer in textjustering för annotationen.

### setUpdateAppearanceOnConvert {#setUpdateAppearanceOnConvert-boolean-}
```
public static void setUpdateAppearanceOnConvert(boolean value)
```

Om true uppdateras annoteringens utseende innan PDF-dokumentet konverteras till bild. Detta gör att fält konverteras korrekt men kan kräva mer tid.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUseFontSubset {#setUseFontSubset-boolean-}
```
public static void setUseFontSubset(boolean value)
```

Om den här egenskapen är satt till true kommer typsnitt att läggas till dokumentet som delmängder. Standardvärdet är true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Ställer in bredden på annotationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | bredd på annotationen. |
