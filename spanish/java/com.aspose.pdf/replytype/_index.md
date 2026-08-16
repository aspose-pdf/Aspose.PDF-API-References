---
title: "ReplyType"
linktitle: "ReplyType"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Enumera los tipos de relaciones (el \"tipo de respuesta\") entre la anotación y una especificada por InReplyTo."
type: docs
weight: 4210
url: /es/java/com.aspose.pdf/replytype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ReplyType > com.aspose.pdf.ReplyType, java.lang.Enum < ReplyType >, com.aspose.pdf.ReplyType

**All Implemented Interfaces:**
Serializable, Comparable < ReplyType >

```
public enum ReplyType extends Enum < ReplyType >
```

Enumera los tipos de relaciones (el "tipo de respuesta") entre la anotación y una especificada por InReplyTo.

## Campos

| Campo | Descripción |
| --- | --- |
| [Group](#Group) | La anotación se agrupa con la anotación especificada por InReplyTo. |
| [Reply](#Reply) | La anotación se considera una respuesta a la anotación especificada por InReplyTo. |
| [Undefined](#Undefined) | Relación indefinida. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Devuelve la constante enum de este tipo con el nombre especificado. |
| [values](#values--) | Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran. |

### Group {#Group}
```
public static final ReplyType Group
```

La anotación se agrupa con la anotación especificada por InReplyTo.

### Reply {#Reply}
```
public static final ReplyType Reply
```

La anotación se considera una respuesta a la anotación especificada por InReplyTo.

### Undefined {#Undefined}
```
public static final ReplyType Undefined
```

Relación indefinida.

### getByValue {#getByValue-int-}
```
public static ReplyType getByValue(int value)
```



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Devuelve la constante enum de este tipo con el nombre especificado.

### values {#values--}
```
public static ReplyType [] values()
```

Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran.

**Returns:**
una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran
