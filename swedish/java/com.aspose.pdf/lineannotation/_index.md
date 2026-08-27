---
title: "LineAnnotation"
linktitle: "LineAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar linjeanteckning."
type: docs
weight: 2710
url: /sv/java/com.aspose.pdf/lineannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.LineAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class LineAnnotation extends MarkupAnnotation
```

Klass som representerar linjeanteckning.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Konstruktor för användning med Generator. |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Skapar en ny linjeanteckning på den angivna sidan. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökare för annoteringsbearbetning. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Uppdaterar start- och slutpunkterna enligt matrisomvandlingen. |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getCaptionOffset](#getCaptionOffset--) | Hämtar bildtextens förskjutning från dess normala position. |
| [getCaptionPosition](#getCaptionPosition--) | Hämtar annoteringens bildtextposition. |
| [getEnding](#getEnding--) | Hämtar linjens slutpunkt. |
| [getEndingStyle](#getEndingStyle--) | Hämtar avslutningsstil för linjens slutpunkt. |
| [getIntent](#getIntent--) | Hämtar avsikten med linjeannoteringen. |
| [getInteriorColor](#getInteriorColor--) | Hämtar den inre färgen på annoteringen. |
| [getLeaderLine](#getLeaderLine--) | Hämtar ledarlinjens längd. |
| [getLeaderLineExtension](#getLeaderLineExtension--) | Hämtar förlängningens längd för ledarlinjen. |
| [getLeaderLineOffset](#getLeaderLineOffset--) | Hämtar ledarlinjens förskjutning. |
| [getMeasure](#getMeasure--) | Måttenheter specificerade för denna annotering. |
| [getShowCaption](#getShowCaption--) | Hämtar booleskt flagga som bestämmer om innehållet ska visas som bildtext. |
| [getStarting](#getStarting--) | Hämtar linjens startpunkt. |
| [getStartingStyle](#getStartingStyle--) | Hämtar linjens avslutningsstil för linjens startpunkt. |
| [setCaptionOffset](#setCaptionOffset-com.aspose.pdf.Point-) | Ställer in bildtextens förskjutning från dess normala position. |
| [setCaptionPosition](#setCaptionPosition-com.aspose.pdf.CaptionPosition-) | Ställer in annoteringens bildtextposition. |
| [setEnding](#setEnding-com.aspose.pdf.Point-) | Ställer in linjens slutpunkt. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Ställer in avslutningsstil för linjens slutpunkt. |
| [setIntent](#setIntent-com.aspose.pdf.LineIntent-) | Ställer in avsikten med linjeannoteringen. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Ställer in den inre färgen på annoteringen. |
| [setLeaderLine](#setLeaderLine-double-) | Ställer in ledarlinjens längd. |
| [setLeaderLineExtension](#setLeaderLineExtension-double-) | Ställer in förlängningens längd för ledarlinjen. |
| [setLeaderLineOffset](#setLeaderLineOffset-double-) | Ställer in förskjutning för ledarlinje. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Måttenheter specificerade för denna annotering. |
| [setShowCaption](#setShowCaption-boolean-) | Ställer in booleskt flagga som bestämmer om innehållet ska visas som bildtext. |
| [setStarting](#setStarting-com.aspose.pdf.Point-) | Ställer in startpunkten för linjen. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Ställer in linjeavslutningsstil för linjens startpunkt. |

### LineAnnotation {#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Konstruktor för användning med Generator.

### LineAnnotation {#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Skapar en ny linjeanteckning på den angivna sidan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökare för annoteringsbearbetning.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Uppdaterar start- och slutpunkterna enligt matrisomvandlingen.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
AnnotationType-element @see AnnotationType

### getCaptionOffset {#getCaptionOffset--}
```
public Point getCaptionOffset()
```

Hämtar bildtextens förskjutning från dess normala position.

**Returns:**
Point objekt

### getCaptionPosition {#getCaptionPosition--}
```
public CaptionPosition getCaptionPosition()
```

Hämtar annoteringens bildtextposition.

**Returns:**
CaptionPosition-element @see CaptionPosition

### getEnding {#getEnding--}
```
public Point getEnding()
```

Hämtar linjens slutpunkt.

**Returns:**
Punktvärde

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Hämtar avslutningsstil för linjens slutpunkt.

**Returns:**
LineEnding-element @see LineEnding

### getIntent {#getIntent--}
```
public LineIntent getIntent()
```

Hämtar avsikten med linjeannoteringen.

**Returns:**
LineIntent-element @see LineIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Hämtar den inre färgen på annoteringen.

**Returns:**
Color‑objekt

### getLeaderLine {#getLeaderLine--}
```
public double getLeaderLine()
```

Hämtar ledarlinjens längd.

**Returns:**
double-värde

### getLeaderLineExtension {#getLeaderLineExtension--}
```
public double getLeaderLineExtension()
```

Hämtar förlängningens längd för ledarlinjen.

**Returns:**
double-värde

### getLeaderLineOffset {#getLeaderLineOffset--}
```
public double getLeaderLineOffset()
```

Hämtar ledarlinjens förskjutning.

**Returns:**
double-värde

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Måttenheter specificerade för denna annotering.

**Returns:**
Mätningsobjekt

### getShowCaption {#getShowCaption--}
```
public boolean getShowCaption()
```

Hämtar booleskt flagga som bestämmer om innehållet ska visas som bildtext.

**Returns:**
booleskt värde

### getStarting {#getStarting--}
```
public Point getStarting()
```

Hämtar linjens startpunkt.

**Returns:**
Punktvärde

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Hämtar linjens avslutningsstil för linjens startpunkt.

**Returns:**
LineEnding-element @see LineEnding

### setCaptionOffset {#setCaptionOffset-com.aspose.pdf.Point-}
Ställer in bildtextens förskjutning från dess normala position.

### setCaptionPosition {#setCaptionPosition-com.aspose.pdf.CaptionPosition-}
Ställer in annoteringens bildtextposition.

### setEnding {#setEnding-com.aspose.pdf.Point-}
Ställer in linjens slutpunkt.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Ställer in avslutningsstil för linjens slutpunkt.

### setIntent {#setIntent-com.aspose.pdf.LineIntent-}
Ställer in avsikten med linjeannoteringen.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Ställer in den inre färgen på annoteringen.

### setLeaderLine {#setLeaderLine-double-}
```
public void setLeaderLine(double value)
```

Ställer in ledarlinjens längd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setLeaderLineExtension {#setLeaderLineExtension-double-}
```
public void setLeaderLineExtension(double value)
```

Ställer in förlängningens längd för ledarlinjen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setLeaderLineOffset {#setLeaderLineOffset-double-}
```
public void setLeaderLineOffset(double value)
```

Ställer in förskjutning för ledarlinje.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Måttenheter specificerade för denna annotering.

### setShowCaption {#setShowCaption-boolean-}
```
public void setShowCaption(boolean value)
```

Ställer in booleskt flagga som bestämmer om innehållet ska visas som bildtext.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setStarting {#setStarting-com.aspose.pdf.Point-}
Ställer in startpunkten för linjen.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Ställer in linjeavslutningsstil för linjens startpunkt.
