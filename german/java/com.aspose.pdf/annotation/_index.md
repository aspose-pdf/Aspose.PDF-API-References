---
title: "Annotation"
linktitle: "Annotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die ein Annotationsobjekt darstellt."
type: docs
weight: 60
url: /de/java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class Annotation extends BaseParagraph
```

Klasse, die ein Annotationsobjekt darstellt.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert Besucher für die Annotationsverarbeitung. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Aktualisiert Parameter und Darstellung gemäß der Matrixtransformation. |
| [createAnnotation](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | Nur für den internen Gebrauch. |
| [flatten](#flatten--) | Platziert Annotationsinhalte direkt auf der Seite, das Annotationsobjekt wird entfernt. |
| [getActiveState](#getActiveState--) | Liefert den aktuellen Anzeigestatus der Annotation. |
| [getAlignment](#getAlignment--) | ff / * / * Gibt den Namen des "checked"-Zustands gemäß vorhandener Zustandsnamen zurück. / * / * / * |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getAppearance](#getAppearance--) | Liefert das Erscheinungsdictionary der Annotation. |
| [getAssignedPageIndex](#getAssignedPageIndex--) | Liefert den Seitenindex (eins-basiert), auf dem die Annotation erscheinen soll. |
| [getBorder](#getBorder--) | Liefert die Randmerkmale der Annotation. {@code Border} |
| [getCharacteristics](#getCharacteristics--) | Liefert die Merkmale der Annotation. |
| [getColor](#getColor--) | Liefert die Farbe der Annotation. |
| [getContents](#getContents--) | Liefert den Text der Annotation. |
| [getEngineDict](#getEngineDict--) | Nur intern |
| [getEngineObj](#getEngineObj--) | Nur für den internen Gebrauch |
| [getFlags](#getFlags--) | Liefert die Flags der Annotation. |
| [getFullName](#getFullName--) | Liefert den vollständig qualifizierten Namen der Annotation. |
| [getHeight](#getHeight--) | Ruft die Höhe der Anmerkung ab. |
| [getHorizontalAlignment_Annotation_New](#getHorizontalAlignment_Annotation_New--) | Ruft die Textausrichtung für die Anmerkung ab oder legt sie fest. |
| [getModified](#getModified--) | Ruft Datum und Uhrzeit ab, wann die Anmerkung zuletzt geändert wurde. |
| [getModifiedInternal](#getModifiedInternal--) | Ruft Datum und Uhrzeit ab, wann die Anmerkung zuletzt geändert wurde. |
| [getName](#getName--) | Ruft den Namen der Anmerkung auf der Seite ab. |
| [getNormalAppearance](#getNormalAppearance--) | Ruft das normale Erscheinungsbild ab. |
| [getPage](#getPage--) | Ruft das Seitenobjekt ab, dem diese Anmerkung zugeordnet ist. |
| [getPageIndex](#getPageIndex--) | Ruft den Index der Seite ab, die die Anmerkung enthält. |
| [getPageIndex](#getPageIndex-com.aspose.pdf.Annotation-) | Ruft den Index der Seite ab, die die Anmerkung enthält. |
| [getPdfActions](#getPdfActions--) | Ruft die Liste der Anmerkungsaktionen ab. |
| [getRect](#getRect--) | Ruft das Rechteck der Anmerkung ab. |
| [getRectangle](#getRectangle-boolean-) | Gibt das Rechteck der Anmerkung unter Berücksichtigung der Seitendrehung zurück. |
| [getStates](#getStates--) | Ruft das Erscheinungswörterbuch der Anmerkung ab. |
| [getTextHorizontalAlignment](#getTextHorizontalAlignment--) | Ruft die Textausrichtung für die Anmerkung ab. |
| [getWidth](#getWidth--) | Ruft die Breite der Anmerkung ab. |
| [initialize](#initialize-com.aspose.pdf.IDocument-) | Instanzinitialisierung |
| [isUpdateAppearanceOnConvert](#isUpdateAppearanceOnConvert--) | Wenn true, wird das Erscheinungsbild der Anmerkung vor der Konvertierung des PDF-Dokuments in ein Bild aktualisiert. Dies ermöglicht eine korrekte Konvertierung der Felder, kann jedoch wahrscheinlich mehr Zeit erfordern. |
| [isUseFontSubset](#isUseFontSubset--) | Wenn diese Eigenschaft auf true gesetzt ist, werden Schriftarten dem Dokument als Teilmengen hinzugefügt. Der Standardwert ist true. |
| [setActiveState](#setActiveState-java.lang.String-) | Legt den aktuellen Anmerkungs‑Erscheinungszustand fest. |
| [setAlignment](#setAlignment-com.aspose.pdf.TextAlignment-) | Anmerkungsausrichtung. Diese Eigenschaft ist veraltet. Verwenden Sie stattdessen getHorizontalAlignment_Annotation_New. |
| [setAssignedPageIndex](#setAssignedPageIndex-com.aspose.ms.System.Nullable-) | Legt den Seitenindex (einsbasiert) fest, auf dem die Anmerkung erscheinen soll. |
| [setBorder](#setBorder-com.aspose.pdf.Border-) | Legt die Randmerkmale der Anmerkung fest. {@code Border} |
| [setColor](#setColor-com.aspose.pdf.Color-) | Legt die Farbe der Anmerkung fest. |
| [setContents](#setContents-java.lang.String-) | Legt den Text der Anmerkung fest. |
| [setFlags](#setFlags-int-) | Setzt die Flags der Anmerkung. |
| [setHeight](#setHeight-double-) | Legt die Höhe der Anmerkung fest. |
| [setHorizontalAlignment_Annotation_New](#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-) | Ruft die Textausrichtung für die Anmerkung ab oder legt sie fest. |
| [setModified](#setModified-java.util.Date-) | Legt Datum und Uhrzeit fest, wann die Anmerkung zuletzt geändert wurde. |
| [setModifiedInternal](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Legt Datum und Uhrzeit fest, wann die Anmerkung zuletzt geändert wurde. |
| [setName](#setName-java.lang.String-) | Setzt den Anmerkungsnamen auf der Seite. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Setzt das Anmerkungsrechteck. |
| [setTextHorizontalAlignment](#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Setzt die Textausrichtung für die Anmerkung. |
| [setUpdateAppearanceOnConvert](#setUpdateAppearanceOnConvert-boolean-) | Wenn true, wird das Erscheinungsbild der Anmerkung vor der Konvertierung des PDF-Dokuments in ein Bild aktualisiert. Dies ermöglicht eine korrekte Konvertierung der Felder, kann jedoch wahrscheinlich mehr Zeit erfordern. |
| [setUseFontSubset](#setUseFontSubset-boolean-) | Wenn diese Eigenschaft auf true gesetzt ist, werden Schriftarten dem Dokument als Teilmengen hinzugefügt. Der Standardwert ist true. |
| [setWidth](#setWidth-double-) | Setzt die Breite der Anmerkung. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert Besucher für die Annotationsverarbeitung.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Aktualisiert Parameter und Darstellung gemäß der Matrixtransformation.

### createAnnotation {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
Nur für den internen Gebrauch.

### flatten {#flatten--}
```
public void flatten()
```

Platziert Annotationsinhalte direkt auf der Seite, das Annotationsobjekt wird entfernt.

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Liefert den aktuellen Anzeigestatus der Annotation.

**Returns:**
String Wert

### getAlignment {#getAlignment--}
```
@Deprecated public TextAlignment getAlignment()
```

ff / * / * Gibt den Namen des "checked"-Zustands gemäß vorhandener Zustandsnamen zurück. / * / * / *

**Returns:**
String-Wert /

### getAnnotationType {#getAnnotationType--}
```
public abstract AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
int-Wert @see AnnotationType

### getAppearance {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```

Liefert das Erscheinungsdictionary der Annotation.

**Returns:**
AppearanceDictionary-Objekt

### getAssignedPageIndex {#getAssignedPageIndex--}
```
public final com.aspose.ms.System.Nullable< Integer > getAssignedPageIndex()
```

Liefert den Seitenindex (eins-basiert), auf dem die Annotation erscheinen soll.

**Returns:**
Der Seitenindex (einsbasiert), an dem die Anmerkung erscheinen soll.

### getBorder {#getBorder--}
```
public Border getBorder()
```

Liefert die Randmerkmale der Annotation. {@code Border}

**Returns:**
Border-Objekt

### getCharacteristics {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```

Liefert die Merkmale der Annotation.

**Returns:**
Characteristics-Objekt

### getColor {#getColor--}
```
public Color getColor()
```

Liefert die Farbe der Annotation.

**Returns:**
Color-Objekt

### getContents {#getContents--}
```
public String getContents()
```

Liefert den Text der Annotation.

**Returns:**
String Wert

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Nur intern

**Returns:**
IPdfDictionary-Objekt

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Nur für den internen Gebrauch

**Returns:**
Internes Objekt

### getFlags {#getFlags--}
```
public int getFlags()
```

Liefert die Flags der Annotation.

**Returns:**
Flags der Anmerkung @see AnnotationFlags

### getFullName {#getFullName--}
```
public String getFullName()
```

Liefert den vollständig qualifizierten Namen der Annotation.

**Returns:**
String Wert

### getHeight {#getHeight--}
```
public double getHeight()
```

Ruft die Höhe der Anmerkung ab.

**Returns:**
Höhe der Anmerkung

### getHorizontalAlignment_Annotation_New {#getHorizontalAlignment_Annotation_New--}
```
@Deprecated public final HorizontalAlignment getHorizontalAlignment_Annotation_New()
```

Ruft die Textausrichtung für die Anmerkung ab oder legt sie fest.

**Returns:**
Textausrichtung für die Anmerkung. @see HorizontalAlignment @deprecated Use TextHorizontalAlignment property

### getModified {#getModified--}
```
public Date getModified()
```

Ruft Datum und Uhrzeit ab, wann die Anmerkung zuletzt geändert wurde.

**Returns:**
Datum und Uhrzeit, wann die Anmerkung zuletzt geändert wurde.

### getModifiedInternal {#getModifiedInternal--}
```
public com.aspose.ms.System.DateTime getModifiedInternal()
```

Ruft Datum und Uhrzeit ab, wann die Anmerkung zuletzt geändert wurde.

**Returns:**
DateTime-Objekt

### getName {#getName--}
```
public String getName()
```

Ruft den Namen der Anmerkung auf der Seite ab.

**Returns:**
String Wert

### getNormalAppearance {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```

Ruft das normale Erscheinungsbild ab.

**Returns:**
XForm-Objekt

### getPage {#getPage--}
```
public Page getPage()
```

Ruft das Seitenobjekt ab, dem diese Anmerkung zugeordnet ist.

**Returns:**
Page-Objekt

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Ruft den Index der Seite ab, die die Anmerkung enthält.

**Returns:**
int-Wert

### getPageIndex {#getPageIndex-com.aspose.pdf.Annotation-}
Ruft den Index der Seite ab, die die Anmerkung enthält.

**Returns:**
int-Wert

### getPdfActions {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```

Ruft die Liste der Anmerkungsaktionen ab.

**Returns:**
PdfActionCollection-Instanz

### getRect {#getRect--}
```
public Rectangle getRect()
```

Ruft das Rechteck der Anmerkung ab.

**Returns:**
Rectangle-Objekt

### getRectangle {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```

Gibt das Rechteck der Anmerkung unter Berücksichtigung der Seitendrehung zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| considerRotation |  | Wenn true, wird die Seitendrehung berücksichtigt. |

**Returns:**
Rectangle-Objekt

### getStates {#getStates--}
```
public AppearanceDictionary getStates()
```

Ruft das Erscheinungswörterbuch der Anmerkung ab.

