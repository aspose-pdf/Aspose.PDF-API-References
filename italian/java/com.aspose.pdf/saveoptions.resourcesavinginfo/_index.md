---
title: "SaveOptions.ResourceSavingInfo"
linktitle: "SaveOptions.ResourceSavingInfo"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa classe rappresenta un insieme di dati relativi al salvataggio di file di risorse esterne che si verifica durante la conversione di PDF in altri formati (ad es. HTML)."
type: docs
weight: 4440
url: /it/java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo

```
public static class SaveOptions.ResourceSavingInfo extends Object
```

Questa classe rappresenta un insieme di dati relativi al salvataggio di file di risorse esterne che si verifica durante la conversione di PDF in altri formati (ad es. HTML).

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getContentStream](#getContentStream--) | Impostato dal convertitore. Rappresenta il contenuto binario del file salvato. |
| [getResourceType](#getResourceType--) | Impostato dal convertitore. Nome file previsto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare quel file. |
| [getSupposedFileName](#getSupposedFileName--) | Impostato dal convertitore. Nome file previsto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare quel file. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Questo flag deve essere impostato su \"true\" nel codice personalizzato se, per qualche motivo, il file proposto dovrebbe essere elaborato non dal codice personalizzato ma dal codice del convertitore stesso, nel modo standard per il convertitore. Quindi, impostarlo su true significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo autonomamente (in entrambi i sensi - per il salvataggio da qualche parte e per la denominazione nel file di riferimento). |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Questo flag deve essere impostato su \"true\" nel codice personalizzato se, per qualche motivo, il file proposto dovrebbe essere elaborato non dal codice personalizzato ma dal codice del convertitore stesso, nel modo standard per il convertitore. Quindi, impostarlo su true significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo autonomamente (in entrambi i sensi - per il salvataggio da qualche parte e per la denominazione nel file di riferimento). |

### getContentStream {#getContentStream--}
```
public byte[] getContentStream()
```

Impostato dal convertitore. Rappresenta il contenuto binario del file salvato.

**Returns:**
array di byte

### getResourceType {#getResourceType--}
```
public SaveOptions.NodeLevelResourceType getResourceType()
```

Impostato dal convertitore. Nome file previsto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare quel file.

**Returns:**
Elemento NodeLevelResourceType @see NodeLevelResourceType

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Impostato dal convertitore. Nome file previsto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare quel file.

**Returns:**
valore String

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Questo flag deve essere impostato su \"true\" nel codice personalizzato se, per qualche motivo, il file proposto dovrebbe essere elaborato non dal codice personalizzato ma dal codice del convertitore stesso, nel modo standard per il convertitore. Quindi, impostarlo su true significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo autonomamente (in entrambi i sensi - per il salvataggio da qualche parte e per la denominazione nel file di riferimento).

**Returns:**
valore booleano

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Questo flag deve essere impostato su \"true\" nel codice personalizzato se, per qualche motivo, il file proposto dovrebbe essere elaborato non dal codice personalizzato ma dal codice del convertitore stesso, nel modo standard per il convertitore. Quindi, impostarlo su true significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo autonomamente (in entrambi i sensi - per il salvataggio da qualche parte e per la denominazione nel file di riferimento).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| customProcessingCancelled |  | valore booleano |
