---
title: "CosPdfString"
linktitle: "CosPdfString"
second_title: "Aspose.PDF for Java API 参考"
description: "此类表示 Pdf String 对象。"
type: docs
weight: 60
url: /zh/java/com.aspose.pdf.dataeditor/cospdfstring/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfString, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfString

**All Implemented Interfaces:**
ICosPdfPrimitive

```
public final class CosPdfString extends CosPdfPrimitive
```

此类表示 Pdf String 对象。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CosPdfString](#CosPdfString-java.lang.String-) | 初始化 {@link CosPdfString} 类的新实例。 |
| [CosPdfString](#CosPdfString-java.lang.String-boolean-) | 初始化 {@link CosPdfString} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [equals](#equals-java.lang.Object-) | 确定指定的对象是否等于当前对象。 |
| [getValue](#getValue--) | 获取字符串（ANSII）。值：该字符串。 |
| [hashCode](#hashCode--) | 获取当前对象的哈希码。 |
| [isHexadecimal](#isHexadecimal--) | 获取一个值，指示此实例是否为十六进制。值：如果此实例是十六进制，则为 {@code true}；否则为 {@code false}。 |
| [toCosPdfString](#toCosPdfString--) | 尝试将此实例转换为 {@link CosPdfString}。 |
| [toString](#toString--) | 返回一个 {@link String}，它表示当前 {@link CosPdfString}。 |

### CosPdfString {#CosPdfString-java.lang.String-}
初始化 {@link CosPdfString} 类的新实例。

### CosPdfString {#CosPdfString-java.lang.String-boolean-}
初始化 {@link CosPdfString} 类的新实例。

### equals {#equals-java.lang.Object-}
确定指定的对象是否等于当前对象。

### getValue {#getValue--}
```
public final String getValue()
```

获取字符串（ANSII）。值：该字符串。

**Returns:**
字符串值

### hashCode {#hashCode--}
```
public int hashCode()
```

获取当前对象的哈希码。

**Returns:**
当前对象的哈希码。

### isHexadecimal {#isHexadecimal--}
```
public final boolean isHexadecimal()
```

获取一个值，指示此实例是否为十六进制。值：如果此实例是十六进制，则为 {@code true}；否则为 {@code false}。

**Returns:**
布尔值

### toCosPdfString {#toCosPdfString--}
```
public CosPdfString toCosPdfString()
```

尝试将此实例转换为 {@link CosPdfString}。

**Returns:**
如果实例不是 {@link CosPdfString} 则为 null，否则为 {@link CosPdfString}。

### toString {#toString--}
```
public String toString()
```

返回一个 {@link String}，它表示当前 {@link CosPdfString}。

**Returns:**
一个表示当前 {@link CosPdfString} 的 {@link String}。
