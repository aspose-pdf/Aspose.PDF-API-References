---
title: "PdfASymbolicFontEncodingStrategy.QueueItem"
linktitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "エンコーディングサブテーブルを指定します。各エンコーディングサブテーブルは、パラメータ (PlatformID、PlatformSpecificID) のユニークな組み合わせを持ちます。列挙型 {@code CMapEncodingTableType} とプロパティ。"
type: docs
weight: 3700
url: /ja/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem

```
public static class PdfASymbolicFontEncodingStrategy.QueueItem extends Object
```

エンコーディングサブテーブルを指定します。各エンコーディングサブテーブルはパラメータ (PlatformID, PlatformSpecificID) のユニークな組み合わせを持ちます。列挙型 {@code CMapEncodingTableType} とプロパティ {@code CMapEncodingTable} は、必要なエンコーディングサブテーブルの設定を容易にするために実装されました。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [QueueItem](#QueueItem--) | コンストラクタ。デフォルトで mac サブテーブル (1,0) を指定します。 |
| [QueueItem](#QueueItem-int-int-) | コンストラクタ |
| [QueueItem](#QueueItem-short-) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCMapEncodingTable](#getCMapEncodingTable--) | {@code CMapEncodingTableType} 列挙型を使用してエンコーディングサブテーブルを指定します。 |
| [getPlatformId](#getPlatformId--) | エンコーディングサブテーブルのプラットフォーム識別子 |
| [getPlatformSpecificId](#getPlatformSpecificId--) | エンコーディングサブテーブルのプラットフォーム固有エンコーディング識別子 |
| [setCMapEncodingTable](#setCMapEncodingTable-short-) | {@code CMapEncodingTableType} 列挙型を使用してエンコーディングサブテーブルを指定します。 |
| [setPlatformId](#setPlatformId-int-) | エンコーディングサブテーブルのプラットフォーム識別子 |
| [setPlatformSpecificId](#setPlatformSpecificId-int-) | エンコーディングサブテーブルのプラットフォーム固有エンコーディング識別子 |

### QueueItem {#QueueItem--}
```
public QueueItem()
```

コンストラクタ。デフォルトで mac サブテーブル (1,0) を指定します。

### QueueItem {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```

コンストラクタ

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| platformID |  | エンコーディングサブテーブルのプラットフォーム識別子 |
| platformSpecificID |  | エンコーディングサブテーブルのプラットフォーム固有エンコーディング識別子 |

### QueueItem {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```

コンストラクタ

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmapTable |  | エンコーディングサブテーブル |

### getCMapEncodingTable {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```

{@code CMapEncodingTableType} 列挙型を使用してエンコーディングサブテーブルを指定します。

**Returns:**
エンコーディングサブテーブル

### getPlatformId {#getPlatformId--}
```
public int getPlatformId()
```

エンコーディングサブテーブルのプラットフォーム識別子

**Returns:**
int 値です。

### getPlatformSpecificId {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```

エンコーディングサブテーブルのプラットフォーム固有エンコーディング識別子

**Returns:**
int 値です。

### setCMapEncodingTable {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```

{@code CMapEncodingTableType} 列挙型を使用してエンコーディングサブテーブルを指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | エンコーディングサブテーブル |

### setPlatformId {#setPlatformId-int-}
```
public void setPlatformId(int value)
```

エンコーディングサブテーブルのプラットフォーム識別子

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setPlatformSpecificId {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```

エンコーディングサブテーブルのプラットフォーム固有エンコーディング識別子

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
