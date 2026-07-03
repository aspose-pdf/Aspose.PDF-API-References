---
title: ReplyType
second_title: Aspose.PDF for Java API Reference
description: Enumerates the kinds of the relationships (the \"reply type\") between the annotation and one specified by InReplyTo.
type: docs
weight: 4210
url: /java/com.aspose.pdf/replytype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ReplyType > com.aspose.pdf.ReplyType, java.lang.Enum < ReplyType >, com.aspose.pdf.ReplyType

**All Implemented Interfaces:**
Serializable, Comparable < ReplyType >

```
public enum ReplyType extends Enum < ReplyType >
```

Enumerates the kinds of the relationships (the "reply type") between the annotation and one specified by InReplyTo.

## Fields

| Field | Description |
| --- | --- |
| [Group](#Group) | The annotation is grouped with the annotation specified by InReplyTo. |
| [Reply](#Reply) | The annotation is considered a reply to the annotation specified by InReplyTo. |
| [Undefined](#Undefined) | Undefined relationship. |

## Methods

| Method | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returns the enum constant of this type with the specified name. |
| [values](#values--) | Returns an array containing the constants of this enum type, in the order they are declared. |

### Group {#Group}
```
public static final ReplyType Group
```

The annotation is grouped with the annotation specified by InReplyTo.

### Reply {#Reply}
```
public static final ReplyType Reply
```

The annotation is considered a reply to the annotation specified by InReplyTo.

### Undefined {#Undefined}
```
public static final ReplyType Undefined
```

Undefined relationship.

### getByValue {#getByValue-int-}
```
public static ReplyType getByValue(int value)
```



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returns the enum constant of this type with the specified name.

### values {#values--}
```
public static ReplyType [] values()
```

Returns an array containing the constants of this enum type, in the order they are declared.

**Returns:**
an array containing the constants of this enum type, in the order they are declared
