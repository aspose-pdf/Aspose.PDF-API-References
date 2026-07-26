---
title: "TextSearchOptions"
linktitle: "TextSearchOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le opzioni di ricerca del testo"
type: docs
weight: 5290
url: /it/java/com.aspose.pdf/textsearchoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextSearchOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextSearchOptions

```
public final class TextSearchOptions extends TextOptions
```

Rappresenta le opzioni di ricerca del testo

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextSearchOptions](#TextSearchOptions-boolean-) | Inizializza una nuova istanza dell'oggetto {@code TextSearchOptions}. Specifica la modalità di utilizzo delle espressioni regolari. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-) | Inizializza una nuova istanza dell'oggetto TextSearchOptions. Specifica il rettangolo che delimita il testo ricercato. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | Inizializza una nuova istanza dell'oggetto TextSearchOptions. Specifica il rettangolo che delimita il testo ricercato e la modalità di utilizzo delle espressioni regolari. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getExcludeRectangles](#getExcludeRectangles--) | Ottiene o imposta i rettangoli i cui bordi escludono il testo dalla ricerca. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Ottiene o imposta l'indicazione che gli errori relativi all'assenza del font saranno ignorati dall'assorbitore di testo (frammento). true - indica che gli errori di assenza del font saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione. false (predefinito) - l'errore di assenza del font terminerà l'elaborazione lanciando un'eccezione. |
| [getLimitToPageBounds](#getLimitToPageBounds--) | Ottiene l'indicazione che il testo è ricercato entro i limiti della pagina. |
| [getLogTextExtractionErrors](#getLogTextExtractionErrors--) | Ottiene o imposta l'indicazione che gli errori di estrazione del testo (decodifica) saranno registrati nell'assorbitore di testo (frammento). true - indica che gli errori di estrazione del testo (decodifica) saranno registrati. Potrebbe ridurre le prestazioni. false (predefinito) - nessuna registrazione degli errori. |
| [getRectangle](#getRectangle--) | Ottiene il rettangolo che delimita il testo ricercato. La proprietà può essere usata nel caso sia necessario delimitare l'estrazione del testo o l'area di sostituzione del testo. |
| [getSearchForTextRelatedGraphics](#getSearchForTextRelatedGraphics--) | Ottiene o imposta il valore che consente la ricerca di grafica correlata al testo (sottolineatura, sfondo ecc.) durante la ricerca del testo. true - la ricerca di grafica correlata al testo verrà eseguita (valore predefinito). false - gli elementi grafici presenti nel documento sorgente saranno ignorati. Impostare questo in caso di problemi di prestazioni o se non è necessario gestire sottolineature, sfondi o ritagli. |
| [getStoredGraphicElementsMaxCount](#getStoredGraphicElementsMaxCount--) | Ottiene il valore che limita la ricerca di grafica correlata al testo (sottolineatura, sfondo ecc.) su una pagina per il numero specificato di elementi. Il valore predefinito è 250. Impostare un valore inferiore in caso di problemi di prestazioni, provare un valore maggiore se alcuni elementi grafici non sono stati trovati. |
| [getUseFontEngineEncoding](#getUseFontEngineEncoding--) | Ottiene l'indicazione che il testo sarà ricercato usando la codifica del motore dei font. true - indica che verrà usata la codifica del motore dei font (prova questo se la ricerca del testo fallisce a causa di una codifica imperfetta nel documento). false - indica che verrà usata la codifica dei font del documento (valore predefinito). |
| [isDotallMode](#isDotallMode--) | <p> In modalità dotall, l'espressione <tt>.</tt> corrisponde a qualsiasi carattere, inclusi i terminatori di riga. Per impostazione predefinita questa espressione non corrisponde ai terminatori di riga. |
| [isIgnoreShadowText](#isIgnoreShadowText--) | Ottiene o imposta l'indicazione che i frammenti di testo che rappresentano l'ombra del testo normale saranno ignorati durante la ricerca. true - indica che il testo in ombra non sarà trovato (prova questo se la ricerca del testo restituisce frammenti duplicati in posizioni vicine). false - indica che il testo in ombra sarà trovato insieme al testo normale (valore predefinito). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Indica se l'espressione regolare è utilizzata o meno. |
| [isSearchInAnnotations](#isSearchInAnnotations--) | Ottiene o imposta il valore che consente la ricerca di testo nelle Annotazioni. true - il testo sarà ricercato nelle Annotazioni. false - il testo nelle Annotazioni non sarà analizzato da TextFragmentAbsorber. |
| [setDotallMode](#setDotallMode-boolean-) | Abilita la modalità dotall. <p> In modalità dotall, l'espressione <tt>.</tt> corrisponde a qualsiasi carattere, inclusi i terminatori di riga. Per impostazione predefinita questa espressione non corrisponde ai terminatori di riga. |
| [setExcludeRectangles](#setExcludeRectangles-com.aspose.pdf.Rectangle:A-) | Ottiene o imposta i rettangoli i cui bordi escludono il testo dalla ricerca. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Ottiene o imposta l'indicazione che gli errori relativi all'assenza del font saranno ignorati dall'assorbitore di testo (frammento). true - indica che gli errori di assenza del font saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione. false (predefinito) - l'errore di assenza del font terminerà l'elaborazione lanciando un'eccezione. |
| [setIgnoreShadowText](#setIgnoreShadowText-boolean-) | Ottiene o imposta l'indicazione che i frammenti di testo che rappresentano l'ombra del testo normale saranno ignorati durante la ricerca. true - indica che il testo in ombra non sarà trovato (prova questo se la ricerca del testo restituisce frammenti duplicati in posizioni vicine). false - indica che il testo in ombra sarà trovato insieme al testo normale (valore predefinito). |
| [setLimitToPageBounds](#setLimitToPageBounds-boolean-) | Imposta l'indicazione che il testo è ricercato entro i limiti della pagina. |
| [setLogTextExtractionErrors](#setLogTextExtractionErrors-boolean-) | Ottiene o imposta l'indicazione che gli errori di estrazione del testo (decodifica) saranno registrati nell'assorbitore di testo (frammento). true - indica che gli errori di estrazione del testo (decodifica) saranno registrati. Potrebbe ridurre le prestazioni. false (predefinito) - nessuna registrazione degli errori. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Imposta il rettangolo che delimita il testo ricercato. La proprietà può essere usata nel caso sia necessario delimitare l'estrazione del testo o l'area di sostituzione del testo. |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Indica se l'espressione regolare è utilizzata o meno. |
| [setSearchForTextRelatedGraphics](#setSearchForTextRelatedGraphics-boolean-) | Ottiene o imposta il valore che consente la ricerca di grafica correlata al testo (sottolineatura, sfondo ecc.) durante la ricerca del testo. true - la ricerca di grafica correlata al testo verrà eseguita (valore predefinito). false - gli elementi grafici presenti nel documento sorgente saranno ignorati. Impostare questo in caso di problemi di prestazioni o se non è necessario gestire sottolineature, sfondi o ritagli. |
| [setSearchInAnnotations](#setSearchInAnnotations-boolean-) | Ottiene o imposta il valore che consente la ricerca di testo nelle Annotazioni. true - il testo sarà ricercato nelle Annotazioni. false - il testo nelle Annotazioni non sarà analizzato da TextFragmentAbsorber. |
| [setStoredGraphicElementsMaxCount](#setStoredGraphicElementsMaxCount-int-) | Imposta il valore che limita la ricerca di grafica correlata al testo (sottolineatura, sfondo ecc.) su una pagina per il numero specificato di elementi. Il valore predefinito è 250. Impostare un valore inferiore in caso di problemi di prestazioni, provare un valore maggiore se alcuni elementi grafici non sono stati trovati. |
| [setUseFontEngineEncoding](#setUseFontEngineEncoding-boolean-) | Imposta l'indicazione che il testo sarà ricercato usando la codifica del motore dei font. true - indica che verrà usata la codifica del motore dei font (prova questo se la ricerca del testo fallisce a causa di una codifica imperfetta nel documento). false - indica che verrà usata la codifica dei font del documento (valore predefinito). |

### TextSearchOptions {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```

Inizializza una nuova istanza dell'oggetto {@code TextSearchOptions}. Specifica la modalità di utilizzo delle espressioni regolari.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isRegularExpressionUsed |  | Valore che indica che l'espressione regolare è utilizzata. |

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-}
Inizializza una nuova istanza dell'oggetto TextSearchOptions. Specifica il rettangolo che delimita il testo ricercato.

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
Inizializza una nuova istanza dell'oggetto TextSearchOptions. Specifica il rettangolo che delimita il testo ricercato e la modalità di utilizzo delle espressioni regolari.

### getExcludeRectangles {#getExcludeRectangles--}
```
public final Rectangle [] getExcludeRectangles()
```

Ottiene o imposta i rettangoli i cui bordi escludono il testo dalla ricerca.

**Returns:**
array di istanze Rectangle

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Ottiene o imposta l'indicazione che gli errori relativi all'assenza del font saranno ignorati dall'assorbitore di testo (frammento). true - indica che gli errori di assenza del font saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione. false (predefinito) - l'errore di assenza del font terminerà l'elaborazione lanciando un'eccezione.

**Returns:**
valore booleano

### getLimitToPageBounds {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```

Ottiene l'indicazione che il testo è ricercato entro i limiti della pagina.

**Returns:**
valore booleano

### getLogTextExtractionErrors {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```

Ottiene o imposta l'indicazione che gli errori di estrazione del testo (decodifica) saranno registrati nell'assorbitore di testo (frammento). true - indica che gli errori di estrazione del testo (decodifica) saranno registrati. Potrebbe ridurre le prestazioni. false (predefinito) - nessuna registrazione degli errori.

**Returns:**
valore booleano

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Ottiene il rettangolo che delimita il testo ricercato. La proprietà può essere usata nel caso sia necessario delimitare l'estrazione del testo o l'area di sostituzione del testo.

**Returns:**
Valore del rettangolo

### getSearchForTextRelatedGraphics {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```

Ottiene o imposta il valore che consente la ricerca di grafica correlata al testo (sottolineatura, sfondo ecc.) durante la ricerca del testo. true - la ricerca di grafica correlata al testo verrà eseguita (valore predefinito). false - gli elementi grafici presenti nel documento sorgente saranno ignorati. Impostare questo in caso di problemi di prestazioni o se non è necessario gestire sottolineature, sfondi o ritagli.

**Returns:**
valore booleano

### getStoredGraphicElementsMaxCount {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```

Ottiene il valore che limita la ricerca di grafica correlata al testo (sottolineatura, sfondo ecc.) su una pagina per il numero specificato di elementi. Il valore predefinito è 250. Impostare un valore inferiore in caso di problemi di prestazioni, provare un valore maggiore se alcuni elementi grafici non sono stati trovati.

**Returns:**
valore int

### getUseFontEngineEncoding {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```

Ottiene l'indicazione che il testo sarà ricercato usando la codifica del motore dei font. true - indica che verrà usata la codifica del motore dei font (prova questo se la ricerca del testo fallisce a causa di una codifica imperfetta nel documento). false - indica che verrà usata la codifica dei font del documento (valore predefinito).

**Returns:**
valore booleano

### isDotallMode {#isDotallMode--}
```
public static boolean isDotallMode()
```

<p> In modalità dotall, l'espressione <tt>.</tt> corrisponde a qualsiasi carattere, inclusi i terminatori di riga. Per impostazione predefinita questa espressione non corrisponde ai terminatori di riga.

**Returns:**
valore booleano

### isIgnoreShadowText {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```

Ottiene o imposta l'indicazione che i frammenti di testo che rappresentano l'ombra del testo normale saranno ignorati durante la ricerca. true - indica che il testo in ombra non sarà trovato (prova questo se la ricerca del testo restituisce frammenti duplicati in posizioni vicine). false - indica che il testo in ombra sarà trovato insieme al testo normale (valore predefinito).

**Returns:**
valore booleano

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Indica se l'espressione regolare è utilizzata o meno.

**Returns:**
valore booleano

### isSearchInAnnotations {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```

Ottiene o imposta il valore che consente la ricerca di testo nelle Annotazioni. true - il testo sarà ricercato nelle Annotazioni. false - il testo nelle Annotazioni non sarà analizzato da TextFragmentAbsorber.

**Returns:**
valore booleano

### setDotallMode {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```

Abilita la modalità dotall. <p> In modalità dotall, l'espressione <tt>.</tt> corrisponde a qualsiasi carattere, inclusi i terminatori di riga. Per impostazione predefinita questa espressione non corrisponde ai terminatori di riga.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dotallMode |  | valore booleano |

### setExcludeRectangles {#setExcludeRectangles-com.aspose.pdf.Rectangle:A-}
Ottiene o imposta i rettangoli i cui bordi escludono il testo dalla ricerca.

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Ottiene o imposta l'indicazione che gli errori relativi all'assenza del font saranno ignorati dall'assorbitore di testo (frammento). true - indica che gli errori di assenza del font saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione. false (predefinito) - l'errore di assenza del font terminerà l'elaborazione lanciando un'eccezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setIgnoreShadowText {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```

Ottiene o imposta l'indicazione che i frammenti di testo che rappresentano l'ombra del testo normale saranno ignorati durante la ricerca. true - indica che il testo in ombra non sarà trovato (prova questo se la ricerca del testo restituisce frammenti duplicati in posizioni vicine). false - indica che il testo in ombra sarà trovato insieme al testo normale (valore predefinito).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setLimitToPageBounds {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```

Imposta l'indicazione che il testo è ricercato entro i limiti della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setLogTextExtractionErrors {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```

Ottiene o imposta l'indicazione che gli errori di estrazione del testo (decodifica) saranno registrati nell'assorbitore di testo (frammento). true - indica che gli errori di estrazione del testo (decodifica) saranno registrati. Potrebbe ridurre le prestazioni. false (predefinito) - nessuna registrazione degli errori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Imposta il rettangolo che delimita il testo ricercato. La proprietà può essere usata nel caso sia necessario delimitare l'estrazione del testo o l'area di sostituzione del testo.

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Indica se l'espressione regolare è utilizzata o meno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSearchForTextRelatedGraphics {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```

Ottiene o imposta il valore che consente la ricerca di grafica correlata al testo (sottolineatura, sfondo ecc.) durante la ricerca del testo. true - la ricerca di grafica correlata al testo verrà eseguita (valore predefinito). false - gli elementi grafici presenti nel documento sorgente saranno ignorati. Impostare questo in caso di problemi di prestazioni o se non è necessario gestire sottolineature, sfondi o ritagli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSearchInAnnotations {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```

Ottiene o imposta il valore che consente la ricerca di testo nelle Annotazioni. true - il testo sarà ricercato nelle Annotazioni. false - il testo nelle Annotazioni non sarà analizzato da TextFragmentAbsorber.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setStoredGraphicElementsMaxCount {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```

Imposta il valore che limita la ricerca di grafica correlata al testo (sottolineatura, sfondo ecc.) su una pagina per il numero specificato di elementi. Il valore predefinito è 250. Impostare un valore inferiore in caso di problemi di prestazioni, provare un valore maggiore se alcuni elementi grafici non sono stati trovati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setUseFontEngineEncoding {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```

Imposta l'indicazione che il testo sarà ricercato usando la codifica del motore dei font. true - indica che verrà usata la codifica del motore dei font (prova questo se la ricerca del testo fallisce a causa di una codifica imperfetta nel documento). false - indica che verrà usata la codifica dei font del documento (valore predefinito).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
