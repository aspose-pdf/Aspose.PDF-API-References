---
title: "UnifiedSaveOptions"
linktitle: "UnifiedSaveOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta classe representa opções de salvamento que utilizam um método de conversão unificado (com modelo interno de documento unificado)."
type: docs
weight: 5420
url: /pt/java/com.aspose.pdf/unifiedsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions

```
public class UnifiedSaveOptions extends SaveOptions
```

Esta classe representa opções de salvamento que utilizam um método de conversão unificado (com modelo interno de documento unificado).

## Campos

| Campo | Descrição |
| --- | --- |
| [IsMultiThreading](#IsMultiThreading) | Processa páginas em algumas threads. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [UnifiedSaveOptions](#UnifiedSaveOptions--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [getProgressEventsRetranslator](#getProgressEventsRetranslator--) | Representa o processador interno de eventos de progresso que funciona durante a conversão e traduz os eventos de conversão das etapas internas de conversão em eventos externos de progresso total. Também a classe transmite eventos que permitem liberar recursos que não são mais necessários. Esta classe interna lida com eventos de progresso da conversão de PDF para APS e de APS para [Other format] para calcular o progresso total e informar o código do cliente sobre esse progresso total. Esta classe usa dois tipos de eventos: conversão de modelo ApsToExternal e eventos de conversão de PDF para APS para gerar eventos de progresso total. A exportação tem três estágios: 1) PDF para APS 2) Reconhecimento APS 3) Exportação APS para o formato de destino. O construtor permite ajustar quantas páginas são convertidas e qual é a parte aproximada desta ou daquela etapa no progresso total |
| [isExtractOcrSublayerOnly](#isExtractOcrSublayerOnly--) | Este atributo habilita a funcionalidade de extração de imagem ou texto para documentos PDF com camada OCR. Valor: {@code true} o texto será extraído no documento resultante; caso contrário, {@code false}. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo idênticas em mosaico colocadas próximas umas das outras. Nesse caso, os renderizadores dos formatos de destino (por exemplo, MsWord para o formato DOCS) às vezes geram limites visíveis entre partes das imagens de fundo, pois suas técnicas de suavização de bordas de imagem (anti‑aliasing) são diferentes das do Acrobat Reader. Se parecer que o documento exportado contém esses limites visíveis entre partes das mesmas imagens de fundo, tente usar esta configuração para eliminar esse efeito indesejado. ATENÇÃO! Essa otimização de qualidade geralmente desacelera significativamente a conversão, portanto, use esta opção somente quando for realmente necessária. |
| [setExtractOcrSublayerOnly](#setExtractOcrSublayerOnly-boolean-) | <p> Este atributo ativou a funcionalidade de extração de imagem ou texto para documentos PDF com subcamada OCR. </p>Value: {@code true} o texto será extraído no documento resultante; caso contrário, {@code false}. <hr> Valor padrão == false |
| [setProgressEventsRetranslator](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Representa o processador interno de eventos de progresso que funciona durante a conversão e traduz os eventos de conversão das etapas internas de conversão em eventos externos de progresso total. Também a classe transmite eventos que permitem liberar recursos que não são mais necessários. Esta classe interna lida com eventos de progresso da conversão de PDF para APS e de APS para [Other format] para calcular o progresso total e informar o código do cliente sobre esse progresso total. Esta classe usa dois tipos de eventos: conversão de modelo ApsToExternal e eventos de conversão de PDF para APS para gerar eventos de progresso total. A exportação tem três estágios: 1) PDF para APS 2) Reconhecimento APS 3) Exportação APS para o formato de destino. O construtor permite ajustar quantas páginas são convertidas e qual é a parte aproximada desta ou daquela etapa no progresso total |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo idênticas em mosaico colocadas próximas umas das outras. Nesse caso, os renderizadores dos formatos de destino (por exemplo, MsWord para o formato DOCS) às vezes geram limites visíveis entre partes das imagens de fundo, pois suas técnicas de suavização de bordas de imagem (anti‑aliasing) são diferentes das do Acrobat Reader. Se parecer que o documento exportado contém esses limites visíveis entre partes das mesmas imagens de fundo, tente usar esta configuração para eliminar esse efeito indesejado. ATENÇÃO! Essa otimização de qualidade geralmente desacelera significativamente a conversão, portanto, use esta opção somente quando for realmente necessária. |

### IsMultiThreading {#IsMultiThreading}
```
public boolean IsMultiThreading
```

Processa páginas em algumas threads.

### UnifiedSaveOptions {#UnifiedSaveOptions--}
```
public UnifiedSaveOptions()
```



### getProgressEventsRetranslator {#getProgressEventsRetranslator--}
```
public com.aspose.pdf.ConversionProgressEventsTranslator getProgressEventsRetranslator()
```

Representa o processador interno de eventos de progresso que funciona durante a conversão e traduz os eventos de conversão das etapas internas de conversão em eventos externos de progresso total. Também a classe transmite eventos que permitem liberar recursos que não são mais necessários. Esta classe interna lida com eventos de progresso da conversão de PDF para APS e de APS para [Other format] para calcular o progresso total e informar o código do cliente sobre esse progresso total. Esta classe usa dois tipos de eventos: conversão de modelo ApsToExternal e eventos de conversão de PDF para APS para gerar eventos de progresso total. A exportação tem três estágios: 1) PDF para APS 2) Reconhecimento APS 3) Exportação APS para o formato de destino. O construtor permite ajustar quantas páginas são convertidas e qual é a parte aproximada desta ou daquela etapa no progresso total

