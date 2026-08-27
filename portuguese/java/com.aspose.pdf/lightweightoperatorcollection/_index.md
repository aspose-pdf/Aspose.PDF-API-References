---
title: "LightweightOperatorCollection"
linktitle: "LightweightOperatorCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Coleção de operadores leve. Destinada a ser usada em cenários onde o fluxo de conteúdo subjacente não está anexado, e apenas a coleção de operadores é necessária como resultado."
type: docs
weight: 2700
url: /pt/java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.LightweightOperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.LightweightOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

Coleção de operadores leve. Destinada a ser usada em cenários onde o fluxo de conteúdo subjacente não está anexado, e apenas a coleção de operadores é necessária como resultado.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [LightweightOperatorCollection](#LightweightOperatorCollection--) | Inicializar objeto |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-) | Inicializar objeto |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | Inicializar objeto |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Adicionar operador |
| [addRange](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | Adicionar LightweightOperatorCollection |
| [cancelUpdate](#cancelUpdate--) | Cancela a última atualização. Este método pode ser chamado quando a alteração não deve disparar a atualização de conteúdo. |
| [clear](#clear--) | Limpa a coleção. |
| [contains](#contains-com.aspose.pdf.Operator-) | Verifica se o item está na coleção. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | exclusão interna Unrestrictedelement |
| [get_Item](#get_Item-int-) | <p> Obtém o operador pelo seu índice. </p> <hr> <pre> O exemplo demonstra como obter o operador do conteúdo da página pelo índice. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Para uso interno do operador getUnrestricted |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Inserir operador |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indica se a coleção está limitada à extração rápida de texto |
| [isReadOnly](#isReadOnly--) | Obtém um valor que indica se a coleção é somente leitura. |
| [iterator](#iterator--) | Retornar iterador |
| [remove](#remove-com.aspose.pdf.Operator-) | Remove o operador da coleção. |
| [resumeUpdate](#resumeUpdate--) | Retoma a atualização do documento. Atualiza o fluxo de conteúdo caso existam alterações pendentes. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Define o operador pelo seu índice. <hr> <pre> O exemplo demonstra como obter o operador do conteúdo da página pelo índice. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [size](#size--) | Contagem de operadores |
| [suppressUpdate](#suppressUpdate--) | Suprime a atualização dos dados de conteúdo. O fluxo de conteúdo não é atualizado até que ResumeUpdate seja chamado. |
| [toList](#toList--) | Retorna a lista de operadores. |
| [updateData](#updateData--) | interno |

### LightweightOperatorCollection {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```

Inicializar objeto

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-}
Inicializar objeto

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
Inicializar objeto

### add {#add-com.aspose.pdf.Operator-}
Adicionar operador

### addRange {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
Adicionar LightweightOperatorCollection

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Cancela a última atualização. Este método pode ser chamado quando a alteração não deve disparar a atualização de conteúdo.

### clear {#clear--}
```
public void clear()
```

Limpa a coleção.

### contains {#contains-com.aspose.pdf.Operator-}
Verifica se o item está na coleção.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

exclusão interna Unrestrictedelement

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | valor int |

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Obtém o operador pelo seu índice. </p> <hr> <pre> O exemplo demonstra como obter o operador do conteúdo da página pelo índice. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice do operador. A numeração começa em 1. |

**Returns:**
Operador do índice solicitado

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

Para uso interno do operador getUnrestricted

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | valor int |

**Returns:**
Objeto operador

### insert {#insert-int-com.aspose.pdf.Operator-}
Inserir operador

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

Indica se a coleção está limitada à extração rápida de texto

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtém um valor que indica se a coleção é somente leitura.

**Returns:**
valor booleano

### iterator {#iterator--}
```
public Iterator < Operator > iterator()
```

Retornar iterador

**Returns:**
{@code IGenericEnumerator<Operator>} objeto

### remove {#remove-com.aspose.pdf.Operator-}
Remove o operador da coleção.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Retoma a atualização do documento. Atualiza o fluxo de conteúdo caso existam alterações pendentes.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Define o operador pelo seu índice. <hr> <pre> O exemplo demonstra como obter o operador do conteúdo da página pelo índice. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

### size {#size--}
```
public int size()
```

Contagem de operadores

**Returns:**
valor int

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Suprime a atualização dos dados de conteúdo. O fluxo de conteúdo não é atualizado até que ResumeUpdate seja chamado.

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Retorna a lista de operadores.

**Returns:**
lista de operadores.

### updateData {#updateData--}
```
public void updateData()
```

interno
