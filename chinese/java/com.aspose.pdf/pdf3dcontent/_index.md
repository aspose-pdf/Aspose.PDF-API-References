---
title: "PDF3DContent"
linktitle: "PDF3DContent"
second_title: "Aspose.PDF for Java API 参考"
description: "类 PDF3DContent。"
type: docs
weight: 3580
url: /zh/java/com.aspose.pdf/pdf3dcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DContent

```
public class PDF3DContent extends Object
```

类 PDF3DContent。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PDF3DContent](#PDF3DContent--) | 初始化 {@code PDF3DContent} 类的新实例。 |
| [PDF3DContent](#PDF3DContent-java.lang.String-) | 初始化 {@code PDF3DContent} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsByteArray](#getAsByteArray--) | 获取 3D 内容的字节数组。 |
| [getAsStream](#getAsStream--) | 获取 3D 内容的流。 |
| [getExtension](#getExtension--) | 获取扩展名。 |
| [load](#load-java.lang.String-) | 使用指定的文件名加载 3D 内容。 |
| [loadAsPRC](#loadAsPRC-byte:A-) | 将 3D 内容从字节数组加载为 PRC 格式。 |
| [loadAsPRC](#loadAsPRC-java.io.InputStream-) | 将 3D 内容从流加载为 PRC 格式。 |
| [loadAsPRC](#loadAsPRC-java.lang.String-) | 将 3D 内容使用指定的文件名加载为 PRC 格式。 |
| [loadAsU3D](#loadAsU3D-byte:A-) | 将 3D 内容从字节数组加载为 U3D 格式。 |
| [loadAsU3D](#loadAsU3D-java.io.InputStream-) | 将 3D 内容从流加载为 U3D 格式。 |
| [loadAsU3D](#loadAsU3D-java.lang.String-) | 将 3D 内容使用指定的文件名加载为 U3D 格式。 |
| [saveToFile](#saveToFile-java.lang.String-) | 将 3D 内容保存到文件。 |

### PDF3DContent {#PDF3DContent--}
```
public PDF3DContent()
```

初始化 {@code PDF3DContent} 类的新实例。

### PDF3DContent {#PDF3DContent-java.lang.String-}
初始化 {@code PDF3DContent} 类的新实例。

### getAsByteArray {#getAsByteArray--}
```
public byte[] getAsByteArray()
```

获取 3D 内容的字节数组。

**Returns:**
System.Byte[].

### getAsStream {#getAsStream--}
```
public InputStream getAsStream()
```

获取 3D 内容的流。

**Returns:**
流。

### getExtension {#getExtension--}
```
public String getExtension()
```

获取扩展名。

**Returns:**
字符串对象：扩展名。

### load {#load-java.lang.String-}
使用指定的文件名加载 3D 内容。

### loadAsPRC {#loadAsPRC-byte:A-}
```
public void loadAsPRC(byte[] stream)
```

将 3D 内容从字节数组加载为 PRC 格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 |  | 该流。 |

### loadAsPRC {#loadAsPRC-java.io.InputStream-}
将 3D 内容从流加载为 PRC 格式。

### loadAsPRC {#loadAsPRC-java.lang.String-}
将 3D 内容使用指定的文件名加载为 PRC 格式。

### loadAsU3D {#loadAsU3D-byte:A-}
```
public void loadAsU3D(byte[] stream)
```

将 3D 内容从字节数组加载为 U3D 格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 |  | 该流。 |

### loadAsU3D {#loadAsU3D-java.io.InputStream-}
将 3D 内容从流加载为 U3D 格式。

### loadAsU3D {#loadAsU3D-java.lang.String-}
将 3D 内容使用指定的文件名加载为 U3D 格式。

### saveToFile {#saveToFile-java.lang.String-}
将 3D 内容保存到文件。
