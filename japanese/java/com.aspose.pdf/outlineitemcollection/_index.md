---
title: "OutlineItemCollection"
linktitle: "OutlineItemCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントのアウトライン階層内のアウトラインエントリを表します。"
type: docs
weight: 3270
url: /ja/java/com.aspose.pdf/outlineitemcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineItemCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineItemCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineItemCollection extends Outlines
```

PDF ドキュメントのアウトライン階層内のアウトラインエントリを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | 内部エンジンのアウトラインエントリオブジェクトを使用してこのクラスの新しいインスタンスを初期化します。 |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | ルート階層オブジェクトを使用してアウトライン項目インスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | アウトライン項目をコレクションに追加します。 |
| [clear](#clear--) | コレクションからすべての項目をクリアします。 |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | まだサポートされていません。常に NotImplementedException をスローします。 |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | アウトラインエントリを System.Array にコピーし、特定の System.Array インデックスから開始します。 |
| [delete](#delete--) | このアウトライン項目をドキュメントのアウトライン階層から削除します。 |
| [delete](#delete-java.lang.String-) | このアウトライン項目をドキュメントのアウトライン階層から削除します。 |
| [get_Item](#get_Item-int-) | インデックスを使用してコレクションからアウトライン項目を取得します。 |
| [getAction](#getAction--) | このアウトライン項目のアクションを取得します。 |
| [getBold](#getBold--) | このアウトライン項目のタイトルテキストの太字フラグを取得します |
| [getColor](#getColor--) | このアウトライン項目のタイトルテキストの色を取得します。 |
| [getDestination](#getDestination--) | このアウトライン項目の宛先を取得します。 |
| [getEngineDict](#getEngineDict--) | 内部のみ |
| [getEngineObj](#getEngineObj--) | 内部のみ |
| [getFirst](#getFirst--) | アウトライン階層で最上位の最初の項目を表すアウトライン項目を取得します。 |
| [getItalic](#getItalic--) | このアウトライン項目のタイトルテキストの斜体フラグを取得します。 |
| [getLast](#getLast--) | アウトライン階層で最上位の最後の項目を表すアウトライン項目を取得します。 |
| [getLevel](#getLevel--) | アウトライン項目の階層レベルを取得します。 |
| [getNext](#getNext--) | アウトライン階層でこの項目に対して相対的に次の項目を表すアウトライン項目を取得します。 |
| [getOpen](#getOpen--) | アウトライン項目の開閉状態（true/false）を取得します。 |
| [getParent](#getParent--) | アウトライン階層内のこのアウトライン項目の親オブジェクトを取得します。 |
| [getPrev](#getPrev--) | アウトライン階層でこの項目に対して相対的に前の項目を表すアウトライン項目を取得します。 |
| [getSyncRoot](#getSyncRoot--) | このコレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
| [getTitle](#getTitle--) | このアウトライン項目のタイトルを取得します。 |
| [getVisibleCount](#getVisibleCount--) | ドキュメントのアウトライン階層全レベルにおけるアウトライン項目の総数を取得します。 |
| [hasNext](#hasNext--) | アウトライン階層でこの項目に対して相対的に次の項目を表すアウトライン項目かどうかを確認します。 |
| [insert](#insert-int-com.aspose.pdf.OutlineItemCollection-) | 指定された位置にアウトライン項目をコレクションへ挿入します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [isSynchronized](#isSynchronized--) | このコレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を取得します。 |
| [iterator](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [next](#next--) |  |
| [remove](#remove-int-) | インデックスで項目を削除します。 |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | まだサポートされていません。常に NotImplementedException をスローします。 |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | このアウトライン項目のアクションを設定します。 |
| [setBold](#setBold-boolean-) | このアウトライン項目のタイトルテキストの太字フラグを設定します。 |
| [setColor](#setColor-java.awt.Color-) | このアウトライン項目のタイトルテキストの色を設定します。 |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | このアウトライン項目の宛先を設定します。 |
| [setItalic](#setItalic-boolean-) | このアウトライン項目のタイトルテキストの斜体フラグを設定します。 |
| [setOpen](#setOpen-boolean-) | アウトライン項目の開閉状態（true/false）を設定します。 |
| [setTitle](#setTitle-java.lang.String-) | このアウトライン項目のタイトルを設定します。 |
| [size](#size--) | コレクション項目の数です。VisibleCount と混同しないでください。VisibleCount は全レベルの表示されているアウトライン項目の数を取得します。 |

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
内部エンジンのアウトラインエントリオブジェクトを使用してこのクラスの新しいインスタンスを初期化します。

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
ルート階層オブジェクトを使用してアウトライン項目インスタンスを初期化します。

### add {#add-com.aspose.pdf.OutlineItemCollection-}
アウトライン項目をコレクションに追加します。

### clear {#clear--}
```
public void clear()
```

コレクションからすべての項目をクリアします。

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
まだサポートされていません。常に NotImplementedException をスローします。

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
アウトラインエントリを System.Array にコピーし、特定の System.Array インデックスから開始します。

### delete {#delete--}
```
public void delete()
```

このアウトライン項目をドキュメントのアウトライン階層から削除します。

### delete {#delete-java.lang.String-}
このアウトライン項目をドキュメントのアウトライン階層から削除します。

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

インデックスを使用してコレクションからアウトライン項目を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | コレクション内のインデックス。 |

**Returns:**
OutlineItemCollection オブジェクト。

### getAction {#getAction--}
```
public PdfAction getAction()
```

このアウトライン項目のアクションを取得します。

**Returns:**
PdfAction 値

### getBold {#getBold--}
```
public boolean getBold()
```

このアウトライン項目のタイトルテキストの太字フラグを取得します

**Returns:**
ブール値

### getColor {#getColor--}
```
public Color getColor()
```

このアウトライン項目のタイトルテキストの色を取得します。

**Returns:**
カラー値

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

このアウトライン項目の宛先を取得します。

**Returns:**
IAppointment 値

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

内部のみ

**Returns:**
IPdfDictionary オブジェクト

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

内部のみ

**Returns:**
IPdfObject オブジェクト

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

アウトライン階層で最上位の最初の項目を表すアウトライン項目を取得します。

**Returns:**
OutlineItemCollection の値

### getItalic {#getItalic--}
```
public boolean getItalic()
```

このアウトライン項目のタイトルテキストの斜体フラグを取得します。

**Returns:**
ブール値

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

アウトライン階層で最上位の最後の項目を表すアウトライン項目を取得します。

**Returns:**
OutlineItemCollection の値

### getLevel {#getLevel--}
```
public int getLevel()
```

アウトライン項目の階層レベルを取得します。

**Returns:**
int 値です。

### getNext {#getNext--}
```
public OutlineItemCollection getNext()
```

アウトライン階層でこの項目に対して相対的に次の項目を表すアウトライン項目を取得します。

**Returns:**
OutlineItemCollection の値

### getOpen {#getOpen--}
```
public boolean getOpen()
```

アウトライン項目の開閉状態（true/false）を取得します。

**Returns:**
ブール値

### getParent {#getParent--}
```
public Outlines getParent()
```

アウトライン階層内のこのアウトライン項目の親オブジェクトを取得します。

**Returns:**
Object の値

### getPrev {#getPrev--}
```
public OutlineItemCollection getPrev()
```

アウトライン階層でこの項目に対して相対的に前の項目を表すアウトライン項目を取得します。

**Returns:**
OutlineItemCollection の値

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

このコレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。

**Returns:**
Object の値

### getTitle {#getTitle--}
```
public String getTitle()
```

このアウトライン項目のタイトルを取得します。

**Returns:**
文字列値

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

ドキュメントのアウトライン階層全レベルにおけるアウトライン項目の総数を取得します。

**Returns:**
int 値です。

### hasNext {#hasNext--}
```
public final boolean hasNext()
```

アウトライン階層でこの項目に対して相対的に次の項目を表すアウトライン項目かどうかを確認します。

**Returns:**
ブール値

### insert {#insert-int-com.aspose.pdf.OutlineItemCollection-}
指定された位置にアウトライン項目をコレクションへ挿入します。

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

コレクションが読み取り専用かどうかを示す値を取得します。

**Returns:**
ブール値

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

このコレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を取得します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

コレクションを反復処理する列挙子を返します。

**Returns:**
コレクションを反復処理できる System.Collections.IEnumerator オブジェクトです。

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

インデックスで項目を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 削除する項目のインデックス。 |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
まだサポートされていません。常に NotImplementedException をスローします。

### setAction {#setAction-com.aspose.pdf.PdfAction-}
このアウトライン項目のアクションを設定します。

### setBold {#setBold-boolean-}
```
public void setBold(boolean value)
```

このアウトライン項目のタイトルテキストの太字フラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setColor {#setColor-java.awt.Color-}
このアウトライン項目のタイトルテキストの色を設定します。

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
このアウトライン項目の宛先を設定します。

### setItalic {#setItalic-boolean-}
```
public void setItalic(boolean value)
```

このアウトライン項目のタイトルテキストの斜体フラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

アウトライン項目の開閉状態（true/false）を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setTitle {#setTitle-java.lang.String-}
このアウトライン項目のタイトルを設定します。

### size {#size--}
```
public int size()
```

コレクション項目の数です。VisibleCount と混同しないでください。VisibleCount は全レベルの表示されているアウトライン項目の数を取得します。

**Returns:**
int 値です。
