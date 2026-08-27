---
title: "FontEmbeddingOptions"
linktitle: "FontEmbeddingOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF/A 標準では、すべてのフォントを文書に埋め込むことが要求されています。このクラスは、フォントが存在しないために埋め込めない場合のフラグを含みます。"
type: docs
weight: 1680
url: /ja/java/com.aspose.pdf/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontEmbeddingOptions

```
public class FontEmbeddingOptions extends Object
```

PDF/A 標準では、すべてのフォントを文書に埋め込むことが要求されています。このクラスには、フォントが宛先 PC に存在せず埋め込めない場合のフラグが含まれています。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontEmbeddingOptions](#FontEmbeddingOptions--) | {@link FontEmbeddingOptions} クラスの新しいインスタンスを初期化します。このコンストラクタは、{@code UseDefaultSubstitution}（{@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}）プロパティのデフォルト値を {@code } に設定します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getUseDefaultSubstitution](#getUseDefaultSubstitution--) | デフォルトのフォント置換戦略を使用して、埋め込みされていないフォントを置き換えるかどうかを示します。デフォルトは false です。 |
| [setUseDefaultSubstitution](#setUseDefaultSubstitution-boolean-) | デフォルトのフォント置換戦略を使用して、埋め込みされていないフォントを置き換えるかどうかを示します。デフォルトは false です。 |

### FontEmbeddingOptions {#FontEmbeddingOptions--}
```
public FontEmbeddingOptions()
```

{@link FontEmbeddingOptions} クラスの新しいインスタンスを初期化します。このコンストラクタは、{@code UseDefaultSubstitution}（{@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}）プロパティのデフォルト値を {@code } に設定します。

### getUseDefaultSubstitution {#getUseDefaultSubstitution--}
```
public boolean getUseDefaultSubstitution()
```

デフォルトのフォント置換戦略を使用して、埋め込みされていないフォントを置き換えるかどうかを示します。デフォルトは false です。

**Returns:**
ブール値

### setUseDefaultSubstitution {#setUseDefaultSubstitution-boolean-}
```
public void setUseDefaultSubstitution(boolean value)
```

デフォルトのフォント置換戦略を使用して、埋め込みされていないフォントを置き換えるかどうかを示します。デフォルトは false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
