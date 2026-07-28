---
title: "WidgetAnnotation"
linktitle: "WidgetAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen som representerar widget-annotering."
type: docs
weight: 5540
url: /sv/java/com.aspose.pdf/widgetannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WidgetAnnotation extends Annotation
```

Klassen som representerar widget-annotering.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [WidgetAnnotation](#WidgetAnnotation-com.aspose.pdf.IDocument-) | Skapa annotation (används för Generator) |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökare. |
| [getAnnotationActions](#getAnnotationActions--) | Hämtar annoteringsåtgärderna. |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getCheckedStateName](#getCheckedStateName--) | Returnerar namnet på "checked" state enligt befintliga tillståndsnamn. |
| [getDefaultAppearance](#getDefaultAppearance--) | Hämtar standardutseendet för fältet. |
| [getExportable](#getExportable--) | Hämtar exportflaggan för fältet. |
| [getHighlighting](#getHighlighting--) | Markeringsläge för annotation. |
| [getOnActivated](#getOnActivated--) | Hämta en åtgärd som ska utföras när annotationen aktiveras. |
| [getParent](#getParent--) | Hämtar annotationens förälder. |
| [getReadOnly](#getReadOnly--) | Hämtar skrivskyddad status för fältet. |
| [getRequired](#getRequired--) | Hämtar obligatorisk status för fältet. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Ställer in standardutseende för fältet. |
| [setExportable](#setExportable-boolean-) | Ställer in skrivskyddad status för fältet. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Markeringsläge för annotation. |
| [setOnActivated](#setOnActivated-com.aspose.pdf.PdfAction-) | Ställ in en åtgärd som ska utföras när annotationen aktiveras. |
| [setReadOnly](#setReadOnly-boolean-) | Ställer in skrivskyddad status för fältet. |
| [setRequired](#setRequired-boolean-) | Ställer in skrivskyddad status för fältet. |

### WidgetAnnotation {#WidgetAnnotation-com.aspose.pdf.IDocument-}
Skapa annotation (används för Generator)

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökare.

### getAnnotationActions {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```

Hämtar annoteringsåtgärderna.

**Returns:**
AnnotationActionCollection-objekt

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
AnnotationType-element @see AnnotationType

### getCheckedStateName {#getCheckedStateName--}
```
public final String getCheckedStateName()
```

Returnerar namnet på "checked" state enligt befintliga tillståndsnamn.

**Returns:**
Namnet på det "checked"-tillståndet för denna annotation.

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Hämtar standardutseendet för fältet.

**Returns:**
DefaultAppearance‑objekt

### getExportable {#getExportable--}
```
public boolean getExportable()
```

Hämtar exportflaggan för fältet.

**Returns:**
booleskt värde

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Markeringsläge för annotation.

**Returns:**
HighlightingMode-värde @see HighlightingMode

### getOnActivated {#getOnActivated--}
```
public PdfAction getOnActivated()
```

Hämta en åtgärd som ska utföras när annotationen aktiveras.

**Returns:**
PdfAction-objekt

### getParent {#getParent--}
```
public Field getParent()
```

Hämtar annotationens förälder.

**Returns:**
Field-objekt

### getReadOnly {#getReadOnly--}
```
public boolean getReadOnly()
```

Hämtar skrivskyddad status för fältet.

**Returns:**
booleskt värde

### getRequired {#getRequired--}
```
public boolean getRequired()
```

Hämtar obligatorisk status för fältet.

**Returns:**
booleskt värde

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Ställer in standardutseende för fältet.

### setExportable {#setExportable-boolean-}
```
public void setExportable(boolean value)
```

Ställer in skrivskyddad status för fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Markeringsläge för annotation.

### setOnActivated {#setOnActivated-com.aspose.pdf.PdfAction-}
Ställ in en åtgärd som ska utföras när annotationen aktiveras.

### setReadOnly {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```

Ställer in skrivskyddad status för fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRequired {#setRequired-boolean-}
```
public void setRequired(boolean value)
```

Ställer in skrivskyddad status för fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
