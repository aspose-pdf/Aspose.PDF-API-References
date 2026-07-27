---
title: "BaseOperatorCollection"
linktitle: "BaseOperatorCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a classe base para a coleção de operadores."
type: docs
weight: 270
url: /pt/java/com.aspose.pdf/baseoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public abstract class BaseOperatorCollection extends Object implements Iterable < Operator >
```

Representa a classe base para a coleção de operadores.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [BaseOperatorCollection](#BaseOperatorCollection--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Adiciona novo operador à coleção. |
| [cancelUpdate](#cancelUpdate--) | Cancela a última atualização. Este método pode ser chamado quando a alteração não deve disparar a atualização de conteúdo. |
| [clear](#clear--) | Limpa a coleção. |
| [contains](#contains-com.aspose.pdf.Operator-) | Verifica se o item está na coleção. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | interno |
| [get_Item](#get_Item-int-) | Obtém o operador pelo seu índice. |
| [getUnrestricted](#getUnrestricted-int-) | Somente para uso interno |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Insere o operador na coleção. |
| [isEmpty](#isEmpty--) | Retorna TRUE se a coleção estiver vazia. |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indica se a coleção está limitada à extração rápida de texto |
| [isReadOnly](#isReadOnly--) | Retorna true se a coleção for somente leitura. |
| [iterator](#iterator--) | Retorna um enumerador para a coleção |
| [remove](#remove-com.aspose.pdf.Operator-) | Remove o operador da coleção. |
| [resumeUpdate](#resumeUpdate--) | Retoma a atualização do documento. Atualiza o fluxo de conteúdo caso existam alterações pendentes. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Define o operador pelo seu índice. |
| [size](#size--) | Obtém a contagem de operadores na coleção. |
| [suppressUpdate](#suppressUpdate--) | Suprime a atualização dos dados de conteúdo. O fluxo de conteúdo não é atualizado até que ResumeUpdate seja chamado. |
| [toList](#toList--) | Retorna a lista de opetator. |
| [updateData](#updateData--) | interno |

### BaseOperatorCollection {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```



### add {#add-com.aspose.pdf.Operator-}
Adiciona novo operador à coleção.

### cancelUpdate {#cancelUpdate--}
```
public abstract void cancelUpdate()
```

Cancela a última atualização. Este método pode ser chamado quando a alteração não deve disparar a atualização de conteúdo.

### clear {#clear--}
```
public abstract void clear()
```

Limpa a coleção.

### contains {#contains-com.aspose.pdf.Operator-}
Verifica se o item está na coleção.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```

interno

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | valor int |

### get_Item {#get_Item-int-}
```
public abstract Operator get_Item(int index)
```

Obtém o operador pelo seu índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice do operador. A numeração começa em 1. |

**Returns:**
Operador do índice solicitado

### getUnrestricted {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```

Somente para uso interno

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | valor int |

**Returns:**
Objeto operador

### insert {#insert-int-com.aspose.pdf.Operator-}
Insere o operador na coleção.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Retorna TRUE se a coleção estiver vazia.

**Returns:**
valor booleano

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```

Indica se a coleção está limitada à extração rápida de texto

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public abstract boolean isReadOnly()
```

Retorna true se a coleção for somente leitura.

**Returns:**
valor booleano

### iterator {#iterator--}
```
public abstract Iterator < Operator > iterator()
```

Retorna um enumerador para a coleção

**Returns:**
Enumerador da coleção

### remove {#remove-com.aspose.pdf.Operator-}
Remove o operador da coleção.

### resumeUpdate {#resumeUpdate--}
```
public abstract void resumeUpdate()
```

Retoma a atualização do documento. Atualiza o fluxo de conteúdo caso existam alterações pendentes.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Define o operador pelo seu índice.

### size {#size--}
```
public abstract int size()
```

Obtém a contagem de operadores na coleção.

**Returns:**
valor inteiro

### suppressUpdate {#suppressUpdate--}
```
public abstract void suppressUpdate()
```

Suprime a atualização dos dados de conteúdo. O fluxo de conteúdo não é atualizado até que ResumeUpdate seja chamado.

### toList {#toList--}
```
public abstract com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Retorna a lista de opetator.

**Returns:**
lista de opetator.

### updateData {#updateData--}
```
public abstract void updateData()
```

interno
