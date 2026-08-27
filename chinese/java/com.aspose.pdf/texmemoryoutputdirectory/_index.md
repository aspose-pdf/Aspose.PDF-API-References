---
title: "TeXMemoryOutputDirectory"
linktitle: "TeXMemoryOutputDirectory"
second_title: "Aspose.PDF for Java API 参考"
description: "实现从内存获取输出流。您可以在例如不想将伴随的输出（如日志文件）写入磁盘但希望保留时使用它。"
type: docs
weight: 4880
url: /zh/java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TeXMemoryOutputDirectory

**All Implemented Interfaces:**
ITeXInputDirectory, ITeXOutputDirectory, Closeable, AutoCloseable

```
public class TeXMemoryOutputDirectory extends Object implements ITeXOutputDirectory
```

实现从内存获取输出流。例如，当您不希望伴随的输出（如日志文件）写入磁盘，而希望随后从内存中读取时，可使用它。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TeXMemoryOutputDirectory](#TeXMemoryOutputDirectory--) | 创建新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [close](#close--) | 释放实例。@throws IOException 如果发生 I/O 错误，可能会抛出 IOException 异常 |
| [getFile](#getFile-java.lang.String-java.lang.String:A-) | 返回用于读取的流。无需在子目录中查找文件。 |
| [getFile](#getFile-java.lang.String-java.lang.String:A-boolean-) | 返回用于读取的流。 |
| [getOutputFile](#getOutputFile-java.lang.String-java.lang.String:A-) | 返回用于写入的流。 |

### TeXMemoryOutputDirectory {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```

创建新实例。

### close {#close--}
```
public void close() throws IOException
```

释放实例。@throws IOException 如果发生 I/O 错误，可能会抛出 IOException 异常

### getFile {#getFile-java.lang.String-java.lang.String:A-}
返回用于读取的流。无需在子目录中查找文件。

### getFile {#getFile-java.lang.String-java.lang.String:A-boolean-}
返回用于读取的流。

### getOutputFile {#getOutputFile-java.lang.String-java.lang.String:A-}
返回用于写入的流。
