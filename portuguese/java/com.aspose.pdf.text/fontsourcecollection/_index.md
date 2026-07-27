---
title: "FontSourceCollection"
linktitle: "FontSourceCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a coleção de fontes."
type: docs
weight: 40
url: /pt/java/com.aspose.pdf.text/fontsourcecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSourceCollection

**All Implemented Interfaces:**
Iterable < FontSource >

```
public final class FontSourceCollection extends Object implements Iterable < FontSource >
```

Representa a coleção de fontes.

## Campos

| Campo | Descrição |
| --- | --- |
| [CollectionChanged](#CollectionChanged) | Evento CollectionChanged |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FontSourceCollection](#FontSourceCollection--) | Inicializa o objeto de coleção |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.FontSource-) | Adiciona um novo objeto de fonte ao conjunto. |
| [clear](#clear--) | Limpa a coleção de fontes. |
| [contains](#contains-com.aspose.pdf.FontSource-) | Determina se um elemento está na coleção. |
| [copyTo](#copyTo-com.aspose.pdf.FontSource:A-int-) | Copia toda a coleção para um Array unidimensional compatível, começando no índice especificado do array de destino. |
| [delete](#delete-com.aspose.pdf.FontSource-) | Exclui o elemento de fonte. |
| [getItem](#getItem-int-) | Obtém o elemento de fonte no índice especificado. |
| [getSyncRoot](#getSyncRoot--) | Obtém um objeto que pode ser usado para sincronizar o acesso à coleção. |
| [isSynchronized](#isSynchronized--) | Obtém um valor que indica se o acesso à coleção está sincronizado (thread safe). |
| [iterator](#iterator--) | Retorna um enumerador para toda a coleção. |
| [remove](#remove-com.aspose.pdf.FontSource-) | Exclui o elemento de fonte. |
| [size](#size--) | Obtém o número de elementos do objeto Font realmente contidos na coleção. |

### CollectionChanged {#CollectionChanged}
```
public final PdfEvent <com.aspose.ms.System.EventHandler> CollectionChanged
```

Evento CollectionChanged

### FontSourceCollection {#FontSourceCollection--}
```
public FontSourceCollection()
```

Inicializa o objeto de coleção

### add {#add-com.aspose.pdf.FontSource-}
Adiciona um novo objeto de fonte ao conjunto.

### clear {#clear--}
```
public void clear()
```

Limpa a coleção de fontes.

### contains {#contains-com.aspose.pdf.FontSource-}
Determina se um elemento está na coleção.

### copyTo {#copyTo-com.aspose.pdf.FontSource:A-int-}
Copia toda a coleção para um Array unidimensional compatível, começando no índice especificado do array de destino.

### delete {#delete-com.aspose.pdf.FontSource-}
Exclui o elemento de fonte.

### getItem {#getItem-int-}
```
public FontSource getItem(int index)
```

Obtém o elemento de fonte no índice especificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice dentro da coleção. |

**Returns:**
Objeto de fonte.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtém um objeto que pode ser usado para sincronizar o acesso à coleção.

**Returns:**
Elemento Object

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtém um valor que indica se o acesso à coleção está sincronizado (thread safe).

**Returns:**
valor booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator()
```

Retorna um enumerador para toda a coleção.

**Returns:**
Objeto enumerador.

### remove {#remove-com.aspose.pdf.FontSource-}
Exclui o elemento de fonte.

### size {#size--}
```
public int size()
```

Obtém o número de elementos do objeto Font realmente contidos na coleção.

**Returns:**
valor int
