---
title: "HtmlLoadOptions"
linktitle: "HtmlLoadOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa opções para carregar/importar arquivo HTML em documento PDF."
type: docs
weight: 1960
url: /pt/java/com.aspose.pdf/htmlloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.HtmlLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.HtmlLoadOptions

```
public final class HtmlLoadOptions extends LoadOptions
```

Representa opções para carregar/importar arquivo HTML em documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [HtmlLoadOptions](#HtmlLoadOptions--) | Cria opções de carregamento para converter html em documento pdf com caminho base vazio. |
| [HtmlLoadOptions](#HtmlLoadOptions-java.lang.String-) | Cria opções de carregamento para converter html em documento pdf com caminho base vazio. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBasePath](#getBasePath--) | O caminho/base ou URL para o arquivo html. |
| [getCustomLoaderOfExternalResources](#getCustomLoaderOfExternalResources--) | Às vezes é necessário evitar o uso do carregador interno de recursos externos (como imagens ou CSSes) e fornecer um método personalizado que obtenha os recursos solicitados de algum lugar. Por exemplo, durante o uso do Aspose.PDF na nuvem, o acesso direto aos arquivos referenciados é impossível: nesse caso, algum código do cliente colocado em um método especial deve ser usado, e o delegate que referencia esse método deve ser atribuído a este atributo. |
| [getHtmlMediaType](#getHtmlMediaType--) | Obtém ou define os tipos de mídia possíveis usados durante a renderização. |
| [getInputEncoding](#getInputEncoding--) | Obtém o atributo que especifica a codificação usada para este documento no momento da análise. Se este atributo for nulo, a codificação será determinada a partir do conjunto de caracteres do documento. |
| [getPageInfo](#getPageInfo--) | Obtém informações da página do documento |
| [getPageLayoutOption](#getPageLayoutOption--) | Obtém ou define a opção de layout. |
| [isEmbedFonts](#isEmbedFonts--) | Obtém ou define a incorporação de fontes no documento resultante |
| [isPriorityCssPageRule](#isPriorityCssPageRule--) | Obtém ou define o sinalizador que especifica que as regras @page definidas em css substituirão os valores definidos em PageInfo. |
| [isRenderToSinglePage](#isRenderToSinglePage--) | Obtém ou define a renderização de todo o documento em uma única página |
| [setCustomLoaderOfExternalResources](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | Às vezes é necessário evitar o uso do carregador interno de recursos externos (como imagens ou CSSes) e fornecer um método personalizado que obtenha os recursos solicitados de algum lugar. |
| [setEmbedFonts](#setEmbedFonts-boolean-) | Obtém ou define a incorporação de fontes no documento resultante |
| [setHtmlMediaType](#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-) | Obtém ou define os tipos de mídia possíveis usados durante a renderização. |
| [setInputEncoding](#setInputEncoding-java.lang.String-) | Define o atributo que especifica a codificação usada para este documento no momento da análise. Se este atributo for nulo, a codificação será determinada a partir do conjunto de caracteres do documento. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Define as informações da página do documento |
| [setPageLayoutOption](#setPageLayoutOption-int-) | Obtém ou define a opção de layout. |
| [setPriorityCssPageRule](#setPriorityCssPageRule-boolean-) | Obtém ou define o sinalizador que especifica que as regras @page definidas em css substituirão os valores definidos em PageInfo. |
| [setRenderToSinglePage](#setRenderToSinglePage-boolean-) | Obtém ou define a renderização de todo o documento em uma única página |

### HtmlLoadOptions {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```

Cria opções de carregamento para converter html em documento pdf com caminho base vazio.

### HtmlLoadOptions {#HtmlLoadOptions-java.lang.String-}
Cria opções de carregamento para converter html em documento pdf com caminho base vazio.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

O caminho/base ou URL para o arquivo html.

**Returns:**
valor String

### getCustomLoaderOfExternalResources {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```

Às vezes é necessário evitar o uso do carregador interno de recursos externos (como imagens ou CSSes) e fornecer um método personalizado que obtenha os recursos solicitados de algum lugar. Por exemplo, durante o uso do Aspose.PDF na nuvem, o acesso direto aos arquivos referenciados é impossível: nesse caso, algum código do cliente colocado em um método especial deve ser usado, e o delegate que referencia esse método deve ser atribuído a este atributo.

**Returns:**
Instância de ResourceLoadingStrategy

### getHtmlMediaType {#getHtmlMediaType--}
```
public HtmlMediaType getHtmlMediaType()
```

Obtém ou define os tipos de mídia possíveis usados durante a renderização.

**Returns:**
Elemento HtmlMediaType

### getInputEncoding {#getInputEncoding--}
```
public String getInputEncoding()
```

Obtém o atributo que especifica a codificação usada para este documento no momento da análise. Se este atributo for nulo, a codificação será determinada a partir do conjunto de caracteres do documento.

**Returns:**
valor String

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Obtém informações da página do documento

**Returns:**
informação da página

### getPageLayoutOption {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```

Obtém ou define a opção de layout.

**Returns:**
Elemento HtmlPageLayoutOption @see HtmlPageLayoutOption

### isEmbedFonts {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```

Obtém ou define a incorporação de fontes no documento resultante

**Returns:**
valor booleano

### isPriorityCssPageRule {#isPriorityCssPageRule--}
```
public final boolean isPriorityCssPageRule()
```

Obtém ou define o sinalizador que especifica que as regras @page definidas em css substituirão os valores definidos em PageInfo.

**Returns:**
valor booleano

### isRenderToSinglePage {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```

Obtém ou define a renderização de todo o documento em uma única página

**Returns:**
valor booleano

### setCustomLoaderOfExternalResources {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
Às vezes é necessário evitar o uso do carregador interno de recursos externos (como imagens ou CSSes) e fornecer um método personalizado que obtenha os recursos solicitados de algum lugar.

### setEmbedFonts {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```

Obtém ou define a incorporação de fontes no documento resultante

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHtmlMediaType {#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-}
Obtém ou define os tipos de mídia possíveis usados durante a renderização.

### setInputEncoding {#setInputEncoding-java.lang.String-}
Define o atributo que especifica a codificação usada para este documento no momento da análise. Se este atributo for nulo, a codificação será determinada a partir do conjunto de caracteres do documento.

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Define as informações da página do documento

### setPageLayoutOption {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```

Obtém ou define a opção de layout.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento HtmlPageLayoutOption @see HtmlPageLayoutOption |

### setPriorityCssPageRule {#setPriorityCssPageRule-boolean-}
```
public final void setPriorityCssPageRule(boolean value)
```

Obtém ou define o sinalizador que especifica que as regras @page definidas em css substituirão os valores definidos em PageInfo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRenderToSinglePage {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```

Obtém ou define a renderização de todo o documento em uma única página

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
