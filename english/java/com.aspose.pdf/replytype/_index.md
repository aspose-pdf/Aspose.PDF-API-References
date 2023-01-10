---
title: ReplyType
second_title: Aspose.PDF for Java API Reference
description: Enumerates the kinds of the relationships the u201creply typeu201d between the annotation and one specified by InReplyTo.
type: docs
weight: 310
url: /java/com.aspose.pdf/replytype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ReplyType extends System.Enum
```

Enumerates the kinds of the relationships (the \\u201creply type\\u201d) between the annotation and one specified by InReplyTo.
## Fields

| Field | Description |
| --- | --- |
| [Undefined](#Undefined) | Undefined relationship. |
| [Reply](#Reply) | The annotation is considered a reply to the annotation specified by InReplyTo. |
| [Group](#Group) | The annotation is grouped with the annotation specified by InReplyTo. |
### Undefined {#Undefined}
```
public static final int Undefined
```


Undefined relationship.

### Reply {#Reply}
```
public static final int Reply
```


The annotation is considered a reply to the annotation specified by InReplyTo. Viewer applications should not display replies to an annotation individually but together in the form of threaded comments.

### Group {#Group}
```
public static final int Group
```


The annotation is grouped with the annotation specified by InReplyTo.

