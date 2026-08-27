---
title: "MarkdownSaveOptions"
linktitle: "MarkdownSaveOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la classe di opzioni di salvataggio del documento nel formato markdown."
type: docs
weight: 60
url: /it/java/com.aspose.pdf.markdownoptions/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.markdownoptions.MarkdownSaveOptions

```
public class MarkdownSaveOptions extends UnifiedSaveOptions
```

Rappresenta la classe di opzioni di salvataggio del documento nel formato markdown.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MarkdownSaveOptions](#MarkdownSaveOptions--) | Crea un'opzione di istanza per salvare un documento in formato markdown. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAreaToExtract](#getAreaToExtract--) | Ottieni o imposta un'area rettangolare per estrarre il contenuto in markdown. |
| [getEmphasisStyle](#getEmphasisStyle--) | Ottiene o imposta lo stile di enfasi per il documento generato. |
| [getExtractVectorGraphics](#getExtractVectorGraphics--) | Ottiene e imposta una proprietà che indica se i grafici vettoriali devono essere estratti. |
| [getHeadingLevels](#getHeadingLevels--) | Definisce i livelli di intestazione attesi da utilizzare nella strategia di riconoscimento delle intestazioni FontSize. Se il valore di questa proprietà è impostato, la strategia di riconoscimento delle intestazioni {@link HeadingRecognitionStrategy#Heuristic} verrà selezionata quando è impostata la strategia {@link HeadingRecognitionStrategy#Auto}, anche se il documento contiene segnalibri. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Ottiene o imposta la strategia di riconoscimento delle intestazioni. |
| [getHeadingStyle](#getHeadingStyle--) | Ottiene o imposta lo stile di intestazione per il documento generato. |
| [getLineBreakStyle](#getLineBreakStyle--) | Ottiene o imposta lo stile di interruzione di riga per il documento generato. |
| [getResourcesDirectoryName](#getResourcesDirectoryName--) | Ottiene e imposta il nome della directory in cui salvare le risorse del documento, come le immagini. Se il valore non è specificato, le immagini verranno scritte nella stessa directory del file markdown stesso. Questo non è un percorso, è solo un nome! Questa directory verrà creata automaticamente nella directory contenente il file markdown salvato. |
| [getResourcesDirectoryPath](#getResourcesDirectoryPath--) | Ottiene e imposta il nome della directory in cui salvare le risorse del documento, come le immagini. Questa directory verrà creata automaticamente nella directory contenente il file markdown salvato. |
| [getSubscriptAndSuperscriptConversion](#getSubscriptAndSuperscriptConversion--) | Ottiene e imposta l'autorizzazione a convertire pedici e apici. Questo valore è true per impostazione predefinita. |
| [getUseImageHtmlTag](#getUseImageHtmlTag--) | Ottiene e imposta l'autorizzazione all'uso del tag img per inserire immagini a sinistra e a destra del testo. In questo caso, nel visualizzatore markdown, il testo avvolgerà l'immagine. |
| [setAreaToExtract](#setAreaToExtract-com.aspose.pdf.Rectangle-) | Ottieni o imposta un'area rettangolare per estrarre il contenuto in markdown. |
| [setEmphasisStyle](#setEmphasisStyle-int-) | Ottiene o imposta lo stile di enfasi per il documento generato. |
| [setExtractVectorGraphics](#setExtractVectorGraphics-boolean-) | Ottiene e imposta una proprietà che indica se i grafici vettoriali devono essere estratti. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Definisce i livelli di intestazione attesi da utilizzare nella strategia di riconoscimento delle intestazioni FontSize. Se il valore di questa proprietà è impostato, la strategia di riconoscimento delle intestazioni {@link HeadingRecognitionStrategy#Heuristic} verrà selezionata quando è impostata la strategia {@link HeadingRecognitionStrategy#Auto}, anche se il documento contiene segnalibri. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Ottiene o imposta la strategia di riconoscimento delle intestazioni. |
| [setHeadingStyle](#setHeadingStyle-int-) | Ottiene o imposta lo stile di intestazione per il documento generato. |
| [setLineBreakStyle](#setLineBreakStyle-int-) | Ottiene o imposta lo stile di interruzione di riga per il documento generato. |
| [setResourcesDirectoryName](#setResourcesDirectoryName-java.lang.String-) | Ottiene e imposta il nome della directory in cui salvare le risorse del documento, come le immagini. Se il valore non è specificato, le immagini verranno scritte nella stessa directory del file markdown stesso. Questo non è un percorso, è solo un nome! Questa directory verrà creata automaticamente nella directory contenente il file markdown salvato. |
| [setResourcesDirectoryPath](#setResourcesDirectoryPath-java.lang.String-) | Ottiene e imposta il nome della directory in cui salvare le risorse del documento, come le immagini. Questa directory verrà creata automaticamente nella directory contenente il file markdown salvato. |
| [setSubscriptAndSuperscriptConversion](#setSubscriptAndSuperscriptConversion-boolean-) | Ottiene e imposta l'autorizzazione a convertire pedici e apici. Questo valore è true per impostazione predefinita. |
| [setUseImageHtmlTag](#setUseImageHtmlTag-boolean-) | Ottiene e imposta l'autorizzazione all'uso del tag img per inserire immagini a sinistra e a destra del testo. In questo caso, nel visualizzatore markdown, il testo avvolgerà l'immagine. |

### MarkdownSaveOptions {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Crea un'opzione di istanza per salvare un documento in formato markdown.

### getAreaToExtract {#getAreaToExtract--}
```
public final Rectangle getAreaToExtract()
```

Ottieni o imposta un'area rettangolare per estrarre il contenuto in markdown.

**Returns:**
Istanza Rectangle

### getEmphasisStyle {#getEmphasisStyle--}
```
public final int getEmphasisStyle()
```

Ottiene o imposta lo stile di enfasi per il documento generato.

**Returns:**
Elemento EmphasisStyle

### getExtractVectorGraphics {#getExtractVectorGraphics--}
```
public final boolean getExtractVectorGraphics()
```

Ottiene e imposta una proprietà che indica se i grafici vettoriali devono essere estratti.

**Returns:**
valore booleano

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Definisce i livelli di intestazione attesi da utilizzare nella strategia di riconoscimento delle intestazioni FontSize. Se il valore di questa proprietà è impostato, la strategia di riconoscimento delle intestazioni {@link HeadingRecognitionStrategy#Heuristic} verrà selezionata quando è impostata la strategia {@link HeadingRecognitionStrategy#Auto}, anche se il documento contiene segnalibri.

**Returns:**
Istanza HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Ottiene o imposta la strategia di riconoscimento delle intestazioni.

**Returns:**
Elemento HeadingRecognitionStrategy

### getHeadingStyle {#getHeadingStyle--}
```
public final int getHeadingStyle()
```

Ottiene o imposta lo stile di intestazione per il documento generato.

**Returns:**
Elemento HeadingStyle

### getLineBreakStyle {#getLineBreakStyle--}
```
public final int getLineBreakStyle()
```

Ottiene o imposta lo stile di interruzione di riga per il documento generato.

**Returns:**
Elemento LineBreakStyle

### getResourcesDirectoryName {#getResourcesDirectoryName--}
```
public final String getResourcesDirectoryName()
```

Ottiene e imposta il nome della directory in cui salvare le risorse del documento, come le immagini. Se il valore non è specificato, le immagini verranno scritte nella stessa directory del file markdown stesso. Questo non è un percorso, è solo un nome! Questa directory verrà creata automaticamente nella directory contenente il file markdown salvato.

**Returns:**
valore String

### getResourcesDirectoryPath {#getResourcesDirectoryPath--}
```
public final String getResourcesDirectoryPath()
```

Ottiene e imposta il nome della directory in cui salvare le risorse del documento, come le immagini. Questa directory verrà creata automaticamente nella directory contenente il file markdown salvato.

**Returns:**
valore String

### getSubscriptAndSuperscriptConversion {#getSubscriptAndSuperscriptConversion--}
```
public final boolean getSubscriptAndSuperscriptConversion()
```

Ottiene e imposta l'autorizzazione a convertire pedici e apici. Questo valore è true per impostazione predefinita.

**Returns:**
valore booleano

### getUseImageHtmlTag {#getUseImageHtmlTag--}
```
public final boolean getUseImageHtmlTag()
```

Ottiene e imposta l'autorizzazione all'uso del tag img per inserire immagini a sinistra e a destra del testo. In questo caso, nel visualizzatore markdown, il testo avvolgerà l'immagine.

**Returns:**
valore booleano

### setAreaToExtract {#setAreaToExtract-com.aspose.pdf.Rectangle-}
Ottieni o imposta un'area rettangolare per estrarre il contenuto in markdown.

### setEmphasisStyle {#setEmphasisStyle-int-}
```
public final void setEmphasisStyle(int value)
```

Ottiene o imposta lo stile di enfasi per il documento generato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento EmphasisStyle |

### setExtractVectorGraphics {#setExtractVectorGraphics-boolean-}
```
public final void setExtractVectorGraphics(boolean value)
```

Ottiene e imposta una proprietà che indica se i grafici vettoriali devono essere estratti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Definisce i livelli di intestazione attesi da utilizzare nella strategia di riconoscimento delle intestazioni FontSize. Se il valore di questa proprietà è impostato, la strategia di riconoscimento delle intestazioni {@link HeadingRecognitionStrategy#Heuristic} verrà selezionata quando è impostata la strategia {@link HeadingRecognitionStrategy#Auto}, anche se il documento contiene segnalibri.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Ottiene o imposta la strategia di riconoscimento delle intestazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento HeadingRecognitionStrategy |

### setHeadingStyle {#setHeadingStyle-int-}
```
public final void setHeadingStyle(int value)
```

Ottiene o imposta lo stile di intestazione per il documento generato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento HeadingStyle |

### setLineBreakStyle {#setLineBreakStyle-int-}
```
public final void setLineBreakStyle(int value)
```

Ottiene o imposta lo stile di interruzione di riga per il documento generato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento LineBreakStyle |

### setResourcesDirectoryName {#setResourcesDirectoryName-java.lang.String-}
Ottiene e imposta il nome della directory in cui salvare le risorse del documento, come le immagini. Se il valore non è specificato, le immagini verranno scritte nella stessa directory del file markdown stesso. Questo non è un percorso, è solo un nome! Questa directory verrà creata automaticamente nella directory contenente il file markdown salvato.

### setResourcesDirectoryPath {#setResourcesDirectoryPath-java.lang.String-}
Ottiene e imposta il nome della directory in cui salvare le risorse del documento, come le immagini. Questa directory verrà creata automaticamente nella directory contenente il file markdown salvato.

### setSubscriptAndSuperscriptConversion {#setSubscriptAndSuperscriptConversion-boolean-}
```
public final void setSubscriptAndSuperscriptConversion(boolean value)
```

Ottiene e imposta l'autorizzazione a convertire pedici e apici. Questo valore è true per impostazione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUseImageHtmlTag {#setUseImageHtmlTag-boolean-}
```
public final void setUseImageHtmlTag(boolean value)
```

Ottiene e imposta l'autorizzazione all'uso del tag img per inserire immagini a sinistra e a destra del testo. In questo caso, nel visualizzatore markdown, il testo avvolgerà l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
