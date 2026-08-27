---
title: "SignatureName"
linktitle: "SignatureName"
second_title: "Aspose.PDF for Java API 参考"
description: "表示签名名称的类。表示更精确的签名名称。用于替代字符串名称。允许您使用相同的字符串名称呈现签名。"
type: docs
weight: 690
url: /zh/java/com.aspose.pdf.facades/signaturename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.SignatureName

```
public final class SignatureName extends Object
```

表示签名名称的类。表示更精确的签名名称。用于替代字符串名称。允许您使用相同的字符串名称呈现签名。

## 字段

| 字段 | 描述 |
| --- | --- |
| [FullName](#FullName) | 获取签名的完整名称，为签名字段提供唯一且精确的标识符。 |
| [Name](#Name) | 获取签名的名称。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [equals](#equals-java.lang.Object-) | 确定此实例与指定对象是否相等。 |
| [getSignatureDictionary](#getSignatureDictionary--) | 获取签名字典。 |
| [hashCode](#hashCode--) | 返回基于 FullName 属性的此实例的哈希码。 |
| [hasSignature](#hasSignature--) | 指示签名是否存在。 |
| [toString](#toString--) | 返回 {@link SignatureName} 实例的字符串表示，主要使用其名称。 |

### FullName {#FullName}
```
public final String FullName
```

获取签名的完整名称，为签名字段提供唯一且精确的标识符。

### Name {#Name}
```
public final String Name
```

获取签名的名称。

### equals {#equals-java.lang.Object-}
确定此实例与指定对象是否相等。

### getSignatureDictionary {#getSignatureDictionary--}
```
public final com.aspose.pdf.engine.data.IPdfDictionary getSignatureDictionary()
```

获取签名字典。

**Returns:**
签名字典，如果未找到则为 null。

### hashCode {#hashCode--}
```
public int hashCode()
```

返回基于 FullName 属性的此实例的哈希码。

**Returns:**
一个整数，表示 FullName 属性的哈希码。

### hasSignature {#hasSignature--}
```
public final boolean hasSignature()
```

指示签名是否存在。

**Returns:**
布尔值

### toString {#toString--}
```
public String toString()
```

返回 {@link SignatureName} 实例的字符串表示，主要使用其名称。

**Returns:**
表示签名名称的字符串。
