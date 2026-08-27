---
title: "PageNumberStamp"
linktitle: "PageNumberStamp"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページ番号スタンプを表し、ページ番号付けに使用されます。"
type: docs
weight: 3440
url: /ja/java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.TextStamp, com.aspose.pdf.PageNumberStamp

```
public final class PageNumberStamp extends TextStamp
```

ページ番号スタンプを表し、ページ番号付けに使用されます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PageNumberStamp](#PageNumberStamp--) | 新しい {@code PageNumberStamp} クラスのインスタンスを初期化します。フォーマットは "#" に設定されます。 |
| [PageNumberStamp](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | 新しい {@code PageNumberStamp} クラスのインスタンスを初期化します。フォーマットは "#" に設定されます。 |
| [PageNumberStamp](#PageNumberStamp-java.lang.String-) | 新しい {@code PageNumberStamp} クラスのインスタンスを初期化します。フォーマットは "#" に設定されます。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFormat](#getFormat--) | ページ番号をスタンプするための文字列値を取得します。値には文字 '#' を含める必要があり、スタンプ処理中にページ番号に置き換えられます。 |
| [getNumberingStyle](#getNumberingStyle--) | このスタンプで使用される番号付けスタイル。 |
| [getStartingNumber](#getStartingNumber--) | 開始ページ番号の値を取得します。この値から他のページが番号付けされます。 |
| [put](#put-com.aspose.pdf.Page-) | ページ番号を追加します。 |
| [setFormat](#setFormat-java.lang.String-) | ページ番号をスタンプするための文字列値を設定します。値には文字 '#' を含める必要があり、スタンプ処理中にページ番号に置き換えられます。 |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | このスタンプで使用される番号付けスタイル。 |
| [setStartingNumber](#setStartingNumber-int-) | 開始ページ番号の値を設定します。この値から他のページが番号付けされます。 |

### PageNumberStamp {#PageNumberStamp--}
```
public PageNumberStamp()
```

新しい {@code PageNumberStamp} クラスのインスタンスを初期化します。フォーマットは "#" に設定されます。

### PageNumberStamp {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
新しい {@code PageNumberStamp} クラスのインスタンスを初期化します。フォーマットは "#" に設定されます。

### PageNumberStamp {#PageNumberStamp-java.lang.String-}
新しい {@code PageNumberStamp} クラスのインスタンスを初期化します。フォーマットは "#" に設定されます。

### getFormat {#getFormat--}
```
public String getFormat()
```

ページ番号をスタンプするための文字列値を取得します。値には文字 '#' を含める必要があり、スタンプ処理中にページ番号に置き換えられます。

**Returns:**
文字列値

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

このスタンプで使用される番号付けスタイル。

**Returns:**
NumberingStyle の値 @see NumberingStyle

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

開始ページ番号の値を取得します。この値から他のページが番号付けされます。

**Returns:**
int 値です。

### put {#put-com.aspose.pdf.Page-}
ページ番号を追加します。

### setFormat {#setFormat-java.lang.String-}
ページ番号をスタンプするための文字列値を設定します。値には文字 '#' を含める必要があり、スタンプ処理中にページ番号に置き換えられます。

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
このスタンプで使用される番号付けスタイル。

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

開始ページ番号の値を設定します。この値から他のページが番号付けされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
