---
title: "SimpleFontSubstitution"
linktitle: "SimpleFontSubstitution"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "シンプルなフォント置換戦略のクラスを表します。"
type: docs
weight: 90
url: /ja/java/com.aspose.pdf.text/simplefontsubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SimpleFontSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SimpleFontSubstitution

```
public final class SimpleFontSubstitution extends FontSubstitution
```

シンプルなフォント置換戦略のクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-) | 新しい {@code SimpleFontSubstitution} クラスのインスタンスを初期化します。 |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-) | 新しい {@code SimpleFontSubstitution} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | {@code SubstitutionFontName} に置換される元のフォント名を取得します |
| [getSubstitutedUnicode](#getSubstitutedUnicode-char-) | unicode 置換を返します |
| [getSubstitutionFontName](#getSubstitutionFontName--) | {@code OriginalFontName} を置換すべきフォント名を取得します |

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-}
新しい {@code SimpleFontSubstitution} クラスのインスタンスを初期化します。

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-}
新しい {@code SimpleFontSubstitution} クラスのインスタンスを初期化します。

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

{@code SubstitutionFontName} に置換される元のフォント名を取得します

**Returns:**
文字列値

### getSubstitutedUnicode {#getSubstitutedUnicode-char-}
```
public char getSubstitutedUnicode(char unicode)
```

unicode 置換を返します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| unicode |  | char 値 |

**Returns:**
char 値

### getSubstitutionFontName {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```

{@code OriginalFontName} を置換すべきフォント名を取得します

**Returns:**
文字列値
