---
title: "RenderingOptions"
linktitle: "RenderingOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le opzioni di rendering"
type: docs
weight: 4150
url: /it/java/com.aspose.pdf/renderingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RenderingOptions

```
public final class RenderingOptions extends Object
```

Rappresenta le opzioni di rendering

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RenderingOptions](#RenderingOptions--) | Inizializza una nuova istanza dell'oggetto {@code RenderingOptions}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAnalyzeFonts](#getAnalyzeFonts--) | Sostituisce i caratteri tipografici se necessario per garantire che tutti i caratteri nel testo possano essere visualizzati. L'algoritmo di sostituzione dei font segue questi passaggi: 1. Se l'utente imposta esplicitamente la proprietà DefaultFontName, verificare se il font specificato può visualizzare i caratteri desiderati. 2. Se non è impostato alcun font definito dall'utente, cercare tra i font aggiunti tramite {@code FontRepository.Sources}. 3. Analizzare il testo per identificare il suo alfabeto o script e suggerire i nomi dei font di conseguenza. Tentare di individuare e utilizzare questi font dal sistema. 4. Come soluzione di riserva, cercare nel sistema un font capace di visualizzare i caratteri richiesti. |
| [getBarcodeOptimization](#getBarcodeOptimization--) | Ottiene la modalità di ottimizzazione del codice a barre. |
| [getConvertFontsToUnicodeTTF](#getConvertFontsToUnicodeTTF--) | Indica che tutti i font saranno convertiti in versioni TTF Unicode. Ciò è utile per motivi di compatibilità e per ottimizzare l'uso dei font, poiché ogni nuovo font TTF conterrà non tutti i simboli del font di origine, ma solo i simboli utilizzati nel testo. |
| [getDefaultFontName](#getDefaultFontName--) | Ottiene/imposta il nome predefinito del font utilizzato per sostituire i font mancanti. |
| [getHeightExtraUnits](#getHeightExtraUnits--) | Ottiene o imposta un valore utilizzato per aumentare o diminuire la larghezza del rettangolo per l'operatore AppendRectangle. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Ottiene o imposta l'indicazione che gli errori relativi all'assenza di font saranno ignorati. true – indica che gli errori di assenza di font saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione. false per impostazione predefinita. |
| [getInterpolationHighQuality](#getInterpolationHighQuality--) | Ottiene o imposta la modalità ad alta qualità per l'interpolazione. |
| [getMaxFontsCacheSize](#getMaxFontsCacheSize--) | Numero massimo di font nella cache dei font. Il valore predefinito è 10. |
| [getMaxSymbolsCacheSize](#getMaxSymbolsCacheSize--) | Numero massimo di simboli nella cache dei simboli. Il valore predefinito è 100. |
| [getOptimizeDimensions](#getOptimizeDimensions--) | Ottiene o imposta la modalità di ottimizzazione delle dimensioni. |
| [getScaleImagesToFitPageWidth](#getScaleImagesToFitPageWidth--) | Ottiene o imposta un valore utilizzato per ridimensionare tutte le immagini nella pagina in modo da adattarle alla larghezza della pagina. |
| [getSystemFontsNativeRendering](#getSystemFontsNativeRendering--) | Ottiene una modalità in cui i font di sistema vengono renderizzati nativamente |
| [getUseFontHinting](#getUseFontHinting--) | L'utilizzo di questo flag attiva il meccanismo di hinting dei font. Il hinting dei font è l'uso di istruzioni matematiche per regolare la visualizzazione di un font contornato. In alcuni casi l'attivazione di questo flag può risolvere problemi di leggibilità del testo. Al momento attuale l'uso di questo flag può avere effetto solo per i font TTF, se questi font sono utilizzati nel documento di origine. |
| [getUseNewImagingEngine](#getUseNewImagingEngine--) | Ottiene un flag che determina se il nuovo motore di imaging è utilizzato o meno. |
| [getWidthExtraUnits](#getWidthExtraUnits--) | Ottiene o imposta un valore utilizzato per aumentare o diminuire la larghezza del rettangolo per l'operatore AppendRectangle. |
| [isTryToSkipDocumentErrors](#isTryToSkipDocumentErrors--) | Ottiene un valore utilizzato per ignorare gli errori durante l'elaborazione del file PDF |
| [setAnalyzeFonts](#setAnalyzeFonts-boolean-) | Sostituisce i caratteri tipografici se necessario per garantire che tutti i caratteri nel testo possano essere visualizzati. L'algoritmo di sostituzione dei font segue questi passaggi: 1. Se l'utente imposta esplicitamente la proprietà DefaultFontName, verificare se il font specificato può visualizzare i caratteri desiderati. 2. Se non è impostato alcun font definito dall'utente, cercare tra i font aggiunti tramite {@code FontRepository.Sources}. 3. Analizzare il testo per identificare il suo alfabeto o script e suggerire i nomi dei font di conseguenza. Tentare di individuare e utilizzare questi font dal sistema. 4. Come soluzione di riserva, cercare nel sistema un font capace di visualizzare i caratteri richiesti. |
| [setBarcodeOptimization](#setBarcodeOptimization-boolean-) | Imposta la modalità di ottimizzazione del codice a barre. |
| [setConvertFontsToUnicodeTTF](#setConvertFontsToUnicodeTTF-boolean-) | Indica che tutti i font saranno convertiti in versioni TTF Unicode. Ciò è utile per motivi di compatibilità e per ottimizzare l'uso dei font, poiché ogni nuovo font TTF conterrà non tutti i simboli del font di origine, ma solo i simboli utilizzati nel testo. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Ottiene/imposta il nome predefinito del font utilizzato per sostituire i font mancanti. |
| [setHeightExtraUnits](#setHeightExtraUnits-float-) | Ottiene o imposta un valore utilizzato per aumentare o diminuire la larghezza del rettangolo per l'operatore AppendRectangle. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Ottiene o imposta l'indicazione che gli errori relativi all'assenza di font saranno ignorati. true – indica che gli errori di assenza di font saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione. false per impostazione predefinita. |
| [setInterpolationHighQuality](#setInterpolationHighQuality-boolean-) | Ottiene o imposta la modalità ad alta qualità per l'interpolazione. |
| [setMaxFontsCacheSize](#setMaxFontsCacheSize-int-) | Numero massimo di font nella cache dei font. Il valore predefinito è 10. |
| [setMaxSymbolsCacheSize](#setMaxSymbolsCacheSize-int-) | Numero massimo di simboli nella cache dei simboli. Il valore predefinito è 100. |
| [setOptimizeDimensions](#setOptimizeDimensions-boolean-) | Ottiene o imposta la modalità di ottimizzazione delle dimensioni. |
| [setScaleImagesToFitPageWidth](#setScaleImagesToFitPageWidth-boolean-) | Ottiene o imposta un valore utilizzato per ridimensionare tutte le immagini nella pagina in modo da adattarle alla larghezza della pagina. |
| [setSystemFontsNativeRendering](#setSystemFontsNativeRendering-boolean-) | Imposta una modalità in cui i font di sistema vengono renderizzati nativamente |
| [setTryToSkipDocumentErrors](#setTryToSkipDocumentErrors-boolean-) | Imposta un valore utilizzato per ignorare gli errori durante l'elaborazione del file PDF |
| [setUseFontHinting](#setUseFontHinting-boolean-) | L'utilizzo di questo flag attiva il meccanismo di hinting dei font. Il hinting dei font è l'uso di istruzioni matematiche per regolare la visualizzazione di un font contornato. In alcuni casi l'attivazione di questo flag può risolvere problemi di leggibilità del testo. Al momento attuale l'uso di questo flag può avere effetto solo per i font TTF, se questi font sono utilizzati nel documento di origine. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Imposta un flag che determina se il nuovo motore di imaging è utilizzato o meno. |
| [setWidthExtraUnits](#setWidthExtraUnits-float-) | Ottiene o imposta un valore utilizzato per aumentare o diminuire la larghezza del rettangolo per l'operatore AppendRectangle. |

### RenderingOptions {#RenderingOptions--}
```
public RenderingOptions()
```

Inizializza una nuova istanza dell'oggetto {@code RenderingOptions}.

### getAnalyzeFonts {#getAnalyzeFonts--}
```
public final boolean getAnalyzeFonts()
```

Sostituisce i caratteri tipografici se necessario per garantire che tutti i caratteri nel testo possano essere visualizzati. L'algoritmo di sostituzione dei font segue questi passaggi: 1. Se l'utente imposta esplicitamente la proprietà DefaultFontName, verificare se il font specificato può visualizzare i caratteri desiderati. 2. Se non è impostato alcun font definito dall'utente, cercare tra i font aggiunti tramite {@code FontRepository.Sources}. 3. Analizzare il testo per identificare il suo alfabeto o script e suggerire i nomi dei font di conseguenza. Tentare di individuare e utilizzare questi font dal sistema. 4. Come soluzione di riserva, cercare nel sistema un font capace di visualizzare i caratteri richiesti.

**Returns:**
valore booleano

### getBarcodeOptimization {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```

Ottiene la modalità di ottimizzazione del codice a barre.

**Returns:**
valore booleano

### getConvertFontsToUnicodeTTF {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```

Indica che tutti i font saranno convertiti in versioni TTF Unicode. Ciò è utile per motivi di compatibilità e per ottimizzare l'uso dei font, poiché ogni nuovo font TTF conterrà non tutti i simboli del font di origine, ma solo i simboli utilizzati nel testo.

**Returns:**
valore booleano

### getDefaultFontName {#getDefaultFontName--}
```
public final String getDefaultFontName()
```

Ottiene/imposta il nome predefinito del font utilizzato per sostituire i font mancanti.

**Returns:**
valore String

### getHeightExtraUnits {#getHeightExtraUnits--}
```
public final float getHeightExtraUnits()
```

Ottiene o imposta un valore utilizzato per aumentare o diminuire la larghezza del rettangolo per l'operatore AppendRectangle.

**Returns:**
valore float

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Ottiene o imposta l'indicazione che gli errori relativi all'assenza di font saranno ignorati. true – indica che gli errori di assenza di font saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione. false per impostazione predefinita.

**Returns:**
valore booleano

### getInterpolationHighQuality {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```

Ottiene o imposta la modalità ad alta qualità per l'interpolazione.

**Returns:**
valore booleano

### getMaxFontsCacheSize {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```

Numero massimo di font nella cache dei font. Il valore predefinito è 10.

**Returns:**
valore int

### getMaxSymbolsCacheSize {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```

Numero massimo di simboli nella cache dei simboli. Il valore predefinito è 100.

**Returns:**
valore int

### getOptimizeDimensions {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```

Ottiene o imposta la modalità di ottimizzazione delle dimensioni.

**Returns:**
valore booleano

### getScaleImagesToFitPageWidth {#getScaleImagesToFitPageWidth--}
```
@Deprecated public final boolean getScaleImagesToFitPageWidth()
```

Ottiene o imposta un valore utilizzato per ridimensionare tutte le immagini nella pagina in modo da adattarle alla larghezza della pagina.

**Returns:**
valore booleano @deprecated ScaleImagesToFitPageWidth è deprecato.

### getSystemFontsNativeRendering {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```

Ottiene una modalità in cui i font di sistema vengono renderizzati nativamente

**Returns:**
valore booleano

### getUseFontHinting {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```

L'utilizzo di questo flag attiva il meccanismo di hinting dei font. Il hinting dei font è l'uso di istruzioni matematiche per regolare la visualizzazione di un font contornato. In alcuni casi l'attivazione di questo flag può risolvere problemi di leggibilità del testo. Al momento attuale l'uso di questo flag può avere effetto solo per i font TTF, se questi font sono utilizzati nel documento di origine.

**Returns:**
valore booleano

### getUseNewImagingEngine {#getUseNewImagingEngine--}
```
@Deprecated public boolean getUseNewImagingEngine()
```

Ottiene un flag che determina se il nuovo motore di imaging è utilizzato o meno.

**Returns:**
valore booleano @deprecated UseNewImagingEngine è deprecato

### getWidthExtraUnits {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```

Ottiene o imposta un valore utilizzato per aumentare o diminuire la larghezza del rettangolo per l'operatore AppendRectangle.

**Returns:**
valore float

### isTryToSkipDocumentErrors {#isTryToSkipDocumentErrors--}
```
public boolean isTryToSkipDocumentErrors()
```

Ottiene un valore utilizzato per ignorare gli errori durante l'elaborazione del file PDF

**Returns:**
valore booleano

### setAnalyzeFonts {#setAnalyzeFonts-boolean-}
```
public final void setAnalyzeFonts(boolean value)
```

Sostituisce i caratteri tipografici se necessario per garantire che tutti i caratteri nel testo possano essere visualizzati. L'algoritmo di sostituzione dei font segue questi passaggi: 1. Se l'utente imposta esplicitamente la proprietà DefaultFontName, verificare se il font specificato può visualizzare i caratteri desiderati. 2. Se non è impostato alcun font definito dall'utente, cercare tra i font aggiunti tramite {@code FontRepository.Sources}. 3. Analizzare il testo per identificare il suo alfabeto o script e suggerire i nomi dei font di conseguenza. Tentare di individuare e utilizzare questi font dal sistema. 4. Come soluzione di riserva, cercare nel sistema un font capace di visualizzare i caratteri richiesti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setBarcodeOptimization {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```

Imposta la modalità di ottimizzazione del codice a barre.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setConvertFontsToUnicodeTTF {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```

Indica che tutti i font saranno convertiti in versioni TTF Unicode. Ciò è utile per motivi di compatibilità e per ottimizzare l'uso dei font, poiché ogni nuovo font TTF conterrà non tutti i simboli del font di origine, ma solo i simboli utilizzati nel testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Ottiene/imposta il nome predefinito del font utilizzato per sostituire i font mancanti.

### setHeightExtraUnits {#setHeightExtraUnits-float-}
```
public final void setHeightExtraUnits(float value)
```

Ottiene o imposta un valore utilizzato per aumentare o diminuire la larghezza del rettangolo per l'operatore AppendRectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Ottiene o imposta l'indicazione che gli errori relativi all'assenza di font saranno ignorati. true – indica che gli errori di assenza di font saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione. false per impostazione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setInterpolationHighQuality {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```

Ottiene o imposta la modalità ad alta qualità per l'interpolazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMaxFontsCacheSize {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```

Numero massimo di font nella cache dei font. Il valore predefinito è 10.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setMaxSymbolsCacheSize {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```

Numero massimo di simboli nella cache dei simboli. Il valore predefinito è 100.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setOptimizeDimensions {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```

Ottiene o imposta la modalità di ottimizzazione delle dimensioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setScaleImagesToFitPageWidth {#setScaleImagesToFitPageWidth-boolean-}
```
@Deprecated public final void setScaleImagesToFitPageWidth(boolean value)
```

Ottiene o imposta un valore utilizzato per ridimensionare tutte le immagini nella pagina in modo da adattarle alla larghezza della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano @deprecated ScaleImagesToFitPageWidth è deprecato. |

### setSystemFontsNativeRendering {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```

Imposta una modalità in cui i font di sistema vengono renderizzati nativamente

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setTryToSkipDocumentErrors {#setTryToSkipDocumentErrors-boolean-}
```
public void setTryToSkipDocumentErrors(boolean value)
```

Imposta un valore utilizzato per ignorare gli errori durante l'elaborazione del file PDF

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUseFontHinting {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```

L'utilizzo di questo flag attiva il meccanismo di hinting dei font. Il hinting dei font è l'uso di istruzioni matematiche per regolare la visualizzazione di un font contornato. In alcuni casi l'attivazione di questo flag può risolvere problemi di leggibilità del testo. Al momento attuale l'uso di questo flag può avere effetto solo per i font TTF, se questi font sono utilizzati nel documento di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public void setUseNewImagingEngine(boolean value)
```

Imposta un flag che determina se il nuovo motore di imaging è utilizzato o meno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano @deprecated UseNewImagingEngine è deprecato |

### setWidthExtraUnits {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```

Ottiene o imposta un valore utilizzato per aumentare o diminuire la larghezza del rettangolo per l'operatore AppendRectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |
