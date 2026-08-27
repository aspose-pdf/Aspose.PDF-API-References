---
title: "CosPdfDictionary"
linktitle: "CosPdfDictionary"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "オブジェクトの辞書にアクセスするためのクラスです。"
type: docs
weight: 20
url: /ja/java/com.aspose.pdf.dataeditor/cospdfdictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfDictionary, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, ICosPdfPrimitive >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, ICosPdfPrimitive, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>

```
public class CosPdfDictionary extends CosPdfPrimitive implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , ICosPdfPrimitive >
```

オブジェクトの辞書にアクセスするためのクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CosPdfDictionary](#CosPdfDictionary-com.aspose.pdf.Resources-) | リソースから辞書を作成します。 @exception ArgumentNullException リソースが null です。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | ICosPdfPrimitive をディクショナリに設定します。 |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | 辞書に {@link ICosPdfPrimitive} を設定します。 @exception ArgumentException キー/値が編集または削除できない場合に例外をスローします。 |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | アイテムのペアを追加します。 |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | アイテムを追加します。 |
| [clear](#clear--) |  {@link CosPdfDictionary} からすべてのアイテムを削除します。 |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | CosPdfDictionary が特定の値を含むかどうかを判断します。 |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | アイテムが含まれている場合は true を返します |
| [containsKey](#containsKey-java.lang.String-) | 指定されたキーを持つ要素が {@link CosPdfDictionary} に含まれているかどうかを判断します。 |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | CosPdfDictionary の要素を配列にコピーします。特定の配列インデックスから開始します。 |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | 配列にコピー |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Document-) | ドキュメントに添付される空の辞書を作成します。 |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Page-) | ページに添付される空の辞書を作成します。 |
| [get_Item](#get_Item-java.lang.String-) | 指定されたキーの要素を取得または設定します。 |
| [getAllKeys](#getAllKeys--) | キーの完全なコレクションです。編集可能なキーと編集不可能なキーが含まれます。 |
| [getKeys](#getKeys--) | 編集可能なキーのコレクションです。 |
| [getValues](#getValues--) | {@link CosPdfDictionary} の値を含む {@link ICollection} を取得します。 |
| [isReadOnly](#isReadOnly--) | {@link CosPdfDictionary} が読み取り専用かどうかを示す値を取得します。 |
| [iterator](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | CosPdfDictionary から特定のオブジェクトの最初の出現を削除します。 |
| [remove](#remove-java.lang.String-) | 指定されたキーを持つ要素を {@link CosPdfDictionary} から削除します。 |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 項目を削除 |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | キーで項目を削除します。 |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | 指定されたキーを持つ要素を取得または設定します。 @exception ArgumentNullException キーが null です。 @exception KeyNotFoundException プロパティを取得したがキーが見つかりません。 @exception ArgumentException キーを編集/設定できない場合に例外をスローします。 |
| [size](#size--) | {@link CosPdfDictionary} に含まれる要素数を取得します。 |
| [toCosPdfDictionary](#toCosPdfDictionary--) | このインスタンスを {@link CosPdfDictionary} にキャストしようとします。 |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | 文字列、名前、ブール、数値などの単純データ型にアクセスするためです。他の型に対しては null を返します。 |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | 値を取得しようとする |

### CosPdfDictionary {#CosPdfDictionary-com.aspose.pdf.Resources-}
リソースから辞書を作成します。 @exception ArgumentNullException リソースが null です。

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
ICosPdfPrimitive をディクショナリに設定します。

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
辞書に {@link ICosPdfPrimitive} を設定します。 @exception ArgumentException キー/値が編集または削除できない場合に例外をスローします。

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
アイテムのペアを追加します。

### addItem {#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
アイテムを追加します。

### clear {#clear--}
```
public final void clear()
```

 {@link CosPdfDictionary} からすべてのアイテムを削除します。

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
CosPdfDictionary が特定の値を含むかどうかを判断します。

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
アイテムが含まれている場合は true を返します

### containsKey {#containsKey-java.lang.String-}
指定されたキーを持つ要素が {@link CosPdfDictionary} に含まれているかどうかを判断します。

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
CosPdfDictionary の要素を配列にコピーします。特定の配列インデックスから開始します。

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
配列にコピー

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Document-}
ドキュメントに添付される空の辞書を作成します。

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Page-}
ページに添付される空の辞書を作成します。

### get_Item {#get_Item-java.lang.String-}
指定されたキーの要素を取得または設定します。

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

キーの完全なコレクションです。編集可能なキーと編集不可能なキーが含まれます。

**Returns:**
文字列値のリスト

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

編集可能なキーのコレクションです。

**Returns:**
文字列値のリスト

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

{@link CosPdfDictionary} の値を含む {@link ICollection} を取得します。

**Returns:**
ICosPdfPrimitive インスタンスのリスト

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

{@link CosPdfDictionary} が読み取り専用かどうかを示す値を取得します。

**Returns:**
{@link CosPdfDictionary} が読み取り専用の場合は true、そうでない場合は false。

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

コレクションを反復処理する列挙子を返します。

**Returns:**
コレクションを反復処理するために使用できる列挙子です。

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
CosPdfDictionary から特定のオブジェクトの最初の出現を削除します。

### remove {#remove-java.lang.String-}
指定されたキーを持つ要素を {@link CosPdfDictionary} から削除します。

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
項目を削除

### removeItemByKey {#removeItemByKey-java.lang.String-}
キーで項目を削除します。

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
指定されたキーを持つ要素を取得または設定します。 @exception ArgumentNullException キーが null です。 @exception KeyNotFoundException プロパティを取得したがキーが見つかりません。 @exception ArgumentException キーを編集/設定できない場合に例外をスローします。

### size {#size--}
```
public final int size()
```

{@link CosPdfDictionary} に含まれる要素数を取得します。

**Returns:**
int 値です。

### toCosPdfDictionary {#toCosPdfDictionary--}
```
public CosPdfDictionary toCosPdfDictionary()
```

このインスタンスを {@link CosPdfDictionary} にキャストしようとします。

**Returns:**
インスタンスが {@link CosPdfDictionary} でない場合は null、そうであれば {@link CosPdfDictionary}。

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
文字列、名前、ブール、数値などの単純データ型にアクセスするためです。他の型に対しては null を返します。

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
値を取得しようとする
