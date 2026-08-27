---
title: "PclLoadOptions"
linktitle: "PclLoadOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le opzioni per il caricamento (import) di file PCL in un documento pdf."
type: docs
weight: 3530
url: /it/java/com.aspose.pdf/pclloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PclLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PclLoadOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

Rappresenta le opzioni per il caricamento (import) di file PCL in un documento pdf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PclLoadOptions](#PclLoadOptions--) | Crea l'oggetto {@code PclLoadOptions}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione. |
| [getConversionEngine](#getConversionEngine--) | Definisce il motore di conversione che verrà utilizzato per la conversione |
| [getExceptions](#getExceptions--) | Elenco degli errori di conversione. |
| [isSupressErrors](#isSupressErrors--) | Ottiene o imposta il valore booleano che indica se gli errori di conversione PCL devono essere soppressi. |
| [setBatchSize](#setBatchSize-int-) | Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione. |
| [setConversionEngine](#setConversionEngine-int-) | Definisce il motore di conversione che verrà utilizzato per la conversione |
| [setSupressErrors](#setSupressErrors-boolean-) | Ottiene o imposta il valore booleano che indica se gli errori di conversione PCL devono essere soppressi. |

### PclLoadOptions {#PclLoadOptions--}
```
public PclLoadOptions()
```

Crea l'oggetto {@code PclLoadOptions}.

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione.

**Returns:**
valore int

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Definisce il motore di conversione che verrà utilizzato per la conversione

**Returns:**
Elemento ConversionEngines @see ConversionEngines

### getExceptions {#getExceptions--}
```
public List < Exception > getExceptions()
```

Elenco degli errori di conversione.

**Returns:**
Elenco delle eccezioni

### isSupressErrors {#isSupressErrors--}
```
public boolean isSupressErrors()
```

Ottiene o imposta il valore booleano che indica se gli errori di conversione PCL devono essere soppressi.

**Returns:**
valore booleano

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Definisce il motore di conversione che verrà utilizzato per la conversione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| conversionEngine |  | Elemento ConversionEngines @see ConversionEngines |

### setSupressErrors {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```

Ottiene o imposta il valore booleano che indica se gli errori di conversione PCL devono essere soppressi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| supressErrors |  | valore booleano |
