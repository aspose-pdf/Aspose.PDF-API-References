---
title: "SideBySideComparisonOptions"
linktitle: "SideBySideComparisonOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe di opzioni per il confronto di documenti con output affiancato."
type: docs
weight: 60
url: /it/java/com.aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget, com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions

```
public class SideBySideComparisonOptions extends IVentureLicenseTarget
```

Rappresenta una classe di opzioni per il confronto di documenti con output affiancato.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SideBySideComparisonOptions](#SideBySideComparisonOptions--) | Crea un'istanza della classe {@link SideBySideComparisonOptions}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAdditionalChangeMarks](#getAdditionalChangeMarks--) | Ottieni e imposta la proprietà che determina se i marcatori di modifica aggiuntivi sono visualizzati. Se impostata, visualizza i segni di modifica che non sono nella pagina corrente ma sono presenti in un'altra pagina. Se la modifica si colloca tra le parole, il segno potrebbe non essere posizionato esattamente rispetto al carattere di spazio. Il valore predefinito è {@code false}. |
| [getComparisonArea1](#getComparisonArea1--) | Ottieni e imposta l'area di confronto. Utilizzata per la prima pagina o documento nel metodo di confronto. Questa opzione non può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opzioni. |
| [getComparisonArea2](#getComparisonArea2--) | Ottieni e imposta l'area di confronto. Utilizzata per la seconda pagina o documento nel metodo di confronto. Questa opzione non può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opzioni. |
| [getComparisonMode](#getComparisonMode--) | Restituisce e imposta una modalità di confronto. Il valore predefinito è {@link ComparisonMode#IgnoreSpaces}. |
| [getDeleteColor](#getDeleteColor--) | Restituisce il colore utilizzato per evidenziare il contenuto eliminato durante un confronto affiancato. Questa proprietà definisce la rappresentazione visiva delle eliminazioni nel risultato del confronto. |
| [getExcludeAreas1](#getExcludeAreas1--) | Ottieni e imposta le aree da escludere. Utilizzate per la prima pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme all'opzione {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}). |
| [getExcludeAreas2](#getExcludeAreas2--) | Ottieni e imposta le aree da escludere. Utilizzate per la seconda pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme all'opzione {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). |
| [getExcludeTables](#getExcludeTables--) | Ottieni e imposta l'opzione che determina se le tabelle sono escluse dal confronto. Questa opzione non può essere impostata insieme a {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) e {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Il valore predefinito è {@code false}. |
| [getInsertColor](#getInsertColor--) | Restituisce il colore utilizzato per evidenziare il contenuto inserito durante un confronto affiancato. Questa proprietà definisce la rappresentazione visiva dell'inserimento nel risultato del confronto. |
| [setAdditionalChangeMarks](#setAdditionalChangeMarks-boolean-) | Ottieni e imposta la proprietà che determina se i marcatori di modifica aggiuntivi sono visualizzati. Se impostata, visualizza i segni di modifica che non sono nella pagina corrente ma sono presenti in un'altra pagina. Se la modifica si colloca tra le parole, il segno potrebbe non essere posizionato esattamente rispetto al carattere di spazio. Il valore predefinito è {@code false}. |
| [setComparisonArea1](#setComparisonArea1-com.aspose.pdf.Rectangle-) | Ottieni e imposta l'area di confronto. Utilizzata per la prima pagina o documento nel metodo di confronto. Questa opzione non può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opzioni. |
| [setComparisonArea2](#setComparisonArea2-com.aspose.pdf.Rectangle-) | Ottieni e imposta l'area di confronto. Utilizzata per la seconda pagina o documento nel metodo di confronto. Questa opzione non può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opzioni. |
| [setComparisonMode](#setComparisonMode-int-) | Restituisce e imposta una modalità di confronto. Il valore predefinito è {@link ComparisonMode#IgnoreSpaces}. |
| [setDeleteColor](#setDeleteColor-com.aspose.pdf.Color-) | Imposta il colore utilizzato per evidenziare il contenuto eliminato durante un confronto affiancato. Questa proprietà definisce la rappresentazione visiva delle eliminazioni nel risultato del confronto. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Ottieni e imposta le aree da escludere. Utilizzate per la prima pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme all'opzione {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}). |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Ottieni e imposta le aree da escludere. Utilizzate per la seconda pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme all'opzione {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). |
| [setExcludeTables](#setExcludeTables-boolean-) | Ottieni e imposta l'opzione che determina se le tabelle sono escluse dal confronto. Questa opzione non può essere impostata insieme a {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) e {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Il valore predefinito è {@code false}. |
| [setInsertColor](#setInsertColor-com.aspose.pdf.Color-) | Imposta il colore utilizzato per evidenziare il contenuto inserito durante un confronto affiancato. Questa proprietà definisce la rappresentazione visiva dell'inserimento nel risultato del confronto. |
| [setVentureLicense](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |

### SideBySideComparisonOptions {#SideBySideComparisonOptions--}
```
public SideBySideComparisonOptions()
```

Crea un'istanza della classe {@link SideBySideComparisonOptions}.

### getAdditionalChangeMarks {#getAdditionalChangeMarks--}
```
public final boolean getAdditionalChangeMarks()
```

Ottieni e imposta la proprietà che determina se i marcatori di modifica aggiuntivi sono visualizzati. Se impostata, visualizza i segni di modifica che non sono nella pagina corrente ma sono presenti in un'altra pagina. Se la modifica si colloca tra le parole, il segno potrebbe non essere posizionato esattamente rispetto al carattere di spazio. Il valore predefinito è {@code false}.

**Returns:**
valore booleano

### getComparisonArea1 {#getComparisonArea1--}
```
public final Rectangle getComparisonArea1()
```

Ottieni e imposta l'area di confronto. Utilizzata per la prima pagina o documento nel metodo di confronto. Questa opzione non può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opzioni.

**Returns:**
Istanza Rectangle

### getComparisonArea2 {#getComparisonArea2--}
```
public final Rectangle getComparisonArea2()
```

Ottieni e imposta l'area di confronto. Utilizzata per la seconda pagina o documento nel metodo di confronto. Questa opzione non può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opzioni.

**Returns:**
Istanza Rectangle

### getComparisonMode {#getComparisonMode--}
```
public final int getComparisonMode()
```

Restituisce e imposta una modalità di confronto. Il valore predefinito è {@link ComparisonMode#IgnoreSpaces}.

**Returns:**
Elemento ComparisonMode

### getDeleteColor {#getDeleteColor--}
```
public final Color getDeleteColor()
```

Restituisce il colore utilizzato per evidenziare il contenuto eliminato durante un confronto affiancato. Questa proprietà definisce la rappresentazione visiva delle eliminazioni nel risultato del confronto.

**Returns:**
il colore utilizzato per evidenziare il contenuto eliminato durante un confronto affiancato.

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Ottieni e imposta le aree da escludere. Utilizzate per la prima pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme all'opzione {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}).

**Returns:**
array di istanze Rectangle

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Ottieni e imposta le aree da escludere. Utilizzate per la seconda pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme all'opzione {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}).

**Returns:**
array di istanze Rectangle

### getExcludeTables {#getExcludeTables--}
```
public final boolean getExcludeTables()
```

Ottieni e imposta l'opzione che determina se le tabelle sono escluse dal confronto. Questa opzione non può essere impostata insieme a {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) e {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Il valore predefinito è {@code false}.

**Returns:**
valore booleano

### getInsertColor {#getInsertColor--}
```
public final Color getInsertColor()
```

Restituisce il colore utilizzato per evidenziare il contenuto inserito durante un confronto affiancato. Questa proprietà definisce la rappresentazione visiva dell'inserimento nel risultato del confronto.

**Returns:**
il colore utilizzato per evidenziare il contenuto inserito durante un confronto affiancato.

### setAdditionalChangeMarks {#setAdditionalChangeMarks-boolean-}
```
public final void setAdditionalChangeMarks(boolean value)
```

Ottieni e imposta la proprietà che determina se i marcatori di modifica aggiuntivi sono visualizzati. Se impostata, visualizza i segni di modifica che non sono nella pagina corrente ma sono presenti in un'altra pagina. Se la modifica si colloca tra le parole, il segno potrebbe non essere posizionato esattamente rispetto al carattere di spazio. Il valore predefinito è {@code false}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setComparisonArea1 {#setComparisonArea1-com.aspose.pdf.Rectangle-}
Ottieni e imposta l'area di confronto. Utilizzata per la prima pagina o documento nel metodo di confronto. Questa opzione non può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opzioni.

### setComparisonArea2 {#setComparisonArea2-com.aspose.pdf.Rectangle-}
Ottieni e imposta l'area di confronto. Utilizzata per la seconda pagina o documento nel metodo di confronto. Questa opzione non può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) e {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) opzioni.

### setComparisonMode {#setComparisonMode-int-}
```
public final void setComparisonMode(int value)
```

Restituisce e imposta una modalità di confronto. Il valore predefinito è {@link ComparisonMode#IgnoreSpaces}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento ComparisonMode |

### setDeleteColor {#setDeleteColor-com.aspose.pdf.Color-}
Imposta il colore utilizzato per evidenziare il contenuto eliminato durante un confronto affiancato. Questa proprietà definisce la rappresentazione visiva delle eliminazioni nel risultato del confronto.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Ottieni e imposta le aree da escludere. Utilizzate per la prima pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme all'opzione {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}).

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Ottieni e imposta le aree da escludere. Utilizzate per la seconda pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Questa opzione non può essere impostata insieme all'opzione {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}).

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Ottieni e imposta l'opzione che determina se le tabelle sono escluse dal confronto. Questa opzione non può essere impostata insieme a {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) e {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Il valore predefinito è {@code false}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setInsertColor {#setInsertColor-com.aspose.pdf.Color-}
Imposta il colore utilizzato per evidenziare il contenuto inserito durante un confronto affiancato. Questa proprietà definisce la rappresentazione visiva dell'inserimento nel risultato del confronto.

### setVentureLicense {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
