---
title: "WidgetAnnotation"
linktitle: "WidgetAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die eine Widget-Annotation darstellt."
type: docs
weight: 5540
url: /de/java/com.aspose.pdf/widgetannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WidgetAnnotation extends Annotation
```

Klasse, die eine Widget-Annotation darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WidgetAnnotation](#WidgetAnnotation-com.aspose.pdf.IDocument-) | Annotation erstellen (verwendet für Generator) |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert Besucher. |
| [getAnnotationActions](#getAnnotationActions--) | Ruft die Annotationsaktionen ab. |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getCheckedStateName](#getCheckedStateName--) | Gibt den Namen des "checked"-Zustands gemäß vorhandenen Zustandsnamen zurück. |
| [getDefaultAppearance](#getDefaultAppearance--) | Liefert das Standardaussehen des Feldes. |
| [getExportable](#getExportable--) | Liefert das exportierbare Flag des Feldes. |
| [getHighlighting](#getHighlighting--) | Markierungsmodus der Annotation. |
| [getOnActivated](#getOnActivated--) | Erhalte eine Aktion, die ausgeführt werden soll, wenn die Annotation aktiviert wird. |
| [getParent](#getParent--) | Liefert das übergeordnete Element der Annotation. |
| [getReadOnly](#getReadOnly--) | Liefert den Nur-Lese-Status des Feldes. |
| [getRequired](#getRequired--) | Liefert den erforderlichen Status des Feldes. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Setzt das Standardaussehen des Feldes. |
| [setExportable](#setExportable-boolean-) | Setzt den Nur-Lese-Status des Feldes. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Markierungsmodus der Annotation. |
| [setOnActivated](#setOnActivated-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt werden soll, wenn die Annotation aktiviert wird. |
| [setReadOnly](#setReadOnly-boolean-) | Setzt den Nur-Lese-Status des Feldes. |
| [setRequired](#setRequired-boolean-) | Setzt den Nur-Lese-Status des Feldes. |

### WidgetAnnotation {#WidgetAnnotation-com.aspose.pdf.IDocument-}
Annotation erstellen (verwendet für Generator)

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert Besucher.

### getAnnotationActions {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```

Ruft die Annotationsaktionen ab.

**Returns:**
AnnotationActionCollection-Objekt

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
AnnotationType-Element @see AnnotationType

### getCheckedStateName {#getCheckedStateName--}
```
public final String getCheckedStateName()
```

Gibt den Namen des "checked"-Zustands gemäß vorhandenen Zustandsnamen zurück.

**Returns:**
Der Name des "checked"-Zustands für diese Annotation.

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Liefert das Standardaussehen des Feldes.

**Returns:**
DefaultAppearance-Objekt

### getExportable {#getExportable--}
```
public boolean getExportable()
```

Liefert das exportierbare Flag des Feldes.

**Returns:**
boolescher Wert

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Markierungsmodus der Annotation.

**Returns:**
HighlightingMode-Wert @see HighlightingMode

### getOnActivated {#getOnActivated--}
```
public PdfAction getOnActivated()
```

Erhalte eine Aktion, die ausgeführt werden soll, wenn die Annotation aktiviert wird.

**Returns:**
PdfAction-Objekt

### getParent {#getParent--}
```
public Field getParent()
```

Liefert das übergeordnete Element der Annotation.

**Returns:**
Feld-Objekt

### getReadOnly {#getReadOnly--}
```
public boolean getReadOnly()
```

Liefert den Nur-Lese-Status des Feldes.

**Returns:**
boolescher Wert

### getRequired {#getRequired--}
```
public boolean getRequired()
```

Liefert den erforderlichen Status des Feldes.

**Returns:**
boolescher Wert

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Setzt das Standardaussehen des Feldes.

### setExportable {#setExportable-boolean-}
```
public void setExportable(boolean value)
```

Setzt den Nur-Lese-Status des Feldes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Markierungsmodus der Annotation.

### setOnActivated {#setOnActivated-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt werden soll, wenn die Annotation aktiviert wird.

### setReadOnly {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```

Setzt den Nur-Lese-Status des Feldes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRequired {#setRequired-boolean-}
```
public void setRequired(boolean value)
```

Setzt den Nur-Lese-Status des Feldes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
