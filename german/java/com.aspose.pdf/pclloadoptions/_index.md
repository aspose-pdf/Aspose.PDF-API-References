---
title: "PclLoadOptions"
linktitle: "PclLoadOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Optionen für das Laden (Import) einer PCL-Datei in ein PDF-Dokument dar."
type: docs
weight: 3530
url: /de/java/com.aspose.pdf/pclloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PclLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PclLoadOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

Stellt Optionen für das Laden (Import) einer PCL-Datei in ein PDF-Dokument dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PclLoadOptions](#PclLoadOptions--) | Erstellt ein {@code PclLoadOptions}-Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist. |
| [getConversionEngine](#getConversionEngine--) | Definiert die Konvertierungs-Engine, die für die Konvertierung verwendet wird. |
| [getExceptions](#getExceptions--) | Liste der Konvertierungsfehler. |
| [isSupressErrors](#isSupressErrors--) | Liest oder setzt den booleschen Wert, der angibt, ob PCL-Konvertierungsfehler unterdrückt werden sollen. |
| [setBatchSize](#setBatchSize-int-) | Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist. |
| [setConversionEngine](#setConversionEngine-int-) | Definiert die Konvertierungs-Engine, die für die Konvertierung verwendet wird. |
| [setSupressErrors](#setSupressErrors-boolean-) | Liest oder setzt den booleschen Wert, der angibt, ob PCL-Konvertierungsfehler unterdrückt werden sollen. |

### PclLoadOptions {#PclLoadOptions--}
```
public PclLoadOptions()
```

Erstellt ein {@code PclLoadOptions}-Objekt.

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist.

**Returns:**
int-Wert

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Definiert die Konvertierungs-Engine, die für die Konvertierung verwendet wird.

**Returns:**
ConversionEngines element @see ConversionEngines

### getExceptions {#getExceptions--}
```
public List < Exception > getExceptions()
```

Liste der Konvertierungsfehler.

**Returns:**
Liste der Ausnahmen

### isSupressErrors {#isSupressErrors--}
```
public boolean isSupressErrors()
```

Liest oder setzt den booleschen Wert, der angibt, ob PCL-Konvertierungsfehler unterdrückt werden sollen.

**Returns:**
boolescher Wert

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Definiert die Konvertierungs-Engine, die für die Konvertierung verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| conversionEngine |  | ConversionEngines element @see ConversionEngines |

### setSupressErrors {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```

Liest oder setzt den booleschen Wert, der angibt, ob PCL-Konvertierungsfehler unterdrückt werden sollen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| supressErrors |  | boolescher Wert |
