---
title: "XfaParserOptions"
linktitle: "XfaParserOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "class 関連データのカプセル化を処理する"
type: docs
weight: 5560
url: /ja/java/com.aspose.pdf/xfaparseroptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfaParserOptions

```
public class XfaParserOptions extends Object
```

class 関連データのカプセル化を処理する

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XfaParserOptions](#XfaParserOptions-java.awt.geom.Dimension2D-) | {@code XfaParserOptions} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBasePath](#getBasePath--) | ベースパスを取得または設定します。値: ベースパス。 |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | このプロパティが true の場合、必要な Xfa \"除外グループ\" に対して追加の赤い矩形が描画されます。このプロパティは、変換時に除外グループの類似が欠如しているために導入されました。デフォルトは false です。 |
| [getPageSize](#getPageSize--) | ページのサイズを取得または設定します。値: ページのサイズ。 |
| [getSigned](#getSigned--) | このプロパティが true の場合、（存在すれば）Xfa フォームストリームを使用してドキュメントが変換されます。false の場合、Xfa フォームストリームは無視されます。このプロパティは、署名の検証に使用されるチェックサムの計算方法が不明確であるために導入されました。 |
| [setBasePath](#setBasePath-java.net.URI-) | ベースパスを取得または設定します。値: ベースパス。 |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | このプロパティが true の場合、必要な Xfa \"除外グループ\" に対して追加の赤い矩形が描画されます。このプロパティは、変換時に除外グループの類似が欠如しているために導入されました。デフォルトは false です。 |
| [setPageSize](#setPageSize-java.awt.geom.Dimension2D-) | ページのサイズを取得または設定します。値: ページのサイズ。 |
| [setSigned](#setSigned-boolean-) | このプロパティが true の場合、（存在すれば）Xfa フォームストリームを使用してドキュメントが変換されます。false の場合、Xfa フォームストリームは無視されます。このプロパティは、署名の検証に使用されるチェックサムの計算方法が不明確であるために導入されました。 |

### XfaParserOptions {#XfaParserOptions-java.awt.geom.Dimension2D-}
{@code XfaParserOptions} クラスの新しいインスタンスを初期化します。

### getBasePath {#getBasePath--}
```
public URI getBasePath()
```

ベースパスを取得または設定します。値: ベースパス。

**Returns:**
URI オブジェクト

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

このプロパティが true の場合、必要な Xfa \"除外グループ\" に対して追加の赤い矩形が描画されます。このプロパティは、変換時に除外グループの類似が欠如しているために導入されました。デフォルトは false です。

**Returns:**
ブール値

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

ページのサイズを取得または設定します。値: ページのサイズ。

**Returns:**
Dimension2D オブジェクト

### getSigned {#getSigned--}
```
public boolean getSigned()
```

このプロパティが true の場合、（存在すれば）Xfa フォームストリームを使用してドキュメントが変換されます。false の場合、Xfa フォームストリームは無視されます。このプロパティは、署名の検証に使用されるチェックサムの計算方法が不明確であるために導入されました。

**Returns:**
ブール値

### setBasePath {#setBasePath-java.net.URI-}
ベースパスを取得または設定します。値: ベースパス。

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

このプロパティが true の場合、必要な Xfa \"除外グループ\" に対して追加の赤い矩形が描画されます。このプロパティは、変換時に除外グループの類似が欠如しているために導入されました。デフォルトは false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setPageSize {#setPageSize-java.awt.geom.Dimension2D-}
ページのサイズを取得または設定します。値: ページのサイズ。

### setSigned {#setSigned-boolean-}
```
public void setSigned(boolean value)
```

このプロパティが true の場合、（存在すれば）Xfa フォームストリームを使用してドキュメントが変換されます。false の場合、Xfa フォームストリームは無視されます。このプロパティは、署名の検証に使用されるチェックサムの計算方法が不明確であるために導入されました。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
