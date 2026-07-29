---
title: "TextExtractionOptions"
linktitle: "TextExtractionOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le opzioni di estrazione del testo"
type: docs
weight: 5060
url: /it/java/com.aspose.pdf/textextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextExtractionOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextExtractionOptions

```
public final class TextExtractionOptions extends TextOptions
```

Rappresenta le opzioni di estrazione del testo

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextExtractionOptions](#TextExtractionOptions-int-) | Inizializza una nuova istanza dell'oggetto {@code TextExtractionOptions} per la modalità di formattazione del testo specificata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormattingMode](#getFormattingMode--) | Ottiene la modalità di formattazione. |
| [getScaleFactor](#getScaleFactor--) | Ottiene il fattore che verrà applicato per scalare la dimensione del font durante l'estrazione in modalità pura. Impostare un valore più basso porta a più spazi nel testo estratto. Il valore predefinito è 1 - nessuna scalatura; impostare il valore a zero consente all'algoritmo di scegliere automaticamente la scalatura. |
| [setFormattingMode](#setFormattingMode-int-) | Imposta la modalità di formattazione. |
| [setScaleFactor](#setScaleFactor-double-) | Imposta il fattore che verrà applicato per scalare la dimensione del font durante l'estrazione in modalità pura. Impostare un valore più basso porta a più spazi nel testo estratto (da 1 a 10). Il valore predefinito è 1 - nessuna scalatura; impostare il valore a zero consente all'algoritmo di scegliere automaticamente la scalatura. |

### TextExtractionOptions {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```

Inizializza una nuova istanza dell'oggetto {@code TextExtractionOptions} per la modalità di formattazione del testo specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formattingMode |  | Valore della modalità di formattazione del testo. @see TextFormattingMode |

### getFormattingMode {#getFormattingMode--}
```
public int getFormattingMode()
```

Ottiene la modalità di formattazione.

**Returns:**
Valore TextFormattingMode @see TextFormattingMode

### getScaleFactor {#getScaleFactor--}
```
public double getScaleFactor()
```

Ottiene il fattore che verrà applicato per scalare la dimensione del font durante l'estrazione in modalità pura. Impostare un valore più basso porta a più spazi nel testo estratto. Il valore predefinito è 1 - nessuna scalatura; impostare il valore a zero consente all'algoritmo di scegliere automaticamente la scalatura.

**Returns:**
valore double

### setFormattingMode {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```

Imposta la modalità di formattazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore TextFormattingMode @see TextFormattingMode |

### setScaleFactor {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```

Imposta il fattore che verrà applicato per scalare la dimensione del font durante l'estrazione in modalità pura. Impostare un valore più basso porta a più spazi nel testo estratto (da 1 a 10). Il valore predefinito è 1 - nessuna scalatura; impostare il valore a zero consente all'algoritmo di scegliere automaticamente la scalatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |
