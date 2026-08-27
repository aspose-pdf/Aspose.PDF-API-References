---
title: "OutlineCollection"
linktitle: "OutlineCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a hierarquia de contorno do documento."
type: docs
weight: 3260
url: /pt/java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineCollection extends Outlines
```

Representa a hierarquia de contorno do documento.

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Adiciona item de contorno à coleção. |
| [clear](#clear--) | Limpa todos os itens da coleção. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Ainda não suportado. Verifica se a coleção contém o item fornecido. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Copia os itens de contorno para um System.Array, iniciando em um índice específico do System.Array. |
| [delete](#delete--) | Exclui todos os itens de contorno do contorno do documento. |
| [delete](#delete-java.lang.String-) | Exclui todos os itens de contorno do contorno do documento. |
| [get_Item](#get_Item-int-) | Obtém o item de contorno da coleção por índice. |
| [getFirst](#getFirst--) | Obtém um item de contorno que representa o primeiro item de nível superior no contorno. |
| [getLast](#getLast--) | Obtém um item de contorno que representa o último item de nível superior no contorno. |
| [getSyncRoot](#getSyncRoot--) | Obtém um objeto que pode ser usado para sincronizar o acesso a esta coleção. |
| [getVisibleCount](#getVisibleCount--) | Count é a soma do número de itens de contorno descendentes visíveis em todos os níveis. Nota: por favor, não confunda com Count que é o número de itens na coleção. |
| [hasNext](#hasNext--) |  |
| [isReadOnly](#isReadOnly--) | Obtém um valor que indica se a coleção é somente leitura. |
| [isSynchronized](#isSynchronized--) | Obtém um valor que indica se o acesso a esta coleção está sincronizado (thread safe). |
| [iterator](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [next](#next--) |  |
| [remove](#remove-int-) | Remove o item por índice. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Ainda não suportado. Sempre lança uma exceção |
| [size](#size--) | Obtém o número total de itens de contorno (marcadores) em todos os níveis do contorno do documento. |

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Adiciona item de contorno à coleção.

### clear {#clear--}
```
public void clear()
```

Limpa todos os itens da coleção.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Ainda não suportado. Verifica se a coleção contém o item fornecido.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Copia os itens de contorno para um System.Array, iniciando em um índice específico do System.Array.

### delete {#delete--}
```
public void delete()
```

Exclui todos os itens de contorno do contorno do documento.

### delete {#delete-java.lang.String-}
Exclui todos os itens de contorno do contorno do documento.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Obtém o item de contorno da coleção por índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice do item solicitado. |

**Returns:**
Objeto OutlineItemCollection

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Obtém um item de contorno que representa o primeiro item de nível superior no contorno.

**Returns:**
Objeto OutlineItemCollection

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Obtém um item de contorno que representa o último item de nível superior no contorno.

**Returns:**
Objeto OutlineItemCollection

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtém um objeto que pode ser usado para sincronizar o acesso a esta coleção.

**Returns:**
Objeto para sincronização

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Count é a soma do número de itens de contorno descendentes visíveis em todos os níveis. Nota: por favor, não confunda com Count que é o número de itens na coleção.

**Returns:**
valor int

### hasNext {#hasNext--}
```
public boolean hasNext()
```



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

Obtém um valor que indica se o acesso a esta coleção está sincronizado (thread safe).

**Returns:**
valor booleano

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Retorna um enumerador que itera através da coleção.

**Returns:**
Um objeto System.Collections.IEnumerator que pode ser usado para iterar através da coleção.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

Remove o item por índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice do item a ser removido. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Ainda não suportado. Sempre lança uma exceção

### size {#size--}
```
public int size()
```

Obtém o número total de itens de contorno (marcadores) em todos os níveis do contorno do documento.

**Returns:**
valor int
