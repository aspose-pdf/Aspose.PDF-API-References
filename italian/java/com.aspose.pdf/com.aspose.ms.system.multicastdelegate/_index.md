---
title: "com.aspose.ms.System.MulticastDelegate>"
linktitle: "com.aspose.ms.System.MulticastDelegate>"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta eventi."
type: docs
weight: 740
url: /it/java/com.aspose.pdf/com.aspose.ms.system.multicastdelegate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfEvent<T>

```
public abstract class PdfEvent<T extends com.aspose.ms.System.MulticastDelegate> extends Object
```

Classe che rappresenta eventi.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfEvent](#PdfEvent--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-T-) | Aggiungi un delegato in più. |
| [assign](#assign-T-) | Aggiungi solo il delegato corrente, cancellando gli altri. |
| [clear](#clear--) | Cancella l'elenco dei delegati |
| [isEmpty](#isEmpty--) | Restituisce true se l'elenco dei gestori è vuoto |
| [remove](#remove-T-) | Elimina delegate dall'elenco |

### PdfEvent {#PdfEvent--}
```
public PdfEvent()
```



### add {#add-T-}
```
public final void add( T delegate)
```

Aggiungi un delegato in più.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| delegate |  | Oggetto Handlers |

### assign {#assign-T-}
```
public final void assign( T delegate)
```

Aggiungi solo il delegato corrente, cancellando gli altri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| delegate |  | Oggetto Handlers |

### clear {#clear--}
```
public final void clear()
```

Cancella l'elenco dei delegati

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Restituisce true se l'elenco dei gestori è vuoto

**Returns:**
valore booleano

### remove {#remove-T-}
```
public final void remove( T delegate)
```

Elimina delegate dall'elenco

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| delegate |  | Oggetto Handlers |
