---
title: "TextStamp"
linktitle: "TextStamp"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un timbro testuale."
type: docs
weight: 5320
url: /it/java/com.aspose.pdf/textstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp

```
public class TextStamp extends Stamp
```

Rappresenta un timbro testuale.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-) | Inizializza una nuova istanza della classe {@code TextStamp} con l'oggetto formattedText |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-) | Inizializza una nuova istanza della classe {@code TextStamp} con l'oggetto formattedText |
| [TextStamp](#TextStamp-java.lang.String-) | Inizializza una nuova istanza della classe {@code TextStamp}. |
| [TextStamp](#TextStamp-java.lang.String-com.aspose.pdf.TextState-) | Inizializza una nuova istanza della classe TextStamp. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAutoAdjustFontSizePrecision](#getAutoAdjustFontSizePrecision--) | Regola automaticamente la precisione della dimensione del carattere. Valore predefinito: 0.1; |
| [getAutoAdjustFontSizeToFitStampRectangle](#getAutoAdjustFontSizeToFitStampRectangle--) | Se abilitato, la dimensione del carattere verrà regolata automaticamente per adattarsi al rettangolo del timbro di dimensioni: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) e {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). La larghezza e l'altezza predefinite sono derivate dal rettangolo della pagina. |
| [getDefaultFont](#getDefaultFont--) | Restituisce il carattere predefinito |
| [getDefaultFontSize](#getDefaultFontSize--) | Dimensione predefinita del carattere |
| [getDraw](#getDraw--) | Questa proprietà determina come il timbro viene disegnato nella pagina. Se Draw = true il timbro è disegnato come operatori grafici e se draw = false il timbro è disegnato come testo. |
| [getFontSize](#getFontSize--) | Dimensione effettiva del carattere dopo che il timbro è stato posizionato. (Può differire dalla dimensione iniziale del carattere fornita tramite il costruttore se l'opzione 'AutoAdjustFontSizeToFitStampRectangle' è abilitata.) |
| [getHeight](#getHeight--) | Altezza desiderata del timbro nella pagina. |
| [getMaxRowWidth](#getMaxRowWidth--) | Altezza massima della riga per l'opzione WordWrap. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Ottiene o imposta la modalità che definisce il comportamento nel caso in cui i font non contengano i caratteri richiesti. |
| [getReplacementFont](#getReplacementFont--) | Ottiene o imposta il font utilizzato per la sostituzione se il font dell'utente non contiene il carattere richiesto. |
| [getTextAlignment](#getTextAlignment--) | Allineamento del testo all'interno del timbro. |
| [getTextState](#getTextState--) | Ottiene le proprietà del testo del timbro. Vedi {@code TextState} per i dettagli. |
| [getTreatYIndentAsBaseLine](#getTreatYIndentAsBaseLine--) | Definisce l'origine delle coordinate per il posizionamento del testo. Se TreatYIndentAsBaseLine = true (predefinito quando Draw = true) il valore YIndent sarà trattato come linea di base del testo. Se TreatYIndentAsBaseLine = false (predefinito quando Draw = false) il valore YIndent sarà trattato come fondo (linea di discesa) del testo. |
| [getValue](#getValue--) | Ottiene il valore stringa utilizzato come timbro nella pagina. |
| [getWidth](#getWidth--) | Larghezza desiderata del timbro nella pagina. |
| [getWordWrapMode](#getWordWrapMode--) | Ottiene o imposta la modalità di word wrap per il rendering del testo. |
| [isJustify](#isJustify--) | Definisce la giustificazione del testo. Se questa proprietà è impostata su true, entrambi i bordi sinistro e destro del testo sono allineati. Valore predefinito: false. |
| [isScale](#isScale--) | Definisce la scalatura del testo. Se questa proprietà è impostata su true e viene specificato un valore Width, il testo verrà scalato per adattarsi alla larghezza specificata. |
| [isWordWrap](#isWordWrap--) | Definisce il word wrap. Se questa proprietà è impostata su true e viene specificato un valore Width, il testo verrà suddiviso in più righe per adattarsi alla larghezza specificata. Valore predefinito: false. |
| [put](#put-com.aspose.pdf.Page-) | Aggiunge un timbro testuale nella pagina. |
| [setAutoAdjustFontSizePrecision](#setAutoAdjustFontSizePrecision-float-) | Regola automaticamente la precisione della dimensione del carattere. Valore predefinito: 0.1; |
| [setAutoAdjustFontSizeToFitStampRectangle](#setAutoAdjustFontSizeToFitStampRectangle-boolean-) | Se abilitato, la dimensione del carattere verrà regolata automaticamente per adattarsi al rettangolo del timbro di dimensioni: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) e {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). La larghezza e l'altezza predefinite sono derivate dal rettangolo della pagina. |
| [setDraw](#setDraw-boolean-) | Questa proprietà determina come il timbro viene disegnato nella pagina. Se Draw = true il timbro è disegnato come operatori grafici e se draw = false il timbro è disegnato come testo. |
| [setHeight](#setHeight-double-) | Altezza desiderata del timbro nella pagina. |
| [setJustify](#setJustify-boolean-) | Definisce la giustificazione del testo. Se questa proprietà è impostata su true, entrambi i bordi sinistro e destro del testo sono allineati. Valore predefinito: false. |
| [setMaxRowWidth](#setMaxRowWidth-double-) | Altezza massima della riga per l'opzione WordWrap. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-int-) | Ottiene o imposta la modalità che definisce il comportamento nel caso in cui i font non contengano i caratteri richiesti. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Ottiene o imposta il font utilizzato per la sostituzione se il font dell'utente non contiene il carattere richiesto. |
| [setScale](#setScale-boolean-) | Definisce la scalatura del testo. Se questa proprietà è impostata su true e viene specificato un valore Width, il testo verrà scalato per adattarsi alla larghezza specificata. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Allineamento del testo all'interno del timbro. |
| [setTreatYIndentAsBaseLine](#setTreatYIndentAsBaseLine-boolean-) | Definisce l'origine delle coordinate per il posizionamento del testo. Se TreatYIndentAsBaseLine = true (predefinito quando Draw = true) il valore YIndent sarà trattato come linea di base del testo. Se TreatYIndentAsBaseLine = false (predefinito quando Draw = false) il valore YIndent sarà trattato come fondo (linea di discesa) del testo. |
| [setValue](#setValue-java.lang.String-) | Imposta il valore stringa utilizzato come timbro nella pagina. |
| [setWidth](#setWidth-double-) | Larghezza desiderata del timbro nella pagina. |
| [setWordWrap](#setWordWrap-boolean-) | Definisce il word wrap. Se questa proprietà è impostata su true e viene specificato un valore Width, il testo verrà suddiviso in più righe per adattarsi alla larghezza specificata. Valore predefinito: false. |
| [setWordWrapMode](#setWordWrapMode-int-) | Ottiene o imposta la modalità di word wrap per il rendering del testo. |

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-}
Inizializza una nuova istanza della classe {@code TextStamp} con l'oggetto formattedText

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-}
Inizializza una nuova istanza della classe {@code TextStamp} con l'oggetto formattedText

### TextStamp {#TextStamp-java.lang.String-}
Inizializza una nuova istanza della classe {@code TextStamp}.

### TextStamp {#TextStamp-java.lang.String-com.aspose.pdf.TextState-}
Inizializza una nuova istanza della classe TextStamp.

### getAutoAdjustFontSizePrecision {#getAutoAdjustFontSizePrecision--}
```
public final float getAutoAdjustFontSizePrecision()
```

Regola automaticamente la precisione della dimensione del carattere. Valore predefinito: 0.1;

**Returns:**
valore float

### getAutoAdjustFontSizeToFitStampRectangle {#getAutoAdjustFontSizeToFitStampRectangle--}
```
public final boolean getAutoAdjustFontSizeToFitStampRectangle()
```

Se abilitato, la dimensione del carattere verrà regolata automaticamente per adattarsi al rettangolo del timbro di dimensioni: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) e {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). La larghezza e l'altezza predefinite sono derivate dal rettangolo della pagina.

**Returns:**
valore booleano

### getDefaultFont {#getDefaultFont--}
```
public static Font getDefaultFont()
```

Restituisce il carattere predefinito

**Returns:**
oggetto com.aspose.pdf.Font

### getDefaultFontSize {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```

Dimensione predefinita del carattere

**Returns:**
valore float

### getDraw {#getDraw--}
```
public boolean getDraw()
```

Questa proprietà determina come il timbro viene disegnato nella pagina. Se Draw = true il timbro è disegnato come operatori grafici e se draw = false il timbro è disegnato come testo.

**Returns:**
valore booleano

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Dimensione effettiva del carattere dopo che il timbro è stato posizionato. (Può differire dalla dimensione iniziale del carattere fornita tramite il costruttore se l'opzione 'AutoAdjustFontSizeToFitStampRectangle' è abilitata.)

**Returns:**
valore float

### getHeight {#getHeight--}
```
public double getHeight()
```

Altezza desiderata del timbro nella pagina.

**Returns:**
valore double

### getMaxRowWidth {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```

Altezza massima della riga per l'opzione WordWrap.

**Returns:**
valore double

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public final int getNoCharacterBehavior()
```

Ottiene o imposta la modalità che definisce il comportamento nel caso in cui i font non contengano i caratteri richiesti.

**Returns:**
Elemento NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Ottiene o imposta il font utilizzato per la sostituzione se il font dell'utente non contiene il carattere richiesto.

**Returns:**
Font istanza

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Allineamento del testo all'interno del timbro.

**Returns:**
Valore HorizontalAlignment @see HorizontalAlignment

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Ottiene le proprietà del testo del timbro. Vedi {@code TextState} per i dettagli.

**Returns:**
Elemento TextState

### getTreatYIndentAsBaseLine {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```

Definisce l'origine delle coordinate per il posizionamento del testo. Se TreatYIndentAsBaseLine = true (predefinito quando Draw = true) il valore YIndent sarà trattato come linea di base del testo. Se TreatYIndentAsBaseLine = false (predefinito quando Draw = false) il valore YIndent sarà trattato come fondo (linea di discesa) del testo.

**Returns:**
valore booleano

### getValue {#getValue--}
```
public String getValue()
```

Ottiene il valore stringa utilizzato come timbro nella pagina.

**Returns:**
valore String

### getWidth {#getWidth--}
```
public double getWidth()
```

Larghezza desiderata del timbro nella pagina.

**Returns:**
valore double

### getWordWrapMode {#getWordWrapMode--}
```
public final int getWordWrapMode()
```

Ottiene o imposta la modalità di word wrap per il rendering del testo.

**Returns:**
Elemento WordWrapMode

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Definisce la giustificazione del testo. Se questa proprietà è impostata su true, entrambi i bordi sinistro e destro del testo sono allineati. Valore predefinito: false.

**Returns:**
valore booleano

### isScale {#isScale--}
```
public boolean isScale()
```

Definisce la scalatura del testo. Se questa proprietà è impostata su true e viene specificato un valore Width, il testo verrà scalato per adattarsi alla larghezza specificata.

**Returns:**
valore booleano

### isWordWrap {#isWordWrap--}
```
@Deprecated public boolean isWordWrap()
```

Definisce il word wrap. Se questa proprietà è impostata su true e viene specificato un valore Width, il testo verrà suddiviso in più righe per adattarsi alla larghezza specificata. Valore predefinito: false.

**Returns:**
valore booleano @deprecated "Usa WordWrapMode invece."

### put {#put-com.aspose.pdf.Page-}
Aggiunge un timbro testuale nella pagina.

### setAutoAdjustFontSizePrecision {#setAutoAdjustFontSizePrecision-float-}
```
public final void setAutoAdjustFontSizePrecision(float value)
```

Regola automaticamente la precisione della dimensione del carattere. Valore predefinito: 0.1;

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setAutoAdjustFontSizeToFitStampRectangle {#setAutoAdjustFontSizeToFitStampRectangle-boolean-}
```
public final void setAutoAdjustFontSizeToFitStampRectangle(boolean value)
```

Se abilitato, la dimensione del carattere verrà regolata automaticamente per adattarsi al rettangolo del timbro di dimensioni: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) e {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). La larghezza e l'altezza predefinite sono derivate dal rettangolo della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setDraw {#setDraw-boolean-}
```
public void setDraw(boolean value)
```

Questa proprietà determina come il timbro viene disegnato nella pagina. Se Draw = true il timbro è disegnato come operatori grafici e se draw = false il timbro è disegnato come testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Altezza desiderata del timbro nella pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Definisce la giustificazione del testo. Se questa proprietà è impostata su true, entrambi i bordi sinistro e destro del testo sono allineati. Valore predefinito: false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMaxRowWidth {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```

Altezza massima della riga per l'opzione WordWrap.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setNoCharacterBehavior {#setNoCharacterBehavior-int-}
```
public final void setNoCharacterBehavior(int value)
```

Ottiene o imposta la modalità che definisce il comportamento nel caso in cui i font non contengano i caratteri richiesti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento NoCharacterAction |

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Ottiene o imposta il font utilizzato per la sostituzione se il font dell'utente non contiene il carattere richiesto.

### setScale {#setScale-boolean-}
```
public void setScale(boolean value)
```

Definisce la scalatura del testo. Se questa proprietà è impostata su true e viene specificato un valore Width, il testo verrà scalato per adattarsi alla larghezza specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Allineamento del testo all'interno del timbro.

### setTreatYIndentAsBaseLine {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```

Definisce l'origine delle coordinate per il posizionamento del testo. Se TreatYIndentAsBaseLine = true (predefinito quando Draw = true) il valore YIndent sarà trattato come linea di base del testo. Se TreatYIndentAsBaseLine = false (predefinito quando Draw = false) il valore YIndent sarà trattato come fondo (linea di discesa) del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setValue {#setValue-java.lang.String-}
Imposta il valore stringa utilizzato come timbro nella pagina.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Larghezza desiderata del timbro nella pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setWordWrap {#setWordWrap-boolean-}
```
@Deprecated public void setWordWrap(boolean value)
```

Definisce il word wrap. Se questa proprietà è impostata su true e viene specificato un valore Width, il testo verrà suddiviso in più righe per adattarsi alla larghezza specificata. Valore predefinito: false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano @deprecated "Usa WordWrapMode invece." |

### setWordWrapMode {#setWordWrapMode-int-}
```
public final void setWordWrapMode(int value)
```

Ottiene o imposta la modalità di word wrap per il rendering del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento WordWrapMode @see WordWrapMode |
