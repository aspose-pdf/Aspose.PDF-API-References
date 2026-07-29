---
title: "CaretAnnotation"
linktitle: "CaretAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen som representerar Caret-annotation."
type: docs
weight: 470
url: /sv/java/com.aspose.pdf/caretannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.CaretAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class CaretAnnotation extends MarkupAnnotation
```

Klassen som representerar Caret-annotation.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.IDocument-) | Konstruktor för usign i Generator. |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Skapar ny Caret-annotation på den angivna sidan. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökarobjekt för att bearbeta annotationen. |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getFrame](#getFrame--) | Hämtar caret-rektangel. |
| [getSymbol](#getSymbol--) | Hämtar symbol som är associerad med caret. {@code CaretSymbol} |
| [setFrame](#setFrame-com.aspose.pdf.Rectangle-) | Ställer in caret-rektangel. |
| [setSymbol](#setSymbol-com.aspose.pdf.CaretSymbol-) | Ställer in utskrifts sidstorlek för import. |

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.IDocument-}
Konstruktor för usign i Generator.

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Skapar ny Caret-annotation på den angivna sidan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökarobjekt för att bearbeta annotationen.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
AnnotationType-element

### getFrame {#getFrame--}
```
public Rectangle getFrame()
```

Hämtar caret-rektangel.

**Returns:**
caret-rektangel.

### getSymbol {#getSymbol--}
```
public CaretSymbol getSymbol()
```

Hämtar symbol som är associerad med caret. {@code CaretSymbol}

**Returns:**
CaretSymbol-element @see CaretSymbol

### setFrame {#setFrame-com.aspose.pdf.Rectangle-}
Ställer in caret-rektangel.

### setSymbol {#setSymbol-com.aspose.pdf.CaretSymbol-}
Ställer in utskrifts sidstorlek för import.
