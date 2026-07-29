---
title: "SaveOptions"
linktitle: "SaveOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Il tipo SaveOptions mantiene il livello di astrazione sulle singole opzioni di salvataggio."
type: docs
weight: 4370
url: /it/java/com.aspose.pdf/saveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions

```
public abstract class SaveOptions extends Object
```

Il tipo SaveOptions mantiene il livello di astrazione sulle singole opzioni di salvataggio.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSaveFormat](#getSaveFormat--) | Formato di salvataggio dei dati. |
| [getWarningHandler](#getWarningHandler--) | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione di salvataggio continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di salvataggio deve terminare. |
| [isCacheGlyphs](#isCacheGlyphs--) | Ottiene o imposta il valore booleano che indica se i glifi dei font saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione PDF in altri formati ma aumenta il consumo di memoria. |
| [isCloseResponse](#isCloseResponse--) | Ottiene il valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [setCacheGlyphs](#setCacheGlyphs-boolean-) | Ottiene o imposta il valore booleano che indica se i glifi dei font saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione PDF in altri formati ma aumenta il consumo di memoria. |
| [setCloseResponse](#setCloseResponse-boolean-) | Imposta il valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione di salvataggio continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di salvataggio deve terminare. |

### getSaveFormat {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```

Formato di salvataggio dei dati.

**Returns:**
Valore SaveFormat @see SaveFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione di salvataggio continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di salvataggio deve terminare.

**Returns:**
Valore IWarningCallback

### isCacheGlyphs {#isCacheGlyphs--}
```
public final boolean isCacheGlyphs()
```

Ottiene o imposta il valore booleano che indica se i glifi dei font saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione PDF in altri formati ma aumenta il consumo di memoria.

**Returns:**
valore booleano

### isCloseResponse {#isCloseResponse--}
```
public boolean isCloseResponse()
```

Ottiene il valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta.

**Returns:**
valore booleano

### setCacheGlyphs {#setCacheGlyphs-boolean-}
```
public final void setCacheGlyphs(boolean value)
```

Ottiene o imposta il valore booleano che indica se i glifi dei font saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione PDF in altri formati ma aumenta il consumo di memoria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setCloseResponse {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```

Imposta il valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione di salvataggio continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di salvataggio deve terminare.
