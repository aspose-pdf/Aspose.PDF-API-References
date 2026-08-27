---
title: "DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ドキュメントのツリーディクトリ（ドキュメント辞書、ページ辞書、リソース辞書）にアクセスするためのクラスです。"
type: docs
weight: 70
url: /ja/java/com.aspose.pdf.dataeditor/dictionaryeditor/
---
**Inheritance:**
java.lang.Object, java.util.Dictionary <K,V> java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Dictionary <K,V>, java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Hashtable < String , ICosPdfPrimitive >, com.aspose.pdf.dataeditor.DictionaryEditor

**All Implemented Interfaces:**
Serializable, Cloneable, Map < String, ICosPdfPrimitive >

```
public class DictionaryEditor extends Hashtable < String , ICosPdfPrimitive >
```

ドキュメントのツリーディクトリ（ドキュメント辞書、ページ辞書、リソース辞書）にアクセスするためのクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Document-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Page-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Resources-) | @exception ArgumentNullException リソースが null です。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | ICosPdfPrimitive をディクショナリに設定します。 |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | {@link ICosPdfPrimitive} をディクショナリに設定します。 |
| [clear](#clear--) | {@link DictionaryEditor} からすべての項目を削除します。 |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | DictionaryEditor が特定の値を含むかどうかを判断します。 |
| [containsKey](#containsKey-java.lang.String-) | {@link DictionaryEditor} が指定されたキーを持つ要素を含むかどうかを判断します。 |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | DictionaryEditor の要素を配列にコピーします。特定の配列インデックスから開始します。 |
| [get_Item](#get_Item-java.lang.String-) | 指定されたキーの要素を取得または設定します。 |
| [getAllKeys](#getAllKeys--) | キーの完全なコレクションです。編集可能なキーと編集不可能なキーが含まれます。 |
| [getKeys](#getKeys--) | 編集可能なキーのコレクションです。 |
| [getValues](#getValues--) | {@link DictionaryEditor} の値を含む {@link ICollection} を取得します。 |
| [isReadOnly](#isReadOnly--) | {@link DictionaryEditor} が読み取り専用かどうかを示す値を取得します。 |
| [iterator](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | DictionaryEditor から特定のオブジェクトの最初の出現を削除します。 |
| [remove](#remove-java.lang.String-) | 指定されたキーを持つ要素を {@link DictionaryEditor} から削除します。 |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | 指定されたキーの要素を取得または設定します。 |
| [size](#size--) | {@link DictionaryEditor} に含まれる要素数を取得します。 |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | 文字列、名前、ブール、数値などの単純データ型にアクセスするためです。他の型に対しては null を返します。 |

### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Document-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Page-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Resources-}
@exception ArgumentNullException リソースが null です。

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
ICosPdfPrimitive をディクショナリに設定します。

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
{@link ICosPdfPrimitive} をディクショナリに設定します。

### clear {#clear--}
```
public final void clear()
```

{@link DictionaryEditor} からすべての項目を削除します。

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
DictionaryEditor が特定の値を含むかどうかを判断します。

### containsKey {#containsKey-java.lang.String-}
{@link DictionaryEditor} が指定されたキーを持つ要素を含むかどうかを判断します。

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
DictionaryEditor の要素を配列にコピーします。特定の配列インデックスから開始します。

### get_Item {#get_Item-java.lang.String-}
指定されたキーの要素を取得または設定します。

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

キーの完全なコレクションです。編集可能なキーと編集不可能なキーが含まれます。

**Returns:**
String インスタンスのイテラブル

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

編集可能なキーのコレクションです。

**Returns:**
String インスタンスのイテラブル

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

{@link DictionaryEditor} の値を含む {@link ICollection} を取得します。

**Returns:**
ICosPdfPrimitive インスタンスのイテラブル

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

{@link DictionaryEditor} が読み取り専用かどうかを示す値を取得します。

**Returns:**
{@link DictionaryEditor} が読み取り専用の場合は true、そうでない場合は false。

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

コレクションを反復処理する列挙子を返します。

**Returns:**
コレクションを反復処理するために使用できる列挙子です。

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
DictionaryEditor から特定のオブジェクトの最初の出現を削除します。

### remove {#remove-java.lang.String-}
指定されたキーを持つ要素を {@link DictionaryEditor} から削除します。

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
指定されたキーの要素を取得または設定します。

### size {#size--}
```
public final int size()
```

{@link DictionaryEditor} に含まれる要素数を取得します。

**Returns:**
int 値です。

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
文字列、名前、ブール、数値などの単純データ型にアクセスするためです。他の型に対しては null を返します。
