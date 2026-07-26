---
title: "TextExtractionError"
linktitle: "TextExtractionError"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントにテキスト抽出エラーが発生したことを説明します。"
type: docs
weight: 5040
url: /ja/java/com.aspose.pdf/textextractionerror/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionError

```
public final class TextExtractionError extends Object
```

PDF ドキュメントにテキスト抽出エラーが発生したことを説明します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDescription](#getDescription--) | エラーの拡張説明。 |
| [getExtractedText](#getExtractedText--) | 実際に抽出されたテキスト。 |
| [getFontKey](#getFontKey--) | 抽出エラーを引き起こすテキストの表示に使用される Font オブジェクトのキー（PDF 名）。 |
| [getFontName](#getFontName--) | 抽出エラーを引き起こすテキストの表示に使用される Font オブジェクトの読み取り可能（内部）名。 |
| [getLocation](#getLocation--) | エラーの位置。 |
| [getSummary](#getSummary--) | エラーの簡潔な説明。 |
| [toString](#toString--) | 文字列表現を返します。 |

### getDescription {#getDescription--}
```
public String getDescription()
```

エラーの拡張説明。

**Returns:**
文字列値

### getExtractedText {#getExtractedText--}
```
public String getExtractedText()
```

実際に抽出されたテキスト。

**Returns:**
文字列値

### getFontKey {#getFontKey--}
```
public String getFontKey()
```

抽出エラーを引き起こすテキストの表示に使用される Font オブジェクトのキー（PDF 名）。

**Returns:**
文字列値

### getFontName {#getFontName--}
```
public String getFontName()
```

抽出エラーを引き起こすテキストの表示に使用される Font オブジェクトの読み取り可能（内部）名。

**Returns:**
文字列値

### getLocation {#getLocation--}
```
public TextExtractionErrorLocation getLocation()
```

エラーの位置。

**Returns:**
TextExtractionErrorLocation インスタンス

### getSummary {#getSummary--}
```
public String getSummary()
```

エラーの簡潔な説明。

**Returns:**
文字列値

### toString {#toString--}
```
public String toString()
```

文字列表現を返します。

**Returns:**
文字列表現
