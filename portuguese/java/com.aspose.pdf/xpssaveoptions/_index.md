---
title: "XpsSaveOptions"
linktitle: "XpsSaveOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Opções de salvamento para exportação para o formato XPS"
type: docs
weight: 5770
url: /pt/java/com.aspose.pdf/xpssaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.XpsSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class XpsSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Opções de salvamento para exportação para o formato XPS

## Construtores

| Construtor | Descrição |
| --- | --- |
| [XpsSaveOptions](#XpsSaveOptions--) | Construtor |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino. |
| [getDefaultFont](#getDefaultFont--) | Obtém/define o nome da fonte padrão. Usado se o nome da fonte incorporada não for encontrado no sistema. |
| [getSaveTransparentTexts](#getSaveTransparentTexts--) | Indica se deve preservar texto transparente (OCR). |
| [getUseEmbeddedTrueTypeFonts](#getUseEmbeddedTrueTypeFonts--) | Obtém/define a sinalização para usar fontes TrueType incorporadas. Evitar o uso de fontes TrueType incorporadas pode reduzir o tempo de conversão. |
| [isUseNewImagingEngine](#isUseNewImagingEngine--) | Obtém ou define a opção UseNewImagingEngine. |
| [setBatchSize](#setBatchSize-int-) | Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino. |
| [setDefaultFont](#setDefaultFont-java.lang.String-) | Obtém/define o nome da fonte padrão. Usado se o nome da fonte incorporada não for encontrado no sistema. |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Indica se deve preservar texto transparente (OCR). |
| [setUseEmbeddedTrueTypeFonts](#setUseEmbeddedTrueTypeFonts-boolean-) | Obtém/define a sinalização para usar fontes TrueType incorporadas. Evitar o uso de fontes TrueType incorporadas pode reduzir o tempo de conversão. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Obtém ou define a opção UseNewImagingEngine. |

### XpsSaveOptions {#XpsSaveOptions--}
```
public XpsSaveOptions()
```

Construtor

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino.

**Returns:**
valor int

### getDefaultFont {#getDefaultFont--}
```
public final String getDefaultFont()
```

Obtém/define o nome da fonte padrão. Usado se o nome da fonte incorporada não for encontrado no sistema.

**Returns:**
valor String

### getSaveTransparentTexts {#getSaveTransparentTexts--}
```
public final boolean getSaveTransparentTexts()
```

Indica se deve preservar texto transparente (OCR).

**Returns:**
valor booleano

### getUseEmbeddedTrueTypeFonts {#getUseEmbeddedTrueTypeFonts--}
```
public final boolean getUseEmbeddedTrueTypeFonts()
```

Obtém/define a sinalização para usar fontes TrueType incorporadas. Evitar o uso de fontes TrueType incorporadas pode reduzir o tempo de conversão.

**Returns:**
valor booleano

### isUseNewImagingEngine {#isUseNewImagingEngine--}
```
@Deprecated public final boolean isUseNewImagingEngine()
```

Obtém ou define a opção UseNewImagingEngine.

**Returns:**
valor booleano @deprecated UseNewImagingEngine está obsoleto

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setDefaultFont {#setDefaultFont-java.lang.String-}
Obtém/define o nome da fonte padrão. Usado se o nome da fonte incorporada não for encontrado no sistema.

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public final void setSaveTransparentTexts(boolean value)
```

Indica se deve preservar texto transparente (OCR).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseEmbeddedTrueTypeFonts {#setUseEmbeddedTrueTypeFonts-boolean-}
```
public final void setUseEmbeddedTrueTypeFonts(boolean value)
```

Obtém/define a sinalização para usar fontes TrueType incorporadas. Evitar o uso de fontes TrueType incorporadas pode reduzir o tempo de conversão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public final void setUseNewImagingEngine(boolean value)
```

Obtém ou define a opção UseNewImagingEngine.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano @deprecated UseNewImagingEngine está obsoleto |
