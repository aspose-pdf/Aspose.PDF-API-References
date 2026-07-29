---
title: "Cell"
linktitle: "Cell"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en cell i tabellens rad."
type: docs
weight: 510
url: /sv/java/com.aspose.pdf/cell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Cell

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Cell extends Object implements com.aspose.ms.System.ICloneable
```

Representerar en cell i tabellens rad.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Cell](#Cell--) | Initierar en ny instans av Cell-klassen. |
| [Cell](#Cell-com.aspose.pdf.Rectangle-) | Initierar en ny instans av Cell-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone](#deepClone--) | Klona cellen. |
| [getAlignment](#getAlignment--) | Hämtar justeringen. |
| [getBackgroundColor](#getBackgroundColor--) | Hämtar bakgrundsfärgen. |
| [getBackgroundImage](#getBackgroundImage--) | Hämtar eller anger bakgrundsbilden |
| [getBackgroundImageFile](#getBackgroundImageFile--) | Hämtar bakgrundsbildfilen. |
| [getBorder](#getBorder--) | Hämtar kanten. |
| [getColSpan](#getColSpan--) | Hämtar eller anger kolumnspannet. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Hämtar standardcellens texttillstånd. |
| [getMargin](#getMargin--) | Hämtar utfyllnaden. |
| [getParagraphs](#getParagraphs--) | Hämtar cellens formaterade text. |
| [getRowSpan](#getRowSpan--) | Hämtar radspannet. |
| [getVerticalAlignment](#getVerticalAlignment--) | Hämtar vertikal justering. |
| [getWidth](#getWidth--) | Hämtar kolumnbredden. |
| [isNoBorder](#isNoBorder--) | Hämtar om cellen har kant. |
| [isOverrideByFragment](#isOverrideByFragment--) | Ställer in att cellens TextState-egenskap åsidosätts av TextFragment TextState-egenskap. |
| [isWordWrapped](#isWordWrapped--) | Hämtar om cellens text är radbryten. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Ställer in justeringen. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Hämtar eller ställer in bakgrundsfärgen. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Hämtar eller anger bakgrundsbilden |
| [setBackgroundImageFile](#setBackgroundImageFile-java.lang.String-) | Ställer in bakgrundsbildfilen. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Anger kanten. |
| [setColSpan](#setColSpan-int-) | Ställer in kolumnspannet. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Sätter standardcelltexttillstånd. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Ställer in utfyllnaden. |
| [setNoBorder](#setNoBorder-boolean-) | Ställer in att cellen har kant. |
| [setOverrideByFragment](#setOverrideByFragment-boolean-) | Ställer in att cellens TextState-egenskap åsidosätts av TextFragment TextState-egenskap. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Ställer in cellens formaterade text. |
| [setRowSpan](#setRowSpan-int-) | Ställer in radspannet. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Ställer in vertikal justering. |
| [setWidth](#setWidth-double-) | Ställer in kolumnbredden. |
| [setWordWrapped](#setWordWrapped-boolean-) | Ställer in att cellens text är radbryten. |

### Cell {#Cell--}
```
public Cell()
```

Initierar en ny instans av Cell-klassen.

### Cell {#Cell-com.aspose.pdf.Rectangle-}
Initierar en ny instans av Cell-klassen.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klona cellen.

**Returns:**
Det klonade objektet

### getAlignment {#getAlignment--}
```
public HorizontalAlignment getAlignment()
```

Hämtar justeringen.

**Returns:**
HorizontalAlignment-element @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Hämtar bakgrundsfärgen.

**Returns:**
Color‑objekt

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Hämtar eller anger bakgrundsbilden

**Returns:**
Bildinstans

### getBackgroundImageFile {#getBackgroundImageFile--}
```
@Deprecated public String getBackgroundImageFile()
```

Hämtar bakgrundsbildfilen.

**Returns:**
Strängvärde @deprecated Egenskapen utökades, använd BackgroundImage

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Hämtar kanten.

**Returns:**
BorderInfo-objekt

### getColSpan {#getColSpan--}
```
public int getColSpan()
```

Hämtar eller anger kolumnspannet.

**Returns:**
int‑värde

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Hämtar standardcellens texttillstånd.

**Returns:**
TextState-objekt

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Hämtar utfyllnaden.

**Returns:**
MarginInfo‑objekt

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Hämtar cellens formaterade text.

**Returns:**
Paragraphs-objekt

### getRowSpan {#getRowSpan--}
```
public int getRowSpan()
```

Hämtar radspannet.

**Returns:**
int‑värde

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Hämtar vertikal justering.

**Returns:**
VerticalAlignment-element @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Hämtar kolumnbredden.

**Returns:**
double-värde

### isNoBorder {#isNoBorder--}
```
public boolean isNoBorder()
```

Hämtar om cellen har kant.

**Returns:**
booleskt värde

### isOverrideByFragment {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```

Ställer in att cellens TextState-egenskap åsidosätts av TextFragment TextState-egenskap.

**Returns:**
booleskt värde

### isWordWrapped {#isWordWrapped--}
```
public boolean isWordWrapped()
```

Hämtar om cellens text är radbryten.

**Returns:**
booleskt värde

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Ställer in justeringen.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Hämtar eller ställer in bakgrundsfärgen.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Hämtar eller anger bakgrundsbilden

### setBackgroundImageFile {#setBackgroundImageFile-java.lang.String-}
Ställer in bakgrundsbildfilen.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Anger kanten.

### setColSpan {#setColSpan-int-}
```
public void setColSpan(int value)
```

Ställer in kolumnspannet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Sätter standardcelltexttillstånd.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Ställer in utfyllnaden.

### setNoBorder {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```

Ställer in att cellen har kant.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setOverrideByFragment {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```

Ställer in att cellens TextState-egenskap åsidosätts av TextFragment TextState-egenskap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Ställer in cellens formaterade text.

### setRowSpan {#setRowSpan-int-}
```
public void setRowSpan(int value)
```

Ställer in radspannet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Ställer in vertikal justering.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Ställer in kolumnbredden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setWordWrapped {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```

Ställer in att cellens text är radbryten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
