---
title: "AnnotationCollection"
linktitle: "AnnotationCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa a coleção de anotações."
type: docs
weight: 80
url: /pt/java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationCollection

**All Implemented Interfaces:**
Iterable < Annotation >

```
public final class AnnotationCollection extends Object implements Iterable < Annotation >
```

Classe que representa a coleção de anotações.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [AnnotationCollection](#AnnotationCollection-com.aspose.pdf.Page-) | Construtor de AnnotationCollection. Cria uma coleção de anotações para a página fornecida. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita um visitante para processar a anotação. |
| [add](#add-com.aspose.pdf.Annotation-) | Adiciona a anotação à coleção. |
| [add](#add-com.aspose.pdf.Annotation-boolean-) | Adiciona a anotação à coleção. Se a página estiver girada, então o retângulo da anotação será recalculado adequadamente. |
| [clear](#clear--) | Exclui todas as anotações da coleção. |
| [contains](#contains-com.aspose.pdf.Annotation-) | Verifica se a anotação especificada pertence à coleção. |
| [copyTo](#copyTo-com.aspose.pdf.Annotation:A-int-) | Copia o array de anotações para a coleção. |
| [delete](#delete--) | Exclui todas as anotações da coleção. |
| [delete](#delete-com.aspose.pdf.Annotation-) | Exclui todas as anotações da coleção. |
| [delete](#delete-int-) | Exclui a anotação da coleção por índice. |
| [findByName](#findByName-java.lang.String-) | Retorna a anotação pelo seu nome. |
| [get_Item](#get_Item-int-) | O índice do elemento a ser obtido. |
| [getSyncRoot](#getSyncRoot--) | Obtém um objeto que pode ser usado para sincronizar o acesso ao com.aspose.pdf.AnnotationCollection. |
| [isReadOnly](#isReadOnly--) | Obtém um valor que indica se a coleção é somente leitura. |
| [isSynchronized](#isSynchronized--) | Obtém um valor que indica se o acesso ao com.aspose.pdf.AnnotationCollection está sincronizado (seguro para threads). |
| [iterator](#iterator--) | Retorna o enumerador da coleção. |
| [remove](#remove-com.aspose.pdf.Annotation-) | Exclui a anotação especificada da coleção. |
| [size](#size--) | Obtém a contagem de anotações na coleção. |

### AnnotationCollection {#AnnotationCollection-com.aspose.pdf.Page-}
Construtor de AnnotationCollection. Cria uma coleção de anotações para a página fornecida.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita um visitante para processar a anotação.

### add {#add-com.aspose.pdf.Annotation-}
Adiciona a anotação à coleção.

### add {#add-com.aspose.pdf.Annotation-boolean-}
Adiciona a anotação à coleção. Se a página estiver girada, então o retângulo da anotação será recalculado adequadamente.

### clear {#clear--}
```
public void clear()
```

Exclui todas as anotações da coleção.

### contains {#contains-com.aspose.pdf.Annotation-}
Verifica se a anotação especificada pertence à coleção.

### copyTo {#copyTo-com.aspose.pdf.Annotation:A-int-}
Copia o array de anotações para a coleção.

### delete {#delete--}
```
public void delete()
```

Exclui todas as anotações da coleção.

### delete {#delete-com.aspose.pdf.Annotation-}
Exclui todas as anotações da coleção.

### delete {#delete-int-}
```
public void delete(int index)
```

Exclui a anotação da coleção por índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice da anotação que será excluída. |

### findByName {#findByName-java.lang.String-}
Retorna a anotação pelo seu nome.

### get_Item {#get_Item-int-}
```
public Annotation get_Item(int index)
```

O índice do elemento a ser obtido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | O valor do índice começa em um. |

**Returns:**
Objeto de anotação

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtém um objeto que pode ser usado para sincronizar o acesso ao com.aspose.pdf.AnnotationCollection.

**Returns:**
Objeto para sincronização

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

Obtém um valor que indica se o acesso ao com.aspose.pdf.AnnotationCollection está sincronizado (seguro para threads).

**Returns:**
valor booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Annotation > iterator()
```

Retorna o enumerador da coleção.

**Returns:**
Objeto enumerador

### remove {#remove-com.aspose.pdf.Annotation-}
Exclui a anotação especificada da coleção.

### size {#size--}
```
public int size()
```

Obtém a contagem de anotações na coleção.

**Returns:**
valor int
