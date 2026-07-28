---
title: "TextAnnotation"
linktitle: "TextAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en textannotation som är en \\\"sticky note\\\" fäst vid en punkt i PDF-dokumentet."
type: docs
weight: 4920
url: /sv/java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class TextAnnotation extends MarkupAnnotation
```

Representerar en textanteckning som är en "sticky note" fäst vid en punkt i PDF-dokumentet.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextAnnotation](#TextAnnotation--) | Skapa TextAnnotation-instans |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.IDocument-) | Skapa TextAnnotation-instans |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Skapa TextAnnotation-instans |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökarobjekt för att bearbeta annotationen. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Åsidosätter definitionen i basklassen med en tom kropp. |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getIcon](#getIcon--) | Hämtar en ikon som ska användas vid visning av annotationen. |
| [getOpen](#getOpen--) | Hämtar en flagga som specificerar om annotationen initialt ska visas öppen. |
| [setIcon](#setIcon-int-) | Ställer in en ikon som ska användas vid visning av annotationen. |
| [setOpen](#setOpen-boolean-) | Ställer in en flagga som specificerar om annotationen initialt ska visas öppen. |

### TextAnnotation {#TextAnnotation--}
```
public TextAnnotation()
```

Skapa TextAnnotation-instans

### TextAnnotation {#TextAnnotation-com.aspose.pdf.IDocument-}
Skapa TextAnnotation-instans

### TextAnnotation {#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Skapa TextAnnotation-instans

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökarobjekt för att bearbeta annotationen.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Åsidosätter definitionen i basklassen med en tom kropp.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
AnnotationType-värde @see AnnotationState

### getIcon {#getIcon--}
```
public int getIcon()
```

Hämtar en ikon som ska användas vid visning av annotationen.

**Returns:**
TextIcon-värde @see TextIcon

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Hämtar en flagga som specificerar om annotationen initialt ska visas öppen.

**Returns:**
booleskt värde

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Ställer in en ikon som ska användas vid visning av annotationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | TextIcon-värde @see TextIcon |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Ställer in en flagga som specificerar om annotationen initialt ska visas öppen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
