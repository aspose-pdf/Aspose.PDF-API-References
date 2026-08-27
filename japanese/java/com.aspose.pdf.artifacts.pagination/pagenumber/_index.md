---
title: "PageNumber"
linktitle: "PageNumber"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "インデックス、総ページ数、区切り文字を含むページ番号フォーマットを表します。"
type: docs
weight: 150
url: /ja/java/com.aspose.pdf.artifacts.pagination/pagenumber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.artifacts.pagination.PageNumber

```
public final class PageNumber extends Object
```

インデックス、総ページ数、区切り文字を含むページ番号フォーマットを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PageNumber](#PageNumber--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDelimiter](#getDelimiter--) | ページ番号書式で使用される区切り文字を取得または設定します。指定された区切り文字に基づいて書式化された文字列が更新されます。 |
| [getIndex](#getIndex--) | ページ番号書式のページインデックスコンポーネントを取得または設定します。書式化された文字列にはページインデックスのプレースホルダーが含まれます。 |
| [getOffset](#getOffset--) | ページインデックスに加えるオフセットを取得または設定します。 |
| [getPageNumberString](#getPageNumberString-int-int-) | 現在の設定に基づいてページ番号を表す書式化された文字列を返します。 |
| [getTotalNum](#getTotalNum--) | ページ番号書式の総ページ数コンポーネントを取得または設定します。書式化された文字列には総ページ数のプレースホルダーが含まれます。 |
| [setDelimiter](#setDelimiter-java.lang.String-) | ページ番号書式で使用される区切り文字を取得または設定します。指定された区切り文字に基づいて書式化された文字列が更新されます。 |
| [setIndex](#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-) | ページ番号書式のページインデックスコンポーネントを取得または設定します。 |
| [setOffset](#setOffset-int-) | ページインデックスに加えるオフセットを取得または設定します。 |
| [setTotalNum](#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-) | ページ番号書式の総ページ数コンポーネントを取得または設定します。 |

### PageNumber {#PageNumber--}
```
public PageNumber()
```



### getDelimiter {#getDelimiter--}
```
public final String getDelimiter()
```

ページ番号書式で使用される区切り文字を取得または設定します。指定された区切り文字に基づいて書式化された文字列が更新されます。

**Returns:**
文字列値

### getIndex {#getIndex--}
```
public final PageNumber.PageIndex getIndex()
```

ページ番号書式のページインデックスコンポーネントを取得または設定します。書式化された文字列にはページインデックスのプレースホルダーが含まれます。

**Returns:**
PageIndex インスタンス

### getOffset {#getOffset--}
```
public final int getOffset()
```

ページインデックスに加えるオフセットを取得または設定します。

**Returns:**
int 値です。

### getPageNumberString {#getPageNumberString-int-int-}
```
public final String getPageNumberString(int pageNumber, int count)
```

現在の設定に基づいてページ番号を表す書式化された文字列を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | 現在のページ番号です。 |
| カウント |  | 総ページ数です。 |

**Returns:**
書式設定されたページ番号文字列です。

### getTotalNum {#getTotalNum--}
```
public final PageNumber.PageTotalNum getTotalNum()
```

ページ番号書式の総ページ数コンポーネントを取得または設定します。書式化された文字列には総ページ数のプレースホルダーが含まれます。

**Returns:**
PageTotalNum インスタンス

### setDelimiter {#setDelimiter-java.lang.String-}
ページ番号書式で使用される区切り文字を取得または設定します。指定された区切り文字に基づいて書式化された文字列が更新されます。

### setIndex {#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-}
ページ番号書式のページインデックスコンポーネントを取得または設定します。

### setOffset {#setOffset-int-}
```
public final void setOffset(int value)
```

ページインデックスに加えるオフセットを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setTotalNum {#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-}
ページ番号書式の総ページ数コンポーネントを取得または設定します。
