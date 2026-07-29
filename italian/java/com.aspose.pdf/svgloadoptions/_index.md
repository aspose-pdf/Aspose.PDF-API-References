---
title: "SvgLoadOptions"
linktitle: "SvgLoadOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le opzioni per caricare/importare un file SVG in un documento PDF."
type: docs
weight: 4700
url: /it/java/com.aspose.pdf/svgloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.SvgLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.SvgLoadOptions

```
public final class SvgLoadOptions extends LoadOptions
```

Rappresenta le opzioni per caricare/importare un file SVG in un documento PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SvgLoadOptions](#SvgLoadOptions--) | Crea l'oggetto {@code SvgLoadOptions}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getConversionEngine](#getConversionEngine--) | Consente di selezionare il motore di conversione che verrà utilizzato durante la conversione. Attualmente il nuovo motore è in fase di B-testing, quindi questo valore è impostato per impostazione predefinita su ConversionEngines.LegacyEngine |
| [getPageInfo](#getPageInfo--) | Ottiene le informazioni della pagina che devono essere applicate durante il caricamento del documento. |
| [isAdjustPageSize](#isAdjustPageSize--) | Adatta le dimensioni della pagina PDF alle dimensioni SVG |
| [setAdjustPageSize](#setAdjustPageSize-boolean-) | Adatta le dimensioni della pagina PDF alle dimensioni SVG |
| [setConversionEngine](#setConversionEngine-int-) | Consente di selezionare il motore di conversione che verrà utilizzato durante la conversione. Attualmente il nuovo motore è in fase di B-testing, quindi questo valore è impostato per impostazione predefinita su ConversionEngines.LegacyEngine |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Imposta le informazioni della pagina che devono essere applicate durante il caricamento del documento. |

### SvgLoadOptions {#SvgLoadOptions--}
```
public SvgLoadOptions()
```

Crea l'oggetto {@code SvgLoadOptions}.

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Consente di selezionare il motore di conversione che verrà utilizzato durante la conversione. Attualmente il nuovo motore è in fase di B-testing, quindi questo valore è impostato per impostazione predefinita su ConversionEngines.LegacyEngine

**Returns:**
Elemento ConversionEngines @see ConversionEngines

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Ottiene le informazioni della pagina che devono essere applicate durante il caricamento del documento.

**Returns:**
Oggetto PageInfo

### isAdjustPageSize {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```

Adatta le dimensioni della pagina PDF alle dimensioni SVG

**Returns:**
valore booleano

### setAdjustPageSize {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```

Adatta le dimensioni della pagina PDF alle dimensioni SVG

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Consente di selezionare il motore di conversione che verrà utilizzato durante la conversione. Attualmente il nuovo motore è in fase di B-testing, quindi questo valore è impostato per impostazione predefinita su ConversionEngines.LegacyEngine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| conversionEngine |  | Elemento ConversionEngines @see ConversionEngines |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Imposta le informazioni della pagina che devono essere applicate durante il caricamento del documento.
