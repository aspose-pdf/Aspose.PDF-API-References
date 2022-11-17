---
title: IFacade
second_title: 用于 Java API 参考的 Aspose.PDF
description: 定义通用外观方法的通用外观接口。
type: docs
weight: 67
url: /zh/java/com.aspose.pdf.facades/ifacade/
---
**所有已实现的接口：**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public interface IFacade extends System.IDisposable, Closeable
```

定义通用外观方法的通用外观接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 绑定 PDF 文档进行编辑。 |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | 绑定 PDF 文档进行编辑。 |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | 绑定 PDF 文档进行编辑。 |
| [close()](#close--) | 释放与当前外观关联的任何资源。 |
### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public abstract void bindPdf(IDocument srcDoc)
```


绑定 PDF 文档进行编辑。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 输入 PDF 文档。 |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public abstract void bindPdf(InputStream srcStream)
```


绑定 PDF 文档进行编辑。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | 输入 PDF 文档的流。 |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public abstract void bindPdf(String srcFile)
```


绑定 PDF 文档进行编辑。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | 输入PDF文档的路径。 |

### close() {#close--}
```
public abstract void close()
```


释放与当前外观关联的任何资源。
