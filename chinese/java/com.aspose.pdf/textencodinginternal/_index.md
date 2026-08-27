---
title: "TextEncodingInternal"
linktitle: "TextEncodingInternal"
second_title: "Aspose.PDF for Java API 参考"
description:
type: docs
weight: 5030
url: /zh/java/com.aspose.pdf/textencodinginternal/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextEncodingInternal

```
public final class TextEncodingInternal extends Object
```



## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextEncodingInternal](#TextEncodingInternal-com.aspose.ms.System.Text.Encoding-) | 内部构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getASCII](#getASCII--) | 获取 ASCII（7 位）字符集的编码。 |
| [getBigEndianUnicode](#getBigEndianUnicode--) | 获取使用大端字节序的 UTF-16 格式的编码。 |
| [getDefault](#getDefault--) | 获取操作系统当前 ANSI 代码页的编码。 |
| [getEncoding](#getEncoding-java.lang.String-) | 返回与指定代码页名称关联的编码。 |
| [getInternalFormat](#getInternalFormat--) | 内部方法 |
| [getNames](#getNames--) | 获取包含编码名称的数组。 |
| [getString](#getString-byte:A-) | 在派生类中重写时，将指定字节数组中的所有字节解码为字符串。 |
| [getUnicode](#getUnicode--) | 获取使用小端字节序的 UTF-16 格式的编码。 |
| [getUTF32](#getUTF32--) | 获取使用小端字节序的 UTF-32 格式的编码。 |
| [getUTF32BE](#getUTF32BE--) | 获取使用大端字节序的 UTF-16 格式的编码。 |
| [getUTF7](#getUTF7--) | 获取 UTF-7 格式的编码。 |
| [getUTF8](#getUTF8--) | 获取 UTF-8 格式的编码。 |
| [getUTF8Unmarked](#getUTF8Unmarked--) | 获取 UTF-8 Unmarked 格式的编码。 |
| [toString](#toString-com.aspose.pdf.TextEncodingInternal-) | 返回表示当前对象的字符串。 |

### TextEncodingInternal {#TextEncodingInternal-com.aspose.ms.System.Text.Encoding-}
内部构造函数

### getASCII {#getASCII--}
```
public static TextEncodingInternal getASCII()
```

获取 ASCII（7 位）字符集的编码。

**Returns:**
TextEncodingInternal 实例

### getBigEndianUnicode {#getBigEndianUnicode--}
```
public static TextEncodingInternal getBigEndianUnicode()
```

获取使用大端字节序的 UTF-16 格式的编码。

**Returns:**
TextEncodingInternal 实例

### getDefault {#getDefault--}
```
public static TextEncodingInternal getDefault()
```

获取操作系统当前 ANSI 代码页的编码。

**Returns:**
TextEncodingInternal 实例

### getEncoding {#getEncoding-java.lang.String-}
返回与指定代码页名称关联的编码。

### getInternalFormat {#getInternalFormat--}
```
public com.aspose.ms.System.Text.Encoding getInternalFormat()
```

内部方法

**Returns:**
内部对象

### getNames {#getNames--}
```
public static String [] getNames()
```

获取包含编码名称的数组。

**Returns:**
字符串数组

### getString {#getString-byte:A-}
```
public String getString(byte[] value)
```

在派生类中重写时，将指定字节数组中的所有字节解码为字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 包含要解码的字节序列的字节数组。 |

**Returns:**
包含对指定字节序列解码结果的字符串。

### getUnicode {#getUnicode--}
```
public static TextEncodingInternal getUnicode()
```

获取使用小端字节序的 UTF-16 格式的编码。

**Returns:**
TextEncodingInternal 实例

### getUTF32 {#getUTF32--}
```
public static TextEncodingInternal getUTF32()
```

获取使用小端字节序的 UTF-32 格式的编码。

**Returns:**
TextEncodingInternal 实例

### getUTF32BE {#getUTF32BE--}
```
public static TextEncodingInternal getUTF32BE()
```

获取使用大端字节序的 UTF-16 格式的编码。

**Returns:**
TextEncodingInternal 实例

### getUTF7 {#getUTF7--}
```
public static TextEncodingInternal getUTF7()
```

获取 UTF-7 格式的编码。

**Returns:**
TextEncodingInternal 实例

### getUTF8 {#getUTF8--}
```
public static TextEncodingInternal getUTF8()
```

获取 UTF-8 格式的编码。

**Returns:**
TextEncodingInternal 实例

### getUTF8Unmarked {#getUTF8Unmarked--}
```
public static TextEncodingInternal getUTF8Unmarked()
```

获取 UTF-8 Unmarked 格式的编码。

**Returns:**
TextEncodingInternal 实例

### toString {#toString-com.aspose.pdf.TextEncodingInternal-}
返回表示当前对象的字符串。
