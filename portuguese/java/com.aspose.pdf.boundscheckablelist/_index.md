---
title: "com.aspose.pdf.boundscheckablelist"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa BoundsCheckableList - um wrapper em torno de System.Collections.Generic.List."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.boundscheckablelist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.boundscheckablelist.BoundsCheckableList<T>

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<T>, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T>, com.aspose.ms.System.Collections.Generic.IGenericList<T>, com.aspose.ms.System.Collections.IEnumerable<T>, Iterable <T>

```
public class BoundsCheckableList<T extends IBoundsCheckableItem > extends Object implements com.aspose.ms.System.Collections.Generic.IGenericList<T>
```

Representa BoundsCheckableList - um wrapper em torno de System.Collections.Generic.List.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [BoundsCheckableList](#BoundsCheckableList--) | Inicializa uma nova instância da classe BoundsCheckableList. |
| [BoundsCheckableList](#BoundsCheckableList-int-double-double-) | Inicializa uma nova instância da classe BoundsCheckableList. |

## Métodos

| Método | Descrição |
| --- | --- |
| [addItem](#addItem-T-) | Adiciona um objeto ao final de System.Collections.Generic.List dependendo do parâmetro \"boundsCheckMode\". |
| [clear](#clear--) | Remove todos os elementos de System.Collections.Generic.List. |
| [containsItem](#containsItem-T-) | Determina se um elemento está em System.Collections.Generic.List. |
| [copyToTArray](#copyToTArray-T:A-int-) | Copia toda a System.Collections.Generic.List para um array unidimensional compatível, começando no índice especificado do array de destino. |
| [get_Item](#get_Item-int-) | Obtém ou define o parágrafo da ou para a coleção. |
| [indexOfItem](#indexOfItem-T-) | Procura o objeto especificado e retorna o índice baseado em zero da primeira ocorrência dentro de toda a System.Collections.Generic.List. |
| [insertItem](#insertItem-int-T-) | Insere um elemento em System.Collections.Generic.List no índice especificado. |
| [isReadOnly](#isReadOnly--) | Obtém o valor que indica se a coleção é somente leitura. |
| [iterator](#iterator--) | Retorna um enumerador que itera através de System.Collections.Generic.List. |
| [removeAt](#removeAt-int-) | Remove o elemento no índice especificado da System.Collections.Generic.List. |
| [removeItem](#removeItem-T-) | Remove a primeira ocorrência de um objeto específico da System.Collections.Generic.List. |
| [set_Item](#set_Item-int-T-) | Obtém ou define o parágrafo da ou para a coleção. |
| [size](#size--) | Obtém o número de elementos contidos na System.Collections.Generic.List. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-) | Atualiza o parâmetro boundsCheckMode para a coleção inicializada. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-double-double-) | Atualiza o parâmetro boundsCheckMode para a coleção inicializada. |

### BoundsCheckableList {#BoundsCheckableList--}
```
public BoundsCheckableList()
```

Inicializa uma nova instância da classe BoundsCheckableList.

### BoundsCheckableList {#BoundsCheckableList-int-double-double-}
```
public BoundsCheckableList(int boundsCheckMode, double containerWidth, double containerHeight)
```

Inicializa uma nova instância da classe BoundsCheckableList.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| boundsCheckMode |  | O modo de verificação de limites. |
| containerWidth |  | A largura do contêiner. |
| containerHeight |  | A altura do contêiner. |

### addItem {#addItem-T-}
```
public final void addItem( T item)
```

Adiciona um objeto ao final de System.Collections.Generic.List dependendo do parâmetro \"boundsCheckMode\".

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item |  | O objeto a ser adicionado ao final da System.Collections.Generic.List. O valor pode ser "null" para tipos de referência. |

### clear {#clear--}
```
public final void clear()
```

Remove todos os elementos de System.Collections.Generic.List.

### containsItem {#containsItem-T-}
```
public final boolean containsItem( T item)
```

Determina se um elemento está em System.Collections.Generic.List.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item |  | O objeto a ser localizado na System.Collections.Generic.List. O valor pode ser null para tipos de referência. |

**Returns:**
verdadeiro se itemitem for encontrado na System.Collections.Generic.List; caso contrário, falso.

### copyToTArray {#copyToTArray-T:A-int-}
```
public final void copyToTArray( T [] array, int arrayIndex)
```

Copia toda a System.Collections.Generic.List para um array unidimensional compatível, começando no índice especificado do array de destino.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array |  | O System.Array unidimensional que é o destino dos elementos copiados da System.Collections.Generic.List. O System.Array deve ter indexação baseada em zero. |
| arrayIndex |  | O índice baseado em zero em array onde a cópia começa. |

### get_Item {#get_Item-int-}
```
public final T get_Item(int index)
```

Obtém ou define o parágrafo da ou para a coleção.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | O índice do parágrafo. |

**Returns:**
o elemento no índice especificado.

### indexOfItem {#indexOfItem-T-}
```
public final int indexOfItem( T item)
```

Procura o objeto especificado e retorna o índice baseado em zero da primeira ocorrência dentro de toda a System.Collections.Generic.List.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item |  | O objeto a ser localizado na System.Collections.Generic.List. O valor pode ser null para tipos de referência. |

**Returns:**
O índice baseado em zero da primeira ocorrência de itemitem dentro de toda a System.Collections.Generic.List, se encontrado; caso contrário, –1.

### insertItem {#insertItem-int-T-}
```
public final void insertItem(int index, T item)
```

Insere um elemento em System.Collections.Generic.List no índice especificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | O índice baseado em zero onde item deve ser inserido. |
| item |  | O objeto a ser inserido. O valor pode ser nulo para tipos de referência. |

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtém o valor que indica se a coleção é somente leitura.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< T > iterator()
```

Retorna um enumerador que itera através de System.Collections.Generic.List.

**Returns:**
Um enumerador para o System.Collections.Generic.List.

### removeAt {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove o elemento no índice especificado da System.Collections.Generic.List.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | O índice baseado em zero do elemento a ser removido. |

### removeItem {#removeItem-T-}
```
public final boolean removeItem( T item)
```

Remove a primeira ocorrência de um objeto específico da System.Collections.Generic.List.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item |  | O objeto a ser removido da System.Collections.Generic.List. O valor pode ser nulo para tipos de referência. |

**Returns:**
true se itemitem for removido com sucesso; caso contrário, false. Este método também retorna false se itemitem não for encontrado na System.Collections.Generic.List.

### set_Item {#set_Item-int-T-}
```
public final void set_Item(int index, T value)
```

Obtém ou define o parágrafo da ou para a coleção.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | O índice do parágrafo. |

### size {#size--}
```
public final int size()
```

Obtém o número de elementos contidos na System.Collections.Generic.List.

**Returns:**
O número de elementos contidos na System.Collections.Generic.List.

### updateBoundsCheckMode {#updateBoundsCheckMode-int-}
```
public final void updateBoundsCheckMode(int boundsCheckMode)
```

Atualiza o parâmetro boundsCheckMode para a coleção inicializada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| boundsCheckMode |  | O modo de verificação de limites. |

### updateBoundsCheckMode {#updateBoundsCheckMode-int-double-double-}
```
public final void updateBoundsCheckMode(int boundsCheckMode, double containerWidth, double containerHeight)
```

Atualiza o parâmetro boundsCheckMode para a coleção inicializada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| boundsCheckMode |  | O modo de verificação de limites. |
| containerWidth |  | A largura do contêiner. |
| containerHeight |  | A altura do contêiner. |
