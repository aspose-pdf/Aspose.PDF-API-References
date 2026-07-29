---
title: "ReplyType"
linktitle: "ReplyType"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Énumère les types de relations (le \"type de réponse\") entre l'annotation et celle spécifiée par InReplyTo."
type: docs
weight: 4210
url: /fr/java/com.aspose.pdf/replytype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ReplyType > com.aspose.pdf.ReplyType, java.lang.Enum < ReplyType >, com.aspose.pdf.ReplyType

**All Implemented Interfaces:**
Serializable, Comparable < ReplyType >

```
public enum ReplyType extends Enum < ReplyType >
```

Énumère les types de relations (le "type de réponse") entre l'annotation et celle spécifiée par InReplyTo.

## Champs

| Champ | Description |
| --- | --- |
| [Group](#Group) | L'annotation est groupée avec l'annotation spécifiée par InReplyTo. |
| [Reply](#Reply) | L'annotation est considérée comme une réponse à l'annotation spécifiée par InReplyTo. |
| [Undefined](#Undefined) | Relation indéfinie. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Renvoie la constante d'énumération de ce type avec le nom spécifié. |
| [values](#values--) | Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées. |

### Group {#Group}
```
public static final ReplyType Group
```

L'annotation est groupée avec l'annotation spécifiée par InReplyTo.

### Reply {#Reply}
```
public static final ReplyType Reply
```

L'annotation est considérée comme une réponse à l'annotation spécifiée par InReplyTo.

### Undefined {#Undefined}
```
public static final ReplyType Undefined
```

Relation indéfinie.

### getByValue {#getByValue-int-}
```
public static ReplyType getByValue(int value)
```



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Renvoie la constante d'énumération de ce type avec le nom spécifié.

### values {#values--}
```
public static ReplyType [] values()
```

Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées.

**Returns:**
un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées
