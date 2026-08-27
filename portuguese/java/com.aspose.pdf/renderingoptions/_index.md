---
title: "RenderingOptions"
linktitle: "RenderingOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa opções de renderização"
type: docs
weight: 4150
url: /pt/java/com.aspose.pdf/renderingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RenderingOptions

```
public final class RenderingOptions extends Object
```

Representa opções de renderização

## Construtores

| Construtor | Descrição |
| --- | --- |
| [RenderingOptions](#RenderingOptions--) | Inicializa uma nova instância do objeto {@code RenderingOptions}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getAnalyzeFonts](#getAnalyzeFonts--) | Substitui fontes conforme necessário para garantir que todos os caracteres do texto possam ser exibidos. O algoritmo de substituição de fontes segue estas etapas: 1. Se o usuário definir explicitamente a propriedade DefaultFontName, verifique se a fonte especificada pode exibir os caracteres desejados. 2. Se nenhuma fonte definida pelo usuário estiver configurada, procure fontes adicionadas via {@code FontRepository.Sources}. 3. Analise o texto para identificar seu alfabeto ou script e sugira nomes de fontes adequados. Tente localizar e usar essas fontes no sistema. 4. Como alternativa, procure no sistema qualquer fonte capaz de exibir os caracteres necessários. |
| [getBarcodeOptimization](#getBarcodeOptimization--) | Obtém o modo de otimização de código de barras. |
| [getConvertFontsToUnicodeTTF](#getConvertFontsToUnicodeTTF--) | Indica que todas as fontes serão convertidas para versões TTF Unicode. Isso é útil por razões de compatibilidade e para otimizar o uso de fontes, pois cada nova fonte TTF não terá todos os símbolos da fonte original, mas apenas os símbolos que são usados no texto. |
| [getDefaultFontName](#getDefaultFontName--) | Obtém/define o nome padrão da fonte usada para substituir fontes ausentes. |
| [getHeightExtraUnits](#getHeightExtraUnits--) | Obtém ou define um valor usado para aumentar ou diminuir a largura do retângulo para o operador AppendRectangle. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados. true - significa que erros de ausência de fonte serão ignorados. Segmentos de texto que referem recursos incorretos serão pulados durante o processamento. false por padrão |
| [getInterpolationHighQuality](#getInterpolationHighQuality--) | Obtém ou define o modo de alta qualidade para interpolação. |
| [getMaxFontsCacheSize](#getMaxFontsCacheSize--) | Contagem máxima de fontes no cache de fontes. O valor padrão é 10. |
| [getMaxSymbolsCacheSize](#getMaxSymbolsCacheSize--) | Contagem máxima de símbolos no cache de símbolos. O valor padrão é 100. |
| [getOptimizeDimensions](#getOptimizeDimensions--) | Obtém ou define o modo de otimização de dimensões. |
| [getScaleImagesToFitPageWidth](#getScaleImagesToFitPageWidth--) | Obtém ou define um valor usado para dimensionar todas as imagens na página para ajustar à largura da página. |
| [getSystemFontsNativeRendering](#getSystemFontsNativeRendering--) | Obtém um modo onde as fontes do sistema são renderizadas nativamente |
| [getUseFontHinting](#getUseFontHinting--) | O uso desta bandeira ativa o mecanismo de ajuste de fontes. O ajuste de fontes é o uso de instruções matemáticas para ajustar a exibição de uma fonte contornada. Em alguns casos, ativar esta bandeira pode resolver problemas de legibilidade do texto. No momento, o uso desta bandeira pode ter efeito apenas para fontes TTF, se essas fontes forem usadas no documento de origem. |
| [getUseNewImagingEngine](#getUseNewImagingEngine--) | Obtém uma bandeira que determina se o novo mecanismo de imagens é usado ou não. |
| [getWidthExtraUnits](#getWidthExtraUnits--) | Obtém ou define um valor usado para aumentar ou diminuir a largura do retângulo para o operador AppendRectangle. |
| [isTryToSkipDocumentErrors](#isTryToSkipDocumentErrors--) | Obtém um valor usado para ignorar erros durante o processamento do arquivo PDF |
| [setAnalyzeFonts](#setAnalyzeFonts-boolean-) | Substitui fontes conforme necessário para garantir que todos os caracteres do texto possam ser exibidos. O algoritmo de substituição de fontes segue estas etapas: 1. Se o usuário definir explicitamente a propriedade DefaultFontName, verifique se a fonte especificada pode exibir os caracteres desejados. 2. Se nenhuma fonte definida pelo usuário estiver configurada, procure fontes adicionadas via {@code FontRepository.Sources}. 3. Analise o texto para identificar seu alfabeto ou script e sugira nomes de fontes adequados. Tente localizar e usar essas fontes no sistema. 4. Como alternativa, procure no sistema qualquer fonte capaz de exibir os caracteres necessários. |
| [setBarcodeOptimization](#setBarcodeOptimization-boolean-) | Define o modo de otimização de código de barras. |
| [setConvertFontsToUnicodeTTF](#setConvertFontsToUnicodeTTF-boolean-) | Indica que todas as fontes serão convertidas para versões TTF Unicode. Isso é útil por razões de compatibilidade e para otimizar o uso de fontes, pois cada nova fonte TTF não terá todos os símbolos da fonte original, mas apenas os símbolos que são usados no texto. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Obtém/define o nome padrão da fonte usada para substituir fontes ausentes. |
| [setHeightExtraUnits](#setHeightExtraUnits-float-) | Obtém ou define um valor usado para aumentar ou diminuir a largura do retângulo para o operador AppendRectangle. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados. true - significa que erros de ausência de fonte serão ignorados. Segmentos de texto que referem recursos incorretos serão pulados durante o processamento. false por padrão |
| [setInterpolationHighQuality](#setInterpolationHighQuality-boolean-) | Obtém ou define o modo de alta qualidade para interpolação. |
| [setMaxFontsCacheSize](#setMaxFontsCacheSize-int-) | Contagem máxima de fontes no cache de fontes. O valor padrão é 10. |
| [setMaxSymbolsCacheSize](#setMaxSymbolsCacheSize-int-) | Contagem máxima de símbolos no cache de símbolos. O valor padrão é 100. |
| [setOptimizeDimensions](#setOptimizeDimensions-boolean-) | Obtém ou define o modo de otimização de dimensões. |
| [setScaleImagesToFitPageWidth](#setScaleImagesToFitPageWidth-boolean-) | Obtém ou define um valor usado para dimensionar todas as imagens na página para ajustar à largura da página. |
| [setSystemFontsNativeRendering](#setSystemFontsNativeRendering-boolean-) | Define um modo onde as fontes do sistema são renderizadas nativamente |
| [setTryToSkipDocumentErrors](#setTryToSkipDocumentErrors-boolean-) | Define um valor usado para ignorar erros durante o processamento do arquivo PDF |
| [setUseFontHinting](#setUseFontHinting-boolean-) | O uso desta bandeira ativa o mecanismo de ajuste de fontes. O ajuste de fontes é o uso de instruções matemáticas para ajustar a exibição de uma fonte contornada. Em alguns casos, ativar esta bandeira pode resolver problemas de legibilidade do texto. No momento, o uso desta bandeira pode ter efeito apenas para fontes TTF, se essas fontes forem usadas no documento de origem. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Define uma bandeira que determina se o novo mecanismo de imagens é usado ou não. |
| [setWidthExtraUnits](#setWidthExtraUnits-float-) | Obtém ou define um valor usado para aumentar ou diminuir a largura do retângulo para o operador AppendRectangle. |

### RenderingOptions {#RenderingOptions--}
```
public RenderingOptions()
```

Inicializa uma nova instância do objeto {@code RenderingOptions}.

### getAnalyzeFonts {#getAnalyzeFonts--}
```
public final boolean getAnalyzeFonts()
```

Substitui fontes conforme necessário para garantir que todos os caracteres do texto possam ser exibidos. O algoritmo de substituição de fontes segue estas etapas: 1. Se o usuário definir explicitamente a propriedade DefaultFontName, verifique se a fonte especificada pode exibir os caracteres desejados. 2. Se nenhuma fonte definida pelo usuário estiver configurada, procure fontes adicionadas via {@code FontRepository.Sources}. 3. Analise o texto para identificar seu alfabeto ou script e sugira nomes de fontes adequados. Tente localizar e usar essas fontes no sistema. 4. Como alternativa, procure no sistema qualquer fonte capaz de exibir os caracteres necessários.

**Returns:**
valor booleano

### getBarcodeOptimization {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```

Obtém o modo de otimização de código de barras.

**Returns:**
valor booleano

### getConvertFontsToUnicodeTTF {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```

Indica que todas as fontes serão convertidas para versões TTF Unicode. Isso é útil por razões de compatibilidade e para otimizar o uso de fontes, pois cada nova fonte TTF não terá todos os símbolos da fonte original, mas apenas os símbolos que são usados no texto.

**Returns:**
valor booleano

### getDefaultFontName {#getDefaultFontName--}
```
public final String getDefaultFontName()
```

Obtém/define o nome padrão da fonte usada para substituir fontes ausentes.

**Returns:**
valor String

### getHeightExtraUnits {#getHeightExtraUnits--}
```
public final float getHeightExtraUnits()
```

Obtém ou define um valor usado para aumentar ou diminuir a largura do retângulo para o operador AppendRectangle.

**Returns:**
valor float

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados. true - significa que erros de ausência de fonte serão ignorados. Segmentos de texto que referem recursos incorretos serão pulados durante o processamento. false por padrão

**Returns:**
valor booleano

### getInterpolationHighQuality {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```

Obtém ou define o modo de alta qualidade para interpolação.

**Returns:**
valor booleano

### getMaxFontsCacheSize {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```

Contagem máxima de fontes no cache de fontes. O valor padrão é 10.

**Returns:**
valor int

### getMaxSymbolsCacheSize {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```

Contagem máxima de símbolos no cache de símbolos. O valor padrão é 100.

**Returns:**
valor int

### getOptimizeDimensions {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```

Obtém ou define o modo de otimização de dimensões.

**Returns:**
valor booleano

### getScaleImagesToFitPageWidth {#getScaleImagesToFitPageWidth--}
```
@Deprecated public final boolean getScaleImagesToFitPageWidth()
```

Obtém ou define um valor usado para dimensionar todas as imagens na página para ajustar à largura da página.

**Returns:**
valor booleano @deprecated ScaleImagesToFitPageWidth está obsoleto.

### getSystemFontsNativeRendering {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```

Obtém um modo onde as fontes do sistema são renderizadas nativamente

**Returns:**
valor booleano

### getUseFontHinting {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```

O uso desta bandeira ativa o mecanismo de ajuste de fontes. O ajuste de fontes é o uso de instruções matemáticas para ajustar a exibição de uma fonte contornada. Em alguns casos, ativar esta bandeira pode resolver problemas de legibilidade do texto. No momento, o uso desta bandeira pode ter efeito apenas para fontes TTF, se essas fontes forem usadas no documento de origem.

**Returns:**
valor booleano

### getUseNewImagingEngine {#getUseNewImagingEngine--}
```
@Deprecated public boolean getUseNewImagingEngine()
```

Obtém uma bandeira que determina se o novo mecanismo de imagens é usado ou não.

**Returns:**
valor booleano @deprecated UseNewImagingEngine está obsoleto

### getWidthExtraUnits {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```

Obtém ou define um valor usado para aumentar ou diminuir a largura do retângulo para o operador AppendRectangle.

**Returns:**
valor float

### isTryToSkipDocumentErrors {#isTryToSkipDocumentErrors--}
```
public boolean isTryToSkipDocumentErrors()
```

Obtém um valor usado para ignorar erros durante o processamento do arquivo PDF

**Returns:**
valor booleano

### setAnalyzeFonts {#setAnalyzeFonts-boolean-}
```
public final void setAnalyzeFonts(boolean value)
```

Substitui fontes conforme necessário para garantir que todos os caracteres do texto possam ser exibidos. O algoritmo de substituição de fontes segue estas etapas: 1. Se o usuário definir explicitamente a propriedade DefaultFontName, verifique se a fonte especificada pode exibir os caracteres desejados. 2. Se nenhuma fonte definida pelo usuário estiver configurada, procure fontes adicionadas via {@code FontRepository.Sources}. 3. Analise o texto para identificar seu alfabeto ou script e sugira nomes de fontes adequados. Tente localizar e usar essas fontes no sistema. 4. Como alternativa, procure no sistema qualquer fonte capaz de exibir os caracteres necessários.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setBarcodeOptimization {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```

Define o modo de otimização de código de barras.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setConvertFontsToUnicodeTTF {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```

Indica que todas as fontes serão convertidas para versões TTF Unicode. Isso é útil por razões de compatibilidade e para otimizar o uso de fontes, pois cada nova fonte TTF não terá todos os símbolos da fonte original, mas apenas os símbolos que são usados no texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Obtém/define o nome padrão da fonte usada para substituir fontes ausentes.

### setHeightExtraUnits {#setHeightExtraUnits-float-}
```
public final void setHeightExtraUnits(float value)
```

Obtém ou define um valor usado para aumentar ou diminuir a largura do retângulo para o operador AppendRectangle.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados. true - significa que erros de ausência de fonte serão ignorados. Segmentos de texto que referem recursos incorretos serão pulados durante o processamento. false por padrão

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setInterpolationHighQuality {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```

Obtém ou define o modo de alta qualidade para interpolação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMaxFontsCacheSize {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```

Contagem máxima de fontes no cache de fontes. O valor padrão é 10.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setMaxSymbolsCacheSize {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```

Contagem máxima de símbolos no cache de símbolos. O valor padrão é 100.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setOptimizeDimensions {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```

Obtém ou define o modo de otimização de dimensões.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setScaleImagesToFitPageWidth {#setScaleImagesToFitPageWidth-boolean-}
```
@Deprecated public final void setScaleImagesToFitPageWidth(boolean value)
```

Obtém ou define um valor usado para dimensionar todas as imagens na página para ajustar à largura da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano @deprecated ScaleImagesToFitPageWidth está obsoleto. |

### setSystemFontsNativeRendering {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```

Define um modo onde as fontes do sistema são renderizadas nativamente

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setTryToSkipDocumentErrors {#setTryToSkipDocumentErrors-boolean-}
```
public void setTryToSkipDocumentErrors(boolean value)
```

Define um valor usado para ignorar erros durante o processamento do arquivo PDF

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseFontHinting {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```

O uso desta bandeira ativa o mecanismo de ajuste de fontes. O ajuste de fontes é o uso de instruções matemáticas para ajustar a exibição de uma fonte contornada. Em alguns casos, ativar esta bandeira pode resolver problemas de legibilidade do texto. No momento, o uso desta bandeira pode ter efeito apenas para fontes TTF, se essas fontes forem usadas no documento de origem.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public void setUseNewImagingEngine(boolean value)
```

Define uma bandeira que determina se o novo mecanismo de imagens é usado ou não.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano @deprecated UseNewImagingEngine está obsoleto |

### setWidthExtraUnits {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```

Obtém ou define um valor usado para aumentar ou diminuir a largura do retângulo para o operador AppendRectangle.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |
