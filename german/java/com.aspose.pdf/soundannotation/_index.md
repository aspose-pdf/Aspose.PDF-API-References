---
title: "SoundAnnotation"
linktitle: "SoundAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Soundannotation dar, die einen vom Mikrofon des Computers aufgenommenen Ton oder aus einer Datei importierten Ton enthält."
type: docs
weight: 4530
url: /de/java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.SoundAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class SoundAnnotation extends MarkupAnnotation
```

Stellt eine Soundannotation dar, die einen vom Mikrofon des Computers aufgenommenen Ton oder aus einer Datei importierten Ton enthält.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Erstellt eine neue Sound-Anmerkung auf der angegebenen Seite. |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-) | Erstellt eine neue Sound-Anmerkung auf der angegebenen Seite. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten. |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getIcon](#getIcon--) | Liefert ein Symbol, das bei der Anzeige der Anmerkung verwendet wird. |
| [getSoundData](#getSoundData--) | Ruft ein Sound-Objekt ab, das den abzuspielenden Sound definiert, wenn die Anmerkung aktiviert wird. |
| [setIcon](#setIcon-int-) | Setzt ein Symbol, das bei der Anzeige der Anmerkung verwendet wird. |

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Erstellt eine neue Sound-Anmerkung auf der angegebenen Seite.

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-}
Erstellt eine neue Sound-Anmerkung auf der angegebenen Seite.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
AnnotationType-Wert @see AnnotationType

### getIcon {#getIcon--}
```
public int getIcon()
```

Liefert ein Symbol, das bei der Anzeige der Anmerkung verwendet wird.

**Returns:**
SoundIcon-Wert @see SoundIcon

### getSoundData {#getSoundData--}
```
public SoundData getSoundData()
```

Ruft ein Sound-Objekt ab, das den abzuspielenden Sound definiert, wenn die Anmerkung aktiviert wird.

**Returns:**
SoundData-Wert

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Setzt ein Symbol, das bei der Anzeige der Anmerkung verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | SoundIcon-Wert @see SoundIcon |
