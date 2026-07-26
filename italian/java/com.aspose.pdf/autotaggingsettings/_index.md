---
title: "AutoTaggingSettings"
linktitle: "AutoTaggingSettings"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Fornisce impostazioni per la funzionalità di auto‑tagging nei documenti PDF. La classe {@link AutoTaggingSettings} consente di configurare le opzioni per il tagging automatico del contenuto PDF. Essa."
type: docs
weight: 230
url: /it/java/com.aspose.pdf/autotaggingsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AutoTaggingSettings

```
public final class AutoTaggingSettings extends Object
```

Fornisce impostazioni per la funzionalità di auto-tagging nei documenti PDF. La classe {@link AutoTaggingSettings} consente di configurare le opzioni per il tagging automatico del contenuto PDF. Include proprietà per abilitare o disabilitare l'auto-tagging, specificare una strategia per il riconoscimento dei titoli e definire i livelli dei titoli in base alle dimensioni dei caratteri.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AutoTaggingSettings](#AutoTaggingSettings--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDefault](#getDefault--) | Ottiene le impostazioni predefinite per la funzionalità di auto‑tagging nei documenti PDF. Le impostazioni predefinite abilitano l'auto‑tagging e utilizzano la strategia automatica per il riconoscimento delle intestazioni. Queste impostazioni possono essere utilizzate come configurazione di base per la conversione di formati PDF o altre operazioni che richiedono il tagging automatico del contenuto PDF. |
| [getEnableAutoTagging](#getEnableAutoTagging--) | Ottiene o imposta un valore che indica se la funzionalità di auto‑tagging è abilitata. Quando è abilitata, la funzionalità di auto‑tagging genera automaticamente contenuti taggati per il documento PDF, il che può migliorare l'accessibilità e la struttura. |
| [getHeadingLevels](#getHeadingLevels--) | Ottiene o imposta i livelli di intestazione utilizzati per determinare la struttura delle intestazioni in un documento PDF. La proprietà {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) consente di configurare la mappatura delle dimensioni dei caratteri ai livelli di intestazione. Questo viene utilizzato durante il processo di auto‑tagging per identificare e assegnare i livelli di intestazione appropriati in base alla dimensione del carattere degli elementi di testo nel documento. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Ottiene o imposta la strategia utilizzata per riconoscere le intestazioni nel documento durante l'auto-etichettatura. La proprietà {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) determina come le intestazioni sono identificate nel documento. Le strategie disponibili includono il riconoscimento delle intestazioni basato su contorni, analisi euristica o rilevamento automatico. Impostare questa proprietà su {@link HeadingRecognitionStrategy#None} disabilita il riconoscimento delle intestazioni. |
| [setEnableAutoTagging](#setEnableAutoTagging-boolean-) | Ottiene o imposta un valore che indica se la funzionalità di auto‑tagging è abilitata. Quando è abilitata, la funzionalità di auto‑tagging genera automaticamente contenuti taggati per il documento PDF, il che può migliorare l'accessibilità e la struttura. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Ottiene o imposta i livelli di intestazione utilizzati per determinare la struttura delle intestazioni in un documento PDF. La proprietà {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) consente di configurare la mappatura delle dimensioni dei caratteri ai livelli di intestazione. Questo viene utilizzato durante il processo di auto‑tagging per identificare e assegnare i livelli di intestazione appropriati in base alla dimensione del carattere degli elementi di testo nel documento. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Ottiene o imposta la strategia utilizzata per riconoscere le intestazioni nel documento durante l'auto-etichettatura. La proprietà {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) determina come le intestazioni sono identificate nel documento. Le strategie disponibili includono il riconoscimento delle intestazioni basato su contorni, analisi euristica o rilevamento automatico. Impostare questa proprietà su {@link HeadingRecognitionStrategy#None} disabilita il riconoscimento delle intestazioni. |

### AutoTaggingSettings {#AutoTaggingSettings--}
```
public AutoTaggingSettings()
```



### getDefault {#getDefault--}
```
public static AutoTaggingSettings getDefault()
```

Ottiene le impostazioni predefinite per la funzionalità di auto‑tagging nei documenti PDF. Le impostazioni predefinite abilitano l'auto‑tagging e utilizzano la strategia automatica per il riconoscimento delle intestazioni. Queste impostazioni possono essere utilizzate come configurazione di base per la conversione di formati PDF o altre operazioni che richiedono il tagging automatico del contenuto PDF.

**Returns:**
istanza AutoTaggingSettings

### getEnableAutoTagging {#getEnableAutoTagging--}
```
public final boolean getEnableAutoTagging()
```

Ottiene o imposta un valore che indica se la funzionalità di auto‑tagging è abilitata. Quando è abilitata, la funzionalità di auto‑tagging genera automaticamente contenuti taggati per il documento PDF, il che può migliorare l'accessibilità e la struttura.

**Returns:**
valore booleano

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Ottiene o imposta i livelli di intestazione utilizzati per determinare la struttura delle intestazioni in un documento PDF. La proprietà {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) consente di configurare la mappatura delle dimensioni dei caratteri ai livelli di intestazione. Questo viene utilizzato durante il processo di auto‑tagging per identificare e assegnare i livelli di intestazione appropriati in base alla dimensione del carattere degli elementi di testo nel documento.

**Returns:**
Istanza HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Ottiene o imposta la strategia utilizzata per riconoscere le intestazioni nel documento durante l'auto-etichettatura. La proprietà {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) determina come le intestazioni sono identificate nel documento. Le strategie disponibili includono il riconoscimento delle intestazioni basato su contorni, analisi euristica o rilevamento automatico. Impostare questa proprietà su {@link HeadingRecognitionStrategy#None} disabilita il riconoscimento delle intestazioni.

**Returns:**
Elemento HeadingRecognitionStrategy

### setEnableAutoTagging {#setEnableAutoTagging-boolean-}
```
public final void setEnableAutoTagging(boolean value)
```

Ottiene o imposta un valore che indica se la funzionalità di auto‑tagging è abilitata. Quando è abilitata, la funzionalità di auto‑tagging genera automaticamente contenuti taggati per il documento PDF, il che può migliorare l'accessibilità e la struttura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Ottiene o imposta i livelli di intestazione utilizzati per determinare la struttura delle intestazioni in un documento PDF. La proprietà {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) consente di configurare la mappatura delle dimensioni dei caratteri ai livelli di intestazione. Questo viene utilizzato durante il processo di auto‑tagging per identificare e assegnare i livelli di intestazione appropriati in base alla dimensione del carattere degli elementi di testo nel documento.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Ottiene o imposta la strategia utilizzata per riconoscere le intestazioni nel documento durante l'auto-etichettatura. La proprietà {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) determina come le intestazioni sono identificate nel documento. Le strategie disponibili includono il riconoscimento delle intestazioni basato su contorni, analisi euristica o rilevamento automatico. Impostare questa proprietà su {@link HeadingRecognitionStrategy#None} disabilita il riconoscimento delle intestazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento HeadingRecognitionStrategy |
