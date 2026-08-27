---
title: "Facade"
linktitle: "Facade"
second_title: "Aspose.PDF for Java API 参考"
description: "基础外观类。"
type: docs
weight: 130
url: /zh/java/com.aspose.pdf.facades/facade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public abstract class Facade extends Object implements IFacade , com.aspose.ms.System.IDisposable
```

基础外观类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | 初始化 facade。 |
| [bindPdf](#bindPdf-java.io.InputStream-) | 初始化 facade。 |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化 facade。 |
| [bindPdf](#bindPdf-java.lang.String-) | / * / * 初始化 facade。 / * / * / * |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | 初始化 facade。 |
| [close](#close--) | 释放与 facade 绑定的 Document。 |
| [dispose](#dispose--) | 释放 facade。此方法已过时，请改用 close()。 |
| [getDocument](#getDocument--) | 获取正在使用的文档 facade。 |

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
初始化 facade。

### bindPdf {#bindPdf-java.io.InputStream-}
初始化 facade。

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
初始化 facade。

### bindPdf {#bindPdf-java.lang.String-}
/ * / * 初始化 facade。 / * / * / *

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
初始化 facade。

### close {#close--}
```
public void close()
```

释放与 facade 绑定的 Document。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

释放 facade。此方法已过时，请改用 close()。

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

获取正在使用的文档 facade。

**Returns:**
IDocument element
