---
title: "Copier"
linktitle: "Copier"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "オブジェクトをコピーするためのクラスです。"
type: docs
weight: 850
url: /ja/java/com.aspose.pdf/copier/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Copier

```
public class Copier extends Object
```

オブジェクトをコピーするためのクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Copier](#Copier-com.aspose.pdf.engine.data.ITrailerable-) | Copier クラスのインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-) | IPdfPrimitive を複製します |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-) | すべての依存オブジェクトを含むオブジェクトのコピーを作成します。 |
| [getAllowReusePageContent](#getAllowReusePageContent--) | Allow Reuse Page Content を取得 |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Ignore Corrupted Objects を取得 |
| [getRestrictedKeys](#getRestrictedKeys--) | Restricted Keys を取得 |
| [getReuseStreams](#getReuseStreams--) | Reuse Streams を取得 |
| [getUseStubs](#getUseStubs--) | 複製プロセス中にスタブを使用すべきかどうかを示します。オプションが有効な場合、ストリームはコピーされ、無効な場合は元のストリームへのリンクが使用されます。これにより、コピーされたドキュメントを閉じることはできませんが、コピー処理とメモリ使用量を削減できます。 |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Allow Reuse Page Content を設定 |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Ignore Corrupted Objects を設定 |
| [setRestrictedKeys](#setRestrictedKeys-java.lang.String:A-) | Restricted Keys を設定 |
| [setReuseStreams](#setReuseStreams-boolean-) | Reuse Streams を設定 |
| [setUseStubs](#setUseStubs-boolean-) | 複製プロセス中にスタブを使用すべきかどうかを示します。オプションが有効な場合、ストリームはコピーされ、無効な場合は元のストリームへのリンクが使用されます。これにより、コピーされたドキュメントを閉じることはできませんが、コピー処理とメモリ使用量を削減できます。 |

### Copier {#Copier-com.aspose.pdf.engine.data.ITrailerable-}
Copier クラスのインスタンスを作成します。

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-}
IPdfPrimitive を複製します

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-}
すべての依存オブジェクトを含むオブジェクトのコピーを作成します。

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

Allow Reuse Page Content を取得

**Returns:**
ブール値

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

Ignore Corrupted Objects を取得

**Returns:**
ブール値

### getRestrictedKeys {#getRestrictedKeys--}
```
public String [] getRestrictedKeys()
```

Restricted Keys を取得

**Returns:**
String[] 配列

### getReuseStreams {#getReuseStreams--}
```
public boolean getReuseStreams()
```

Reuse Streams を取得

**Returns:**
ブール値

### getUseStubs {#getUseStubs--}
```
public boolean getUseStubs()
```

複製プロセス中にスタブを使用すべきかどうかを示します。オプションが有効な場合、ストリームはコピーされ、無効な場合は元のストリームへのリンクが使用されます。これにより、コピーされたドキュメントを閉じることはできませんが、コピー処理とメモリ使用量を削減できます。

**Returns:**
ブール値

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

Allow Reuse Page Content を設定

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Ignore Corrupted Objects を設定

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRestrictedKeys {#setRestrictedKeys-java.lang.String:A-}
Restricted Keys を設定

### setReuseStreams {#setReuseStreams-boolean-}
```
public void setReuseStreams(boolean value)
```

Reuse Streams を設定

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUseStubs {#setUseStubs-boolean-}
```
public void setUseStubs(boolean value)
```

複製プロセス中にスタブを使用すべきかどうかを示します。オプションが有効な場合、ストリームはコピーされ、無効な場合は元のストリームへのリンクが使用されます。これにより、コピーされたドキュメントを閉じることはできませんが、コピー処理とメモリ使用量を削減できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
