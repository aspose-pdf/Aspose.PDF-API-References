---
title: "ReplyType"
linktitle: "ReplyType"
second_title: "Aspose.PDF för Java API-referens"
description: "Enumererar typerna av relationer (\\\\\"svarstypen\\\\\") mellan annotationen och den som specificeras av InReplyTo."
type: docs
weight: 4210
url: /sv/java/com.aspose.pdf/replytype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ReplyType > com.aspose.pdf.ReplyType, java.lang.Enum < ReplyType >, com.aspose.pdf.ReplyType

**All Implemented Interfaces:**
Serializable, Comparable < ReplyType >

```
public enum ReplyType extends Enum < ReplyType >
```

Enumererar typerna av relationer (\"svarstypen\") mellan annoteringen och den som anges av InReplyTo.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Group](#Group) | Annotationen är grupperad med annotationen som specificeras av InReplyTo. |
| [Reply](#Reply) | Annotationen anses vara ett svar på annotationen som specificeras av InReplyTo. |
| [Undefined](#Undefined) | Odefinierat förhållande. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returnerar enum‑konstanten av denna typ med det angivna namnet. |
| [values](#values--) | Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras. |

### Group {#Group}
```
public static final ReplyType Group
```

Annotationen är grupperad med annotationen som specificeras av InReplyTo.

### Reply {#Reply}
```
public static final ReplyType Reply
```

Annotationen anses vara ett svar på annotationen som specificeras av InReplyTo.

### Undefined {#Undefined}
```
public static final ReplyType Undefined
```

Odefinierat förhållande.

### getByValue {#getByValue-int-}
```
public static ReplyType getByValue(int value)
```



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returnerar enum‑konstanten av denna typ med det angivna namnet.

### values {#values--}
```
public static ReplyType [] values()
```

Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras.

**Returns:**
en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras
