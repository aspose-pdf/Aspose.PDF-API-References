---
title: "SvgExtractionOptions"
linktitle: "SvgExtractionOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe di opzioni per l'estrazione di grafica vettoriale dalla pagina del documento pdf."
type: docs
weight: 30
url: /it/java/com.aspose.pdf.vector.extraction/svgextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SvgExtractionOptions

```
public class SvgExtractionOptions extends Object
```

Rappresenta una classe di opzioni per l'estrazione di grafica vettoriale dalla pagina del documento pdf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SvgExtractionOptions](#SvgExtractionOptions--) | Crea un'istanza della classe SvgExtractionOptions. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAutoGrouping](#getAutoGrouping--) | Ottiene e imposta l'opzione per raggruppare automaticamente i sottopercorsi in immagini. Questa opzione esclude l'opzione {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}). |
| [getExtractEverySubPathToSvg](#getExtractEverySubPathToSvg--) | Ottiene e imposta l'opzione per estrarre ogni sottopercorso da un documento PDF in immagini SVG separate. |
| [getExtractionAreaBound](#getExtractionAreaBound--) | Ottiene e imposta il rettangolo di delimitazione che definisce l'area di estrazione per l'estrazione SVG. |
| [getGroupStrength](#getGroupStrength--) | Ottiene e imposta un'opzione per la forza del raggruppamento dei sottopercorsi in immagini. Consente di configurare il grado di raggruppamento dei sottopercorsi. Il valore varia da 0 a 1. Un valore 0 corrisponde all'opzione {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) abilitata. Un valore 1 creerà un'unica immagine per tutti i percorsi vettoriali nella pagina. L'opzione ha effetto quando {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) è false. Il valore predefinito è {@code 0.8}. |
| [getMinStrokeWidth](#getMinStrokeWidth--) | Ottiene o imposta la larghezza minima del tratto che verrà utilizzata nello SVG risultante. Se il PDF utilizza una larghezza del tratto più sottile, verrà sostituita con questa larghezza. Il valore predefinito è 0,5. Il valore è espresso in unità di spazio utente trasformate della pagina PDF convertita. Per impostazione predefinita 1 unità di spazio utente corrisponde a 1/72 di pollice (0,35 mm), ma può essere sovrascritta dal documento PDF. Le trasformazioni possono influire sulla larghezza minima effettiva nello SVG generato. |
| [getStrictExtractionAreaBoundCheck](#getStrictExtractionAreaBoundCheck--) | Ottiene e imposta un'opzione per definire se controllare rigorosamente se i sottopercorsi sono all'interno del rettangolo specificato in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Se impostata su false, i sottopercorsi che non sono completamente inclusi in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) verranno estratti. Il valore predefinito è {@code True}. |
| [getUnpackPageContentXForm](#getUnpackPageContentXForm--) | Ottiene e imposta un flag che determina se gli XFrom trovati nelle pagine devono essere decompattati o meno. Gli elementi XFrom possono finire in file SVG diversi. Solo gli XForm renderizzati dalle istruzioni Do del contenuto della pagina vengono decompattati. Gli XForm nidificati non vengono decompattati. |
| [getUnpackXFormPredicate](#getUnpackXFormPredicate--) | Ottiene e imposta l'opzione per decompattare solo l'XForm corrispondente al predicato specificato. |
| [setAutoGrouping](#setAutoGrouping-boolean-) | Ottiene e imposta l'opzione per raggruppare automaticamente i sottopercorsi in immagini. Questa opzione esclude l'opzione {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}). |
| [setExtractEverySubPathToSvg](#setExtractEverySubPathToSvg-boolean-) | Ottiene e imposta l'opzione per estrarre ogni sottopercorso da un documento PDF in immagini SVG separate. |
| [setExtractionAreaBound](#setExtractionAreaBound-com.aspose.pdf.Rectangle-) | Ottiene e imposta il rettangolo di delimitazione che definisce l'area di estrazione per l'estrazione SVG. |
| [setGroupStrength](#setGroupStrength-double-) | Ottiene e imposta un'opzione per la forza del raggruppamento dei sottopercorsi in immagini. Consente di configurare il grado di raggruppamento dei sottopercorsi. Il valore varia da 0 a 1. Un valore 0 corrisponde all'opzione {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) abilitata. Un valore 1 creerà un'unica immagine per tutti i percorsi vettoriali nella pagina. L'opzione ha effetto quando {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) è false. Il valore predefinito è {@code 0.8}. |
| [setMinStrokeWidth](#setMinStrokeWidth-double-) | Ottiene o imposta la larghezza minima del tratto che verrà utilizzata nello SVG risultante. Se il PDF utilizza una larghezza del tratto più sottile, verrà sostituita con questa larghezza. Il valore predefinito è 0,5. Il valore è espresso in unità di spazio utente trasformate della pagina PDF convertita. Per impostazione predefinita 1 unità di spazio utente corrisponde a 1/72 di pollice (0,35 mm), ma può essere sovrascritta dal documento PDF. Le trasformazioni possono influire sulla larghezza minima effettiva nello SVG generato. |
| [setStrictExtractionAreaBoundCheck](#setStrictExtractionAreaBoundCheck-boolean-) | Ottiene e imposta un'opzione per definire se controllare rigorosamente se i sottopercorsi sono all'interno del rettangolo specificato in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Se impostata su false, i sottopercorsi che non sono completamente inclusi in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) verranno estratti. Il valore predefinito è {@code True}. |
| [setUnpackPageContentXForm](#setUnpackPageContentXForm-boolean-) | Ottiene e imposta un flag che determina se gli XFrom trovati nelle pagine devono essere decompattati o meno. Gli elementi XFrom possono finire in file SVG diversi. Solo gli XForm renderizzati dalle istruzioni Do del contenuto della pagina vengono decompattati. Gli XForm nidificati non vengono decompattati. |
| [setUnpackXFormPredicate](#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-) | Ottiene e imposta l'opzione per decompattare solo l'XForm corrispondente al predicato specificato. |

### SvgExtractionOptions {#SvgExtractionOptions--}
```
public SvgExtractionOptions()
```

Crea un'istanza della classe SvgExtractionOptions.

### getAutoGrouping {#getAutoGrouping--}
```
public final boolean getAutoGrouping()
```

Ottiene e imposta l'opzione per raggruppare automaticamente i sottopercorsi in immagini. Questa opzione esclude l'opzione {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}).

**Returns:**
valore booleano

### getExtractEverySubPathToSvg {#getExtractEverySubPathToSvg--}
```
public final boolean getExtractEverySubPathToSvg()
```

Ottiene e imposta l'opzione per estrarre ogni sottopercorso da un documento PDF in immagini SVG separate.

**Returns:**
valore booleano

### getExtractionAreaBound {#getExtractionAreaBound--}
```
public final Rectangle getExtractionAreaBound()
```

Ottiene e imposta il rettangolo di delimitazione che definisce l'area di estrazione per l'estrazione SVG.

**Returns:**
Istanza Rectangle

### getGroupStrength {#getGroupStrength--}
```
public final double getGroupStrength()
```

Ottiene e imposta un'opzione per la forza del raggruppamento dei sottopercorsi in immagini. Consente di configurare il grado di raggruppamento dei sottopercorsi. Il valore varia da 0 a 1. Un valore 0 corrisponde all'opzione {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) abilitata. Un valore 1 creerà un'unica immagine per tutti i percorsi vettoriali nella pagina. L'opzione ha effetto quando {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) è false. Il valore predefinito è {@code 0.8}.

**Returns:**
valore double

### getMinStrokeWidth {#getMinStrokeWidth--}
```
public final double getMinStrokeWidth()
```

Ottiene o imposta la larghezza minima del tratto che verrà utilizzata nello SVG risultante. Se il PDF utilizza una larghezza del tratto più sottile, verrà sostituita con questa larghezza. Il valore predefinito è 0,5. Il valore è espresso in unità di spazio utente trasformate della pagina PDF convertita. Per impostazione predefinita 1 unità di spazio utente corrisponde a 1/72 di pollice (0,35 mm), ma può essere sovrascritta dal documento PDF. Le trasformazioni possono influire sulla larghezza minima effettiva nello SVG generato.

**Returns:**
valore double

### getStrictExtractionAreaBoundCheck {#getStrictExtractionAreaBoundCheck--}
```
public final boolean getStrictExtractionAreaBoundCheck()
```

Ottiene e imposta un'opzione per definire se controllare rigorosamente se i sottopercorsi sono all'interno del rettangolo specificato in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Se impostata su false, i sottopercorsi che non sono completamente inclusi in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) verranno estratti. Il valore predefinito è {@code True}.

**Returns:**
valore booleano

### getUnpackPageContentXForm {#getUnpackPageContentXForm--}
```
public final boolean getUnpackPageContentXForm()
```

Ottiene e imposta un flag che determina se gli XFrom trovati nelle pagine devono essere decompattati o meno. Gli elementi XFrom possono finire in file SVG diversi. Solo gli XForm renderizzati dalle istruzioni Do del contenuto della pagina vengono decompattati. Gli XForm nidificati non vengono decompattati.

**Returns:**
valore booleano

### getUnpackXFormPredicate {#getUnpackXFormPredicate--}
```
public final com.aspose.ms.System.Predicate< XFormPlacement > getUnpackXFormPredicate()
```

Ottiene e imposta l'opzione per decompattare solo l'XForm corrispondente al predicato specificato.

**Returns:**
istanza interna di Predicate dell'istanza XFormPlacement

### setAutoGrouping {#setAutoGrouping-boolean-}
```
public final void setAutoGrouping(boolean value)
```

Ottiene e imposta l'opzione per raggruppare automaticamente i sottopercorsi in immagini. Questa opzione esclude l'opzione {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setExtractEverySubPathToSvg {#setExtractEverySubPathToSvg-boolean-}
```
public final void setExtractEverySubPathToSvg(boolean value)
```

Ottiene e imposta l'opzione per estrarre ogni sottopercorso da un documento PDF in immagini SVG separate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setExtractionAreaBound {#setExtractionAreaBound-com.aspose.pdf.Rectangle-}
Ottiene e imposta il rettangolo di delimitazione che definisce l'area di estrazione per l'estrazione SVG.

### setGroupStrength {#setGroupStrength-double-}
```
public final void setGroupStrength(double value)
```

Ottiene e imposta un'opzione per la forza del raggruppamento dei sottopercorsi in immagini. Consente di configurare il grado di raggruppamento dei sottopercorsi. Il valore varia da 0 a 1. Un valore 0 corrisponde all'opzione {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) abilitata. Un valore 1 creerà un'unica immagine per tutti i percorsi vettoriali nella pagina. L'opzione ha effetto quando {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) è false. Il valore predefinito è {@code 0.8}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setMinStrokeWidth {#setMinStrokeWidth-double-}
```
public final void setMinStrokeWidth(double value)
```

Ottiene o imposta la larghezza minima del tratto che verrà utilizzata nello SVG risultante. Se il PDF utilizza una larghezza del tratto più sottile, verrà sostituita con questa larghezza. Il valore predefinito è 0,5. Il valore è espresso in unità di spazio utente trasformate della pagina PDF convertita. Per impostazione predefinita 1 unità di spazio utente corrisponde a 1/72 di pollice (0,35 mm), ma può essere sovrascritta dal documento PDF. Le trasformazioni possono influire sulla larghezza minima effettiva nello SVG generato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setStrictExtractionAreaBoundCheck {#setStrictExtractionAreaBoundCheck-boolean-}
```
public final void setStrictExtractionAreaBoundCheck(boolean value)
```

Ottiene e imposta un'opzione per definire se controllare rigorosamente se i sottopercorsi sono all'interno del rettangolo specificato in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Se impostata su false, i sottopercorsi che non sono completamente inclusi in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) verranno estratti. Il valore predefinito è {@code True}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUnpackPageContentXForm {#setUnpackPageContentXForm-boolean-}
```
public final void setUnpackPageContentXForm(boolean value)
```

Ottiene e imposta un flag che determina se gli XFrom trovati nelle pagine devono essere decompattati o meno. Gli elementi XFrom possono finire in file SVG diversi. Solo gli XForm renderizzati dalle istruzioni Do del contenuto della pagina vengono decompattati. Gli XForm nidificati non vengono decompattati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUnpackXFormPredicate {#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-}
Ottiene e imposta l'opzione per decompattare solo l'XForm corrispondente al predicato specificato.
