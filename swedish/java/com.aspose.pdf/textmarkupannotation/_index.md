---
title: "TextMarkupAnnotation"
linktitle: "TextMarkupAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Abstrakt basklass för textmarkeringanteckningar."
type: docs
weight: 5180
url: /sv/java/com.aspose.pdf/textmarkupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextMarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class TextMarkupAnnotation extends MarkupAnnotation
```

Abstrakt basklass för textmarkeringanteckningar.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Uppdaterar QuadPoints enligt matrisomvandlingen. |
| [getMarkedText](#getMarkedText--) | Hämtar text under markup-annotation som sträng. |
| [getMarkedTextFragments](#getMarkedTextFragments--) | Hämtar text under markup-annotation som {@code TextFragmentCollection}. |
| [getQuadPoints](#getQuadPoints--) | Hämtar en array av punkter som specificerar koordinaterna för n fyrhörningar. Varje fyrhörning omfattar ett ord eller en grupp av sammanhängande ord i den text som ligger under annotationen. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Ställer in en array av punkter som specificerar koordinaterna för n fyrhörningar. Varje fyrhörning omfattar ett ord eller en grupp av sammanhängande ord i den text som ligger under annotationen. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Uppdaterar QuadPoints enligt matrisomvandlingen.

### getMarkedText {#getMarkedText--}
```
public String getMarkedText()
```

Hämtar text under markup-annotation som sträng.

**Returns:**
Sträng som innehåller text som är under markup-annotation.

### getMarkedTextFragments {#getMarkedTextFragments--}
```
public TextFragmentCollection getMarkedTextFragments()
```

Hämtar text under markup-annotation som {@code TextFragmentCollection}.

**Returns:**
{@code TextFragmentCollection} som innehåller {@code TextFragment}s som är under markup-annotation.

### getQuadPoints {#getQuadPoints--}
```
public Point [] getQuadPoints()
```

Hämtar en array av punkter som specificerar koordinaterna för n fyrhörningar. Varje fyrhörning omfattar ett ord eller en grupp av sammanhängande ord i den text som ligger under annotationen.

**Returns:**
array av Point-värde

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Ställer in en array av punkter som specificerar koordinaterna för n fyrhörningar. Varje fyrhörning omfattar ett ord eller en grupp av sammanhängande ord i den text som ligger under annotationen.
