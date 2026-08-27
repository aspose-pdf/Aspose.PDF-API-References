---
title: "XpsSaveOptions"
linktitle: "XpsSaveOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Spara alternativ för export till Xps-format"
type: docs
weight: 5770
url: /sv/java/com.aspose.pdf/xpssaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.XpsSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class XpsSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Spara alternativ för export till Xps-format

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XpsSaveOptions](#XpsSaveOptions--) | Konstruktör |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet. |
| [getDefaultFont](#getDefaultFont--) | Hämtar/sätter standardteckensnittets namn. Används om det inbäddade teckensnittets namn inte hittas i systemet. |
| [getSaveTransparentTexts](#getSaveTransparentTexts--) | Indikerar om transparent (OCR:ad) text ska bevaras. |
| [getUseEmbeddedTrueTypeFonts](#getUseEmbeddedTrueTypeFonts--) | Hämtar/sätter flaggan för att använda inbäddade TrueType-teckensnitt. Att undvika användning av inbäddade TrueType-teckensnitt kan minska konverteringstiden. |
| [isUseNewImagingEngine](#isUseNewImagingEngine--) | Hämtar eller sätter alternativet UseNewImagingEngine. |
| [setBatchSize](#setBatchSize-int-) | Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet. |
| [setDefaultFont](#setDefaultFont-java.lang.String-) | Hämtar/sätter standardteckensnittets namn. Används om det inbäddade teckensnittets namn inte hittas i systemet. |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Indikerar om transparent (OCR:ad) text ska bevaras. |
| [setUseEmbeddedTrueTypeFonts](#setUseEmbeddedTrueTypeFonts-boolean-) | Hämtar/sätter flaggan för att använda inbäddade TrueType-teckensnitt. Att undvika användning av inbäddade TrueType-teckensnitt kan minska konverteringstiden. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Hämtar eller sätter alternativet UseNewImagingEngine. |

### XpsSaveOptions {#XpsSaveOptions--}
```
public XpsSaveOptions()
```

Konstruktör

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet.

**Returns:**
int‑värde

### getDefaultFont {#getDefaultFont--}
```
public final String getDefaultFont()
```

Hämtar/sätter standardteckensnittets namn. Används om det inbäddade teckensnittets namn inte hittas i systemet.

**Returns:**
String värde

### getSaveTransparentTexts {#getSaveTransparentTexts--}
```
public final boolean getSaveTransparentTexts()
```

Indikerar om transparent (OCR:ad) text ska bevaras.

**Returns:**
booleskt värde

### getUseEmbeddedTrueTypeFonts {#getUseEmbeddedTrueTypeFonts--}
```
public final boolean getUseEmbeddedTrueTypeFonts()
```

Hämtar/sätter flaggan för att använda inbäddade TrueType-teckensnitt. Att undvika användning av inbäddade TrueType-teckensnitt kan minska konverteringstiden.

**Returns:**
booleskt värde

### isUseNewImagingEngine {#isUseNewImagingEngine--}
```
@Deprecated public final boolean isUseNewImagingEngine()
```

Hämtar eller sätter alternativet UseNewImagingEngine.

**Returns:**
booleskt värde @deprecated UseNewImagingEngine är föråldrat

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setDefaultFont {#setDefaultFont-java.lang.String-}
Hämtar/sätter standardteckensnittets namn. Används om det inbäddade teckensnittets namn inte hittas i systemet.

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public final void setSaveTransparentTexts(boolean value)
```

Indikerar om transparent (OCR:ad) text ska bevaras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUseEmbeddedTrueTypeFonts {#setUseEmbeddedTrueTypeFonts-boolean-}
```
public final void setUseEmbeddedTrueTypeFonts(boolean value)
```

Hämtar/sätter flaggan för att använda inbäddade TrueType-teckensnitt. Att undvika användning av inbäddade TrueType-teckensnitt kan minska konverteringstiden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public final void setUseNewImagingEngine(boolean value)
```

Hämtar eller sätter alternativet UseNewImagingEngine.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde @deprecated UseNewImagingEngine är föråldrat |
