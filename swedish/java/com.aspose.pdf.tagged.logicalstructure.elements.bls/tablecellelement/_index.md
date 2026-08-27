---
title: "TableCellElement"
linktitle: "TableCellElement"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en basklass för tabellcellselement (TH och TD) i logisk struktur."
type: docs
weight: 150
url: /sv/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class TableCellElement extends TableChildElement implements ITextElement , IAdjustPosition
```

Representerar en basklass för tabellcellselement (TH och TD) i logisk struktur.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Justera position. |
| [getAlignment](#getAlignment--) | Hämtar eller anger cellens justering. |
| [getBackgroundColor](#getBackgroundColor--) | Hämtar eller anger cellens bakgrundsfärg. |
| [getBorder](#getBorder--) | Hämtar eller anger cellens kant. |
| [getCell](#getCell--) |  |
| [getColSpan](#getColSpan--) | Hämtar eller anger kolumnspannet. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Hämtar eller anger standardcellens texttillstånd. |
| [getMargin](#getMargin--) | Hämtar eller anger utfyllnad. |
| [getRowSpan](#getRowSpan--) | Hämtar eller anger radspannet. |
| [getStructureTextState](#getStructureTextState--) | Hämtar {@code /Aspose.Pdf.LogicalStructure.StructureTextState}-objektet för aktuellt element. Värde: {@code /Aspose.Pdf.LogicalStructure.StructureTextState}-objektet för aktuellt element. |
| [getVerticalAlignment](#getVerticalAlignment--) | Hämtar eller anger vertikal justering. |
| [isNoBorder](#isNoBorder--) | Hämtar eller anger om cellen har kant. |
| [isWordWrapped](#isWordWrapped--) | Hämtar eller anger om cellens text är radbryten. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Hämtar eller anger cellens justering. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Hämtar eller anger cellens bakgrundsfärg. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Hämtar eller anger cellens kant. |
| [setColSpan](#setColSpan-int-) | Hämtar eller anger kolumnspannet. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Hämtar eller anger standardcellens texttillstånd. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Hämtar eller anger utfyllnad. |
| [setNoBorder](#setNoBorder-boolean-) | Hämtar eller anger om cellen har kant. |
| [setRowSpan](#setRowSpan-int-) | Hämtar eller anger radspannet. |
| [setText](#setText-java.lang.String-) | Lägger till textinnehåll till aktuellt textelement. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Hämtar eller anger vertikal justering. |
| [setWordWrapped](#setWordWrapped-boolean-) | Hämtar eller anger om cellens text är radbryten. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Justera position.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Hämtar eller anger cellens justering.

**Returns:**
HorizontalAlignment-element

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Hämtar eller anger cellens bakgrundsfärg.

**Returns:**
Color-instans

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Hämtar eller anger cellens kant.

**Returns:**
BorderInfo instans

### getCell {#getCell--}
```
public final Cell getCell()
```



### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Hämtar eller anger kolumnspannet.

**Returns:**
int‑värde

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Hämtar eller anger standardcellens texttillstånd.

**Returns:**
TextState-instans

### getMargin {#getMargin--}
```
public final MarginInfo getMargin()
```

Hämtar eller anger utfyllnad.

**Returns:**
MarginInfo instans

### getRowSpan {#getRowSpan--}
```
public final int getRowSpan()
```

Hämtar eller anger radspannet.

**Returns:**
int‑värde

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Hämtar {@code /Aspose.Pdf.LogicalStructure.StructureTextState}-objektet för aktuellt element. Värde: {@code /Aspose.Pdf.LogicalStructure.StructureTextState}-objektet för aktuellt element.

**Returns:**
StructureTextState-instans

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Hämtar eller anger vertikal justering.

**Returns:**
VerticalAlignment-element

### isNoBorder {#isNoBorder--}
```
public final boolean isNoBorder()
```

Hämtar eller anger om cellen har kant.

**Returns:**
booleskt värde

### isWordWrapped {#isWordWrapped--}
```
public final boolean isWordWrapped()
```

Hämtar eller anger om cellens text är radbryten.

**Returns:**
booleskt värde

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Hämtar eller anger cellens justering.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Hämtar eller anger cellens bakgrundsfärg.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Hämtar eller anger cellens kant.

### setColSpan {#setColSpan-int-}
```
public final void setColSpan(int value)
```

Hämtar eller anger kolumnspannet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Hämtar eller anger standardcellens texttillstånd.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Hämtar eller anger utfyllnad.

### setNoBorder {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```

Hämtar eller anger om cellen har kant.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRowSpan {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```

Hämtar eller anger radspannet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setText {#setText-java.lang.String-}
Lägger till textinnehåll till aktuellt textelement.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Hämtar eller anger vertikal justering.

### setWordWrapped {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```

Hämtar eller anger om cellens text är radbryten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
