---
title: "TextSearchOptions"
linktitle: "TextSearchOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa opções de pesquisa de texto"
type: docs
weight: 5290
url: /pt/java/com.aspose.pdf/textsearchoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextSearchOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextSearchOptions

```
public final class TextSearchOptions extends TextOptions
```

Representa opções de pesquisa de texto

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextSearchOptions](#TextSearchOptions-boolean-) | Inicializa uma nova instância do objeto {@code TextSearchOptions}. Especifica o modo de uso de expressão regular. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-) | Inicializa uma nova instância do objeto TextSearchOptions. Especifica o retângulo que delimita o texto pesquisado. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | Inicializa uma nova instância do objeto TextSearchOptions. Especifica o retângulo que delimita o texto pesquisado e o modo de uso de expressão regular. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getExcludeRectangles](#getExcludeRectangles--) | Obtém ou define retângulos cujas bordas excluem texto da pesquisa. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados pelo absorvedor de texto (fragmento). true - significa que os erros de ausência de fonte serão ignorados. Segmentos de texto que se referem a recursos incorretos serão ignorados durante o processamento. false (padrão) - o erro de ausência de fonte encerrará o processamento lançando uma exceção. |
| [getLimitToPageBounds](#getLimitToPageBounds--) | Obtém a indicação de que o texto é pesquisado dentro dos limites da página. |
| [getLogTextExtractionErrors](#getLogTextExtractionErrors--) | Obtém ou define a indicação de que erros de extração de texto (decodificação) serão registrados no absorvedor de texto (fragmento). true - significa que os erros de extração de texto (decodificação) serão registrados. Isso pode diminuir o desempenho. false (padrão) - nenhum registro de erro. |
| [getRectangle](#getRectangle--) | Obtém o retângulo que delimita o texto pesquisado. A propriedade pode ser usada caso seja necessário delimitar a extração de texto ou a região de substituição de texto. |
| [getSearchForTextRelatedGraphics](#getSearchForTextRelatedGraphics--) | Obtém ou define o valor que permite a pesquisa de gráficos relacionados ao texto (sublinhado, plano de fundo etc.) durante a pesquisa de texto. true - a pesquisa de gráficos relacionados ao texto será realizada (valor padrão). false - os elementos gráficos que possam estar presentes no documento de origem serão ignorados. Defina isso em caso de problemas de desempenho ou quando não for necessário lidar com sublinhado, plano de fundo ou recorte. |
| [getStoredGraphicElementsMaxCount](#getStoredGraphicElementsMaxCount--) | Obtém o valor que limita a pesquisa de gráficos relacionados ao texto (sublinhado, plano de fundo etc.) em uma página para o número especificado de elementos. O padrão é 250. Defina um valor menor em caso de problemas de desempenho, experimente um valor maior caso alguns elementos gráficos não sejam encontrados. |
| [getUseFontEngineEncoding](#getUseFontEngineEncoding--) | Obtém a indicação de que o texto será pesquisado usando a codificação do mecanismo de fontes. true - significa que a codificação do mecanismo de fontes será usada (tente isso se a pesquisa de texto falhar devido a codificação imperfeita no documento). false - significa que a codificação de fontes do documento será usada (valor padrão). |
| [isDotallMode](#isDotallMode--) | <p> No modo dotall, a expressão <tt>.</tt> corresponde a qualquer caractere, incluindo um terminador de linha. Por padrão, esta expressão não corresponde a terminadores de linha. |
| [isIgnoreShadowText](#isIgnoreShadowText--) | Obtém ou define a indicação de que fragmentos de texto que representam sombra do texto normal serão ignorados durante a pesquisa. true - significa que o texto em sombra não será encontrado (tente isso se a pesquisa de texto retornar fragmentos duplicados em posições próximas). false - significa que o texto em sombra será encontrado assim como o texto normal (valor padrão). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Indica se a expressão regular é usada ou não. |
| [isSearchInAnnotations](#isSearchInAnnotations--) | Obtém ou define o valor que permite a pesquisa de texto em Anotações. true - o texto será pesquisado nas Anotações. false - o texto nas Anotações não será analisado pelo TextFragmentAbsorber. |
| [setDotallMode](#setDotallMode-boolean-) | Habilita o modo dotall. <p> No modo dotall, a expressão <tt>.</tt> corresponde a qualquer caractere, incluindo um terminador de linha. Por padrão, esta expressão não corresponde a terminadores de linha. |
| [setExcludeRectangles](#setExcludeRectangles-com.aspose.pdf.Rectangle:A-) | Obtém ou define retângulos cujas bordas excluem texto da pesquisa. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados pelo absorvedor de texto (fragmento). true - significa que os erros de ausência de fonte serão ignorados. Segmentos de texto que se referem a recursos incorretos serão ignorados durante o processamento. false (padrão) - o erro de ausência de fonte encerrará o processamento lançando uma exceção. |
| [setIgnoreShadowText](#setIgnoreShadowText-boolean-) | Obtém ou define a indicação de que fragmentos de texto que representam sombra do texto normal serão ignorados durante a pesquisa. true - significa que o texto em sombra não será encontrado (tente isso se a pesquisa de texto retornar fragmentos duplicados em posições próximas). false - significa que o texto em sombra será encontrado assim como o texto normal (valor padrão). |
| [setLimitToPageBounds](#setLimitToPageBounds-boolean-) | Define a indicação de que o texto é pesquisado dentro dos limites da página. |
| [setLogTextExtractionErrors](#setLogTextExtractionErrors-boolean-) | Obtém ou define a indicação de que erros de extração de texto (decodificação) serão registrados no absorvedor de texto (fragmento). true - significa que os erros de extração de texto (decodificação) serão registrados. Isso pode diminuir o desempenho. false (padrão) - nenhum registro de erro. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Define o retângulo que delimita o texto pesquisado. A propriedade pode ser usada caso seja necessário delimitar a extração de texto ou a região de substituição de texto. |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Indica se a expressão regular é usada ou não. |
| [setSearchForTextRelatedGraphics](#setSearchForTextRelatedGraphics-boolean-) | Obtém ou define o valor que permite a pesquisa de gráficos relacionados ao texto (sublinhado, plano de fundo etc.) durante a pesquisa de texto. true - a pesquisa de gráficos relacionados ao texto será realizada (valor padrão). false - os elementos gráficos que possam estar presentes no documento de origem serão ignorados. Defina isso em caso de problemas de desempenho ou quando não for necessário lidar com sublinhado, plano de fundo ou recorte. |
| [setSearchInAnnotations](#setSearchInAnnotations-boolean-) | Obtém ou define o valor que permite a pesquisa de texto em Anotações. true - o texto será pesquisado nas Anotações. false - o texto nas Anotações não será analisado pelo TextFragmentAbsorber. |
| [setStoredGraphicElementsMaxCount](#setStoredGraphicElementsMaxCount-int-) | Define o valor que limita a pesquisa de gráficos relacionados ao texto (sublinhado, plano de fundo etc.) em uma página para o número especificado de elementos. O padrão é 250. Defina um valor menor em caso de problemas de desempenho, experimente um valor maior caso alguns elementos gráficos não sejam encontrados. |
| [setUseFontEngineEncoding](#setUseFontEngineEncoding-boolean-) | Define a indicação de que o texto será pesquisado usando a codificação do mecanismo de fontes. true - significa que a codificação do mecanismo de fontes será usada (tente isso se a pesquisa de texto falhar devido a codificação imperfeita no documento). false - significa que a codificação de fontes do documento será usada (valor padrão). |

### TextSearchOptions {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```

Inicializa uma nova instância do objeto {@code TextSearchOptions}. Especifica o modo de uso de expressão regular.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isRegularExpressionUsed |  | Valor que indica que a expressão regular é usada. |

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-}
Inicializa uma nova instância do objeto TextSearchOptions. Especifica o retângulo que delimita o texto pesquisado.

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
Inicializa uma nova instância do objeto TextSearchOptions. Especifica o retângulo que delimita o texto pesquisado e o modo de uso de expressão regular.

### getExcludeRectangles {#getExcludeRectangles--}
```
public final Rectangle [] getExcludeRectangles()
```

Obtém ou define retângulos cujas bordas excluem texto da pesquisa.

**Returns:**
array de instâncias de Rectangle

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados pelo absorvedor de texto (fragmento). true - significa que os erros de ausência de fonte serão ignorados. Segmentos de texto que se referem a recursos incorretos serão ignorados durante o processamento. false (padrão) - o erro de ausência de fonte encerrará o processamento lançando uma exceção.

**Returns:**
valor booleano

### getLimitToPageBounds {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```

Obtém a indicação de que o texto é pesquisado dentro dos limites da página.

**Returns:**
valor booleano

### getLogTextExtractionErrors {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```

Obtém ou define a indicação de que erros de extração de texto (decodificação) serão registrados no absorvedor de texto (fragmento). true - significa que os erros de extração de texto (decodificação) serão registrados. Isso pode diminuir o desempenho. false (padrão) - nenhum registro de erro.

**Returns:**
valor booleano

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo que delimita o texto pesquisado. A propriedade pode ser usada caso seja necessário delimitar a extração de texto ou a região de substituição de texto.

**Returns:**
Valor do retângulo

### getSearchForTextRelatedGraphics {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```

Obtém ou define o valor que permite a pesquisa de gráficos relacionados ao texto (sublinhado, plano de fundo etc.) durante a pesquisa de texto. true - a pesquisa de gráficos relacionados ao texto será realizada (valor padrão). false - os elementos gráficos que possam estar presentes no documento de origem serão ignorados. Defina isso em caso de problemas de desempenho ou quando não for necessário lidar com sublinhado, plano de fundo ou recorte.

**Returns:**
valor booleano

### getStoredGraphicElementsMaxCount {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```

Obtém o valor que limita a pesquisa de gráficos relacionados ao texto (sublinhado, plano de fundo etc.) em uma página para o número especificado de elementos. O padrão é 250. Defina um valor menor em caso de problemas de desempenho, experimente um valor maior caso alguns elementos gráficos não sejam encontrados.

**Returns:**
valor int

### getUseFontEngineEncoding {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```

Obtém a indicação de que o texto será pesquisado usando a codificação do mecanismo de fontes. true - significa que a codificação do mecanismo de fontes será usada (tente isso se a pesquisa de texto falhar devido a codificação imperfeita no documento). false - significa que a codificação de fontes do documento será usada (valor padrão).

**Returns:**
valor booleano

### isDotallMode {#isDotallMode--}
```
public static boolean isDotallMode()
```

<p> No modo dotall, a expressão <tt>.</tt> corresponde a qualquer caractere, incluindo um terminador de linha. Por padrão, esta expressão não corresponde a terminadores de linha.

**Returns:**
valor booleano

### isIgnoreShadowText {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```

Obtém ou define a indicação de que fragmentos de texto que representam sombra do texto normal serão ignorados durante a pesquisa. true - significa que o texto em sombra não será encontrado (tente isso se a pesquisa de texto retornar fragmentos duplicados em posições próximas). false - significa que o texto em sombra será encontrado assim como o texto normal (valor padrão).

**Returns:**
valor booleano

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Indica se a expressão regular é usada ou não.

**Returns:**
valor booleano

### isSearchInAnnotations {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```

Obtém ou define o valor que permite a pesquisa de texto em Anotações. true - o texto será pesquisado nas Anotações. false - o texto nas Anotações não será analisado pelo TextFragmentAbsorber.

**Returns:**
valor booleano

### setDotallMode {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```

Habilita o modo dotall. <p> No modo dotall, a expressão <tt>.</tt> corresponde a qualquer caractere, incluindo um terminador de linha. Por padrão, esta expressão não corresponde a terminadores de linha.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dotallMode |  | valor booleano |

### setExcludeRectangles {#setExcludeRectangles-com.aspose.pdf.Rectangle:A-}
Obtém ou define retângulos cujas bordas excluem texto da pesquisa.

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados pelo absorvedor de texto (fragmento). true - significa que os erros de ausência de fonte serão ignorados. Segmentos de texto que se referem a recursos incorretos serão ignorados durante o processamento. false (padrão) - o erro de ausência de fonte encerrará o processamento lançando uma exceção.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setIgnoreShadowText {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```

Obtém ou define a indicação de que fragmentos de texto que representam sombra do texto normal serão ignorados durante a pesquisa. true - significa que o texto em sombra não será encontrado (tente isso se a pesquisa de texto retornar fragmentos duplicados em posições próximas). false - significa que o texto em sombra será encontrado assim como o texto normal (valor padrão).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setLimitToPageBounds {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```

Define a indicação de que o texto é pesquisado dentro dos limites da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setLogTextExtractionErrors {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```

Obtém ou define a indicação de que erros de extração de texto (decodificação) serão registrados no absorvedor de texto (fragmento). true - significa que os erros de extração de texto (decodificação) serão registrados. Isso pode diminuir o desempenho. false (padrão) - nenhum registro de erro.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Define o retângulo que delimita o texto pesquisado. A propriedade pode ser usada caso seja necessário delimitar a extração de texto ou a região de substituição de texto.

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Indica se a expressão regular é usada ou não.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSearchForTextRelatedGraphics {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```

Obtém ou define o valor que permite a pesquisa de gráficos relacionados ao texto (sublinhado, plano de fundo etc.) durante a pesquisa de texto. true - a pesquisa de gráficos relacionados ao texto será realizada (valor padrão). false - os elementos gráficos que possam estar presentes no documento de origem serão ignorados. Defina isso em caso de problemas de desempenho ou quando não for necessário lidar com sublinhado, plano de fundo ou recorte.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSearchInAnnotations {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```

Obtém ou define o valor que permite a pesquisa de texto em Anotações. true - o texto será pesquisado nas Anotações. false - o texto nas Anotações não será analisado pelo TextFragmentAbsorber.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setStoredGraphicElementsMaxCount {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```

Define o valor que limita a pesquisa de gráficos relacionados ao texto (sublinhado, plano de fundo etc.) em uma página para o número especificado de elementos. O padrão é 250. Defina um valor menor em caso de problemas de desempenho, experimente um valor maior caso alguns elementos gráficos não sejam encontrados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setUseFontEngineEncoding {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```

Define a indicação de que o texto será pesquisado usando a codificação do mecanismo de fontes. true - significa que a codificação do mecanismo de fontes será usada (tente isso se a pesquisa de texto falhar devido a codificação imperfeita no documento). false - significa que a codificação de fontes do documento será usada (valor padrão).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
