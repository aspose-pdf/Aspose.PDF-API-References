---
title: "DocSaveOptions"
linktitle: "DocSaveOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Opzioni di salvataggio per l'esportazione in formato Doc"
type: docs
weight: 1030
url: /it/java/com.aspose.pdf/docsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.DocSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Opzioni di salvataggio per l'esportazione in formato Doc

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DocSaveOptions](#DocSaveOptions--) | Costruttore |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Questo gestore può essere usato per gestire gli eventi di avanzamento della conversione, ad es. può essere usato per mostrare una barra di avanzamento o messaggi sul numero corrente di pagine elaborate, esempio del codice del gestore che mostra l'avanzamento sulla console è : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre> |
| [getFormat](#getFormat--) | Ottieni il formato di output |
| [getImageResolutionX](#getImageResolutionX--) | Risoluzione X delle immagini convertite. |
| [getImageResolutionY](#getImageResolutionY--) | Risoluzione Y delle immagini convertite. |
| [getMaxDistanceBetweenTextLines](#getMaxDistanceBetweenTextLines--) | Questo parametro è usato per raggruppare le linee di testo in paragrafi. Determina quanto distanti possono essere due linee di testo relative. Specificato in centinaia di percentuale dell'altezza delle linee di testo. |
| [getMemorySaveModePath](#getMemorySaveModePath--) | Definisce il percorso (nome file o nome directory) per contenere i dati temporanei durante la conversione in modalità di salvataggio in memoria. |
| [getMode](#getMode--) | Modalità di riconoscimento. |
| [getRelativeHorizontalProximity](#getRelativeHorizontalProximity--) | Nell'PDF le parole possono essere rappresentate internamente con operatori che stampano le parole stampando indipendentemente le loro lettere o sillabe. Pertanto, per rilevare le parole a volte è necessario individuare gruppi di caratteri indipendenti che in realtà sono parole. Questa impostazione definisce la larghezza dello spazio tra gli elementi di testo (lettere, sillabe) che deve essere considerata come distanza tra parole durante il riconoscimento delle parole nel PDF di origine. (La presenza di uno spazio vuoto di almeno questa larghezza tra le lettere indica che gli elementi testuali appartengono a parole diverse). È normalizzata alla dimensione del carattere: 1,0 significa il 100 % della dimensione del carattere della parola presunta. ATTENZIONE! Viene utilizzata solo nei casi in cui il PDF di origine contiene caratteri specifici raramente usati per i quali il valore ottimale non può essere calcolato dal carattere. Quindi, nella stragrande maggioranza dei casi questo parametro non modifica nulla nel documento risultante. |
| [isAddReturnToLineEnd](#isAddReturnToLineEnd--) | Viene utilizzato per interruzioni di paragrafo o di riga. |
| [isConvertType3Fonts](#isConvertType3Fonts--) | Ottiene o imposta la conversione per i font Type3. Nei font Type 3, i glifi devono essere definiti da flussi di operatori grafici. Ciò significa che nell'output DOC/DOCX vediamo immagini invece di testo. Imposta questo flag su true per convertire i font Type3 in TTF e ottenere testo nel file risultante. |
| [isRecognizeBullets](#isRecognizeBullets--) | Attiva il riconoscimento dei punti elenco. |
| [isReSaveFonts](#isReSaveFonts--) | Ottiene o imposta la procedura per il ri‑salvataggio dei font. Se impostato su true, ricarichiamo i font in ogni pagina per evitare l'influenza delle proprietà dei font precedenti e carichiamo il font appena creato da zero. Imposta questa opzione su false se desideri migliorare le prestazioni. Il valore predefinito è true; |
| [setAddReturnToLineEnd](#setAddReturnToLineEnd-boolean-) | Usa interruzioni di paragrafo o di riga |
| [setBatchSize](#setBatchSize-int-) | Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione. |
| [setConvertType3Fonts](#setConvertType3Fonts-boolean-) | Ottiene o imposta la conversione per i font Type3. Nei font Type 3, i glifi devono essere definiti da flussi di operatori grafici. Ciò significa che nell'output DOC/DOCX vediamo immagini invece di testo. Imposta questo flag su true per convertire i font Type3 in TTF e ottenere testo nel file risultante. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Questo gestore può essere usato per gestire gli eventi di avanzamento della conversione, per esempio. |
| [setFormat](#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-) | Imposta il formato di output |
| [setImageResolutionX](#setImageResolutionX-int-) | Risoluzione X delle immagini convertite. |
| [setImageResolutionY](#setImageResolutionY-int-) | Risoluzione Y delle immagini convertite. |
| [setMaxDistanceBetweenTextLines](#setMaxDistanceBetweenTextLines-float-) | Questo parametro è usato per raggruppare le linee di testo in paragrafi. Determina quanto distanti possono essere due linee di testo relative. Specificato in centinaia di percentuale dell'altezza delle linee di testo. |
| [setMemorySaveModePath](#setMemorySaveModePath-java.lang.String-) | Definisce il percorso (nome file o nome directory) per contenere i dati temporanei durante la conversione in modalità di salvataggio in memoria. |
| [setMode](#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-) | Modalità di riconoscimento. |
| [setRecognizeBullets](#setRecognizeBullets-boolean-) | Attiva il riconoscimento dei punti elenco. |
| [setRelativeHorizontalProximity](#setRelativeHorizontalProximity-float-) | Nell'PDF le parole possono essere rappresentate internamente con operatori che stampano le parole stampando indipendentemente le loro lettere o sillabe. Pertanto, per rilevare le parole a volte è necessario individuare gruppi di caratteri indipendenti che in realtà sono parole. Questa impostazione definisce la larghezza dello spazio tra gli elementi di testo (lettere, sillabe) che deve essere considerata come distanza tra parole durante il riconoscimento delle parole nel PDF di origine. (La presenza di uno spazio vuoto di almeno questa larghezza tra le lettere indica che gli elementi testuali appartengono a parole diverse). È normalizzata alla dimensione del carattere: 1,0 significa il 100 % della dimensione del carattere della parola presunta. ATTENZIONE! Viene utilizzata solo nei casi in cui il PDF di origine contiene caratteri specifici raramente usati per i quali il valore ottimale non può essere calcolato dal carattere. Quindi, nella stragrande maggioranza dei casi questo parametro non modifica nulla nel documento risultante. |
| [setReSaveFonts](#setReSaveFonts-boolean-) | Ottiene o imposta la procedura per il ri‑salvataggio dei font. Se impostato su true, ricarichiamo i font in ogni pagina per evitare l'influenza delle proprietà dei font precedenti e carichiamo il font appena creato da zero. Imposta questa opzione su false se desideri migliorare le prestazioni. Il valore predefinito è true; |

### DocSaveOptions {#DocSaveOptions--}
```
public DocSaveOptions()
```

Costruttore

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione.

**Returns:**
valore int

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Questo gestore può essere usato per gestire gli eventi di avanzamento della conversione, ad es. può essere usato per mostrare una barra di avanzamento o messaggi sul numero corrente di pagine elaborate; un esempio di codice del gestore che mostra l'avanzamento sulla console è: </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre>

**Returns:**
istanza ConversionProgressEventHandler

### getFormat {#getFormat--}
```
public DocSaveOptions.DocFormat getFormat()
```

Ottieni il formato di output

**Returns:**
Elemento DocFormat @see com.aspose.pdf.DocSaveOptions.DocFormat

### getImageResolutionX {#getImageResolutionX--}
```
public int getImageResolutionX()
```

Risoluzione X delle immagini convertite.

**Returns:**
valore int

### getImageResolutionY {#getImageResolutionY--}
```
public int getImageResolutionY()
```

Risoluzione Y delle immagini convertite.

**Returns:**
valore int

### getMaxDistanceBetweenTextLines {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```

Questo parametro è usato per raggruppare le linee di testo in paragrafi. Determina quanto distanti possono essere due linee di testo relative. Specificato in centinaia di percentuale dell'altezza delle linee di testo.

**Returns:**
valore float

### getMemorySaveModePath {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```

Definisce il percorso (nome file o nome directory) per contenere i dati temporanei durante la conversione in modalità di salvataggio in memoria.

**Returns:**
valore String

### getMode {#getMode--}
```
public DocSaveOptions.RecognitionMode getMode()
```

Modalità di riconoscimento.

**Returns:**
Valore RecognitionMode @see RecognitionMode

### getRelativeHorizontalProximity {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```

Nell'PDF le parole possono essere rappresentate internamente con operatori che stampano le parole stampando indipendentemente le loro lettere o sillabe. Pertanto, per rilevare le parole a volte è necessario individuare gruppi di caratteri indipendenti che in realtà sono parole. Questa impostazione definisce la larghezza dello spazio tra gli elementi di testo (lettere, sillabe) che deve essere considerata come distanza tra parole durante il riconoscimento delle parole nel PDF di origine. (La presenza di uno spazio vuoto di almeno questa larghezza tra le lettere indica che gli elementi testuali appartengono a parole diverse). È normalizzata alla dimensione del carattere: 1,0 significa il 100 % della dimensione del carattere della parola presunta. ATTENZIONE! Viene utilizzata solo nei casi in cui il PDF di origine contiene caratteri specifici raramente usati per i quali il valore ottimale non può essere calcolato dal carattere. Quindi, nella stragrande maggioranza dei casi questo parametro non modifica nulla nel documento risultante.

**Returns:**
Prossimità relativa

### isAddReturnToLineEnd {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```

Viene utilizzato per interruzioni di paragrafo o di riga.

**Returns:**
valore booleano.

### isConvertType3Fonts {#isConvertType3Fonts--}
```
public final boolean isConvertType3Fonts()
```

Ottiene o imposta la conversione per i font Type3. Nei font Type 3, i glifi devono essere definiti da flussi di operatori grafici. Ciò significa che nell'output DOC/DOCX vediamo immagini invece di testo. Imposta questo flag su true per convertire i font Type3 in TTF e ottenere testo nel file risultante.

**Returns:**
valore booleano

### isRecognizeBullets {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```

Attiva il riconoscimento dei punti elenco.

**Returns:**
valore booleano

### isReSaveFonts {#isReSaveFonts--}
```
public final boolean isReSaveFonts()
```

Ottiene o imposta la procedura per il ri‑salvataggio dei font. Se impostato su true, ricarichiamo i font in ogni pagina per evitare l'influenza delle proprietà dei font precedenti e carichiamo il font appena creato da zero. Imposta questa opzione su false se desideri migliorare le prestazioni. Il valore predefinito è true;

**Returns:**
valore booleano

### setAddReturnToLineEnd {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```

Usa interruzioni di paragrafo o di riga

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano. |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |

### setConvertType3Fonts {#setConvertType3Fonts-boolean-}
```
public final void setConvertType3Fonts(boolean value)
```

Ottiene o imposta la conversione per i font Type3. Nei font Type 3, i glifi devono essere definiti da flussi di operatori grafici. Ciò significa che nell'output DOC/DOCX vediamo immagini invece di testo. Imposta questo flag su true per convertire i font Type3 in TTF e ottenere testo nel file risultante.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Questo gestore può essere usato per gestire gli eventi di avanzamento della conversione, per esempio.

### setFormat {#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-}
Imposta il formato di output

### setImageResolutionX {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```

Risoluzione X delle immagini convertite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setImageResolutionY {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```

Risoluzione Y delle immagini convertite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setMaxDistanceBetweenTextLines {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```

Questo parametro è usato per raggruppare le linee di testo in paragrafi. Determina quanto distanti possono essere due linee di testo relative. Specificato in centinaia di percentuale dell'altezza delle linee di testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setMemorySaveModePath {#setMemorySaveModePath-java.lang.String-}
Definisce il percorso (nome file o nome directory) per contenere i dati temporanei durante la conversione in modalità di salvataggio in memoria.

### setMode {#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-}
Modalità di riconoscimento.

### setRecognizeBullets {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```

Attiva il riconoscimento dei punti elenco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRelativeHorizontalProximity {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```

Nell'PDF le parole possono essere rappresentate internamente con operatori che stampano le parole stampando indipendentemente le loro lettere o sillabe. Pertanto, per rilevare le parole a volte è necessario individuare gruppi di caratteri indipendenti che in realtà sono parole. Questa impostazione definisce la larghezza dello spazio tra gli elementi di testo (lettere, sillabe) che deve essere considerata come distanza tra parole durante il riconoscimento delle parole nel PDF di origine. (La presenza di uno spazio vuoto di almeno questa larghezza tra le lettere indica che gli elementi testuali appartengono a parole diverse). È normalizzata alla dimensione del carattere: 1,0 significa il 100 % della dimensione del carattere della parola presunta. ATTENZIONE! Viene utilizzata solo nei casi in cui il PDF di origine contiene caratteri specifici raramente usati per i quali il valore ottimale non può essere calcolato dal carattere. Quindi, nella stragrande maggioranza dei casi questo parametro non modifica nulla nel documento risultante.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Prossimità relativa |

### setReSaveFonts {#setReSaveFonts-boolean-}
```
public final void setReSaveFonts(boolean value)
```

Ottiene o imposta la procedura per il ri‑salvataggio dei font. Se impostato su true, ricarichiamo i font in ogni pagina per evitare l'influenza delle proprietà dei font precedenti e carichiamo il font appena creato da zero. Imposta questa opzione su false se desideri migliorare le prestazioni. Il valore predefinito è true;

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