**Returns:**
Instância de ConversionProgressEventsTranslator

### isExtractOcrSublayerOnly {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```

Este atributo habilita a funcionalidade de extração de imagem ou texto para documentos PDF com camada OCR. Valor: {@code true} o texto será extraído no documento resultante; caso contrário, {@code false}.

**Returns:**
valor booleano

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo idênticas em mosaico colocadas próximas umas das outras. Nesse caso, os renderizadores dos formatos de destino (por exemplo, MsWord para o formato DOCS) às vezes geram limites visíveis entre partes das imagens de fundo, pois suas técnicas de suavização de bordas de imagem (anti‑aliasing) são diferentes das do Acrobat Reader. Se parecer que o documento exportado contém esses limites visíveis entre partes das mesmas imagens de fundo, tente usar esta configuração para eliminar esse efeito indesejado. ATENÇÃO! Essa otimização de qualidade geralmente desacelera significativamente a conversão, portanto, use esta opção somente quando for realmente necessária.

**Returns:**
valor booleano

### setExtractOcrSublayerOnly {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```

<p> Este atributo ativou a funcionalidade de extração de imagem ou texto para documentos PDF com subcamada OCR. </p>Value: {@code true} o texto será extraído no documento resultante; caso contrário, {@code false}. <hr> Valor padrão == false

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setProgressEventsRetranslator {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
Representa o processador interno de eventos de progresso que funciona durante a conversão e traduz os eventos de conversão das etapas internas de conversão em eventos externos de progresso total. Também a classe transmite eventos que permitem liberar recursos que não são mais necessários. Esta classe interna lida com eventos de progresso da conversão de PDF para APS e de APS para [Other format] para calcular o progresso total e informar o código do cliente sobre esse progresso total. Esta classe usa dois tipos de eventos: conversão de modelo ApsToExternal e eventos de conversão de PDF para APS para gerar eventos de progresso total. A exportação tem três estágios: 1) PDF para APS 2) Reconhecimento APS 3) Exportação APS para o formato de destino. O construtor permite ajustar quantas páginas são convertidas e qual é a parte aproximada desta ou daquela etapa no progresso total

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo idênticas em mosaico colocadas próximas umas das outras. Nesse caso, os renderizadores dos formatos de destino (por exemplo, MsWord para o formato DOCS) às vezes geram limites visíveis entre partes das imagens de fundo, pois suas técnicas de suavização de bordas de imagem (anti‑aliasing) são diferentes das do Acrobat Reader. Se parecer que o documento exportado contém esses limites visíveis entre partes das mesmas imagens de fundo, tente usar esta configuração para eliminar esse efeito indesejado. ATENÇÃO! Essa otimização de qualidade geralmente desacelera significativamente a conversão, portanto, use esta opção somente quando for realmente necessária.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | valor booleano |
