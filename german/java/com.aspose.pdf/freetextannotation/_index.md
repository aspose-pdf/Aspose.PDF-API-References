---
title: "FreeTextAnnotation"
linktitle: "FreeTextAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine FreeTextAnnotation dar, die Text direkt auf der Seite anzeigt. Im Gegensatz zu einer normalen Textannotation hat eine FreeTextAnnotation keinen offenen oder geschlossenen Zustand; stattdessen."
type: docs
weight: 1790
url: /de/java/com.aspose.pdf/freetextannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FreeTextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FreeTextAnnotation extends MarkupAnnotation
```

Stellt eine Freitext‑Annotation dar, die Text direkt auf der Seite anzeigt. Im Gegensatz zu einer normalen Text‑Annotation hat eine Freitext‑Annotation keinen offenen oder geschlossenen Zustand; anstatt in einem Popup‑Fenster angezeigt zu werden, ist der Text stets sichtbar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | Konstruktor zur Verwendung mit Generator. |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | Erstellt eine neue FreeTextAnnotation auf der angegebenen Seite. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten. |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getCallout](#getCallout--) | Array von Punkten, das die Hinweislinie angibt. |
| [getDefaultAppearance](#getDefaultAppearance--) | Liefert die Standard‑Darstellungszeichenfolge, die beim Formatieren des Textes verwendet wird. |
| [getDefaultAppearanceObject](#getDefaultAppearanceObject--) | Objekt, das die Standarddarstellung der FreeTextAnnotation repräsentiert. |
| [getDefaultStyle](#getDefaultStyle--) | Liefert eine Standard‑Stilzeichenfolge. |
| [getEndingStyle](#getEndingStyle--) | Liefert den Linienende‑Stil für den Endpunkt der Linie. |
| [getIntent](#getIntent--) | Liefert die Absicht der FreeTextAnnotation. |
| [getJustification](#getJustification--) | Liefert einen Code, der die Form der Ausrichtung (Justierung) angibt, die bei der Anzeige des Annotationstextes verwendet wird. |
| [getRotate](#getRotate--) | Winkel der Annotationsrotation. |
| [getStartingStyle](#getStartingStyle--) | Liefert oder setzt den Linienende‑Stil für den Endpunkt der Linie. Diese Eigenschaft ist veraltet, bitte verwenden Sie EndingStyle. |
| [getTextRectangle](#getTextRectangle--) | Rechteck, das die numerischen Unterschiede zwischen zwei Rechtecken beschreibt: den Rect‑Eintrag der Annotation und ein Rechteck, das innerhalb dieses Rechtecks liegt. Das innere Rechteck ist der Ort, an dem der Text der Annotation angezeigt werden soll. |
| [getTextStyle](#getTextStyle--) | Liefert oder setzt den Stil des Textes in der Darstellung. Wenn der Textstil geändert wird, wird die Textdarstellung aktualisiert. |
| [isValidXml](#isValidXml-java.lang.String-) |  |
| [setCallout](#setCallout-com.aspose.pdf.Point:A-) | Array von Punkten, das die Hinweislinie angibt. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Setzt die Standard‑Darstellungszeichenfolge, die beim Formatieren des Textes verwendet wird. |
| [setDefaultStyle](#setDefaultStyle-java.lang.String-) | Setzt eine Standard‑Stilzeichenfolge. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Setzt den Linienende‑Stil für den Endpunkt der Linie. |
| [setIntent](#setIntent-com.aspose.pdf.FreeTextIntent-) | Setzt die Absicht der FreeTextAnnotation. |
| [setJustification](#setJustification-com.aspose.pdf.Justification-) | Setzt einen Code, der die Form der Ausrichtung (Justierung) angibt, die bei der Anzeige des Annotationstextes verwendet wird. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Winkel der Annotationsrotation. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Liefert oder setzt den Linienende‑Stil für den Endpunkt der Linie. Diese Eigenschaft ist veraltet, bitte verwenden Sie EndingStyle. |
| [setTextRectangle](#setTextRectangle-com.aspose.pdf.Rectangle-) | Rechteck, das die numerischen Unterschiede zwischen zwei Rechtecken beschreibt: den Rect‑Eintrag der Annotation und ein Rechteck, das innerhalb dieses Rechtecks liegt. Das innere Rechteck ist der Ort, an dem der Text der Annotation angezeigt werden soll. |
| [setTextStyle](#setTextStyle-int-int-int-) | Legt die durch den Parameter textStyle bestimmte Formatierung für ein Textfragment vom Index fromInd bis zum Index toInd fest. |
| [setTextStyle](#setTextStyle-int-java.lang.String-double-java.awt.Color-) | Legt die durch den Parameter textStyle bestimmte Formatierung für den gesamten Anmerkungstext fest. |
| [setTextStyle](#setTextStyle-com.aspose.pdf.TextStyle-) | Setzt den Stil des Textes im Erscheinungsbild. Wenn der Textstil geändert wird, wird das Erscheinungsbild des Textes aktualisiert. |
| [updateAppearance](#updateAppearance--) | Aktualisiert das Erscheinungsbild, nachdem der Text geändert/verschoben wurde. |

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
Konstruktor zur Verwendung mit Generator.

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
Erstellt eine neue FreeTextAnnotation auf der angegebenen Seite.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
int-Wert

### getCallout {#getCallout--}
```
public final Point [] getCallout()
```

Array von Punkten, das die Hinweislinie angibt.

**Returns:**
Array von Point

### getDefaultAppearance {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```

