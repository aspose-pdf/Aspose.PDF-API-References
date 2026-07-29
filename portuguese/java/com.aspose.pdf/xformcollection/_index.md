---
title: "XFormCollection"
linktitle: "XFormCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa a coleção XFormCollection."
type: docs
weight: 5600
url: /pt/java/com.aspose.pdf/xformcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFormCollection

**All Implemented Interfaces:**
Iterable < XForm >

```
public final class XFormCollection extends Object implements Iterable < XForm >
```

Classe que representa a coleção XFormCollection.

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.XForm-) | Adiciona um novo XForm à coleção. |
| [clear](#clear--) | Limpa todos os itens da coleção. |
| [contains](#contains-com.aspose.pdf.XForm-) | Determina se a coleção contém um valor específico. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | Copia XFormCollection para a coleção. |
| [delete](#delete--) | Exclui todos os XForms da coleção. |
| [delete](#delete-int-) | Excluir XForm da coleção |
| [delete](#delete-java.lang.String-) | Exclui todos os XForms da coleção. |
| [freeMemory](#freeMemory--) | Limpa dados em cache, libera memória etc. |
| [get_Item](#get_Item-int-) | Retorna XForm por índice. |
| [get_Item](#get_Item-java.lang.String-) | Retorna XForm pelo seu nome. Uma exceção é lançada se XForm com o nome especificado não for encontrado. |
| [getFormName](#getFormName-com.aspose.pdf.XForm-) | Retorna o nome do formulário nesta coleção de formulários |
| [getSyncRoot](#getSyncRoot--) | Objeto de sincronização. |
| [hasForm](#hasForm-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | Obtém um valor que indica se a coleção é somente leitura. |
| [isSynchronized](#isSynchronized--) | Retorna true se o objeto estiver sincronizado. |
| [iterator](#iterator--) | Retorna o enumerador da coleção. |
| [remove](#remove-com.aspose.pdf.XForm-) | Exclui o item especificado da coleção. |
| [size](#size--) | Obtém a contagem de XForms na coleção. |

### add {#add-com.aspose.pdf.XForm-}
Adiciona um novo XForm à coleção.

### clear {#clear--}
```
public void clear()
```

Limpa todos os itens da coleção.

### contains {#contains-com.aspose.pdf.XForm-}
Determina se a coleção contém um valor específico.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
Copia XFormCollection para a coleção.

### delete {#delete--}
```
public void delete()
```

Exclui todos os XForms da coleção.

### delete {#delete-int-}
```
public void delete(int index)
```

Excluir XForm da coleção

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice do XForm que deve ser excluído |

### delete {#delete-java.lang.String-}
Exclui todos os XForms da coleção.

### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Limpa dados em cache, libera memória etc.

### get_Item {#get_Item-int-}
```
public XForm get_Item(int index)
```

Retorna XForm por índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice da XFormCollection. A numeração dos XForms começa em 1 |

**Returns:**
XForm recuperado

### get_Item {#get_Item-java.lang.String-}
Retorna XForm pelo seu nome. Uma exceção é lançada se XForm com o nome especificado não for encontrado.

### getFormName {#getFormName-com.aspose.pdf.XForm-}
Retorna o nome do formulário nesta coleção de formulários

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Objeto de sincronização.

**Returns:**
Objeto

### hasForm {#hasForm-java.lang.String-}


### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtém um valor que indica se a coleção é somente leitura.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Retorna true se o objeto estiver sincronizado.

**Returns:**
boolean

### iterator {#iterator--}
```
public Iterator < XForm > iterator()
```

Retorna o enumerador da coleção.

**Returns:**
Enumerador da coleção

### remove {#remove-com.aspose.pdf.XForm-}
Exclui o item especificado da coleção.

### size {#size--}
```
public int size()
```

Obtém a contagem de XForms na coleção.

**Returns:**
valor int
