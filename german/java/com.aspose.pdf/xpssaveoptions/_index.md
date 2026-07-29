---
title: "XpsSaveOptions"
linktitle: "XpsSaveOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Speicheroptionen für den Export ins XPS‑Format"
type: docs
weight: 5770
url: /de/java/com.aspose.pdf/xpssaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.XpsSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class XpsSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Speicheroptionen für den Export ins XPS‑Format

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XpsSaveOptions](#XpsSaveOptions--) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist. |
| [getDefaultFont](#getDefaultFont--) | Liest/legt den Standard-Schriftartnamen fest. Wird verwendet, wenn der eingebettete Schriftartname im System nicht gefunden wird. |
| [getSaveTransparentTexts](#getSaveTransparentTexts--) | Gibt an, ob transparenter (OCR‑erzeugter) Text erhalten bleiben soll. |
| [getUseEmbeddedTrueTypeFonts](#getUseEmbeddedTrueTypeFonts--) | Liest/legt das Flag fest, eingebettete TrueType‑Schriften zu verwenden. Das Vermeiden der Verwendung eingebetteter TrueType‑Schriften kann die Konvertierungszeit verkürzen. |
| [isUseNewImagingEngine](#isUseNewImagingEngine--) | Liest oder legt die Option UseNewImagingEngine fest. |
| [setBatchSize](#setBatchSize-int-) | Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist. |
| [setDefaultFont](#setDefaultFont-java.lang.String-) | Liest/legt den Standard-Schriftartnamen fest. Wird verwendet, wenn der eingebettete Schriftartname im System nicht gefunden wird. |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Gibt an, ob transparenter (OCR‑erzeugter) Text erhalten bleiben soll. |
| [setUseEmbeddedTrueTypeFonts](#setUseEmbeddedTrueTypeFonts-boolean-) | Liest/legt das Flag fest, eingebettete TrueType‑Schriften zu verwenden. Das Vermeiden der Verwendung eingebetteter TrueType‑Schriften kann die Konvertierungszeit verkürzen. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Liest oder legt die Option UseNewImagingEngine fest. |

### XpsSaveOptions {#XpsSaveOptions--}
```
public XpsSaveOptions()
```

Konstruktor

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist.

**Returns:**
int-Wert

### getDefaultFont {#getDefaultFont--}
```
public final String getDefaultFont()
```

Liest/legt den Standard-Schriftartnamen fest. Wird verwendet, wenn der eingebettete Schriftartname im System nicht gefunden wird.

**Returns:**
String Wert

### getSaveTransparentTexts {#getSaveTransparentTexts--}
```
public final boolean getSaveTransparentTexts()
```

Gibt an, ob transparenter (OCR‑erzeugter) Text erhalten bleiben soll.

**Returns:**
boolescher Wert

### getUseEmbeddedTrueTypeFonts {#getUseEmbeddedTrueTypeFonts--}
```
public final boolean getUseEmbeddedTrueTypeFonts()
```

Liest/legt das Flag fest, eingebettete TrueType‑Schriften zu verwenden. Das Vermeiden der Verwendung eingebetteter TrueType‑Schriften kann die Konvertierungszeit verkürzen.

**Returns:**
boolescher Wert

### isUseNewImagingEngine {#isUseNewImagingEngine--}
```
@Deprecated public final boolean isUseNewImagingEngine()
```

Liest oder legt die Option UseNewImagingEngine fest.

**Returns:**
boolescher Wert @deprecated UseNewImagingEngine ist veraltet

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setDefaultFont {#setDefaultFont-java.lang.String-}
Liest/legt den Standard-Schriftartnamen fest. Wird verwendet, wenn der eingebettete Schriftartname im System nicht gefunden wird.

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public final void setSaveTransparentTexts(boolean value)
```

Gibt an, ob transparenter (OCR‑erzeugter) Text erhalten bleiben soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUseEmbeddedTrueTypeFonts {#setUseEmbeddedTrueTypeFonts-boolean-}
```
public final void setUseEmbeddedTrueTypeFonts(boolean value)
```

Liest/legt das Flag fest, eingebettete TrueType‑Schriften zu verwenden. Das Vermeiden der Verwendung eingebetteter TrueType‑Schriften kann die Konvertierungszeit verkürzen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public final void setUseNewImagingEngine(boolean value)
```

Liest oder legt die Option UseNewImagingEngine fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert @deprecated UseNewImagingEngine ist veraltet |
