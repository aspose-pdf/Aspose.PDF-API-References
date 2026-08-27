---
title: "OperatorCollection"
linktitle: "OperatorCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa a coleção de operadores"
type: docs
weight: 3190
url: /pt/java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.OperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.OperatorCollection

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Iterable < Operator >

```
public class OperatorCollection extends BaseOperatorCollection implements com.aspose.ms.System.IDisposable
```

Classe que representa a coleção de operadores

## Construtores

| Construtor | Descrição |
| --- | --- |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | Somente para uso interno! |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-) | Somente para uso interno! |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante IOperatorSelector para processar operadores. |
| [add](#add-java.lang.Iterable-) | Adiciona à coleção todos os operadores de outra coleção. |
| [add](#add-com.aspose.pdf.Operator-) | <p> Adiciona um novo operador à coleção. </p> <hr> <p> O exemplo demonstra como adicionar operadores ao final de page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p> |
| [add](#add-com.aspose.pdf.Operator:A-) | <p> Adiciona operadores ao final dos operadores de conteúdo. </p> <hr> <p> O exemplo demonstra como adicionar um operador ao final do conteúdo da página. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [cancelUpdate](#cancelUpdate--) | Cancela a última atualização. Este método pode ser chamado quando a alteração não deve disparar a atualização de conteúdo. |
| [clear](#clear--) | <p> Remove todos os operadores da lista. </p> <hr> <p> O exemplo demonstra como limpar o conteúdo da página. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p> |
| [close](#close--) | Executa tarefas definidas pela aplicação associadas à liberação, descarte ou redefinição de recursos não gerenciados. |
| [contains](#contains-com.aspose.pdf.Operator-) | Retorna verdadeiro se a coleção contiver o operador especificado. |
| [delete](#delete-int-) | <p> Exclui o operador da coleção. </p> <hr> <p> O exemplo demonstra como excluir um operador pelo seu índice. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p> |
| [delete](#delete-java.lang.Iterable-) | Exclui operadores da coleção. |
| [delete](#delete-com.aspose.pdf.Operator:A-) | <p> Exclui operadores da coleção. </p> <hr> <p> O exemplo demonstra como remover um operador do conteúdo da página. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p> |
| [deleteUnrestricted](#deleteUnrestricted-int-) | versão interna sem restrições de Delete(index) |
| [dispose](#dispose--) | Executa tarefas definidas pela aplicação associadas à liberação, descarte ou redefinição de recursos não gerenciados. |
| [get_Item](#get_Item-int-) | <p> Obtém o operador pelo seu índice. </p> <hr> O exemplo demonstra como obter o operador do conteúdo da página pelo índice. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Versão interna sem restrições do indexador |
| [insert](#insert-int-java.lang.Iterable-) | Insere operadores na posição especificada. |
| [insert](#insert-int-com.aspose.pdf.Operator-) | <p> Insere um operador na coleção. </p> <hr> <p> O exemplo demonstra como inserir um operador no conteúdo da página. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p> |
| [insert](#insert-int-com.aspose.pdf.Operator:A-) | <p> Insere operadores na posição especificada. </p> <hr> <p> O exemplo demonstra como inserir um operador no conteúdo da página. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [isBracketed](#isBracketed--) | Obtém o status entre colchetes da sequência de operadores, ou seja, se esses operadores estão dentro de blocos q - Q |
| [isCommandsParsed](#isCommandsParsed--) | Obtém os comandos analisados |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indica se a coleção está limitada à extração rápida de texto |
| [isReadOnly](#isReadOnly--) | Obtém um valor que indica se a coleção é somente leitura. |
| [iterator](#iterator--) | Retorna um enumerador para a coleção |
| [precalculateOperatorsCount](#precalculateOperatorsCount--) | Obtém a quantidade de operadores que descrevem o conteúdo da página sem sua inicialização. |
| [remove](#remove-com.aspose.pdf.Operator-) | Remove o operador da coleção. |
| [replace](#replace-java.lang.Iterable-) | Substitui operadores na coleção por outros operadores. |
| [replace](#replace-com.aspose.pdf.Operator:A-) | Substitui operadores na coleção por outros operadores. |
| [resumeUpdate](#resumeUpdate--) | Retoma a atualização do documento. Atualiza o fluxo de conteúdo caso existam alterações pendentes. |
| [resumeUpdate](#resumeUpdate-boolean-) | Retoma a atualização do documento. Atualiza o fluxo de conteúdo caso haja alterações pendentes. Marca todos os operadores como "alterado" se o parâmetro invalidate for verdadeiro. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Define o operador pelo seu índice. |
| [size](#size--) | Obtém a contagem de operadores na coleção. |
| [suppressUpdate](#suppressUpdate--) | Suprime a atualização dos dados de conteúdo. O fluxo de conteúdo não é atualizado até que ResumeUpdate seja chamado. |
| [toList](#toList--) | Retorna a lista de operadores. |
| [toString](#toString--) | Retorna a representação textual do operador. |
| [updateData](#updateData--) | Atualiza o fluxo de objetos. |
| [updateNormalizedData](#updateNormalizedData--) | Atualiza o fluxo de objetos corrigindo operadores GSave/GRestore ausentes. |

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
Somente para uso interno!

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-}
Somente para uso interno!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante IOperatorSelector para processar operadores.

### add {#add-java.lang.Iterable-}
Adiciona à coleção todos os operadores de outra coleção.

### add {#add-com.aspose.pdf.Operator-}
<p> Adiciona um novo operador à coleção. </p> <hr> <p> O exemplo demonstra como adicionar operadores ao final de page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p>

### add {#add-com.aspose.pdf.Operator:A-}
<p> Adiciona operadores ao final dos operadores de conteúdo. </p> <hr> <p> O exemplo demonstra como adicionar um operador ao final do conteúdo da página. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Cancela a última atualização. Este método pode ser chamado quando a alteração não deve disparar a atualização de conteúdo.

### clear {#clear--}
```
public void clear()
```

<p> Remove todos os operadores da lista. </p> <hr> <p> O exemplo demonstra como limpar o conteúdo da página. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p>

### close {#close--}
```
public final void close()
```

Executa tarefas definidas pela aplicação associadas à liberação, descarte ou redefinição de recursos não gerenciados.

### contains {#contains-com.aspose.pdf.Operator-}
Retorna verdadeiro se a coleção contiver o operador especificado.

### delete {#delete-int-}
```
public void delete(int index)
```

<p> Exclui o operador da coleção. </p> <hr> <p> O exemplo demonstra como excluir um operador pelo seu índice. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice do operador que deve ser excluído. A numeração dos operadores começa em 1. |

### delete {#delete-java.lang.Iterable-}
Exclui operadores da coleção.

### delete {#delete-com.aspose.pdf.Operator:A-}
<p> Exclui operadores da coleção. </p> <hr> <p> O exemplo demonstra como remover um operador do conteúdo da página. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p>

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

versão interna sem restrições de Delete(index)

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | valor int |

### dispose {#dispose--}
```
public final void dispose()
```

Executa tarefas definidas pela aplicação associadas à liberação, descarte ou redefinição de recursos não gerenciados.

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Obtém o operador pelo seu índice. </p> <hr> O exemplo demonstra como obter o operador do conteúdo da página pelo índice. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre>

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

Versão interna sem restrições do indexador

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | valor int |

**Returns:**
Objeto operador

### insert {#insert-int-java.lang.Iterable-}
Insere operadores na posição especificada.

### insert {#insert-int-com.aspose.pdf.Operator-}
<p> Insere um operador na coleção. </p> <hr> <p> O exemplo demonstra como inserir um operador no conteúdo da página. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p>

### insert {#insert-int-com.aspose.pdf.Operator:A-}
<p> Insere operadores na posição especificada. </p> <hr> <p> O exemplo demonstra como inserir um operador no conteúdo da página. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### isBracketed {#isBracketed--}
```
public boolean isBracketed()
```

Obtém o status entre colchetes da sequência de operadores, ou seja, se esses operadores estão dentro de blocos q - Q

**Returns:**
valor booleano

### isCommandsParsed {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```

Obtém os comandos analisados

**Returns:**
valor booleano

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
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Operator > iterator()
```

Retorna um enumerador para a coleção

**Returns:**
Enumerador da coleção

### precalculateOperatorsCount {#precalculateOperatorsCount--}
```
public int precalculateOperatorsCount()
```

Obtém a quantidade de operadores que descrevem o conteúdo da página sem sua inicialização.

**Returns:**
valor int

### remove {#remove-com.aspose.pdf.Operator-}
Remove o operador da coleção.

### replace {#replace-java.lang.Iterable-}
Substitui operadores na coleção por outros operadores.

### replace {#replace-com.aspose.pdf.Operator:A-}
Substitui operadores na coleção por outros operadores.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Retoma a atualização do documento. Atualiza o fluxo de conteúdo caso existam alterações pendentes.

### resumeUpdate {#resumeUpdate-boolean-}
```
public final void resumeUpdate(boolean updateAll)
```

Retoma a atualização do documento. Atualiza o fluxo de conteúdo caso haja alterações pendentes. Marca todos os operadores como "alterado" se o parâmetro invalidate for verdadeiro.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| updateAll |  | Se verdadeiro, todos os operadores na coleção são marcados como atualizados. |

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Define o operador pelo seu índice.

### size {#size--}
```
public int size()
```

Obtém a contagem de operadores na coleção.

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

### toString {#toString--}
```
public String toString()
```

Retorna a representação textual do operador.

**Returns:**
Representação textual do operador.

### updateData {#updateData--}
```
public void updateData()
```

Atualiza o fluxo de objetos.

### updateNormalizedData {#updateNormalizedData--}
```
public void updateNormalizedData()
```

Atualiza o fluxo de objetos corrigindo operadores GSave/GRestore ausentes.
