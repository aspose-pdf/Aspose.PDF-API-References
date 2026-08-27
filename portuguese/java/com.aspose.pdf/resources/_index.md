---
title: "Recursos"
linktitle: "Recursos"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa recursos de página."
type: docs
weight: 4220
url: /pt/java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Resources

```
public final class Resources extends Object
```

Classe que representa recursos de página.

## Métodos

| Método | Descrição |
| --- | --- |
| [clearImagesCache](#clearImagesCache--) |  |
| [freeMemory](#freeMemory--) | Limpa dados em cache, libera memória etc. |
| [getExtGStates](#getExtGStates--) | Obtém todos os ExGStates dos recursos. |
| [getFonts](#getFonts--) | Obtém a coleção de recursos {@code Fonts} |
| [getFonts](#getFonts-boolean-) | Retorna a coleção de fontes. Se os recursos não contiverem a entrada de fontes, ela será criada dependendo da flag CreateIfAbsent. |
| [getForms](#getForms--) | Obtém a coleção de formulários {@code Forms} |
| [getImages](#getImages--) | Obtém a coleção de imagens {@code Images} |
| [getResourceDictionary](#getResourceDictionary--) | Campo interno |
| [getResourcesFor](#getResourcesFor-com.aspose.pdf.Form-) | Obtém recursos para |
| [isCommonResource](#isCommonResource--) | Verdadeiro se estes recursos são comuns, ou seja, são compartilhados por várias páginas (colocados no dicionário de páginas ou em cada página como referência de objeto). A manipulação de recursos comuns deve ser realizada com muito cuidado; por exemplo, excluir um objeto dos recursos comuns em uma página pode causar erros em outras páginas se o objeto excluído era usado por elas. |
| [setResourceDictionary](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | Somente para uso interno! |

### clearImagesCache {#clearImagesCache--}
```
public final void clearImagesCache()
```



### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Limpa dados em cache, libera memória etc.

### getExtGStates {#getExtGStates--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , Resources.ExtGStateValue > getExtGStates()
```

Obtém todos os ExGStates dos recursos.

**Returns:**
Retorna um dicionário com chaves de nomes ExGStates.

### getFonts {#getFonts--}
```
public FontCollection getFonts()
```

Obtém a coleção de recursos {@code Fonts}

**Returns:**
Objeto FontCollection

### getFonts {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```

Retorna a coleção de fontes. Se os recursos não contiverem a entrada de fontes, ela será criada dependendo da flag CreateIfAbsent.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| createIfAbsent |  | Se esta bandeira for verdadeira, as fontes serão criadas se esta entrada estiver ausente. |

**Returns:**
Coleção de fontes.

### getForms {#getForms--}
```
public XFormCollection getForms()
```

Obtém a coleção de formulários {@code Forms}

**Returns:**
Objeto XFormCollection

### getImages {#getImages--}
```
public XImageCollection getImages()
```

Obtém a coleção de imagens {@code Images}

**Returns:**
Objeto XImageCollection

### getResourceDictionary {#getResourceDictionary--}
```
public com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary getResourceDictionary()
```

Campo interno

### getResourcesFor {#getResourcesFor-com.aspose.pdf.Form-}
Obtém recursos para

### isCommonResource {#isCommonResource--}
```
public boolean isCommonResource()
```

Verdadeiro se estes recursos são comuns, ou seja, são compartilhados por várias páginas (colocados no dicionário de páginas ou em cada página como referência de objeto). A manipulação de recursos comuns deve ser realizada com muito cuidado; por exemplo, excluir um objeto dos recursos comuns em uma página pode causar erros em outras páginas se o objeto excluído era usado por elas.

**Returns:**
valor booleano

### setResourceDictionary {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
Somente para uso interno!
