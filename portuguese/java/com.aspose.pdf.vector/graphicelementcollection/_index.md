---
title: "GraphicElementCollection"
linktitle: "GraphicElementCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a coleção {@link GraphicElement}."
type: docs
weight: 20
url: /pt/java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElementCollection

**All Implemented Interfaces:**
Iterable < GraphicElement >

```
public final class GraphicElementCollection extends Object implements Iterable < GraphicElement >
```

Representa a coleção {@link GraphicElement}.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [GraphicElementCollection](#GraphicElementCollection--) | Inicializa a nova coleção. |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.vector.GraphicElement-) | Adiciona um novo {@link GraphicElement} à coleção. Todos os itens na coleção devem ter o mesmo {@code GraphicElement.Parent}({@link GraphicElement#getParent}). |
| [clear](#clear--) | Limpa a coleção. |
| [contains](#contains-com.aspose.pdf.vector.GraphicElement-) | Determina se um elemento está na coleção. |
| [copyTo](#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-) | Copia toda a coleção para um Array unidimensional compatível, começando no índice especificado do array de destino. |
| [get_Item](#get_Item-int-) | Obtém o elemento {@link GraphicElement} no índice especificado. |
| [isReadOnly](#isReadOnly--) | Obtém um valor que indica se a coleção é somente leitura. Sempre retorna false. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Retorna um enumerador para toda a coleção. |
| [iterator](#iterator--) | Retorna um enumerador para toda a coleção. |
| [remove](#remove-com.aspose.pdf.vector.GraphicElement-) | Exclui o elemento {@link GraphicElement}. |
| [size](#size--) | Obtém o número de objetos {@link GraphicElement} realmente contidos na coleção. |
| [toList](#toList--) | Retorna a coleção interna para enumeração irrestrita. |
| [toString](#toString--) | Obtém uma representação em string desta coleção. |

### GraphicElementCollection {#GraphicElementCollection--}
```
public GraphicElementCollection()
```

Inicializa a nova coleção.

### add {#add-com.aspose.pdf.vector.GraphicElement-}
Adiciona um novo {@link GraphicElement} à coleção. Todos os itens na coleção devem ter o mesmo {@code GraphicElement.Parent}({@link GraphicElement#getParent}).

### clear {#clear--}
```
public final void clear()
```

Limpa a coleção.

### contains {#contains-com.aspose.pdf.vector.GraphicElement-}
Determina se um elemento está na coleção.

### copyTo {#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-}
Copia toda a coleção para um Array unidimensional compatível, começando no índice especificado do array de destino.

### get_Item {#get_Item-int-}
```
public final GraphicElement get_Item(int index)
```

Obtém o elemento {@link GraphicElement} no índice especificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice dentro da coleção. |

**Returns:**
{@link GraphicElement}.

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtém um valor que indica se a coleção é somente leitura. Sempre retorna false.

**Returns:**
valor booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Retorna um enumerador para toda a coleção.

**Returns:**
Objeto enumerador.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< GraphicElement > iterator()
```

Retorna um enumerador para toda a coleção.

**Returns:**
Objeto enumerador.

### remove {#remove-com.aspose.pdf.vector.GraphicElement-}
Exclui o elemento {@link GraphicElement}.

### size {#size--}
```
public final int size()
```

Obtém o número de objetos {@link GraphicElement} realmente contidos na coleção.

**Returns:**
valor int

### toList {#toList--}
```
public final com.aspose.ms.System.Collections.Generic.List< GraphicElement > toList()
```

Retorna a coleção interna para enumeração irrestrita.

**Returns:**
Lista interna

### toString {#toString--}
```
public String toString()
```

Obtém uma representação em string desta coleção.

**Returns:**
A string.
