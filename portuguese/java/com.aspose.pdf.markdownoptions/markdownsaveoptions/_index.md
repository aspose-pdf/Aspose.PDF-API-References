---
title: "MarkdownSaveOptions"
linktitle: "MarkdownSaveOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a classe de opção de salvamento de documento no formato markdown."
type: docs
weight: 60
url: /pt/java/com.aspose.pdf.markdownoptions/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.markdownoptions.MarkdownSaveOptions

```
public class MarkdownSaveOptions extends UnifiedSaveOptions
```

Representa a classe de opção de salvamento de documento no formato markdown.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [MarkdownSaveOptions](#MarkdownSaveOptions--) | Cria uma opção de instância para salvar um documento no formato markdown. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getAreaToExtract](#getAreaToExtract--) | Obtém ou define uma área retangular para extrair conteúdo para markdown. |
| [getEmphasisStyle](#getEmphasisStyle--) | Obtém ou define o estilo de ênfase para o documento gerado. |
| [getExtractVectorGraphics](#getExtractVectorGraphics--) | Obtém e define uma propriedade que indica se os gráficos vetoriais devem ser extraídos. |
| [getHeadingLevels](#getHeadingLevels--) | Define os níveis de cabeçalho esperados para usar na estratégia de reconhecimento de cabeçalhos por tamanho de fonte. Se o valor desta propriedade for definido, então a estratégia de reconhecimento de cabeçalhos {@link HeadingRecognitionStrategy#Heuristic} será selecionada quando as estratégias {@link HeadingRecognitionStrategy#Auto} forem definidas, mesmo que o documento contenha marcadores. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Obtém ou define a estratégia de reconhecimento de cabeçalhos. |
| [getHeadingStyle](#getHeadingStyle--) | Obtém ou define o estilo de cabeçalho para o documento gerado. |
| [getLineBreakStyle](#getLineBreakStyle--) | Obtém ou define o estilo de quebra de linha para o documento gerado. |
| [getResourcesDirectoryName](#getResourcesDirectoryName--) | Obtém e define o nome do diretório para salvar recursos do documento, como imagens. Se o valor não for especificado, as imagens serão gravadas no mesmo diretório do próprio arquivo markdown. Isso não é um caminho, é apenas um nome! Este diretório será criado automaticamente no diretório onde o arquivo markdown salvo está localizado. |
| [getResourcesDirectoryPath](#getResourcesDirectoryPath--) | Obtém e define o nome do diretório para salvar recursos do documento, como imagens. Este diretório será criado automaticamente no diretório onde o arquivo markdown salvo está localizado. |
| [getSubscriptAndSuperscriptConversion](#getSubscriptAndSuperscriptConversion--) | Obtém e define a permissão para converter subscrito e sobrescrito. Este valor é verdadeiro por padrão. |
| [getUseImageHtmlTag](#getUseImageHtmlTag--) | Obtém e define a permissão para usar a tag img para inserir imagens à esquerda e à direita do texto. Nesse caso, no visualizador markdown, o texto envolverá a imagem. |
| [setAreaToExtract](#setAreaToExtract-com.aspose.pdf.Rectangle-) | Obtém ou define uma área retangular para extrair conteúdo para markdown. |
| [setEmphasisStyle](#setEmphasisStyle-int-) | Obtém ou define o estilo de ênfase para o documento gerado. |
| [setExtractVectorGraphics](#setExtractVectorGraphics-boolean-) | Obtém e define uma propriedade que indica se os gráficos vetoriais devem ser extraídos. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Define os níveis de cabeçalho esperados para usar na estratégia de reconhecimento de cabeçalhos por tamanho de fonte. Se o valor desta propriedade for definido, então a estratégia de reconhecimento de cabeçalhos {@link HeadingRecognitionStrategy#Heuristic} será selecionada quando as estratégias {@link HeadingRecognitionStrategy#Auto} forem definidas, mesmo que o documento contenha marcadores. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Obtém ou define a estratégia de reconhecimento de cabeçalhos. |
| [setHeadingStyle](#setHeadingStyle-int-) | Obtém ou define o estilo de cabeçalho para o documento gerado. |
| [setLineBreakStyle](#setLineBreakStyle-int-) | Obtém ou define o estilo de quebra de linha para o documento gerado. |
| [setResourcesDirectoryName](#setResourcesDirectoryName-java.lang.String-) | Obtém e define o nome do diretório para salvar recursos do documento, como imagens. Se o valor não for especificado, as imagens serão gravadas no mesmo diretório do próprio arquivo markdown. Isso não é um caminho, é apenas um nome! Este diretório será criado automaticamente no diretório onde o arquivo markdown salvo está localizado. |
| [setResourcesDirectoryPath](#setResourcesDirectoryPath-java.lang.String-) | Obtém e define o nome do diretório para salvar recursos do documento, como imagens. Este diretório será criado automaticamente no diretório onde o arquivo markdown salvo está localizado. |
| [setSubscriptAndSuperscriptConversion](#setSubscriptAndSuperscriptConversion-boolean-) | Obtém e define a permissão para converter subscrito e sobrescrito. Este valor é verdadeiro por padrão. |
| [setUseImageHtmlTag](#setUseImageHtmlTag-boolean-) | Obtém e define a permissão para usar a tag img para inserir imagens à esquerda e à direita do texto. Nesse caso, no visualizador markdown, o texto envolverá a imagem. |

### MarkdownSaveOptions {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Cria uma opção de instância para salvar um documento no formato markdown.

### getAreaToExtract {#getAreaToExtract--}
```
public final Rectangle getAreaToExtract()
```

Obtém ou define uma área retangular para extrair conteúdo para markdown.

**Returns:**
Instância de Rectangle

### getEmphasisStyle {#getEmphasisStyle--}
```
public final int getEmphasisStyle()
```

Obtém ou define o estilo de ênfase para o documento gerado.

**Returns:**
Elemento EmphasisStyle

### getExtractVectorGraphics {#getExtractVectorGraphics--}
```
public final boolean getExtractVectorGraphics()
```

Obtém e define uma propriedade que indica se os gráficos vetoriais devem ser extraídos.

**Returns:**
valor booleano

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Define os níveis de cabeçalho esperados para usar na estratégia de reconhecimento de cabeçalhos por tamanho de fonte. Se o valor desta propriedade for definido, então a estratégia de reconhecimento de cabeçalhos {@link HeadingRecognitionStrategy#Heuristic} será selecionada quando as estratégias {@link HeadingRecognitionStrategy#Auto} forem definidas, mesmo que o documento contenha marcadores.

**Returns:**
Instância de HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Obtém ou define a estratégia de reconhecimento de cabeçalhos.

**Returns:**
Elemento HeadingRecognitionStrategy

### getHeadingStyle {#getHeadingStyle--}
```
public final int getHeadingStyle()
```

Obtém ou define o estilo de cabeçalho para o documento gerado.

**Returns:**
Elemento HeadingStyle

### getLineBreakStyle {#getLineBreakStyle--}
```
public final int getLineBreakStyle()
```

Obtém ou define o estilo de quebra de linha para o documento gerado.

**Returns:**
Elemento LineBreakStyle

### getResourcesDirectoryName {#getResourcesDirectoryName--}
```
public final String getResourcesDirectoryName()
```

Obtém e define o nome do diretório para salvar recursos do documento, como imagens. Se o valor não for especificado, as imagens serão gravadas no mesmo diretório do próprio arquivo markdown. Isso não é um caminho, é apenas um nome! Este diretório será criado automaticamente no diretório onde o arquivo markdown salvo está localizado.

**Returns:**
valor String

### getResourcesDirectoryPath {#getResourcesDirectoryPath--}
```
public final String getResourcesDirectoryPath()
```

Obtém e define o nome do diretório para salvar recursos do documento, como imagens. Este diretório será criado automaticamente no diretório onde o arquivo markdown salvo está localizado.

**Returns:**
valor String

### getSubscriptAndSuperscriptConversion {#getSubscriptAndSuperscriptConversion--}
```
public final boolean getSubscriptAndSuperscriptConversion()
```

Obtém e define a permissão para converter subscrito e sobrescrito. Este valor é verdadeiro por padrão.

**Returns:**
valor booleano

### getUseImageHtmlTag {#getUseImageHtmlTag--}
```
public final boolean getUseImageHtmlTag()
```

Obtém e define a permissão para usar a tag img para inserir imagens à esquerda e à direita do texto. Nesse caso, no visualizador markdown, o texto envolverá a imagem.

**Returns:**
valor booleano

### setAreaToExtract {#setAreaToExtract-com.aspose.pdf.Rectangle-}
Obtém ou define uma área retangular para extrair conteúdo para markdown.

### setEmphasisStyle {#setEmphasisStyle-int-}
```
public final void setEmphasisStyle(int value)
```

Obtém ou define o estilo de ênfase para o documento gerado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento EmphasisStyle |

### setExtractVectorGraphics {#setExtractVectorGraphics-boolean-}
```
public final void setExtractVectorGraphics(boolean value)
```

Obtém e define uma propriedade que indica se os gráficos vetoriais devem ser extraídos.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Define os níveis de cabeçalho esperados para usar na estratégia de reconhecimento de cabeçalhos por tamanho de fonte. Se o valor desta propriedade for definido, então a estratégia de reconhecimento de cabeçalhos {@link HeadingRecognitionStrategy#Heuristic} será selecionada quando as estratégias {@link HeadingRecognitionStrategy#Auto} forem definidas, mesmo que o documento contenha marcadores.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Obtém ou define a estratégia de reconhecimento de cabeçalhos.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento HeadingRecognitionStrategy |

### setHeadingStyle {#setHeadingStyle-int-}
```
public final void setHeadingStyle(int value)
```

Obtém ou define o estilo de cabeçalho para o documento gerado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento HeadingStyle |

### setLineBreakStyle {#setLineBreakStyle-int-}
```
public final void setLineBreakStyle(int value)
```

Obtém ou define o estilo de quebra de linha para o documento gerado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento LineBreakStyle |

### setResourcesDirectoryName {#setResourcesDirectoryName-java.lang.String-}
Obtém e define o nome do diretório para salvar recursos do documento, como imagens. Se o valor não for especificado, as imagens serão gravadas no mesmo diretório do próprio arquivo markdown. Isso não é um caminho, é apenas um nome! Este diretório será criado automaticamente no diretório onde o arquivo markdown salvo está localizado.

### setResourcesDirectoryPath {#setResourcesDirectoryPath-java.lang.String-}
Obtém e define o nome do diretório para salvar recursos do documento, como imagens. Este diretório será criado automaticamente no diretório onde o arquivo markdown salvo está localizado.

### setSubscriptAndSuperscriptConversion {#setSubscriptAndSuperscriptConversion-boolean-}
```
public final void setSubscriptAndSuperscriptConversion(boolean value)
```

Obtém e define a permissão para converter subscrito e sobrescrito. Este valor é verdadeiro por padrão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseImageHtmlTag {#setUseImageHtmlTag-boolean-}
```
public final void setUseImageHtmlTag(boolean value)
```

Obtém e define a permissão para usar a tag img para inserir imagens à esquerda e à direita do texto. Nesse caso, no visualizador markdown, o texto envolverá a imagem.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
