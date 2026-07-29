---
title: "DestinationCollection"
linktitle: "DestinationCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "A classe representa a coleção de todos os destinos (uma árvore de nomes que mapeia strings de nomes para destinos (veja 12.3.2.3, \\\"Named Destinations\\\") e (veja 7.7.4, \\\"Name Dictionary\\\")) em."
type: docs
weight: 960
url: /pt/java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DestinationCollection

**All Implemented Interfaces:**
Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, Object >>

```
public final class DestinationCollection extends Object implements Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >>
```

Classe que representa a coleção de todos os destinos (uma árvore de nomes que mapeia strings de nomes para destinos (veja 12.3.2.3, "Named Destinations") e (veja 7.7.4, "Name Dictionary")) no documento PDF.

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Adiciona o item especificado. |
| [clear](#clear--) | A coleção é somente leitura. Sempre lança a exceção NotSupportedException. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Determina se esta instância contém o objeto. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia os elementos da coleção para um Array, começando em um índice específico do Array. |
| [get_Item](#get_Item-int-) | Obtém o objeto de destino por índice. |
| [getExplicitDestination](#getExplicitDestination-java.lang.String-boolean-) | Retorna o destino explícito pelo nome. |
| [getPageNumber](#getPageNumber-java.lang.String-boolean-) | Retorna o número da página do destino pelo nome. |
| [indexOf](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Retorna o índice do destino na coleção. |
| [isReadOnly](#isReadOnly--) | Obtém um valor que indica se a coleção é somente leitura. |
| [iterator](#iterator--) | Retorna o enumerador. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Remove o item especificado. |
| [size](#size--) | Obtém o número de elementos contidos na coleção. |

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Adiciona o item especificado.

### clear {#clear--}
```
public void clear()
```

A coleção é somente leitura. Sempre lança a exceção NotSupportedException.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Determina se esta instância contém o objeto.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia os elementos da coleção para um Array, começando em um índice específico do Array.

### get_Item {#get_Item-int-}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object > get_Item(int index)
```

Obtém o objeto de destino por índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | O índice do destino a obter. |

**Returns:**
Destino.

### getExplicitDestination {#getExplicitDestination-java.lang.String-boolean-}
Retorna o destino explícito pelo nome.

### getPageNumber {#getPageNumber-java.lang.String-boolean-}
Retorna o número da página do destino pelo nome.

### indexOf {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Retorna o índice do destino na coleção.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtém um valor que indica se a coleção é somente leitura.

**Returns:**
valor booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >> iterator()
```

Retorna o enumerador.

**Returns:**
O enumerador.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Remove o item especificado.

### size {#size--}
```
public int size()
```

Obtém o número de elementos contidos na coleção.

**Returns:**
valor int
