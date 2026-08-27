---
title: "PasswordType"
linktitle: "PasswordType"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "この列挙型はパスワードで保護された PDF ドキュメントで使用される既知のパスワードタイプを表します。"
type: docs
weight: 3520
url: /ja/java/com.aspose.pdf/passwordtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PasswordType > com.aspose.pdf.PasswordType, java.lang.Enum < PasswordType >, com.aspose.pdf.PasswordType

**All Implemented Interfaces:**
Serializable, Comparable < PasswordType >

```
public enum PasswordType extends Enum < PasswordType >
```

この列挙型はパスワードで保護された PDF ドキュメントで使用される既知のパスワードタイプを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Inaccessible](#Inaccessible) | PDF ドキュメントはパスワードで保護されていますが、ユーザーと所有者のパスワードがどちらも空ではなく、パスワードが定義されていないか、提供されたパスワードが正しくありません。 |
| [None](#None) | PDF ドキュメントはパスワードで保護されていません。 |
| [Owner](#Owner) | PDF ドキュメントは権限変更パスワード（フルアクセス）を使用して開かれました。 |
| [User](#User) | PDF ドキュメントはドキュメントオープンパスワード（制限付きアクセス）を使用して開かれました。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### Inaccessible {#Inaccessible}
```
public static final PasswordType Inaccessible
```

PDF ドキュメントはパスワードで保護されていますが、ユーザーと所有者のパスワードがどちらも空ではなく、パスワードが定義されていないか、提供されたパスワードが正しくありません。

### None {#None}
```
public static final PasswordType None
```

PDF ドキュメントはパスワードで保護されていません。

### Owner {#Owner}
```
public static final PasswordType Owner
```

PDF ドキュメントは権限変更パスワード（フルアクセス）を使用して開かれました。

### User {#User}
```
public static final PasswordType User
```

PDF ドキュメントはドキュメントオープンパスワード（制限付きアクセス）を使用して開かれました。

### getByValue {#getByValue-int-}
```
public static PasswordType getByValue(int value)
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
public static PasswordType [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列
