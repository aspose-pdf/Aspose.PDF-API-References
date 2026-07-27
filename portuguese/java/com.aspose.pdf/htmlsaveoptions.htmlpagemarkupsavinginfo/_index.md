---
title: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Se a propriedade SplitToPages de HtmlSaveOptions estiver definida, então vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão de PDF para HTML. Esta classe representa um conjunto de."
type: docs
weight: 2100
url: /pt/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo

```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo extends Object
```

Se a propriedade SplitToPages de HtmlSaveOptions estiver habilitada, vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão de PDF para HTML. Esta classe representa um conjunto de dados relacionados ao salvamento personalizado da marcação de uma página HTML durante a conversão de PDF para HTML.

## Métodos

| Método | Descrição |
| --- | --- |
| [getContentStream](#getContentStream--) | Definido pelo conversor. Representa HTML salvo como fluxo |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Definido pelo conversor. Se a propriedade SplitToPages estiver definida, então vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão. Esta propriedade contém o ordinal do arquivo da página HTML salva. A propriedade pode ser usada na lógica de código personalizado para decidir como processar ou onde salvar a página HTML e, se a divisão em páginas estiver desativada, esse valor sempre contém '1', pois nesse caso apenas uma grande página HTML é gerada para todo o documento de origem. |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Definido pelo conversor. Se a propriedade SplitToPages estiver definida, então vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão. Esta propriedade informa ao código personalizado de qual página do PDF original foi criado o markup HTML salvo. Se o número da página original, por algum motivo, for desconhecido ou SplitOnPages=false, então esta propriedade sempre contém '0', o que indica que o conversor não pode fornecer o número exato da página original do PDF para o arquivo de markup HTML fornecido. |
| [getSupposedFileName](#getSupposedFileName--) | Definido pelo conversor. Nome de arquivo suposto que vem do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar o conteúdo. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Deve ser definido no código personalizado quando necessário. Esta flag deve ser definida como "true" no código personalizado se, por algum motivo, o markup HTML fornecido deve ser processado não pelo código personalizado, mas pelo próprio código do conversor de forma padrão. Portanto, definir esta flag no código personalizado significa que o código personalizado não processou o arquivo referenciado e o conversor deve tratá‑lo. |
| [setContentStream](#setContentStream-java.io.InputStream-) | Definido pelo conversor. Representa HTML salvo como fluxo |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Deve ser definido no código personalizado quando necessário. Esta flag deve ser definida como "true" no código personalizado se, por algum motivo, o markup HTML fornecido deve ser processado não pelo código personalizado, mas pelo próprio código do conversor de forma padrão. Portanto, definir esta flag no código personalizado significa que o código personalizado não processou o arquivo referenciado e o conversor deve tratá‑lo. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Definido pelo conversor. Se a propriedade SplitToPages estiver definida, então vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão. Esta propriedade contém o ordinal do arquivo da página HTML salva. A propriedade pode ser usada na lógica de código personalizado para decidir como processar ou onde salvar a página HTML e, se a divisão em páginas estiver desativada, esse valor sempre contém '1', pois nesse caso apenas uma grande página HTML é gerada para todo o documento de origem. |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Definido pelo conversor. Se a propriedade SplitToPages estiver definida, então vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão. Esta propriedade informa ao código personalizado de qual página do PDF original foi criado o markup HTML salvo. Se o número da página original, por algum motivo, for desconhecido ou SplitOnPages=false, então esta propriedade sempre contém '0', o que indica que o conversor não pode fornecer o número exato da página original do PDF para o arquivo de markup HTML fornecido. |
| [setSupposedFileName](#setSupposedFileName-java.lang.String-) | Definido pelo conversor. Nome de arquivo suposto que vem do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar o conteúdo. |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

Definido pelo conversor. Representa HTML salvo como fluxo

**Returns:**
Instância de InputStream

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Definido pelo conversor. Se a propriedade SplitToPages estiver definida, então vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão. Esta propriedade contém o ordinal do arquivo da página HTML salva. A propriedade pode ser usada na lógica de código personalizado para decidir como processar ou onde salvar a página HTML e, se a divisão em páginas estiver desativada, esse valor sempre contém '1', pois nesse caso apenas uma grande página HTML é gerada para todo o documento de origem.

**Returns:**
valor int

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Definido pelo conversor. Se a propriedade SplitToPages estiver definida, então vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão. Esta propriedade informa ao código personalizado de qual página do PDF original foi criado o markup HTML salvo. Se o número da página original, por algum motivo, for desconhecido ou SplitOnPages=false, então esta propriedade sempre contém '0', o que indica que o conversor não pode fornecer o número exato da página original do PDF para o arquivo de markup HTML fornecido.

**Returns:**
valor int

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Definido pelo conversor. Nome de arquivo suposto que vem do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar o conteúdo.

**Returns:**
valor String

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Deve ser definido no código personalizado quando necessário. Esta flag deve ser definida como "true" no código personalizado se, por algum motivo, o markup HTML fornecido deve ser processado não pelo código personalizado, mas pelo próprio código do conversor de forma padrão. Portanto, definir esta flag no código personalizado significa que o código personalizado não processou o arquivo referenciado e o conversor deve tratá‑lo.

**Returns:**
valor booleano

### setContentStream {#setContentStream-java.io.InputStream-}
Definido pelo conversor. Representa HTML salvo como fluxo

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Deve ser definido no código personalizado quando necessário. Esta flag deve ser definida como "true" no código personalizado se, por algum motivo, o markup HTML fornecido deve ser processado não pelo código personalizado, mas pelo próprio código do conversor de forma padrão. Portanto, definir esta flag no código personalizado significa que o código personalizado não processou o arquivo referenciado e o conversor deve tratá‑lo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| customProcessingCancelled |  | valor booleano |

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Definido pelo conversor. Se a propriedade SplitToPages estiver definida, então vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão. Esta propriedade contém o ordinal do arquivo da página HTML salva. A propriedade pode ser usada na lógica de código personalizado para decidir como processar ou onde salvar a página HTML e, se a divisão em páginas estiver desativada, esse valor sempre contém '1', pois nesse caso apenas uma grande página HTML é gerada para todo o documento de origem.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlHostPageNumber |  | valor int |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Definido pelo conversor. Se a propriedade SplitToPages estiver definida, então vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão. Esta propriedade informa ao código personalizado de qual página do PDF original foi criado o markup HTML salvo. Se o número da página original, por algum motivo, for desconhecido ou SplitOnPages=false, então esta propriedade sempre contém '0', o que indica que o conversor não pode fornecer o número exato da página original do PDF para o arquivo de markup HTML fornecido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pdfHostPageNumber |  | valor int |

### setSupposedFileName {#setSupposedFileName-java.lang.String-}
Definido pelo conversor. Nome de arquivo suposto que vem do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar o conteúdo.
