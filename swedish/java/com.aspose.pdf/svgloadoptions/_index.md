---
title: "SvgLoadOptions"
linktitle: "SvgLoadOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar alternativ för att ladda/importera SVG-fil till PDF-dokument."
type: docs
weight: 4700
url: /sv/java/com.aspose.pdf/svgloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.SvgLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.SvgLoadOptions

```
public final class SvgLoadOptions extends LoadOptions
```

Representerar alternativ för att ladda/importera SVG-fil till PDF-dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SvgLoadOptions](#SvgLoadOptions--) | Skapar {@code SvgLoadOptions} objekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getConversionEngine](#getConversionEngine--) | Tillåter att välja konverteringsmotor som kommer att användas under konverteringen. Den nya motorn är för närvarande i B-testningsstadiet, så detta värde är som standard satt till ConversionEngines.LegacyEngine |
| [getPageInfo](#getPageInfo--) | Hämtar sidinformation som ska tillämpas vid inläsning av dokumentet. |
| [isAdjustPageSize](#isAdjustPageSize--) | Justera PDF-sidans storlek till SVG-storlek |
| [setAdjustPageSize](#setAdjustPageSize-boolean-) | Justera PDF-sidans storlek till SVG-storlek |
| [setConversionEngine](#setConversionEngine-int-) | Tillåter att välja konverteringsmotor som kommer att användas under konverteringen. Den nya motorn är för närvarande i B-testningsstadiet, så detta värde är som standard satt till ConversionEngines.LegacyEngine |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Ställer in sidinformation som ska tillämpas vid inläsning av dokumentet. |

### SvgLoadOptions {#SvgLoadOptions--}
```
public SvgLoadOptions()
```

Skapar {@code SvgLoadOptions} objekt.

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Tillåter att välja konverteringsmotor som kommer att användas under konverteringen. Den nya motorn är för närvarande i B-testningsstadiet, så detta värde är som standard satt till ConversionEngines.LegacyEngine

**Returns:**
ConversionEngines‑element @see ConversionEngines

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Hämtar sidinformation som ska tillämpas vid inläsning av dokumentet.

**Returns:**
PageInfo-objekt

### isAdjustPageSize {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```

Justera PDF-sidans storlek till SVG-storlek

**Returns:**
booleskt värde

### setAdjustPageSize {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```

Justera PDF-sidans storlek till SVG-storlek

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Tillåter att välja konverteringsmotor som kommer att användas under konverteringen. Den nya motorn är för närvarande i B-testningsstadiet, så detta värde är som standard satt till ConversionEngines.LegacyEngine

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| conversionEngine |  | ConversionEngines‑element @see ConversionEngines |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Ställer in sidinformation som ska tillämpas vid inläsning av dokumentet.
