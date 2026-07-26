---
title: "アウトライン"
linktitle: "アウトライン"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "アウトラインのコレクションを記述するクラス。"
type: docs
weight: 3280
url: /ja/java/com.aspose.pdf/outlines/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public abstract class Outlines extends Object implements Iterable < OutlineItemCollection >
```

アウトラインのコレクションを記述するクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Outlines](#Outlines--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | アウトライン項目をコレクションに追加します。 |
| [clear](#clear--) | コレクションからすべての項目をクリアします。 |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | 常に NotImplementedException をスローします。 |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | アウトラインエントリを System.Array にコピーし、特定の System.Array インデックスから開始します。 |
| [getVisibleCount](#getVisibleCount--) | ドキュメントのアウトライン階層全レベルにおけるアウトライン項目の総数を取得します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | アウトラインコレクション項目を削除します。 |
| [size](#size--) | カウントを取得します。 |

### Outlines {#Outlines--}
```
public Outlines()
```



### add {#add-com.aspose.pdf.OutlineItemCollection-}
アウトライン項目をコレクションに追加します。

### clear {#clear--}
```
public abstract void clear()
```

コレクションからすべての項目をクリアします。

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
常に NotImplementedException をスローします。

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
アウトラインエントリを System.Array にコピーし、特定の System.Array インデックスから開始します。

### getVisibleCount {#getVisibleCount--}
```
public abstract int getVisibleCount()
```

ドキュメントのアウトライン階層全レベルにおけるアウトライン項目の総数を取得します。

**Returns:**
int 値です。

### isReadOnly {#isReadOnly--}
```
public abstract boolean isReadOnly()
```

コレクションが読み取り専用かどうかを示す値を取得します。

**Returns:**
ブール値

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public abstract Iterator < OutlineItemCollection > iterator()
```

コレクションを反復処理する列挙子を返します。

**Returns:**
コレクションを反復処理できる System.Collections.IEnumerator オブジェクトです。

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
アウトラインコレクション項目を削除します。

### size {#size--}
```
public abstract int size()
```

カウントを取得します。

**Returns:**
int 値です。
