---
title: "Facade"
linktitle: "Facade"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "基本ファサードクラス。"
type: docs
weight: 130
url: /ja/java/com.aspose.pdf.facades/facade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public abstract class Facade extends Object implements IFacade , com.aspose.ms.System.IDisposable
```

基本ファサードクラス。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | ファサードを初期化します。 |
| [bindPdf](#bindPdf-java.io.InputStream-) | ファサードを初期化します。 |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | ファサードを初期化します。 |
| [bindPdf](#bindPdf-java.lang.String-) | / * / * Facade を初期化します。 / * / * / * |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | ファサードを初期化します。 |
| [close](#close--) | Facade にバインドされた Document を破棄します。 |
| [dispose](#dispose--) | Facade を破棄します。このメソッドは廃止予定です。代わりに close() を使用してください。 |
| [getDocument](#getDocument--) | 作業対象のドキュメント Facade を取得します。 |

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
ファサードを初期化します。

### bindPdf {#bindPdf-java.io.InputStream-}
ファサードを初期化します。

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
ファサードを初期化します。

### bindPdf {#bindPdf-java.lang.String-}
/ * / * Facade を初期化します。 / * / * / *

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
ファサードを初期化します。

### close {#close--}
```
public void close()
```

Facade にバインドされた Document を破棄します。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Facade を破棄します。このメソッドは廃止予定です。代わりに close() を使用してください。

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

作業対象のドキュメント Facade を取得します。

**Returns:**
IDocument element
