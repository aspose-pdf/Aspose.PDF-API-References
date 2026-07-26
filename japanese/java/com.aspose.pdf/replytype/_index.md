---
title: "ReplyType"
linktitle: "ReplyType"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "注釈と InReplyTo で指定された注釈との間の関係（\\\"reply type\\\"）の種類を列挙します。"
type: docs
weight: 4210
url: /ja/java/com.aspose.pdf/replytype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ReplyType > com.aspose.pdf.ReplyType, java.lang.Enum < ReplyType >, com.aspose.pdf.ReplyType

**All Implemented Interfaces:**
Serializable, Comparable < ReplyType >

```
public enum ReplyType extends Enum < ReplyType >
```

アノテーションと InReplyTo で指定されたものとの間の関係（"reply type"）の種類を列挙します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Group](#Group) | この注釈は InReplyTo で指定された注釈とグループ化されています。 |
| [Reply](#Reply) | この注釈は InReplyTo で指定された注釈への返信とみなされます。 |
| [Undefined](#Undefined) | 未定義の関係です。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### Group {#Group}
```
public static final ReplyType Group
```

この注釈は InReplyTo で指定された注釈とグループ化されています。

### Reply {#Reply}
```
public static final ReplyType Reply
```

この注釈は InReplyTo で指定された注釈への返信とみなされます。

### Undefined {#Undefined}
```
public static final ReplyType Undefined
```

未定義の関係です。

### getByValue {#getByValue-int-}
```
public static ReplyType getByValue(int value)
```



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
指定された名前でこの型の列挙定数を返します。

### values {#values--}
```
public static ReplyType [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列
