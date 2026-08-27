---
title: "PclLoadOptions"
linktitle: "PclLoadOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar alternativ för att ladda (importera) PCL‑fil till pdf‑dokument."
type: docs
weight: 3530
url: /sv/java/com.aspose.pdf/pclloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PclLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PclLoadOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

Representerar alternativ för att ladda (importera) PCL‑fil till pdf‑dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PclLoadOptions](#PclLoadOptions--) | Skapar {@code PclLoadOptions}-objekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet. |
| [getConversionEngine](#getConversionEngine--) | Definierar konverteringsmotor som kommer att användas för konvertering |
| [getExceptions](#getExceptions--) | Lista över konverteringsfel. |
| [isSupressErrors](#isSupressErrors--) | Hämtar eller anger booleskt värde som indikerar om PCL‑konverteringsfel ska undertryckas. |
| [setBatchSize](#setBatchSize-int-) | Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet. |
| [setConversionEngine](#setConversionEngine-int-) | Definierar konverteringsmotor som kommer att användas för konvertering |
| [setSupressErrors](#setSupressErrors-boolean-) | Hämtar eller anger booleskt värde som indikerar om PCL‑konverteringsfel ska undertryckas. |

### PclLoadOptions {#PclLoadOptions--}
```
public PclLoadOptions()
```

Skapar {@code PclLoadOptions}-objekt.

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet.

**Returns:**
int‑värde

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Definierar konverteringsmotor som kommer att användas för konvertering

**Returns:**
ConversionEngines‑element @see ConversionEngines

### getExceptions {#getExceptions--}
```
public List < Exception > getExceptions()
```

Lista över konverteringsfel.

**Returns:**
Lista över undantag

### isSupressErrors {#isSupressErrors--}
```
public boolean isSupressErrors()
```

Hämtar eller anger booleskt värde som indikerar om PCL‑konverteringsfel ska undertryckas.

**Returns:**
booleskt värde

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Definierar konverteringsmotor som kommer att användas för konvertering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| conversionEngine |  | ConversionEngines‑element @see ConversionEngines |

### setSupressErrors {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```

Hämtar eller anger booleskt värde som indikerar om PCL‑konverteringsfel ska undertryckas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| supressErrors |  | booleskt värde |
