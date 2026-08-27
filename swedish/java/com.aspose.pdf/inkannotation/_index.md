---
title: "InkAnnotation"
linktitle: "InkAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en frihands-\\\"scribble\\\" bestående av en eller flera separata banor."
type: docs
weight: 2430
url: /sv/java/com.aspose.pdf/inkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.InkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class InkAnnotation extends MarkupAnnotation
```

Representerar en frihands‑"klotter" bestående av en eller flera separata banor.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-) | Konstruktor för Ink-annotation för Generator. |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-) | Skapar en ny Ink-annotation på den angivna sidan. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökarobjekt för att bearbeta annotationen. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Uppdaterar punkterna i InkList enligt matrisomvandlingen. |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getCapStyle](#getCapStyle--) | hämta stil för ink-annotationens linjeändar. |
| [getInkList](#getInkList--) | <p> Hämtar lista över gester som är oberoende linjer som representeras av Point[]-arrayer. </p> |
| [setCapStyle](#setCapStyle-com.aspose.pdf.CapStyle-) | Ange stil för ink-annotationens linjeändar. |
| [setInkList](#setInkList-java.util.List-) | Ställer in lista över gester som är oberoende linjer som representeras av Point[]-arrayer. |
| [updateAppearance](#updateAppearance--) | Uppdaterar utseendet efter att text har ändrats/flyttats. |

### InkAnnotation {#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-}
Konstruktor för Ink-annotation för Generator.

### InkAnnotation {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-}
Skapar en ny Ink-annotation på den angivna sidan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökarobjekt för att bearbeta annotationen.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Uppdaterar punkterna i InkList enligt matrisomvandlingen.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
AnnotationType-element @see AnnotationType

### getCapStyle {#getCapStyle--}
```
public CapStyle getCapStyle()
```

hämta stil för ink-annotationens linjeändar.

**Returns:**
CapStyle-element @see CapStyle

### getInkList {#getInkList--}
```
public List < Point []> getInkList()
```

<p> Hämtar lista över gester som är oberoende linjer som representeras av Point[]-arrayer. </p>

**Returns:**
{@code List<Point[]>} objekt

### setCapStyle {#setCapStyle-com.aspose.pdf.CapStyle-}
Ange stil för ink-annotationens linjeändar.

### setInkList {#setInkList-java.util.List-}
Ställer in lista över gester som är oberoende linjer som representeras av Point[]-arrayer.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Uppdaterar utseendet efter att text har ändrats/flyttats.
