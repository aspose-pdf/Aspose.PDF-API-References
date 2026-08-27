---
title: "AppearanceDictionary"
linktitle: "AppearanceDictionary"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページ上でアノテーションが視覚的にどのように表示されるかを指定するアノテーション外観辞書です。"
type: docs
weight: 150
url: /ja/java/com.aspose.pdf/appearancedictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AppearanceDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XForm >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>

```
public final class AppearanceDictionary extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XForm >
```

ページ上でアノテーションが視覚的にどのように表示されるかを指定するアノテーション外観辞書です。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-java.lang.Object-java.lang.Object-) | 指定されたキーと値で要素を追加します。 |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | キーと値のペアをディクショナリに追加します。 |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XForm-) | 指定されたキーに対して XForm を追加します。 |
| [clear](#clear--) | 辞書からすべての要素を削除します。 |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 指定されたキーと値のペアがディクショナリに含まれているか確認します。 |
| [containsKey](#containsKey-java.lang.String-) | このディクショナリが指定されたキーを含むかどうかを判断します。 |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | / * / * 辞書に対する IDictionaryEnumerator オブジェクトを返します。 / * / * / * |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | ICollection の要素を配列にコピーします。コピーは特定の配列インデックスから開始します。 |
| [get_Item](#get_Item-java.lang.String-) | 外観ストリームを取得するための便利な形式を表します。 |
| [getDict](#getDict--) | pdf 辞書を取得します |
| [getKeys_](#getKeys_--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state の値で、N は通常の外観、R はロールオーバー外観、D はダウン外観、state は状態の名前です（例: チェックボックスの On、Off）。 |
| [getKeys](#getKeys--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state の値で、N は通常の外観、R はロールオーバー外観、D はダウン外観、state は状態の名前です（例: チェックボックスの On、Off）。 |
| [getSyncRoot](#getSyncRoot--) | 辞書へのアクセスを同期するために使用できるオブジェクトを取得します。 |
| [getValues_](#getValues_--) | 辞書の値のリストを取得します。結果コレクションには XForm オブジェクトのリストが含まれます。 |
| [getValues](#getValues--) | 辞書の値のリストを取得します。結果コレクションには XForm オブジェクトのリストが含まれます。 |
| [isFixedSize](#isFixedSize--) | 辞書が固定サイズかどうかを示す値を取得します。 |
| [isReadOnly](#isReadOnly--) | 辞書が読み取り専用かどうかを示す値を取得します。 |
| [isSynchronized](#isSynchronized--) | 辞書へのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。 |
| [iterator__Rename_Namesake](#iterator__Rename_Namesake--) | コレクションの列挙子です。 |
| [iterator](#iterator--) | 辞書用の IDictionaryEnumerator オブジェクトを返します。 |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | コレクションからキーと値のペアを削除します。 |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | 辞書からキーを削除します。 |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size](#size--) | 辞書に含まれる要素数を取得します。 |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | 辞書内でキーを検索し、見つかった場合は値を取得します。 |

### add {#add-java.lang.Object-java.lang.Object-}
指定されたキーと値で要素を追加します。

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
キーと値のペアをディクショナリに追加します。

### addItem {#addItem-java.lang.String-com.aspose.pdf.XForm-}
指定されたキーに対して XForm を追加します。

### clear {#clear--}
```
public void clear()
```

辞書からすべての要素を削除します。

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
指定されたキーと値のペアがディクショナリに含まれているか確認します。

### containsKey {#containsKey-java.lang.String-}
このディクショナリが指定されたキーを含むかどうかを判断します。

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
/ * / * 辞書に対する IDictionaryEnumerator オブジェクトを返します。 / * / * / *

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
ICollection の要素を配列にコピーします。コピーは特定の配列インデックスから開始します。

### get_Item {#get_Item-java.lang.String-}
外観ストリームを取得するための便利な形式を表します。

### getDict {#getDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getDict()
```

pdf 辞書を取得します

**Returns:**
IPdfDictionary オブジェクト

### getKeys_ {#getKeys_--}
```
public List < String > getKeys_()
```

辞書のキーを取得します。外観辞書にサブ辞書がある場合、{@code Keys} には (N|R|D).state の値が含まれます。ここで N は通常の外観、R はロールオーバー外観、D はダウン外観を表し、state は状態名（例: チェックボックスの On、Off）です。

**Returns:**
文字列値のリスト

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

辞書のキーを取得します。外観辞書にサブ辞書がある場合、{@code Keys} には (N|R|D).state の値が含まれます。ここで N は通常の外観、R はロールオーバー外観、D はダウン外観を表し、state は状態名（例: チェックボックスの On、Off）です。

**Returns:**
文字列値のリスト

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

辞書へのアクセスを同期するために使用できるオブジェクトを取得します。

**Returns:**
同期用オブジェクト

### getValues_ {#getValues_--}
```
public List < XForm > getValues_()
```

辞書の値のリストを取得します。結果コレクションには XForm オブジェクトのリストが含まれます。

**Returns:**
XForm 値のリスト

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XForm > getValues()
```

辞書の値のリストを取得します。結果コレクションには XForm オブジェクトのリストが含まれます。

**Returns:**
XForm 値のリスト

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

辞書が固定サイズかどうかを示す値を取得します。

**Returns:**
ブール値

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

辞書が読み取り専用かどうかを示す値を取得します。

**Returns:**
ブール値

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

辞書へのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。

**Returns:**
ブール値

### iterator__Rename_Namesake {#iterator__Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator__Rename_Namesake()
```

コレクションの列挙子です。

**Returns:**
コレクション項目の列挙子です。

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator()
```

辞書用の IDictionaryEnumerator オブジェクトを返します。

**Returns:**
辞書の列挙子です。

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
コレクションからキーと値のペアを削除します。

### removeItemByKey {#removeItemByKey-java.lang.String-}
辞書からキーを削除します。

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XForm-}


### size {#size--}
```
public int size()
```

辞書に含まれる要素数を取得します。

**Returns:**
int 値です。

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
辞書内でキーを検索し、見つかった場合は値を取得します。
