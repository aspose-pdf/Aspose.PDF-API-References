---
title: "SvgLoadOptions"
linktitle: "SvgLoadOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Optionen zum Laden/Importieren einer SVG‑Datei in ein PDF‑Dokument dar."
type: docs
weight: 4700
url: /de/java/com.aspose.pdf/svgloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.SvgLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.SvgLoadOptions

```
public final class SvgLoadOptions extends LoadOptions
```

Stellt Optionen zum Laden/Importieren einer SVG‑Datei in ein PDF‑Dokument dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SvgLoadOptions](#SvgLoadOptions--) | Erstellt ein {@code SvgLoadOptions}-Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getConversionEngine](#getConversionEngine--) | Ermöglicht die Auswahl der Konvertierungs-Engine, die während der Konvertierung verwendet wird. Derzeit befindet sich die neue Engine in der B‑Testing‑Phase, daher wird dieser Wert standardmäßig auf ConversionEngines.LegacyEngine gesetzt. |
| [getPageInfo](#getPageInfo--) | Liest die Seiteninformationen, die beim Laden des Dokuments angewendet werden sollen. |
| [isAdjustPageSize](#isAdjustPageSize--) | Passt die PDF‑Seitengröße an die SVG‑Größe an. |
| [setAdjustPageSize](#setAdjustPageSize-boolean-) | Passt die PDF‑Seitengröße an die SVG‑Größe an. |
| [setConversionEngine](#setConversionEngine-int-) | Ermöglicht die Auswahl der Konvertierungs-Engine, die während der Konvertierung verwendet wird. Derzeit befindet sich die neue Engine in der B‑Testing‑Phase, daher wird dieser Wert standardmäßig auf ConversionEngines.LegacyEngine gesetzt. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Setzt die Seiteninformationen, die beim Laden des Dokuments angewendet werden sollen. |

### SvgLoadOptions {#SvgLoadOptions--}
```
public SvgLoadOptions()
```

Erstellt ein {@code SvgLoadOptions}-Objekt.

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Ermöglicht die Auswahl der Konvertierungs-Engine, die während der Konvertierung verwendet wird. Derzeit befindet sich die neue Engine in der B‑Testing‑Phase, daher wird dieser Wert standardmäßig auf ConversionEngines.LegacyEngine gesetzt.

**Returns:**
ConversionEngines element @see ConversionEngines

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Liest die Seiteninformationen, die beim Laden des Dokuments angewendet werden sollen.

**Returns:**
PageInfo‑Objekt

### isAdjustPageSize {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```

Passt die PDF‑Seitengröße an die SVG‑Größe an.

**Returns:**
boolescher Wert

### setAdjustPageSize {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```

Passt die PDF‑Seitengröße an die SVG‑Größe an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Ermöglicht die Auswahl der Konvertierungs-Engine, die während der Konvertierung verwendet wird. Derzeit befindet sich die neue Engine in der B‑Testing‑Phase, daher wird dieser Wert standardmäßig auf ConversionEngines.LegacyEngine gesetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| conversionEngine |  | ConversionEngines element @see ConversionEngines |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Setzt die Seiteninformationen, die beim Laden des Dokuments angewendet werden sollen.
