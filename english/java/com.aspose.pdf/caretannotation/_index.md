---
title: CaretAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class representing Caret annotation.
type: docs
weight: 470
url: /java/com.aspose.pdf/caretannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.CaretAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class CaretAnnotation extends MarkupAnnotation
```

Class representing Caret annotation.

## Constructors

| Constructor | Description |
| --- | --- |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.IDocument-) | Constructor for usign in Generator. |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Caret annotation on the specified page. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getFrame](#getFrame--) | Gets caret rectangle. |
| [getSymbol](#getSymbol--) | Gets symbol associated with caret. {@code CaretSymbol} |
| [setFrame](#setFrame-com.aspose.pdf.Rectangle-) | Sets caret rectangle. |
| [setSymbol](#setSymbol-com.aspose.pdf.CaretSymbol-) | Sets output page size for import. |

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.IDocument-}
Constructor for usign in Generator.

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Creates new Caret annotation on the specified page.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor object to process the annotation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
AnnotationType element

### getFrame {#getFrame--}
```
public Rectangle getFrame()
```

Gets caret rectangle.

**Returns:**
caret rectangle.

### getSymbol {#getSymbol--}
```
public CaretSymbol getSymbol()
```

Gets symbol associated with caret. {@code CaretSymbol}

**Returns:**
CaretSymbol element @see CaretSymbol

### setFrame {#setFrame-com.aspose.pdf.Rectangle-}
Sets caret rectangle.

### setSymbol {#setSymbol-com.aspose.pdf.CaretSymbol-}
Sets output page size for import.
