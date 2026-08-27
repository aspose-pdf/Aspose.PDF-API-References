---
title: "LinkAnnotation"
linktitle: "LinkAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar antingen en hypertextlänk till en destination någon annanstans i dokumentet eller en åtgärd som ska utföras."
type: docs
weight: 2760
url: /sv/java/com.aspose.pdf/linkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.LinkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class LinkAnnotation extends Annotation
```

Representerar antingen en hypertextlänk till en destination någon annanstans i dokumentet eller en åtgärd som ska utföras.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [LinkAnnotation](#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Skapar ny Link-annotation på den angivna sidan. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökarobjekt för att bearbeta annotationen. |
| [getAction](#getAction--) | Hämta en åtgärd som ska utföras när länkanotation aktiveras. |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getDestination](#getDestination--) | Hämta en destination som ska visas när annotationen aktiveras. |
| [getHighlighting](#getHighlighting--) | Hämta den visuella effekten som ska användas när musknappen trycks ned eller hålls ned inom dess aktiva område. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Ställ in en åtgärd som ska utföras när länkanotation aktiveras. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Ställ in en destination som ska visas när annotationen aktiveras. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Ställ in den visuella effekten som ska användas när musknappen trycks ned eller hålls ned inom dess aktiva område. |

### LinkAnnotation {#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Skapar ny Link-annotation på den angivna sidan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökarobjekt för att bearbeta annotationen.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Hämta en åtgärd som ska utföras när länkanotation aktiveras.

**Returns:**
PdfAction‑värde

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
AnnotationType-element @see AnnotationType

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Hämta en destination som ska visas när annotationen aktiveras.

**Returns:**
IAppointment-värde

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Hämta den visuella effekten som ska användas när musknappen trycks ned eller hålls ned inom dess aktiva område.

**Returns:**
HighlightingMode-element @see HighlightingMode

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Ställ in en åtgärd som ska utföras när länkanotation aktiveras.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Ställ in en destination som ska visas när annotationen aktiveras.

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Ställ in den visuella effekten som ska användas när musknappen trycks ned eller hålls ned inom dess aktiva område.
