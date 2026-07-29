---
title: "TableCellElement"
linktitle: "TableCellElement"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe base per gli elementi di cella della tabella (TH e TD) nella struttura logica."
type: docs
weight: 150
url: /it/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class TableCellElement extends TableChildElement implements ITextElement , IAdjustPosition
```

Rappresenta una classe base per gli elementi di cella della tabella (TH e TD) nella struttura logica.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Regola posizione. |
| [getAlignment](#getAlignment--) | Ottiene o imposta l'allineamento della cella. |
| [getBackgroundColor](#getBackgroundColor--) | Ottiene o imposta il colore di sfondo della cella. |
| [getBorder](#getBorder--) | Ottiene o imposta il bordo della cella. |
| [getCell](#getCell--) |  |
| [getColSpan](#getColSpan--) | Ottiene o imposta l'estensione della colonna. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Ottiene o imposta lo stato di testo predefinito della cella. |
| [getMargin](#getMargin--) | Ottiene o imposta il padding. |
| [getRowSpan](#getRowSpan--) | Ottiene o imposta l'estensione della riga. |
| [getStructureTextState](#getStructureTextState--) | Ottiene l'oggetto {@code /Aspose.Pdf.LogicalStructure.StructureTextState} per l'elemento corrente. Valore: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} oggetto per l'elemento corrente. |
| [getVerticalAlignment](#getVerticalAlignment--) | Ottiene o imposta l'allineamento verticale. |
| [isNoBorder](#isNoBorder--) | Ottiene o imposta se la cella ha il bordo. |
| [isWordWrapped](#isWordWrapped--) | Ottiene o imposta l'avvolgimento del testo della cella. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Ottiene o imposta l'allineamento della cella. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Ottiene o imposta il colore di sfondo della cella. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Ottiene o imposta il bordo della cella. |
| [setColSpan](#setColSpan-int-) | Ottiene o imposta l'estensione della colonna. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Ottiene o imposta lo stato di testo predefinito della cella. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Ottiene o imposta il padding. |
| [setNoBorder](#setNoBorder-boolean-) | Ottiene o imposta se la cella ha il bordo. |
| [setRowSpan](#setRowSpan-int-) | Ottiene o imposta l'estensione della riga. |
| [setText](#setText-java.lang.String-) | Aggiunge contenuto di testo all'elemento di testo corrente. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Ottiene o imposta l'allineamento verticale. |
| [setWordWrapped](#setWordWrapped-boolean-) | Ottiene o imposta l'avvolgimento del testo della cella. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Regola posizione.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Ottiene o imposta l'allineamento della cella.

**Returns:**
Elemento HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Ottiene o imposta il colore di sfondo della cella.

**Returns:**
Istanza di Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Ottiene o imposta il bordo della cella.

**Returns:**
Istanza BorderInfo

### getCell {#getCell--}
```
public final Cell getCell()
```



### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Ottiene o imposta l'estensione della colonna.

**Returns:**
valore int

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Ottiene o imposta lo stato di testo predefinito della cella.

**Returns:**
istanza TextState

### getMargin {#getMargin--}
```
public final MarginInfo getMargin()
```

Ottiene o imposta il padding.

**Returns:**
Istanza MarginInfo

### getRowSpan {#getRowSpan--}
```
public final int getRowSpan()
```

Ottiene o imposta l'estensione della riga.

**Returns:**
valore int

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Ottiene l'oggetto {@code /Aspose.Pdf.LogicalStructure.StructureTextState} per l'elemento corrente. Valore: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} oggetto per l'elemento corrente.

**Returns:**
Istanza StructureTextState

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Ottiene o imposta l'allineamento verticale.

**Returns:**
Elemento VerticalAlignment

### isNoBorder {#isNoBorder--}
```
public final boolean isNoBorder()
```

Ottiene o imposta se la cella ha il bordo.

**Returns:**
valore booleano

### isWordWrapped {#isWordWrapped--}
```
public final boolean isWordWrapped()
```

Ottiene o imposta l'avvolgimento del testo della cella.

**Returns:**
valore booleano

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Ottiene o imposta l'allineamento della cella.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Ottiene o imposta il colore di sfondo della cella.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Ottiene o imposta il bordo della cella.

### setColSpan {#setColSpan-int-}
```
public final void setColSpan(int value)
```

Ottiene o imposta l'estensione della colonna.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Ottiene o imposta lo stato di testo predefinito della cella.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Ottiene o imposta il padding.

### setNoBorder {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```

Ottiene o imposta se la cella ha il bordo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRowSpan {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```

Ottiene o imposta l'estensione della riga.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setText {#setText-java.lang.String-}
Aggiunge contenuto di testo all'elemento di testo corrente.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Ottiene o imposta l'allineamento verticale.

### setWordWrapped {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```

Ottiene o imposta l'avvolgimento del testo della cella.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
