---
title: "ReplaceTextStrategy"
linktitle: "ReplaceTextStrategy"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは、ReplaceText 操作が実行されるときの PdfContentEditor の動作を定義するパラメータを含みます。"
type: docs
weight: 650
url: /ja/java/com.aspose.pdf.facades/replacetextstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.ReplaceTextStrategy

```
public final class ReplaceTextStrategy extends Object
```

このクラスは、ReplaceText 操作が実行されるときの PdfContentEditor の動作を定義するパラメータを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ReplaceTextStrategy](#ReplaceTextStrategy--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | 変更されたテキストに適切なフォントが見つからない場合に実行されるアクション（例外をスロー / 別のフォントに置き換える / とにかく置き換える）。 |
| [getReplaceScope](#getReplaceScope--) | 置換操作のスコープ（最初の出現を置換するか、すべての出現を置換するか）。 |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | false の場合、検索文字列は単純なテキストです。true の場合、検索文字列は正規表現です。 |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-) | 変更されたテキストに適切なフォントが見つからない場合に実行されるアクション（例外をスロー / 別のフォントに置き換える / とにかく置き換える）。 |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | false の場合、検索文字列は単純なテキストです。true の場合、検索文字列は正規表現です。 |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-) | 置換操作のスコープ（最初の出現を置換するか、すべての出現を置換するか）。 |

### ReplaceTextStrategy {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```



### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public ReplaceTextStrategy.NoCharacterAction getNoCharacterBehavior()
```

変更されたテキストに適切なフォントが見つからない場合に実行されるアクション（例外をスロー / 別のフォントに置き換える / とにかく置き換える）。

**Returns:**
NoCharacterAction の値。 @see NoCharacterAction

### getReplaceScope {#getReplaceScope--}
```
public ReplaceTextStrategy.Scope getReplaceScope()
```

置換操作のスコープ（最初の出現を置換するか、すべての出現を置換するか）。

**Returns:**
Scope 要素 @see Scope

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

false の場合、検索文字列は単純なテキストです。true の場合、検索文字列は正規表現です。

**Returns:**
ブール値

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-}
変更されたテキストに適切なフォントが見つからない場合に実行されるアクション（例外をスロー / 別のフォントに置き換える / とにかく置き換える）。

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

false の場合、検索文字列は単純なテキストです。true の場合、検索文字列は正規表現です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-}
置換操作のスコープ（最初の出現を置換するか、すべての出現を置換するか）。