Liefert die Standard‑Darstellungszeichenfolge, die beim Formatieren des Textes verwendet wird.

**Returns:**
String Wert

### getDefaultAppearanceObject {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```

Objekt, das die Standarddarstellung der FreeTextAnnotation repräsentiert.

**Returns:**
DefaultAppearance-Objekt

### getDefaultStyle {#getDefaultStyle--}
```
public String getDefaultStyle()
```

Liefert eine Standard‑Stilzeichenfolge.

**Returns:**
String Wert

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Liefert den Linienende‑Stil für den Endpunkt der Linie.

**Returns:**
LineEnding-Wert @see LineEnding

### getIntent {#getIntent--}
```
public FreeTextIntent getIntent()
```

Liefert die Absicht der FreeTextAnnotation.

**Returns:**
int-Wert @see FreeTextIntent

### getJustification {#getJustification--}
```
public Justification getJustification()
```

Liefert einen Code, der die Form der Ausrichtung (Justierung) angibt, die bei der Anzeige des Annotationstextes verwendet wird.

**Returns:**
int-Wert @see Justification

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Winkel der Annotationsrotation.

**Returns:**
Rotation-Element @see Rotation

### getStartingStyle {#getStartingStyle--}
```
public final LineEnding getStartingStyle()
```

Liefert oder setzt den Linienende‑Stil für den Endpunkt der Linie. Diese Eigenschaft ist veraltet, bitte verwenden Sie EndingStyle.

**Returns:**
LineEnding-Element

### getTextRectangle {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```

Rechteck, das die numerischen Unterschiede zwischen zwei Rechtecken beschreibt: den Rect‑Eintrag der Annotation und ein Rechteck, das innerhalb dieses Rechtecks liegt. Das innere Rechteck ist der Ort, an dem der Text der Annotation angezeigt werden soll.

**Returns:**
Rechteck-Instanz

### getTextStyle {#getTextStyle--}
```
public TextStyle getTextStyle()
```

Liefert oder setzt den Stil des Textes in der Darstellung. Wenn der Textstil geändert wird, wird die Textdarstellung aktualisiert.

**Returns:**
TextStyle-Wert

### isValidXml {#isValidXml-java.lang.String-}


### setCallout {#setCallout-com.aspose.pdf.Point:A-}
Array von Punkten, das die Hinweislinie angibt.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Setzt die Standard‑Darstellungszeichenfolge, die beim Formatieren des Textes verwendet wird.

### setDefaultStyle {#setDefaultStyle-java.lang.String-}
Setzt eine Standard‑Stilzeichenfolge.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Setzt den Linienende‑Stil für den Endpunkt der Linie.

### setIntent {#setIntent-com.aspose.pdf.FreeTextIntent-}
Setzt die Absicht der FreeTextAnnotation.

### setJustification {#setJustification-com.aspose.pdf.Justification-}
Setzt einen Code, der die Form der Ausrichtung (Justierung) angibt, die bei der Anzeige des Annotationstextes verwendet wird.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Winkel der Annotationsrotation.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Liefert oder setzt den Linienende‑Stil für den Endpunkt der Linie. Diese Eigenschaft ist veraltet, bitte verwenden Sie EndingStyle.

### setTextRectangle {#setTextRectangle-com.aspose.pdf.Rectangle-}
Rechteck, das die numerischen Unterschiede zwischen zwei Rechtecken beschreibt: den Rect‑Eintrag der Annotation und ein Rechteck, das innerhalb dieses Rechtecks liegt. Das innere Rechteck ist der Ort, an dem der Text der Annotation angezeigt werden soll.

### setTextStyle {#setTextStyle-int-int-int-}
```
public final void setTextStyle(int fromInd, int toInd, int textStyles)
```

Legt die durch den Parameter textStyle bestimmte Formatierung für ein Textfragment vom Index fromInd bis zum Index toInd fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fromInd |  | Startindex des Textfragments (ab 0). |
| toInd |  | Endindex des Textfragments (gezählt ab 0, dieser nicht eingeschlossen). |
| textStyles |  | Stil(e), die auf das Textfragment angewendet werden. |

### setTextStyle {#setTextStyle-int-java.lang.String-double-java.awt.Color-}
Legt die durch den Parameter textStyle bestimmte Formatierung für den gesamten Anmerkungstext fest.

### setTextStyle {#setTextStyle-com.aspose.pdf.TextStyle-}
Setzt den Stil des Textes im Erscheinungsbild. Wenn der Textstil geändert wird, wird das Erscheinungsbild des Textes aktualisiert.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Aktualisiert das Erscheinungsbild, nachdem der Text geändert/verschoben wurde.
