---
title: "PasswordType"
linktitle: "PasswordType"
second_title: "Aspose.PDF for Java API 参考"
description: "此枚举表示用于受密码保护的 PDF 文档的已知密码类型。"
type: docs
weight: 3520
url: /zh/java/com.aspose.pdf/passwordtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PasswordType > com.aspose.pdf.PasswordType, java.lang.Enum < PasswordType >, com.aspose.pdf.PasswordType

**All Implemented Interfaces:**
Serializable, Comparable < PasswordType >

```
public enum PasswordType extends Enum < PasswordType >
```

此枚举表示用于受密码保护的 PDF 文档的已知密码类型。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Inaccessible](#Inaccessible) | Pdf 文档受密码保护，但用户密码和所有者密码均不为空，且未定义任何密码或提供的密码不正确。 |
| [None](#None) | Pdf 文档未受密码保护。 |
| [Owner](#Owner) | Pdf 文档是使用更改权限密码（完全访问）打开的。 |
| [User](#User) | Pdf 文档是使用文档打开密码（受限访问）打开的。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### Inaccessible {#Inaccessible}
```
public static final PasswordType Inaccessible
```

Pdf 文档受密码保护，但用户密码和所有者密码均不为空，且未定义任何密码或提供的密码不正确。

### None {#None}
```
public static final PasswordType None
```

Pdf 文档未受密码保护。

### Owner {#Owner}
```
public static final PasswordType Owner
```

Pdf 文档是使用更改权限密码（完全访问）打开的。

### User {#User}
```
public static final PasswordType User
```

Pdf 文档是使用文档打开密码（受限访问）打开的。

### getByValue {#getByValue-int-}
```
public static PasswordType getByValue(int value)
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
public static PasswordType [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
