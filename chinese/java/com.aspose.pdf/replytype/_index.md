---
title: "ReplyType"
linktitle: "ReplyType"
second_title: "Aspose.PDF for Java API 参考"
description: "枚举注释与 InReplyTo 指定的注释之间的关系类型（即 \"reply type\"）。"
type: docs
weight: 4210
url: /zh/java/com.aspose.pdf/replytype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ReplyType > com.aspose.pdf.ReplyType, java.lang.Enum < ReplyType >, com.aspose.pdf.ReplyType

**All Implemented Interfaces:**
Serializable, Comparable < ReplyType >

```
public enum ReplyType extends Enum < ReplyType >
```

枚举注释与 InReplyTo 指定的对象之间的关系类型（即"回复类型"）。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Group](#Group) | 该注释与 InReplyTo 指定的注释分组在一起。 |
| [Reply](#Reply) | 该注释被视为对 InReplyTo 指定的注释的回复。 |
| [Undefined](#Undefined) | 未定义的关系。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### Group {#Group}
```
public static final ReplyType Group
```

该注释与 InReplyTo 指定的注释分组在一起。

### Reply {#Reply}
```
public static final ReplyType Reply
```

该注释被视为对 InReplyTo 指定的注释的回复。

### Undefined {#Undefined}
```
public static final ReplyType Undefined
```

未定义的关系。

### getByValue {#getByValue-int-}
```
public static ReplyType getByValue(int value)
```



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
返回此类型中具有指定名称的枚举常量。

### values {#values--}
```
public static ReplyType [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
