---
title: "SvgLoadOptions"
linktitle: "SvgLoadOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa opções para carregar/importar arquivo SVG em documento PDF."
type: docs
weight: 4700
url: /pt/java/com.aspose.pdf/svgloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.SvgLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.SvgLoadOptions

```
public final class SvgLoadOptions extends LoadOptions
```

Representa opções para carregar/importar arquivo SVG em documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SvgLoadOptions](#SvgLoadOptions--) | Cria o objeto {@code SvgLoadOptions}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getConversionEngine](#getConversionEngine--) | Permite selecionar o mecanismo de conversão que será usado durante a conversão. Atualmente, o novo mecanismo está em fase de testes B, portanto este valor é definido por padrão como ConversionEngines.LegacyEngine |
| [getPageInfo](#getPageInfo--) | Obtém as informações da página que devem ser aplicadas durante o carregamento do documento. |
| [isAdjustPageSize](#isAdjustPageSize--) | Ajusta o tamanho da página PDF ao tamanho do SVG |
| [setAdjustPageSize](#setAdjustPageSize-boolean-) | Ajusta o tamanho da página PDF ao tamanho do SVG |
| [setConversionEngine](#setConversionEngine-int-) | Permite selecionar o mecanismo de conversão que será usado durante a conversão. Atualmente, o novo mecanismo está em fase de testes B, portanto este valor é definido por padrão como ConversionEngines.LegacyEngine |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Define as informações da página que devem ser aplicadas durante o carregamento do documento. |

### SvgLoadOptions {#SvgLoadOptions--}
```
public SvgLoadOptions()
```

Cria o objeto {@code SvgLoadOptions}.

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Permite selecionar o mecanismo de conversão que será usado durante a conversão. Atualmente, o novo mecanismo está em fase de testes B, portanto este valor é definido por padrão como ConversionEngines.LegacyEngine

**Returns:**
Elemento ConversionEngines @see ConversionEngines

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Obtém as informações da página que devem ser aplicadas durante o carregamento do documento.

**Returns:**
Objeto PageInfo

### isAdjustPageSize {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```

Ajusta o tamanho da página PDF ao tamanho do SVG

**Returns:**
valor booleano

### setAdjustPageSize {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```

Ajusta o tamanho da página PDF ao tamanho do SVG

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Permite selecionar o mecanismo de conversão que será usado durante a conversão. Atualmente, o novo mecanismo está em fase de testes B, portanto este valor é definido por padrão como ConversionEngines.LegacyEngine

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| conversionEngine |  | Elemento ConversionEngines @see ConversionEngines |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Define as informações da página que devem ser aplicadas durante o carregamento do documento.
