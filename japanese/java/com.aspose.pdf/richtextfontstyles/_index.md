---
title: "RichTextFontStyles"
linktitle: "RichTextFontStyles"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "RichText 内のテキストフラグメントのスタイリングオプションです。"
type: docs
weight: 4300
url: /ja/java/com.aspose.pdf/richtextfontstyles/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.Enum, com.aspose.pdf.RichTextFontStyles

```
public final class RichTextFontStyles extends com.aspose.ms.System.Enum
```

RichText 内のテキストフラグメントのスタイリングオプションです。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Bold](#Bold) | 太字を指定するオプションです。 |
| [ClearExisting](#ClearExisting) | 設定されている場合、追加のスタイルを適用する前に既存のすべてのスタイルをクリアします。他のスタイルフラグ（例: {@code RichTextFontStyles#Bold}）と組み合わせると、まずスタイルをリセットし、指定されたスタイルを適用します。このフラグがない場合、新しいスタイルは既存のスタイルに追加されます。 |
| [Italic](#Italic) | 斜体を指定するオプションです。 |
| [Underline](#Underline) | 下線を指定するオプションです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) | 指定されたフラグが設定されているかどうかをチェックします。 |

### Bold {#Bold}
```
public static final int Bold
```

太字を指定するオプションです。

### ClearExisting {#ClearExisting}
```
public static final int ClearExisting
```

設定されている場合、追加のスタイルを適用する前に既存のすべてのスタイルをクリアします。他のスタイルフラグ（例: {@code RichTextFontStyles#Bold}）と組み合わせると、まずスタイルをリセットし、指定されたスタイルを適用します。このフラグがない場合、新しいスタイルは既存のスタイルに追加されます。

### Italic {#Italic}
```
public static final int Italic
```

斜体を指定するオプションです。

### Underline {#Underline}
```
public static final int Underline
```

下線を指定するオプションです。

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```

指定されたフラグが設定されているかどうかをチェックします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| フラグ |  | チェックするフラグを表す列挙値 |
| flagToCheck |  | チェックするフラグを表す列挙値 |

**Returns:**
{@code true} はフラグが設定されている場合、{@code false} はそれ以外の場合です
