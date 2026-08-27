---
title: "PopupAnnotation"
linktitle: "PopupAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar popup-annotation som visar text i ett popup-fönster för inmatning och redigering."
type: docs
weight: 3930
url: /sv/java/com.aspose.pdf/popupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PopupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PopupAnnotation extends Annotation
```

Representerar popup-annotation som visar text i ett popup-fönster för inmatning och redigering.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.IDocument-) | Konstruktor. för användning i Generator. |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Skapar ny Popup‑annotation på den angivna sidan. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökarobjekt för att bearbeta annotationen. |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getOpen](#getOpen--) | Hämtar en flagga som anger om popup‑annotation ska visas öppen från början. |
| [getParent](#getParent--) | Hämtar föräldraannotation som denna popup‑annotation ska vara associerad med. Om denna post finns, ska föräldraannotationens Contents-, M-, C- och T‑poster åsidosätta dem i popup‑annotationens egna poster. |
| [setOpen](#setOpen-boolean-) | Ställer in en flagga som anger om popup‑annotation ska visas öppen från början. |
| [setParent](#setParent-com.aspose.pdf.MarkupAnnotation-) | Ställer in föräldraannotation som denna popup‑annotation ska vara associerad med. Om denna post finns, ska föräldraannotationens Contents-, M-, C- och T‑poster åsidosätta dem i popup‑annotationens egna poster. |

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.IDocument-}
Konstruktor. för användning i Generator.

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Skapar ny Popup‑annotation på den angivna sidan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökarobjekt för att bearbeta annotationen.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
AnnotationType-element @see AnnotationType

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Hämtar en flagga som anger om popup‑annotation ska visas öppen från början.

**Returns:**
booleskt värde

### getParent {#getParent--}
```
public Annotation getParent()
```

Hämtar föräldraannotation som denna popup‑annotation ska vara associerad med. Om denna post finns, ska föräldraannotationens Contents-, M-, C- och T‑poster åsidosätta dem i popup‑annotationens egna poster.

**Returns:**
MarkupAnnotation‑objekt

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Ställer in en flagga som anger om popup‑annotation ska visas öppen från början.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setParent {#setParent-com.aspose.pdf.MarkupAnnotation-}
Ställer in föräldraannotation som denna popup‑annotation ska vara associerad med. Om denna post finns, ska föräldraannotationens Contents-, M-, C- och T‑poster åsidosätta dem i popup‑annotationens egna poster.
