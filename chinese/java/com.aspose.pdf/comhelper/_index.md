---
title: "ComHelper"
linktitle: "ComHelper"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 为 COM 客户端提供将文档加载到 Aspose.PDF 的方法。 </p> <hr> <p> 使用 ComHelper 类从文件或流加载文档到 Document 对象中。</p>"
type: docs
weight: 760
url: /zh/java/com.aspose.pdf/comhelper/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ComHelper

```
public class ComHelper extends Object
```

<p> 为 COM 客户端提供将文档加载到 Aspose.PDF 的方法。 </p> <hr> <p> 使用 ComHelper 类将文档从文件或流加载到 COM 应用程序中的 Document 对象。Document 类提供默认构造函数来创建新文档，并且还提供重载构造函数以从文件或流加载文档。如果您在 .NET 应用程序中使用 Aspose.Words，可以直接使用所有 Document 构造函数，但如果在 COM 应用程序中使用 Aspose.PDF，则仅提供默认的 Document 构造函数。 </p>

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ComHelper](#ComHelper--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [openFile](#openFile-java.lang.String-) | 仅使用 {@code filename} 创建并返回 Document。等同于 {@code Document(Stream)}。 |
| [openFile](#openFile-java.lang.String-com.aspose.pdf.LoadOptions-) | 从文件打开现有文档，提供必要的转换选项以获取 PDF 文档。 |
| [openFile](#openFile-java.lang.String-java.lang.String-) | 初始化并返回用于处理加密文档的 {@code Document} 类的新实例。 |
| [openFile](#openFile-java.lang.String-java.lang.String-boolean-) | 初始化用于处理加密文档的 {@code Document} 类的新实例。 |
| [openStream](#openStream-java.io.InputStream-) | 从 {@code input} 流初始化并返回新的 Document 实例。 |
| [openStream](#openStream-java.io.InputStream-boolean-) | 从 {@code input} 流初始化并返回新的 Document 实例。 |
| [openStream](#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-) | 从流打开并返回现有文档，提供必要的转换以获取 PDF 文档。 |
| [openStream](#openStream-java.io.InputStream-java.lang.String-) | 从 {@code input} 流初始化并返回新的 Document 实例。 |
| [openStream](#openStream-java.io.InputStream-java.lang.String-boolean-) | 从 {@code input} 流初始化并返回新的 Document 实例。 |

### ComHelper {#ComHelper--}
```
public ComHelper()
```



### openFile {#openFile-java.lang.String-}
仅使用 {@code filename} 创建并返回 Document。等同于 {@code Document(Stream)}。

### openFile {#openFile-java.lang.String-com.aspose.pdf.LoadOptions-}
从文件打开现有文档，提供必要的转换选项以获取 PDF 文档。

### openFile {#openFile-java.lang.String-java.lang.String-}
初始化并返回用于处理加密文档的 {@code Document} 类的新实例。

### openFile {#openFile-java.lang.String-java.lang.String-boolean-}
初始化用于处理加密文档的 {@code Document} 类的新实例。

### openStream {#openStream-java.io.InputStream-}
从 {@code input} 流初始化并返回新的 Document 实例。

### openStream {#openStream-java.io.InputStream-boolean-}
从 {@code input} 流初始化并返回新的 Document 实例。

### openStream {#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-}
从流打开并返回现有文档，提供必要的转换以获取 PDF 文档。

### openStream {#openStream-java.io.InputStream-java.lang.String-}
从 {@code input} 流初始化并返回新的 Document 实例。

### openStream {#openStream-java.io.InputStream-java.lang.String-boolean-}
从 {@code input} 流初始化并返回新的 Document 实例。
