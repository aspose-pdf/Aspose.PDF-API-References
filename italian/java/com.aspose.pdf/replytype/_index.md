---
title: "ReplyType"
linktitle: "ReplyType"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Elenca i tipi di relazioni (il \"tipo di risposta\") tra l'annotazione e quella specificata da InReplyTo."
type: docs
weight: 4210
url: /it/java/com.aspose.pdf/replytype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ReplyType > com.aspose.pdf.ReplyType, java.lang.Enum < ReplyType >, com.aspose.pdf.ReplyType

**All Implemented Interfaces:**
Serializable, Comparable < ReplyType >

```
public enum ReplyType extends Enum < ReplyType >
```

Elenca i tipi di relazioni (il "tipo di risposta") tra l'annotazione e quella specificata da InReplyTo.

## Campi

| Campo | Descrizione |
| --- | --- |
| [Group](#Group) | L'annotazione è raggruppata con l'annotazione specificata da InReplyTo. |
| [Reply](#Reply) | L'annotazione è considerata una risposta all'annotazione specificata da InReplyTo. |
| [Undefined](#Undefined) | Relazione non definita. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Restituisce la costante enum di questo tipo con il nome specificato. |
| [values](#values--) | Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate. |

### Group {#Group}
```
public static final ReplyType Group
```

L'annotazione è raggruppata con l'annotazione specificata da InReplyTo.

### Reply {#Reply}
```
public static final ReplyType Reply
```

L'annotazione è considerata una risposta all'annotazione specificata da InReplyTo.

### Undefined {#Undefined}
```
public static final ReplyType Undefined
```

Relazione non definita.

### getByValue {#getByValue-int-}
```
public static ReplyType getByValue(int value)
```



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Restituisce la costante enum di questo tipo con il nome specificato.

### values {#values--}
```
public static ReplyType [] values()
```

Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate.

**Returns:**
un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate
