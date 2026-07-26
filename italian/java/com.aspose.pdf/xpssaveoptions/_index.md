---
title: "XpsSaveOptions"
linktitle: "XpsSaveOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Opzioni di salvataggio per l'esportazione al formato Xps"
type: docs
weight: 5770
url: /it/java/com.aspose.pdf/xpssaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.XpsSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class XpsSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Opzioni di salvataggio per l'esportazione al formato Xps

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XpsSaveOptions](#XpsSaveOptions--) | Costruttore |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione. |
| [getDefaultFont](#getDefaultFont--) | Ottiene/Imposta il nome del font predefinito. Utilizzato se il nome del font incorporato non viene trovato nel sistema. |
| [getSaveTransparentTexts](#getSaveTransparentTexts--) | Indica se preservare il testo trasparente (OCR). |
| [getUseEmbeddedTrueTypeFonts](#getUseEmbeddedTrueTypeFonts--) | Ottiene/Imposta il flag per utilizzare font TrueType incorporati. Evitare l'uso di font TrueType incorporati può ridurre il tempo di conversione. |
| [isUseNewImagingEngine](#isUseNewImagingEngine--) | Ottiene o imposta l'opzione UseNewImagingEngine. |
| [setBatchSize](#setBatchSize-int-) | Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione. |
| [setDefaultFont](#setDefaultFont-java.lang.String-) | Ottiene/Imposta il nome del font predefinito. Utilizzato se il nome del font incorporato non viene trovato nel sistema. |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Indica se preservare il testo trasparente (OCR). |
| [setUseEmbeddedTrueTypeFonts](#setUseEmbeddedTrueTypeFonts-boolean-) | Ottiene/Imposta il flag per utilizzare font TrueType incorporati. Evitare l'uso di font TrueType incorporati può ridurre il tempo di conversione. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Ottiene o imposta l'opzione UseNewImagingEngine. |

### XpsSaveOptions {#XpsSaveOptions--}
```
public XpsSaveOptions()
```

Costruttore

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione.

**Returns:**
valore int

### getDefaultFont {#getDefaultFont--}
```
public final String getDefaultFont()
```

Ottiene/Imposta il nome del font predefinito. Utilizzato se il nome del font incorporato non viene trovato nel sistema.

**Returns:**
valore String

### getSaveTransparentTexts {#getSaveTransparentTexts--}
```
public final boolean getSaveTransparentTexts()
```

Indica se preservare il testo trasparente (OCR).

**Returns:**
valore booleano

### getUseEmbeddedTrueTypeFonts {#getUseEmbeddedTrueTypeFonts--}
```
public final boolean getUseEmbeddedTrueTypeFonts()
```

Ottiene/Imposta il flag per utilizzare font TrueType incorporati. Evitare l'uso di font TrueType incorporati può ridurre il tempo di conversione.

**Returns:**
valore booleano

### isUseNewImagingEngine {#isUseNewImagingEngine--}
```
@Deprecated public final boolean isUseNewImagingEngine()
```

Ottiene o imposta l'opzione UseNewImagingEngine.

**Returns:**
valore booleano @deprecated UseNewImagingEngine è deprecato

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setDefaultFont {#setDefaultFont-java.lang.String-}
Ottiene/Imposta il nome del font predefinito. Utilizzato se il nome del font incorporato non viene trovato nel sistema.

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public final void setSaveTransparentTexts(boolean value)
```

Indica se preservare il testo trasparente (OCR).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUseEmbeddedTrueTypeFonts {#setUseEmbeddedTrueTypeFonts-boolean-}
```
public final void setUseEmbeddedTrueTypeFonts(boolean value)
```

Ottiene/Imposta il flag per utilizzare font TrueType incorporati. Evitare l'uso di font TrueType incorporati può ridurre il tempo di conversione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public final void setUseNewImagingEngine(boolean value)
```

Ottiene o imposta l'opzione UseNewImagingEngine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano @deprecated UseNewImagingEngine è deprecato |
