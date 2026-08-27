---
title: "PDF3DAnnotation"
linktitle: "PDF3DAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse PDF3DAnnotation. Diese Klasse kann nicht geerbt werden. @see Annotation"
type: docs
weight: 3560
url: /de/java/com.aspose.pdf/pdf3dannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PDF3DAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PDF3DAnnotation extends Annotation
```

Klasse PDF3DAnnotation. Diese Klasse kann nicht geerbt werden. @see Annotation

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-) | Initialisiert eine neue Instanz der {@code PDF3DAnnotation}-Klasse. |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-) | Initialisiert eine neue Instanz der {@code PDF3DAnnotation}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert Besucher für die Annotationsverarbeitung. |
| [clearImagePreview](#clearImagePreview--) | Löscht die Bildvorschau. |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Anmerkung. Wert: Der Typ der Anmerkung. |
| [getContent](#getContent--) | Liefert oder setzt den Inhalt. Wert: Der Inhalt. |
| [getImagePreview](#getImagePreview--) | Liefert die Bildvorschau. |
| [getLightingScheme](#getLightingScheme--) | Liefert das Beleuchtungsschema. Wert: Das Beleuchtungsschema. |
| [getPdf3DArtwork](#getPdf3DArtwork--) | Liefert das 3D-Kunstwerk. Wert: Das PDF3 d Kunstwerk. |
| [getRenderMode](#getRenderMode--) | Liefert den Rendermodus. Wert: Der Rendermodus. |
| [getViewArray](#getViewArray--) | Liefert das Ansicht-Array. Wert: Das Ansicht-Array. |
| [setContent](#setContent-com.aspose.pdf.PDF3DContent-) | Liefert oder setzt den Inhalt. Wert: Der Inhalt. |
| [setDefaultViewIndex](#setDefaultViewIndex-int-) | Setzt den Index der Standardansicht. |
| [setImagePreview](#setImagePreview-java.io.InputStream-) | Setzt die Bildvorschau. |
| [setImagePreview](#setImagePreview-java.lang.String-) | Setzt die Bildvorschau. |

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-}
Initialisiert eine neue Instanz der {@code PDF3DAnnotation}-Klasse.

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-}
Initialisiert eine neue Instanz der {@code PDF3DAnnotation}-Klasse.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert Besucher für die Annotationsverarbeitung.

### clearImagePreview {#clearImagePreview--}
```
public void clearImagePreview()
```

Löscht die Bildvorschau.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Anmerkung. Wert: Der Typ der Anmerkung.

**Returns:**
int-Wert

### getContent {#getContent--}
```
public PDF3DContent getContent()
```

Liefert oder setzt den Inhalt. Wert: Der Inhalt.

**Returns:**
PDF3DContent-Objekt

### getImagePreview {#getImagePreview--}
```
public InputStream getImagePreview()
```

Liefert die Bildvorschau.

**Returns:**
Bildvorschau als Stream.

### getLightingScheme {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```

Liefert das Beleuchtungsschema. Wert: Das Beleuchtungsschema.

**Returns:**
PDF3DLightingScheme-Objekt

### getPdf3DArtwork {#getPdf3DArtwork--}
```
public PDF3DArtwork getPdf3DArtwork()
```

Liefert das 3D-Kunstwerk. Wert: Das PDF3 d Kunstwerk.

**Returns:**
PDF3DArtwork Objekt

### getRenderMode {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```

Liefert den Rendermodus. Wert: Der Rendermodus.

**Returns:**
PDF3DRenderMode Objekt

### getViewArray {#getViewArray--}
```
public PDF3DViewArray getViewArray()
```

Liefert das Ansicht-Array. Wert: Das Ansicht-Array.

**Returns:**
PDF3DViewArray Objekt

### setContent {#setContent-com.aspose.pdf.PDF3DContent-}
Liefert oder setzt den Inhalt. Wert: Der Inhalt.

### setDefaultViewIndex {#setDefaultViewIndex-int-}
```
public void setDefaultViewIndex(int index)
```

Setzt den Index der Standardansicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Der Standard-Ansichtsindex. |

### setImagePreview {#setImagePreview-java.io.InputStream-}
Setzt die Bildvorschau.

### setImagePreview {#setImagePreview-java.lang.String-}
Setzt die Bildvorschau.
