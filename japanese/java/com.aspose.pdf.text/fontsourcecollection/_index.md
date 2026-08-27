---
title: "FontSourceCollection"
linktitle: "FontSourceCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フォントソースのコレクションを表します。"
type: docs
weight: 40
url: /ja/java/com.aspose.pdf.text/fontsourcecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSourceCollection

**All Implemented Interfaces:**
イテラブル < FontSource >

```
public final class FontSourceCollection extends Object implements Iterable < FontSource >
```

フォントソースのコレクションを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [CollectionChanged](#CollectionChanged) | CollectionChanged イベント |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontSourceCollection](#FontSourceCollection--) | コレクションオブジェクトを初期化します |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.FontSource-) | 新しいフォントソースオブジェクトをコレクションに追加します。 |
| [clear](#clear--) | フォントソースコレクションをクリアします。 |
| [contains](#contains-com.aspose.pdf.FontSource-) | 要素がコレクションに含まれているかどうかを判断します。 |
| [copyTo](#copyTo-com.aspose.pdf.FontSource:A-int-) | コレクション全体を互換性のある一次元配列にコピーし、対象配列の指定されたインデックスから開始します。 |
| [delete](#delete-com.aspose.pdf.FontSource-) | フォントソース要素を削除します。 |
| [getItem](#getItem-int-) | 指定されたインデックスのフォント要素を取得します。 |
| [getSyncRoot](#getSyncRoot--) | コレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
| [isSynchronized](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。 |
| [iterator](#iterator--) | コレクション全体の列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.FontSource-) | フォントソース要素を削除します。 |
| [size](#size--) | コレクションに実際に含まれる Font オブジェクト要素の数を取得します。 |

### CollectionChanged {#CollectionChanged}
```
public final PdfEvent <com.aspose.ms.System.EventHandler> CollectionChanged
```

CollectionChanged イベント

### FontSourceCollection {#FontSourceCollection--}
```
public FontSourceCollection()
```

コレクションオブジェクトを初期化します

### add {#add-com.aspose.pdf.FontSource-}
新しいフォントソースオブジェクトをコレクションに追加します。

### clear {#clear--}
```
public void clear()
```

フォントソースコレクションをクリアします。

### contains {#contains-com.aspose.pdf.FontSource-}
要素がコレクションに含まれているかどうかを判断します。

### copyTo {#copyTo-com.aspose.pdf.FontSource:A-int-}
コレクション全体を互換性のある一次元配列にコピーし、対象配列の指定されたインデックスから開始します。

### delete {#delete-com.aspose.pdf.FontSource-}
フォントソース要素を削除します。

### getItem {#getItem-int-}
```
public FontSource getItem(int index)
```

指定されたインデックスのフォント要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | コレクション内のインデックス。 |

**Returns:**
フォントソースオブジェクト。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

コレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。

**Returns:**
オブジェクト要素

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator()
```

コレクション全体の列挙子を返します。

**Returns:**
Enumerator オブジェクト。

### remove {#remove-com.aspose.pdf.FontSource-}
フォントソース要素を削除します。

### size {#size--}
```
public int size()
```

コレクションに実際に含まれる Font オブジェクト要素の数を取得します。

**Returns:**
int 値です。
