---
title: "EpubLoadOptions"
linktitle: "EpubLoadOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Contiene le opzioni per il caricamento/importazione di un file EPUB in un documento PDF."
type: docs
weight: 1220
url: /it/java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.EpubLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.EpubLoadOptions

```
public final class EpubLoadOptions extends LoadOptions
```

Contiene le opzioni per il caricamento/importazione di un file EPUB in un documento PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EpubLoadOptions](#EpubLoadOptions--) | Crea le opzioni di caricamento predefinite per la conversione di un file EPUB in documento PDF. Dimensione predefinita della pagina PDF - A4 300dpi 2480 × 3508. |
| [EpubLoadOptions](#EpubLoadOptions-java.awt.geom.Dimension2D-) | Crea le opzioni di caricamento predefinite per la conversione di un file EPUB in documento PDF. Dimensione predefinita della pagina PDF - A4 300dpi 2480 × 3508. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCustomCss](#getCustomCss--) | Ottiene o imposta il Css personalizzato da applicare all'apertura del documento Epub. |
| [getEngineType](#getEngineType--) | Seleziona il tipo di motore per la conversione da EPUB a PDF. L'impostazione predefinita è EngineType.NEW |
| [getMargin](#getMargin--) | Ottiene un riferimento all'oggetto che rappresenta le informazioni di margine. |
| [getMarginsAreaUsageMode](#getMarginsAreaUsageMode--) | Rappresenta la modalità di utilizzo dell'area dei margini - definisce il trattamento delle istruzioni (se presenti) del CSS del documento importato relative all'uso dei margini. |
| [getPageSize](#getPageSize--) | Ottiene la dimensione della pagina di output per l'importazione. |
| [getPageSizeAdjustmentMode](#getPageSizeAdjustmentMode--) | ATTENZIONE! La funzionalità è stata implementata ma non è ancora stata resa disponibile nell'API pubblica a causa di un problema bloccante nel livello OSHARED rilevato per il documento di esempio. Rappresenta la modalità di utilizzo della dimensione della pagina durante la conversione. I formati (come HTML, EPUB, ecc.) solitamente hanno un layout fluido, quindi consentono di adattare la dimensione della pagina richiesta. Tuttavia, a volte il contenuto ha posizioni orizzontali o dimensioni specificate che non permettono di inserire il contenuto nella dimensione della pagina richiesta. In tal caso possiamo definire cosa fare (ad esempio quando la dimensione del contenuto non si adatta alla dimensione iniziale della pagina del PDF risultante). |
| [setCustomCss](#setCustomCss-java.lang.String-) | Ottiene o imposta il Css personalizzato da applicare all'apertura del documento Epub. |
| [setEngineType](#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-) | Seleziona il tipo di motore per la conversione da EPUB a PDF. L'impostazione predefinita è EngineType.NEW |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Ottiene un riferimento all'oggetto che rappresenta le informazioni di margine. |
| [setMarginsAreaUsageMode](#setMarginsAreaUsageMode-int-) | Rappresenta la modalità di utilizzo dell'area dei margini - definisce il trattamento delle istruzioni (se presenti) del CSS del documento importato relative all'uso dei margini. |
| [setPageSizeAdjustmentMode](#setPageSizeAdjustmentMode-int-) | ATTENZIONE! La funzionalità è stata implementata ma non è ancora stata resa disponibile nell'API pubblica a causa di un problema bloccante nel livello OSHARED rilevato per il documento di esempio. Rappresenta la modalità di utilizzo della dimensione della pagina durante la conversione. I formati (come HTML, EPUB, ecc.) solitamente hanno un layout fluido, quindi consentono di adattare la dimensione della pagina richiesta. Tuttavia, a volte il contenuto ha posizioni orizzontali o dimensioni specificate che non permettono di inserire il contenuto nella dimensione della pagina richiesta. In tal caso possiamo definire cosa fare (ad esempio quando la dimensione del contenuto non si adatta alla dimensione iniziale della pagina del PDF risultante). |

### EpubLoadOptions {#EpubLoadOptions--}
```
public EpubLoadOptions()
```

Crea le opzioni di caricamento predefinite per la conversione di un file EPUB in documento PDF. Dimensione predefinita della pagina PDF - A4 300dpi 2480 × 3508.

### EpubLoadOptions {#EpubLoadOptions-java.awt.geom.Dimension2D-}
Crea le opzioni di caricamento predefinite per la conversione di un file EPUB in documento PDF. Dimensione predefinita della pagina PDF - A4 300dpi 2480 × 3508.

### getCustomCss {#getCustomCss--}
```
public final String getCustomCss()
```

Ottiene o imposta il Css personalizzato da applicare all'apertura del documento Epub.

**Returns:**
valore String

### getEngineType {#getEngineType--}
```
public EpubLoadOptions.EngineType getEngineType()
```

Seleziona il tipo di motore per la conversione da EPUB a PDF. L'impostazione predefinita è EngineType.NEW

**Returns:**
Elemento EngineType

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Ottiene un riferimento all'oggetto che rappresenta le informazioni di margine.

**Returns:**
Oggetto MarginInfo

### getMarginsAreaUsageMode {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```

Rappresenta la modalità di utilizzo dell'area dei margini - definisce il trattamento delle istruzioni (se presenti) del CSS del documento importato relative all'uso dei margini.

**Returns:**
Valore MarginsAreaUsageModes @see MarginsAreaUsageModes

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Ottiene la dimensione della pagina di output per l'importazione.

**Returns:**
Oggetto Dimension2D

### getPageSizeAdjustmentMode {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```

ATTENZIONE! La funzionalità è stata implementata ma non è ancora stata resa disponibile nell'API pubblica a causa di un problema bloccante nel livello OSHARED rilevato per il documento di esempio. Rappresenta la modalità di utilizzo della dimensione della pagina durante la conversione. I formati (come HTML, EPUB, ecc.) solitamente hanno un layout fluido, quindi consentono di adattare la dimensione della pagina richiesta. Tuttavia, a volte il contenuto ha posizioni orizzontali o dimensioni specificate che non permettono di inserire il contenuto nella dimensione della pagina richiesta. In tal caso possiamo definire cosa fare (ad esempio quando la dimensione del contenuto non si adatta alla dimensione iniziale della pagina del PDF risultante).

**Returns:**
Valore PageSizeAdjustmentModes @see PageSizeAdjustmentModes

### setCustomCss {#setCustomCss-java.lang.String-}
Ottiene o imposta il Css personalizzato da applicare all'apertura del documento Epub.

### setEngineType {#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-}
Seleziona il tipo di motore per la conversione da EPUB a PDF. L'impostazione predefinita è EngineType.NEW

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Ottiene un riferimento all'oggetto che rappresenta le informazioni di margine.

### setMarginsAreaUsageMode {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```

Rappresenta la modalità di utilizzo dell'area dei margini - definisce il trattamento delle istruzioni (se presenti) del CSS del documento importato relative all'uso dei margini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| marginsAreaUsageMode |  | Valore MarginsAreaUsageModes @see MarginsAreaUsageModes |

### setPageSizeAdjustmentMode {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```

ATTENZIONE! La funzionalità è stata implementata ma non è ancora stata resa disponibile nell'API pubblica a causa di un problema bloccante nel livello OSHARED rilevato per il documento di esempio. Rappresenta la modalità di utilizzo della dimensione della pagina durante la conversione. I formati (come HTML, EPUB, ecc.) solitamente hanno un layout fluido, quindi consentono di adattare la dimensione della pagina richiesta. Tuttavia, a volte il contenuto ha posizioni orizzontali o dimensioni specificate che non permettono di inserire il contenuto nella dimensione della pagina richiesta. In tal caso possiamo definire cosa fare (ad esempio quando la dimensione del contenuto non si adatta alla dimensione iniziale della pagina del PDF risultante).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageSizeAdjustmentMode |  | Valore PageSizeAdjustmentModes @see PageSizeAdjustmentModes |
