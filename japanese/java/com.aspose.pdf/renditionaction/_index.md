---
title: "RenditionAction"
linktitle: "RenditionAction"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "マルチメディアコンテンツの再生を制御するレンディションアクションです。"
type: docs
weight: 4180
url: /ja/java/com.aspose.pdf/renditionaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.RenditionAction, com.aspose.pdf.PdfAction, com.aspose.pdf.RenditionAction

**All Implemented Interfaces:**
IAppointment

```
public final class RenditionAction extends PdfAction
```

マルチメディアコンテンツの再生を制御するレンディションアクションです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RenditionAction](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | レンダリング アクションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getJavaScript](#getJavaScript--) | アクションに関連付けられた JavaScript コードを取得または設定します。 |
| [getRendition](#getRendition--) | アクションに関連付けられたレンダリングを取得または設定します。 |
| [getRenditionOperation](#getRenditionOperation--) | アクションがトリガーされたときに実行される操作です。 |
| [setJavaScript](#setJavaScript-java.lang.String-) | アクションに関連付けられた JavaScript コードを取得または設定します。 |
| [setRenditionOperation](#setRenditionOperation-int-) | アクションがトリガーされたときに実行される操作です。 |

### RenditionAction {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
レンダリング アクションを作成します。

### getJavaScript {#getJavaScript--}
```
public final String getJavaScript()
```

アクションに関連付けられた JavaScript コードを取得または設定します。

**Returns:**
文字列値

### getRendition {#getRendition--}
```
public final Rendition getRendition()
```

アクションに関連付けられたレンダリングを取得または設定します。

**Returns:**
レンダリング インスタンス

### getRenditionOperation {#getRenditionOperation--}
```
public final int getRenditionOperation()
```

アクションがトリガーされたときに実行される操作です。

**Returns:**
RenditionOperation 要素

### setJavaScript {#setJavaScript-java.lang.String-}
アクションに関連付けられた JavaScript コードを取得または設定します。

### setRenditionOperation {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```

アクションがトリガーされたときに実行される操作です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | RenditionOperation 要素 |
