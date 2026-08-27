---
title: "Layer"
linktitle: "Layer"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ページ内のレイヤーを表します。"
type: docs
weight: 2640
url: /ja/java/com.aspose.pdf/layer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Layer

```
public class Layer extends Object
```

PDF ページ内のレイヤーを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Layer](#Layer-java.lang.String-java.lang.String-) | {@code Layer} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [delete](#delete--) | PDF ドキュメントから現在のレイヤーを削除します。 |
| [flatten](#flatten-boolean-) | 指定されたレイヤーをフラット化します。 |
| [getContents](#getContents--) | <p> レイヤーの内容を取得します。 </p> |
| [getDefaultState](#getDefaultState--) | PDFレイヤーのデフォルト状態を取得します。 |
| [getId](#getId--) | レイヤーIDを取得します。 |
| [getLocked](#getLocked--) | レイヤーがロックされているかどうかを示す値を取得します。 |
| [getName](#getName--) | レイヤー名を取得します。 |
| [lock](#lock--) | レイヤーをロックします。 |
| [save](#save-java.io.OutputStream-) | 現在のレイヤーをPDFドキュメントに保存します。 |
| [save](#save-java.lang.String-) | 現在のレイヤーをPDFドキュメントに保存します。 |
| [setDefaultState](#setDefaultState-com.aspose.pdf.DefaultState-) | PDFレイヤーのデフォルト状態を設定します。 |
| [unlock](#unlock--) | レイヤーのロックを解除します。 |

### Layer {#Layer-java.lang.String-java.lang.String-}
{@code Layer} クラスの新しいインスタンスを初期化します。

### delete {#delete--}
```
public final void delete()
```

PDF ドキュメントから現在のレイヤーを削除します。

### flatten {#flatten-boolean-}
```
public final void flatten(boolean cleanupContentStream)
```

指定されたレイヤーをフラット化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cleanupContentStream |  | コンテンツストリームからオプションコンテンツグループマーカーを削除するかどうかを指定します。{@code cleanupContentStream} パラメータを false に設定すると、フラット化の処理が高速化されます。 |

### getContents {#getContents--}
```
public List < Operator > getContents()
```

<p> レイヤーの内容を取得します。 </p>

**Returns:**
{@code List<Operator>} オブジェクト

### getDefaultState {#getDefaultState--}
```
public final DefaultState getDefaultState()
```

PDFレイヤーのデフォルト状態を取得します。

**Returns:**
PDFレイヤーのデフォルト状態。

### getId {#getId--}
```
public String getId()
```

レイヤーIDを取得します。

**Returns:**
文字列値

### getLocked {#getLocked--}
```
public final boolean getLocked()
```

レイヤーがロックされているかどうかを示す値を取得します。

**Returns:**
ブール値

### getName {#getName--}
```
public String getName()
```

レイヤー名を取得します。

**Returns:**
文字列値

### lock {#lock--}
```
public final void lock()
```

レイヤーをロックします。

### save {#save-java.io.OutputStream-}
現在のレイヤーをPDFドキュメントに保存します。

### save {#save-java.lang.String-}
現在のレイヤーをPDFドキュメントに保存します。

### setDefaultState {#setDefaultState-com.aspose.pdf.DefaultState-}
PDFレイヤーのデフォルト状態を設定します。

### unlock {#unlock--}
```
public final void unlock()
```

レイヤーのロックを解除します。
