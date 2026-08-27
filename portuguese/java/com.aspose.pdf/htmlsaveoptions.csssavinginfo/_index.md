---
title: "HtmlSaveOptions.CssSavingInfo"
linktitle: "HtmlSaveOptions.CssSavingInfo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta classe representa um conjunto de dados relacionados ao salvamento personalizado de CSS durante a conversão de PDF para formato HTML"
type: docs
weight: 2010
url: /pt/java/com.aspose.pdf/htmlsaveoptions.csssavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.CssSavingInfo

```
public static class HtmlSaveOptions.CssSavingInfo extends Object
```

Esta classe representa um conjunto de dados relacionados ao salvamento personalizado de CSS durante a conversão de PDF para formato HTML

## Métodos

| Método | Descrição |
| --- | --- |
| [getContentStream](#getContentStream--) | Definido pelo conversor. Representa o conteúdo binário do CSS salvo |
| [getCssNumber](#getCssNumber--) | Definido pelo conversor. Durante a conversão, vários arquivos CSS são criados. Esta propriedade mostra a ordem do arquivo CSS salvo durante a conversão. Pode ser usada na lógica de código personalizado para decidir como processar ou onde salvar o conteúdo CSS. |
| [getSupposedURL](#getSupposedURL--) | Definido pelo conversor. Nome de arquivo suposto que vem do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar o conteúdo. |
| [setContentStream](#setContentStream-java.io.InputStream-) | Definido pelo conversor. Representa o conteúdo binário do CSS salvo |
| [setCssNumber](#setCssNumber-int-) | Definido pelo conversor. Durante a conversão, vários arquivos CSS são criados. Esta propriedade mostra a ordem do arquivo CSS salvo durante a conversão. Pode ser usada na lógica de código personalizado para decidir como processar ou onde salvar o conteúdo CSS. |
| [setSupposedURL](#setSupposedURL-java.lang.String-) | Definido pelo conversor. Nome de arquivo suposto que vem do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar o conteúdo. |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

Definido pelo conversor. Representa o conteúdo binário do CSS salvo

**Returns:**
Instância de InputStream

### getCssNumber {#getCssNumber--}
```
public int getCssNumber()
```

Definido pelo conversor. Durante a conversão, vários arquivos CSS são criados. Esta propriedade mostra a ordem do arquivo CSS salvo durante a conversão. Pode ser usada na lógica de código personalizado para decidir como processar ou onde salvar o conteúdo CSS.

**Returns:**
valor int

### getSupposedURL {#getSupposedURL--}
```
public String getSupposedURL()
```

Definido pelo conversor. Nome de arquivo suposto que vem do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar o conteúdo.

**Returns:**
valor String

### setContentStream {#setContentStream-java.io.InputStream-}
Definido pelo conversor. Representa o conteúdo binário do CSS salvo

### setCssNumber {#setCssNumber-int-}
```
public void setCssNumber(int cssNumber)
```

Definido pelo conversor. Durante a conversão, vários arquivos CSS são criados. Esta propriedade mostra a ordem do arquivo CSS salvo durante a conversão. Pode ser usada na lógica de código personalizado para decidir como processar ou onde salvar o conteúdo CSS.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cssNumber |  | valor int |

### setSupposedURL {#setSupposedURL-java.lang.String-}
Definido pelo conversor. Nome de arquivo suposto que vem do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar o conteúdo.
