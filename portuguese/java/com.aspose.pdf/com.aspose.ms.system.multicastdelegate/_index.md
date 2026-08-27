---
title: "com.aspose.ms.System.MulticastDelegate>"
linktitle: "com.aspose.ms.System.MulticastDelegate>"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa eventos"
type: docs
weight: 740
url: /pt/java/com.aspose.pdf/com.aspose.ms.system.multicastdelegate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfEvent<T>

```
public abstract class PdfEvent<T extends com.aspose.ms.System.MulticastDelegate> extends Object
```

Classe que representa eventos

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfEvent](#PdfEvent--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-T-) | Adicione mais um delegate. |
| [assign](#assign-T-) | Adicione apenas o delegate atual, limpando os demais. |
| [clear](#clear--) | Limpar lista de delegates |
| [isEmpty](#isEmpty--) | Retorna verdadeiro se a lista de manipuladores estiver vazia |
| [remove](#remove-T-) | Excluir delegado da lista |

### PdfEvent {#PdfEvent--}
```
public PdfEvent()
```



### add {#add-T-}
```
public final void add( T delegate)
```

Adicione mais um delegate.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| delegado |  | Objeto Handlers |

### assign {#assign-T-}
```
public final void assign( T delegate)
```

Adicione apenas o delegate atual, limpando os demais.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| delegado |  | Objeto Handlers |

### clear {#clear--}
```
public final void clear()
```

Limpar lista de delegates

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Retorna verdadeiro se a lista de manipuladores estiver vazia

**Returns:**
valor booleano

### remove {#remove-T-}
```
public final void remove( T delegate)
```

Excluir delegado da lista

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| delegado |  | Objeto Handlers |