**Returns:**
AppearanceDictionary-Objekt

### getTextHorizontalAlignment {#getTextHorizontalAlignment--}
```
public HorizontalAlignment getTextHorizontalAlignment()
```

Ruft die Textausrichtung für die Anmerkung ab.

**Returns:**
Textausrichtung für die Anmerkung. @see HorizontalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Ruft die Breite der Anmerkung ab.

**Returns:**
double-Wert, Breite der Anmerkung.

### initialize {#initialize-com.aspose.pdf.IDocument-}
Instanzinitialisierung

### isUpdateAppearanceOnConvert {#isUpdateAppearanceOnConvert--}
```
public static boolean isUpdateAppearanceOnConvert()
```

Wenn true, wird das Erscheinungsbild der Anmerkung vor der Konvertierung des PDF-Dokuments in ein Bild aktualisiert. Dies ermöglicht eine korrekte Konvertierung der Felder, kann jedoch wahrscheinlich mehr Zeit erfordern.

**Returns:**
boolescher Wert

### isUseFontSubset {#isUseFontSubset--}
```
public static boolean isUseFontSubset()
```

Wenn diese Eigenschaft auf true gesetzt ist, werden Schriftarten dem Dokument als Teilmengen hinzugefügt. Der Standardwert ist true.

**Returns:**
boolescher Wert

### setActiveState {#setActiveState-java.lang.String-}
Legt den aktuellen Anmerkungs‑Erscheinungszustand fest.

### setAlignment {#setAlignment-com.aspose.pdf.TextAlignment-}
Anmerkungsausrichtung. Diese Eigenschaft ist veraltet. Verwenden Sie stattdessen getHorizontalAlignment_Annotation_New.

### setAssignedPageIndex {#setAssignedPageIndex-com.aspose.ms.System.Nullable-}
Legt den Seitenindex (einsbasiert) fest, auf dem die Anmerkung erscheinen soll.

### setBorder {#setBorder-com.aspose.pdf.Border-}
Legt die Randmerkmale der Anmerkung fest. {@code Border}

### setColor {#setColor-com.aspose.pdf.Color-}
Legt die Farbe der Anmerkung fest.

### setContents {#setContents-java.lang.String-}
Legt den Text der Anmerkung fest.

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Setzt die Flags der Anmerkung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Flags der Anmerkung @see AnnotationFlags |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Legt die Höhe der Anmerkung fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Höhe der Anmerkung |

### setHorizontalAlignment_Annotation_New {#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-}
Ruft die Textausrichtung für die Anmerkung ab oder legt sie fest.

### setModified {#setModified-java.util.Date-}
Legt Datum und Uhrzeit fest, wann die Anmerkung zuletzt geändert wurde.

### setModifiedInternal {#setModifiedInternal-com.aspose.ms.System.DateTime-}
Legt Datum und Uhrzeit fest, wann die Anmerkung zuletzt geändert wurde.

### setName {#setName-java.lang.String-}
Setzt den Anmerkungsnamen auf der Seite.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Setzt das Anmerkungsrechteck.

### setTextHorizontalAlignment {#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Setzt die Textausrichtung für die Anmerkung.

### setUpdateAppearanceOnConvert {#setUpdateAppearanceOnConvert-boolean-}
```
public static void setUpdateAppearanceOnConvert(boolean value)
```

Wenn true, wird das Erscheinungsbild der Anmerkung vor der Konvertierung des PDF-Dokuments in ein Bild aktualisiert. Dies ermöglicht eine korrekte Konvertierung der Felder, kann jedoch wahrscheinlich mehr Zeit erfordern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUseFontSubset {#setUseFontSubset-boolean-}
```
public static void setUseFontSubset(boolean value)
```

Wenn diese Eigenschaft auf true gesetzt ist, werden Schriftarten dem Dokument als Teilmengen hinzugefügt. Der Standardwert ist true.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Setzt die Breite der Anmerkung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Breite der Anmerkung. |
