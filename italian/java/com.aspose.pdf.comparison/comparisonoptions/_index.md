---
title: "ComparisonOptions"
linktitle: "ComparisonOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe di opzioni di confronto di documenti PDF."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.comparison/comparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.ComparisonOptions

```
public class ComparisonOptions extends Object
```

Rappresenta una classe di opzioni di confronto di documenti PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ComparisonOptions](#ComparisonOptions--) | Crea un'istanza della classe {@link ComparisonOptions}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEditOperationsOrder](#getEditOperationsOrder--) | Ottiene e imposta l'ordine delle operazioni di modifica. |
| [getExcludeAreas1](#getExcludeAreas1--) | Ottieni e imposta le aree escluse. Utilizzato per la prima pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme a {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [getExcludeAreas2](#getExcludeAreas2--) | Ottieni e imposta le aree escluse. Utilizzato per la seconda pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme a {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [getExtractionArea](#getExtractionArea--) | Ottieni e imposta l'area rettangolare in cui il testo delle pagine verrà confrontato. Questa opzione non può essere impostata insieme a {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) e { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) . |
| [isExcludeTables](#isExcludeTables--) | Ottieni e imposta l'opzione che determina se le tabelle sono escluse dal confronto. Questa opzione non può essere impostata insieme a {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). Il valore predefinito è {@code false}. |
| [setEditOperationsOrder](#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-) | Ottiene e imposta l'ordine delle operazioni di modifica. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Ottieni e imposta le aree escluse. Utilizzato per la prima pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme a {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Ottieni e imposta le aree escluse. Utilizzato per la seconda pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme a {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [setExcludeTables](#setExcludeTables-boolean-) | Ottieni e imposta l'opzione che determina se le tabelle sono escluse dal confronto. Questa opzione non può essere impostata insieme a {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). Il valore predefinito è {@code false}. |
| [setExtractionArea](#setExtractionArea-com.aspose.pdf.Rectangle-) | Ottieni e imposta l'area rettangolare in cui il testo delle pagine verrà confrontato. Questa opzione non può essere impostata insieme a {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) e { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) . |

### ComparisonOptions {#ComparisonOptions--}
```
public ComparisonOptions()
```

Crea un'istanza della classe {@link ComparisonOptions}.

### getEditOperationsOrder {#getEditOperationsOrder--}
```
public final EditOperationsOrder getEditOperationsOrder()
```

Ottiene e imposta l'ordine delle operazioni di modifica.

**Returns:**
Elemento EditOperationsOrder

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Ottieni e imposta le aree escluse. Utilizzato per la prima pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme a {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

**Returns:**
array di istanze Rectangle

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Ottieni e imposta le aree escluse. Utilizzato per la seconda pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme a {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

**Returns:**
array di istanze Rectangle

### getExtractionArea {#getExtractionArea--}
```
public final Rectangle getExtractionArea()
```

Ottieni e imposta l'area rettangolare in cui il testo delle pagine verrà confrontato. Questa opzione non può essere impostata insieme a {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) e { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) .

**Returns:**
Istanza Rectangle

### isExcludeTables {#isExcludeTables--}
```
public final boolean isExcludeTables()
```

Ottieni e imposta l'opzione che determina se le tabelle sono escluse dal confronto. Questa opzione non può essere impostata insieme a {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). Il valore predefinito è {@code false}.

**Returns:**
valore booleano

### setEditOperationsOrder {#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-}
Ottiene e imposta l'ordine delle operazioni di modifica.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Ottieni e imposta le aree escluse. Utilizzato per la prima pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme a {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Ottieni e imposta le aree escluse. Utilizzato per la seconda pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme a {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Ottieni e imposta l'opzione che determina se le tabelle sono escluse dal confronto. Questa opzione non può essere impostata insieme a {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). Il valore predefinito è {@code false}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setExtractionArea {#setExtractionArea-com.aspose.pdf.Rectangle-}
Ottieni e imposta l'area rettangolare in cui il testo delle pagine verrà confrontato. Questa opzione non può essere impostata insieme a {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) e { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) .
