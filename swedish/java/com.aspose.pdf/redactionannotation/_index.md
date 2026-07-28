---
title: "RedactionAnnotation"
linktitle: "RedactionAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar Redact-annotation."
type: docs
weight: 4120
url: /sv/java/com.aspose.pdf/redactionannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.RedactionAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class RedactionAnnotation extends MarkupAnnotation
```

Representerar Redact-annotation.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.IDocument-) | Konstruktor för RedactionAnnotation. För användning i Generator. |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Konstruktor för RedactAnnotation. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökarobjekt för att bearbeta annotationen. |
| [flatten](#flatten--) | Plattar till annotation, d.v.s. tar bort annotation och lägger till dess innehåll |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getBorderColor](#getBorderColor--) | Hämtar färgen på kanten som ritas när radering inte är aktiv. |
| [getDefaultAppearance](#getDefaultAppearance--) | Hämtar eller anger standardutseendesträngen som ska användas vid formatering av texten. |
| [getFillColor](#getFillColor--) | Hämtar färgen för att fylla annotation. |
| [getFontSize](#getFontSize--) | Hämtar teckenstorlek för OverlayText. |
| [getOverlayText](#getOverlayText--) | Hämtar text att skriva ut på redact-annotation. |
| [getQuadPoint](#getQuadPoint--) | En array med 8xN‑tal som specificerar koordinaterna för innehållsområdet som ska tas bort. |
| [getQuadPoints](#getQuadPoints--) | Hämtar en array av punkter som specificerar koordinaterna för n fyrhörningar. Varje fyrhörning omfattar ett ord eller en grupp av sammanhängande ord i den text som ligger under annotationen. |
| [getTextAlignment](#getTextAlignment--) | Hämtar justering för Overlay Text. |
| [isRepeat](#isRepeat--) | Om true kommer överlagringstext att upprepas på annotationen. |
| [redact](#redact--) | Plattar till annotation och raderar sidinnehåll (d.v.s. tar bort text- och bildinnehåll under raderad annotation) |
| [redactExact](#redactExact--) | Plattar till annotation och raderar sidinnehåll (d.v.s. tar bort text- och bildinnehåll exakt under raderad annotation) |
| [setBorderColor](#setBorderColor-com.aspose.pdf.Color-) | Anger färgen på kanten som ritas när radering inte är aktiv. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Hämtar eller anger standardutseendesträngen som ska användas vid formatering av texten. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | Ställer in färg för att fylla annotationen. |
| [setFontSize](#setFontSize-float-) | Ställer in teckenstorlek för OverlayText. Standardvärdet är 10. |
| [setOverlayText](#setOverlayText-java.lang.String-) | Ställer in text som ska skrivas på redact-annotation. |
| [setQuadPoint](#setQuadPoint-com.aspose.pdf.Point:A-) | En array med 8xN‑tal som specificerar koordinaterna för innehållsområdet som ska tas bort. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Ställer in en array av punkter som specificerar koordinaterna för n fyrhörningar. Varje fyrhörning omfattar ett ord eller en grupp av sammanhängande ord i den text som ligger under annotationen. |
| [setRepeat](#setRepeat-boolean-) | Om true kommer överlagringstext att upprepas på annotationen. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Ställer in justering av Overlay Text. |

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.IDocument-}
Konstruktor för RedactionAnnotation. För användning i Generator.

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Konstruktor för RedactAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökarobjekt för att bearbeta annotationen.

### flatten {#flatten--}
```
public void flatten()
```

Plattar till annotation, d.v.s. tar bort annotation och lägger till dess innehåll

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
AnnotationType-element @see AnnotationType

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

Hämtar färgen på kanten som ritas när radering inte är aktiv.

**Returns:**
Färgvärde

### getDefaultAppearance {#getDefaultAppearance--}
```
public final String getDefaultAppearance()
```

Hämtar eller anger standardutseendesträngen som ska användas vid formatering av texten.

**Returns:**
String värde

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

Hämtar färgen för att fylla annotation.

**Returns:**
färgvärde

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Hämtar teckenstorlek för OverlayText.

**Returns:**
int‑värde

### getOverlayText {#getOverlayText--}
```
public String getOverlayText()
```

Hämtar text att skriva ut på redact-annotation.

**Returns:**
strängvärde

### getQuadPoint {#getQuadPoint--}
```
public Point [] getQuadPoint()
```

En array med 8xN‑tal som specificerar koordinaterna för innehållsområdet som ska tas bort.

**Returns:**
array av punkter

### getQuadPoints {#getQuadPoints--}
```
@Deprecated public Point [] getQuadPoints()
```

Hämtar en array av punkter som specificerar koordinaterna för n fyrhörningar. Varje fyrhörning omfattar ett ord eller en grupp av sammanhängande ord i den text som ligger under annotationen.

**Returns:**
array av Point-värde

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Hämtar justering för Overlay Text.

**Returns:**
HorizontalAlignment‑värde @see HorizontalAlignment

### isRepeat {#isRepeat--}
```
public boolean isRepeat()
```

Om true kommer överlagringstext att upprepas på annotationen.

**Returns:**
booleskt värde

### redact {#redact--}
```
public void redact()
```

Plattar till annotation och raderar sidinnehåll (d.v.s. tar bort text- och bildinnehåll under raderad annotation)

### redactExact {#redactExact--}
```
public void redactExact()
```

Plattar till annotation och raderar sidinnehåll (d.v.s. tar bort text- och bildinnehåll exakt under raderad annotation)

### setBorderColor {#setBorderColor-com.aspose.pdf.Color-}
Anger färgen på kanten som ritas när radering inte är aktiv.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Hämtar eller anger standardutseendesträngen som ska användas vid formatering av texten.

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
Ställer in färg för att fylla annotationen.

### setFontSize {#setFontSize-float-}
```
public final void setFontSize(float fontSize)
```

Ställer in teckenstorlek för OverlayText. Standardvärdet är 10.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontSize |  | int‑värde |

### setOverlayText {#setOverlayText-java.lang.String-}
Ställer in text som ska skrivas på redact-annotation.

### setQuadPoint {#setQuadPoint-com.aspose.pdf.Point:A-}
En array med 8xN‑tal som specificerar koordinaterna för innehållsområdet som ska tas bort.

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Ställer in en array av punkter som specificerar koordinaterna för n fyrhörningar. Varje fyrhörning omfattar ett ord eller en grupp av sammanhängande ord i den text som ligger under annotationen.

### setRepeat {#setRepeat-boolean-}
```
public void setRepeat(boolean value)
```

Om true kommer överlagringstext att upprepas på annotationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Ställer in justering av Overlay Text.
