---
title: "PdfFormatConversionOptions"
linktitle: "PdfFormatConversionOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "rappresenta un insieme di opzioni per convertire un documento PDF"
type: docs
weight: 3730
url: /it/java/com.aspose.pdf/pdfformatconversionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions

```
public class PdfFormatConversionOptions extends Object
```

rappresenta un insieme di opzioni per convertire un documento PDF

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Costruttore |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | Costruttore |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Costruttore |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | Costruttore |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Costruttore |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Costruttore |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addNotAccessibleFont](#addNotAccessibleFont-java.lang.String-) |  |
| [getAlignStrategy](#getAlignStrategy--) | Strategia per allineare il testo. Questo parametro ha senso solo quando il flag {@code AlignText} è impostato su true. |
| [getAlignText](#getAlignText--) | Questo flag controlla l'allineamento del testo nel documento convertito. Per impostazione predefinita la conversione del documento non influisce sull'allineamento del testo e lo lascia invariato. Tuttavia, in alcuni casi la sostituzione dei caratteri provoca sovrapposizioni di testo o spazi extra nel documento convertito. Quando questo flag è impostato, verranno eseguite operazioni speciali di allineamento. Questo flag dovrebbe essere impostato solo per i documenti che presentano problemi di testo sovrapposto o spazi extra, poiché l'uso di questo flag riduce le prestazioni e in alcuni casi potrebbe corrompere il contenuto del testo. |
| [getAutoTaggingSettings](#getAutoTaggingSettings--) | Ottiene o imposta le impostazioni per il tagging automatico durante la conversione del formato PDF. Le impostazioni di tagging automatico sono utilizzate per configurare il comportamento del processo di auto‑tagging, tipicamente impiegato per migliorare l'accessibilità e la struttura di un documento PDF durante la conversione a un formato PDF specifico. |
| [getConvertSoftMaskAction](#getConvertSoftMaskAction--) | Azione per immagini con maschera morbida. |
| [getDefault](#getDefault--) | Ottiene l'oggetto PdfFormatConversionOptions con i parametri predefiniti. |
| [getErrorAction](#getErrorAction--) | Azione per oggetti che non possono essere convertiti. |
| [getExcludeFontsStrategy](#getExcludeFontsStrategy--) | Strategia(e) per escludere i font superflui e ridurre le dimensioni del file del documento. Questo parametro ha senso solo quando il flag {@code OptimizeFileSize} è impostato su true. Per impostazione predefinita viene utilizzata la combinazione delle strategie {@code SubsetFonts} e {@code RemoveDuplicatedFonts}. |
| [getFontEmbeddingOptions](#getFontEmbeddingOptions--) | Opzioni per i casi in cui non è possibile incorporare alcuni font nel documento PDF. |
| [getFormat](#getFormat--) | Formato PDF. |
| [getIccProfileFileName](#getIccProfileFileName--) | Restituisce il nome file del profilo icc. In caso di null viene utilizzato il profilo icc predefinito. |
| [getLogFileName](#getLogFileName--) | Percorso del file in cui verranno memorizzati i commenti. |
| [getLogStream](#getLogStream--) | Stream in cui verranno memorizzati i commenti. |
| [getNonSpecificationCases](#getNonSpecificationCases--) | Contiene flag per controllare il processo di conversione PDF/A nei casi in cui il documento sorgente non corrisponda alla specifica PDF/A. |
| [getNotAccessibleFonts](#getNotAccessibleFonts--) | Questa proprietà è out-property. Contiene tutti i font (nomi dei font) che non sono stati trovati sul computer nell'ultima conversione PDF/A. |
| [getOptimizeFileSize](#getOptimizeFileSize--) | Restituisce un flag che abilita/disabilita la modalità di conversione speciale per ottenere un documento PDF/A con dimensione ridotta. Attualmente questo flag influisce sull'ottimizzazione dei font utilizzati nel documento PDF; in futuro potrebbe essere usato anche per attivare l'ottimizzazione di altre strutture dati, come la grafica. L'insieme di questo flag e della modalità può ridurre significativamente la dimensione del file, ma allo stesso tempo può diminuire notevolmente le prestazioni della conversione. |
| [getOutputIntent](#getOutputIntent--) | Ottiene o imposta il {@link OutputIntent} per la conversione del formato PDF. Il {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) specifica il dispositivo di output o la condizione prevista per la quale il documento PDF viene preparato. Viene utilizzato per garantire che i colori nel documento siano renderizzati correttamente sul dispositivo di destinazione. |
| [getPuaTextProcessingStrategy](#getPuaTextProcessingStrategy--) | Strategia per elaborare i simboli dall'area Private Use (PUA) Unicode. |
| [getSymbolicFontEncodingStrategy](#getSymbolicFontEncodingStrategy--) | Strategia per copiare i dati di codifica per i font simbolici se un font TrueType simbolico ha più di una sotto-tabella di codifica. |
| [getTransparencyAction](#getTransparencyAction--) | Azione per oggetti immagine mascherati |
| [getTransparencyResolution](#getTransparencyResolution--) | Imposta la risoluzione durante la conversione di immagini trasparenti. Maggiore è la risoluzione, più lenta è la velocità di conversione. Il valore predefinito è 300. |
| [getUnicodeProcessingRules](#getUnicodeProcessingRules--) | Regole per risolvere i problemi di mappatura Unicode. Può essere null. |
| [isAsyncImageStreamsConversionMode](#isAsyncImageStreamsConversionMode--) | Ottiene/imposta l'esecuzione dei flussi di immagini in modalità asincrona. |
| [isLowMemoryMode](#isLowMemoryMode--) | È abilitata la modalità di conversione a bassa memoria |
| [isPageByPageFontProcess](#isPageByPageFontProcess--) | È abilitata la modalità di analisi dei font pagina per pagina. Valore predefinito = false |
| [isTransferInfo](#isTransferInfo--) | Ottiene o imposta se trasferire i dati da Info a Metadata durante la conversione in PDF 2.0. True per impostazione predefinita. |
| [isTransparencyIgnore](#isTransparencyIgnore--) | Valore predefinito FALSE e il colore di trasparenza verrà mantenuto per preservare l'aspetto del documento. Con valore TRUE il colore di trasparenza sarà convertito in opaco, alcuni oggetti potrebbero essere coperti. |
| [setAlignStrategy](#setAlignStrategy-byte-) | Strategia per allineare il testo. Questo parametro ha senso solo quando il flag {@code AlignText} è impostato su true. |
| [setAlignText](#setAlignText-boolean-) | Questo flag controlla l'allineamento del testo nel documento convertito. Per impostazione predefinita la conversione del documento non influisce sull'allineamento del testo e lo lascia invariato. Tuttavia, in alcuni casi la sostituzione dei caratteri provoca sovrapposizioni di testo o spazi extra nel documento convertito. Quando questo flag è impostato, verranno eseguite operazioni speciali di allineamento. Questo flag dovrebbe essere impostato solo per i documenti che presentano problemi di testo sovrapposto o spazi extra, poiché l'uso di questo flag riduce le prestazioni e in alcuni casi potrebbe corrompere il contenuto del testo. |
| [setAsyncImageStreamsConversionMode](#setAsyncImageStreamsConversionMode-boolean-) | Ottiene/imposta l'esecuzione dei flussi di immagini in modalità asincrona. |
| [setAutoTaggingSettings](#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-) | Ottiene o imposta le impostazioni per il tagging automatico durante la conversione del formato PDF. Le impostazioni di tagging automatico sono utilizzate per configurare il comportamento del processo di auto‑tagging, tipicamente impiegato per migliorare l'accessibilità e la struttura di un documento PDF durante la conversione a un formato PDF specifico. |
| [setConvertSoftMaskAction](#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-) | Azione per immagini con maschera morbida. |
| [setErrorAction](#setErrorAction-com.aspose.pdf.ConvertErrorAction-) | Azione per oggetti che non possono essere convertiti. |
| [setExcludeFontsStrategy](#setExcludeFontsStrategy-byte-) | Strategia(e) per escludere i font superflui e ridurre le dimensioni del file del documento. Questo parametro ha senso solo quando il flag {@code OptimizeFileSize} è impostato su true. Per impostazione predefinita viene utilizzata la combinazione delle strategie {@code SubsetFonts} e {@code RemoveDuplicatedFonts}. |
| [setFormat](#setFormat-com.aspose.pdf.PdfFormat-) | Formato PDF. |
| [setIccProfileFileName](#setIccProfileFileName-java.lang.String-) | Imposta il nome file del profilo icc. In caso di null viene utilizzato il profilo icc predefinito. |
| [setLogFileName](#setLogFileName-java.lang.String-) | Percorso del file in cui verranno memorizzati i commenti. |
| [setLogStream](#setLogStream-java.io.OutputStream-) | Stream in cui verranno memorizzati i commenti. |
| [setLowMemoryMode](#setLowMemoryMode-boolean-) | È abilitata la modalità di conversione a bassa memoria |
| [setOptimizeFileSize](#setOptimizeFileSize-boolean-) | Imposta un flag che abilita/disabilita la modalità di conversione speciale per ottenere un documento PDF/A con dimensione ridotta. Attualmente questo flag influisce sull'ottimizzazione dei font usati nel documento PDF; in futuro potrebbe essere usato anche per attivare l'ottimizzazione di altre strutture dati, come la grafica. L'insieme di questo flag e della modalità può ridurre significativamente la dimensione del file, ma allo stesso tempo può diminuire notevolmente le prestazioni della conversione. |
| [setOutputIntent](#setOutputIntent-com.aspose.pdf.OutputIntent-) | Ottiene o imposta il {@link OutputIntent} per la conversione del formato PDF. Il {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) specifica il dispositivo di output o la condizione prevista per la quale il documento PDF viene preparato. Viene utilizzato per garantire che i colori nel documento siano renderizzati correttamente sul dispositivo di destinazione. |
| [setPageByPageFontProcess](#setPageByPageFontProcess-boolean-) | Imposta la modalità di analisi dei font pagina per pagina abilitata. Valore predefinito = false |
| [setPuaTextProcessingStrategy](#setPuaTextProcessingStrategy-int-) | Strategia per elaborare i simboli dall'area Private Use (PUA) Unicode. |
| [setSymbolicFontEncodingStrategy](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | Strategia per copiare i dati di codifica per i font simbolici se un font TrueType simbolico ha più di una sotto-tabella di codifica. |
| [setTransferInfo](#setTransferInfo-boolean-) | Ottiene o imposta se trasferire i dati da Info a Metadata durante la conversione in PDF 2.0. True per impostazione predefinita. |
| [setTransparencyAction](#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-) | Azione per oggetti immagine mascherati |
| [setTransparencyIgnore](#setTransparencyIgnore-boolean-) | Valore predefinito FALSE e il colore di trasparenza verrà mantenuto per preservare l'aspetto del documento. Con valore TRUE il colore di trasparenza sarà convertito in opaco, alcuni oggetti potrebbero essere coperti. |
| [setTransparencyResolution](#setTransparencyResolution-int-) | Imposta la risoluzione durante la conversione di immagini trasparenti. Maggiore è la risoluzione, più lenta è la velocità di conversione. Il valore predefinito è 300. |
| [setUnicodeProcessingRules](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | Regole per risolvere i problemi di mappatura Unicode. Può essere null. |

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Costruttore

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
Costruttore

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Costruttore

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
Costruttore

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Costruttore

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Costruttore

### addNotAccessibleFont {#addNotAccessibleFont-java.lang.String-}


### getAlignStrategy {#getAlignStrategy--}
```
public byte getAlignStrategy()
```

Strategia per allineare il testo. Questo parametro ha senso solo quando il flag {@code AlignText} è impostato su true.

**Returns:**
Elemento SegmentAlignStrategy @see SegmentAlignStrategy

### getAlignText {#getAlignText--}
```
public boolean getAlignText()
```

Questo flag controlla l'allineamento del testo nel documento convertito. Per impostazione predefinita la conversione del documento non influisce sull'allineamento del testo e lo lascia invariato. Tuttavia, in alcuni casi la sostituzione dei caratteri provoca sovrapposizioni di testo o spazi extra nel documento convertito. Quando questo flag è impostato, verranno eseguite operazioni speciali di allineamento. Questo flag dovrebbe essere impostato solo per i documenti che presentano problemi di testo sovrapposto o spazi extra, poiché l'uso di questo flag riduce le prestazioni e in alcuni casi potrebbe corrompere il contenuto del testo.

**Returns:**
valore booleano

### getAutoTaggingSettings {#getAutoTaggingSettings--}
```
public final AutoTaggingSettings getAutoTaggingSettings()
```

Ottiene o imposta le impostazioni per il tagging automatico durante la conversione del formato PDF. Le impostazioni di tagging automatico sono utilizzate per configurare il comportamento del processo di auto‑tagging, tipicamente impiegato per migliorare l'accessibilità e la struttura di un documento PDF durante la conversione a un formato PDF specifico.

**Returns:**
istanza AutoTaggingSettings

### getConvertSoftMaskAction {#getConvertSoftMaskAction--}
```
public final ConvertSoftMaskAction getConvertSoftMaskAction()
```

Azione per immagini con maschera morbida.

**Returns:**
valore int

### getDefault {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```

Ottiene l'oggetto PdfFormatConversionOptions con i parametri predefiniti.

**Returns:**
Oggetto PdfFormatConversionOptions

### getErrorAction {#getErrorAction--}
```
public ConvertErrorAction getErrorAction()
```

Azione per oggetti che non possono essere convertiti.

**Returns:**
Elemento ConvertErrorAction @see ConvertErrorAction

### getExcludeFontsStrategy {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```

Strategia(e) per escludere i font superflui e ridurre le dimensioni del file del documento. Questo parametro ha senso solo quando il flag {@code OptimizeFileSize} è impostato su true. Per impostazione predefinita viene utilizzata la combinazione delle strategie {@code SubsetFonts} e {@code RemoveDuplicatedFonts}.

**Returns:**
Valore byte @see RemoveFontsStrategy

### getFontEmbeddingOptions {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```

Opzioni per i casi in cui non è possibile incorporare alcuni font nel documento PDF.

**Returns:**
Oggetto FontEmbeddingOptions

### getFormat {#getFormat--}
```
public PdfFormat getFormat()
```

Formato PDF.

**Returns:**
Elemento PdfFormat @see PdfFormat

### getIccProfileFileName {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```

Restituisce il nome file del profilo icc. In caso di null viene utilizzato il profilo icc predefinito.

**Returns:**
Oggetto stringa

### getLogFileName {#getLogFileName--}
```
public String getLogFileName()
```

Percorso del file in cui verranno memorizzati i commenti.

**Returns:**
Oggetto stringa

### getLogStream {#getLogStream--}
```
public OutputStream getLogStream()
```

Stream in cui verranno memorizzati i commenti.

**Returns:**
oggetto OutputStream

### getNonSpecificationCases {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```

Contiene flag per controllare il processo di conversione PDF/A nei casi in cui il documento sorgente non corrisponda alla specifica PDF/A.

**Returns:**
oggetto PdfANonSpecificationFlags

### getNotAccessibleFonts {#getNotAccessibleFonts--}
```
public String [] getNotAccessibleFonts()
```

Questa proprietà è out-property. Contiene tutti i font (nomi dei font) che non sono stati trovati sul computer nell'ultima conversione PDF/A.

**Returns:**
Array di stringhe

### getOptimizeFileSize {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```

Restituisce un flag che abilita/disabilita la modalità di conversione speciale per ottenere un documento PDF/A con dimensione ridotta. Attualmente questo flag influisce sull'ottimizzazione dei font utilizzati nel documento PDF; in futuro potrebbe essere usato anche per attivare l'ottimizzazione di altre strutture dati, come la grafica. L'insieme di questo flag e della modalità può ridurre significativamente la dimensione del file, ma allo stesso tempo può diminuire notevolmente le prestazioni della conversione.

**Returns:**
valore booleano

### getOutputIntent {#getOutputIntent--}
```
public final OutputIntent getOutputIntent()
```

Ottiene o imposta il {@link OutputIntent} per la conversione del formato PDF. Il {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) specifica il dispositivo di output o la condizione prevista per la quale il documento PDF viene preparato. Viene utilizzato per garantire che i colori nel documento siano renderizzati correttamente sul dispositivo di destinazione.

**Returns:**
istanza OutputIntent

### getPuaTextProcessingStrategy {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```

Strategia per elaborare i simboli dall'area Private Use (PUA) Unicode.

**Returns:**
elemento PuaProcessingStrategy @see PuaProcessingStrategy

### getSymbolicFontEncodingStrategy {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```

Strategia per copiare i dati di codifica per i font simbolici se un font TrueType simbolico ha più di una sotto-tabella di codifica.

**Returns:**
oggetto PdfASymbolicFontEncodingStrategy

### getTransparencyAction {#getTransparencyAction--}
```
public ConvertTransparencyAction getTransparencyAction()
```

Azione per oggetti immagine mascherati

**Returns:**
elemento ConvertTransparencyAction @see ConvertTransparencyAction

### getTransparencyResolution {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```

Imposta la risoluzione durante la conversione di immagini trasparenti. Maggiore è la risoluzione, più lenta è la velocità di conversione. Il valore predefinito è 300.

**Returns:**
valore di risoluzione

### getUnicodeProcessingRules {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```

Regole per risolvere i problemi di mappatura Unicode. Può essere null.

**Returns:**
oggetto ToUnicodeProcessingRules

### isAsyncImageStreamsConversionMode {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```

Ottiene/imposta l'esecuzione dei flussi di immagini in modalità asincrona.

**Returns:**
valore booleano

### isLowMemoryMode {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```

È abilitata la modalità di conversione a bassa memoria

**Returns:**
valore booleano

### isPageByPageFontProcess {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```

È abilitata la modalità di analisi dei font pagina per pagina. Valore predefinito = false

**Returns:**
valore booleano

### isTransferInfo {#isTransferInfo--}
```
public final boolean isTransferInfo()
```

Ottiene o imposta se trasferire i dati da Info a Metadata durante la conversione in PDF 2.0. True per impostazione predefinita.

**Returns:**
valore booleano

### isTransparencyIgnore {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```

Valore predefinito FALSE e il colore di trasparenza verrà mantenuto per preservare l'aspetto del documento. Con valore TRUE il colore di trasparenza sarà convertito in opaco, alcuni oggetti potrebbero essere coperti.

**Returns:**
valore booleano

### setAlignStrategy {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```

Strategia per allineare il testo. Questo parametro ha senso solo quando il flag {@code AlignText} è impostato su true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alignStrategy |  | Elemento SegmentAlignStrategy @see SegmentAlignStrategy |

### setAlignText {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```

Questo flag controlla l'allineamento del testo nel documento convertito. Per impostazione predefinita la conversione del documento non influisce sull'allineamento del testo e lo lascia invariato. Tuttavia, in alcuni casi la sostituzione dei caratteri provoca sovrapposizioni di testo o spazi extra nel documento convertito. Quando questo flag è impostato, verranno eseguite operazioni speciali di allineamento. Questo flag dovrebbe essere impostato solo per i documenti che presentano problemi di testo sovrapposto o spazi extra, poiché l'uso di questo flag riduce le prestazioni e in alcuni casi potrebbe corrompere il contenuto del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setAsyncImageStreamsConversionMode {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```

Ottiene/imposta l'esecuzione dei flussi di immagini in modalità asincrona.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setAutoTaggingSettings {#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-}
Ottiene o imposta le impostazioni per il tagging automatico durante la conversione del formato PDF. Le impostazioni di tagging automatico sono utilizzate per configurare il comportamento del processo di auto‑tagging, tipicamente impiegato per migliorare l'accessibilità e la struttura di un documento PDF durante la conversione a un formato PDF specifico.

### setConvertSoftMaskAction {#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-}
Azione per immagini con maschera morbida.

### setErrorAction {#setErrorAction-com.aspose.pdf.ConvertErrorAction-}
Azione per oggetti che non possono essere convertiti.

### setExcludeFontsStrategy {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```

Strategia(e) per escludere i font superflui e ridurre le dimensioni del file del documento. Questo parametro ha senso solo quando il flag {@code OptimizeFileSize} è impostato su true. Per impostazione predefinita viene utilizzata la combinazione delle strategie {@code SubsetFonts} e {@code RemoveDuplicatedFonts}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setFormat {#setFormat-com.aspose.pdf.PdfFormat-}
Formato PDF.

### setIccProfileFileName {#setIccProfileFileName-java.lang.String-}
Imposta il nome file del profilo icc. In caso di null viene utilizzato il profilo icc predefinito.

### setLogFileName {#setLogFileName-java.lang.String-}
Percorso del file in cui verranno memorizzati i commenti.

### setLogStream {#setLogStream-java.io.OutputStream-}
Stream in cui verranno memorizzati i commenti.

### setLowMemoryMode {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```

È abilitata la modalità di conversione a bassa memoria

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setOptimizeFileSize {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```

Imposta un flag che abilita/disabilita la modalità di conversione speciale per ottenere un documento PDF/A con dimensione ridotta. Attualmente questo flag influisce sull'ottimizzazione dei font usati nel documento PDF; in futuro potrebbe essere usato anche per attivare l'ottimizzazione di altre strutture dati, come la grafica. L'insieme di questo flag e della modalità può ridurre significativamente la dimensione del file, ma allo stesso tempo può diminuire notevolmente le prestazioni della conversione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setOutputIntent {#setOutputIntent-com.aspose.pdf.OutputIntent-}
Ottiene o imposta il {@link OutputIntent} per la conversione del formato PDF. Il {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) specifica il dispositivo di output o la condizione prevista per la quale il documento PDF viene preparato. Viene utilizzato per garantire che i colori nel documento siano renderizzati correttamente sul dispositivo di destinazione.

### setPageByPageFontProcess {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```

Imposta la modalità di analisi dei font pagina per pagina abilitata. Valore predefinito = false

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| b |  | valore booleano |

### setPuaTextProcessingStrategy {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```

Strategia per elaborare i simboli dall'area Private Use (PUA) Unicode.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | elemento PuaProcessingStrategy @see PuaProcessingStrategy |

### setSymbolicFontEncodingStrategy {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
Strategia per copiare i dati di codifica per i font simbolici se un font TrueType simbolico ha più di una sotto-tabella di codifica.

### setTransferInfo {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```

Ottiene o imposta se trasferire i dati da Info a Metadata durante la conversione in PDF 2.0. True per impostazione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setTransparencyAction {#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-}
Azione per oggetti immagine mascherati

### setTransparencyIgnore {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```

Valore predefinito FALSE e il colore di trasparenza verrà mantenuto per preservare l'aspetto del documento. Con valore TRUE il colore di trasparenza sarà convertito in opaco, alcuni oggetti potrebbero essere coperti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setTransparencyResolution {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```

Imposta la risoluzione durante la conversione di immagini trasparenti. Maggiore è la risoluzione, più lenta è la velocità di conversione. Il valore predefinito è 300.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dpi |  | valore di risoluzione |

### setUnicodeProcessingRules {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
Regole per risolvere i problemi di mappatura Unicode. Può essere null.
