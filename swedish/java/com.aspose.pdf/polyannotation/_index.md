---
title: "PolyAnnotation"
linktitle: "PolyAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Abstrakt basklass för poly-annotationer."
type: docs
weight: 3890
url: /sv/java/com.aspose.pdf/polyannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.PolyAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class PolyAnnotation extends MarkupAnnotation
```

Abstrakt basklass för poly-annotationer.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Uppdaterar punkterna i Vertices enligt matrisens transformation. |
| [getEndingStyle](#getEndingStyle--) | Hämtar stilen för den andra linjeänden. |
| [getIntent](#getIntent--) | Hämtar avsikten för polygon- eller polylinjeanteckningen. |
| [getInteriorColor](#getInteriorColor--) | Hämtar den inre färgen som används för att fylla anteckningens linjeändar. |
| [getMeasure](#getMeasure--) | Måttenheter som specificerats för denna anteckning. |
| [getStartingStyle](#getStartingStyle--) | Hämtar stilen för den första linjeänden. |
| [getVertices](#getVertices--) | Hämtar en matris av punkter som representerar de horisontella och vertikala koordinaterna för varje hörn. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Anger stilen för den andra linjeänden. |
| [setIntent](#setIntent-com.aspose.pdf.PolyIntent-) | Anger avsikten för polygon- eller polylinjeanteckningen. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Anger den inre färgen som används för att fylla anteckningens linjeändar. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Måttenheter som specificerats för denna anteckning. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Anger stilen för den första linjeänden. |
| [setVertices](#setVertices-com.aspose.pdf.Point:A-) | Anger en matris av punkter som representerar de horisontella och vertikala koordinaterna för varje hörn. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Uppdaterar punkterna i Vertices enligt matrisens transformation.

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Hämtar stilen för den andra linjeänden.

**Returns:**
LineEnding-element @see LineEnding

### getIntent {#getIntent--}
```
public PolyIntent getIntent()
```

Hämtar avsikten för polygon- eller polylinjeanteckningen.

**Returns:**
PolyIntent-element @see PolyIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Hämtar den inre färgen som används för att fylla anteckningens linjeändar.

**Returns:**
Color‑objekt

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Måttenheter som specificerats för denna anteckning.

**Returns:**
Måttinstans

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Hämtar stilen för den första linjeänden.

**Returns:**
LineEnding-element @see LineEnding

### getVertices {#getVertices--}
```
public Point [] getVertices()
```

Hämtar en matris av punkter som representerar de horisontella och vertikala koordinaterna för varje hörn.

**Returns:**
array av Point-värde

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Anger stilen för den andra linjeänden.

### setIntent {#setIntent-com.aspose.pdf.PolyIntent-}
Anger avsikten för polygon- eller polylinjeanteckningen.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Anger den inre färgen som används för att fylla anteckningens linjeändar.

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Måttenheter som specificerats för denna anteckning.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Anger stilen för den första linjeänden.

### setVertices {#setVertices-com.aspose.pdf.Point:A-}
Anger en matris av punkter som representerar de horisontella och vertikala koordinaterna för varje hörn.
