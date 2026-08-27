---
title: "FontCollection"
linktitle: "FontCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> フォントコレクションを表します。 </p> <hr> <pre> 例では、ページで宣言されたすべてのフォントを埋め込みにする方法を示しています。 // Open document Document doc = new."
type: docs
weight: 1670
url: /ja/java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontCollection

**All Implemented Interfaces:**
Iterable < Font >

```
public final class FontCollection extends Object implements Iterable < Font >
```

<p> フォントコレクションを表します。 </p> <hr> <pre> この例では、ページで宣言されたすべてのフォントを埋め込みにする方法を示しています。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // ensure all fonts declared on page resources are embedded // note that if fonts are declared on form resources they are not accessible from page resources for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\Tests\\input.pdf"); </pre> <hr> <p> フォントコレクションは {@code FontCollection} クラスによって表され、いくつかのシナリオで使用されます。例えば、{@code Resources.Fonts} プロパティを持つリソースで使用されます。 </p>

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.Font-) | フォントをコレクションに追加します。 |
| [add](#add-com.aspose.pdf.Font-java.lang.String:A-) | 新しいフォントをフォントリソースに追加し、フォントリソースに自動的に割り当てられた名前を返します。 |
| [add](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | フォントコレクションに新しいフォントを追加します。 |
| [add](#add-java.lang.String-java.lang.String-) | 指定されたベースフォント名でフォントリソースに新しいフォントエントリを追加します。 |
| [clear_Rename_Namesake](#clear_Rename_Namesake--) | / * / * コレクションにフォントを追加します。 / * / * |
| [contains](#contains-com.aspose.pdf.Font-) | コレクションが特定の値を含むかどうかを判断します。 |
| [contains](#contains-java.lang.String-) | フォントがフォントコレクションに存在するか確認します。 |
| [copyTo](#copyTo-com.aspose.pdf.Font:A-int-) | コレクション全体を互換性のある一次元配列にコピーし、対象配列の指定されたインデックスから開始します。 |
| [delete](#delete-java.lang.String-) | 指定されたリソース名のフォントを削除します |
| [get_Item](#get_Item-int-) | 指定されたインデックスのフォント要素を取得します。 |
| [get_Item](#get_Item-java.lang.String-) | フォント名でコレクションからフォントを取得します。フォントが見つからない場合は例外がスローされます。 |
| [getFontsDictionary](#getFontsDictionary--) | IPdfDictionary オブジェクトを取得します |
| [getHash](#getHash--) |  |
| [getSyncRoot](#getSyncRoot--) | コレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します |
| [isSynchronized](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | コレクション全体の列挙子を返します。 |
| [iterator](#iterator--) | コレクション全体の列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.Font-) | コレクションから指定された項目を削除します。 |
| [size](#size--) | コレクションに実際に含まれる {@code Font} オブジェクト要素の数を取得します。 |

### add {#add-com.aspose.pdf.Font-}
フォントをコレクションに追加します。

### add {#add-com.aspose.pdf.Font-java.lang.String:A-}
新しいフォントをフォントリソースに追加し、フォントリソースに自動的に割り当てられた名前を返します。

### add {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
フォントコレクションに新しいフォントを追加します。

### add {#add-java.lang.String-java.lang.String-}
指定されたベースフォント名でフォントリソースに新しいフォントエントリを追加します。

### clear_Rename_Namesake {#clear_Rename_Namesake--}
```
public void clear_Rename_Namesake()
```

/ * / * コレクションにフォントを追加します。 / * / *

### contains {#contains-com.aspose.pdf.Font-}
コレクションが特定の値を含むかどうかを判断します。

### contains {#contains-java.lang.String-}
フォントがフォントコレクションに存在するか確認します。

### copyTo {#copyTo-com.aspose.pdf.Font:A-int-}
コレクション全体を互換性のある一次元配列にコピーし、対象配列の指定されたインデックスから開始します。

### delete {#delete-java.lang.String-}
指定されたリソース名のフォントを削除します

### get_Item {#get_Item-int-}
```
public Font get_Item(int index)
```

指定されたインデックスのフォント要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | コレクション内のインデックス。 |

**Returns:**
フォントオブジェクト。

### get_Item {#get_Item-java.lang.String-}
フォント名でコレクションからフォントを取得します。フォントが見つからない場合は例外がスローされます。

### getFontsDictionary {#getFontsDictionary--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getFontsDictionary()
```

IPdfDictionary オブジェクトを取得します

**Returns:**
IPdfDictionary オブジェクト

### getHash {#getHash--}
```
public com.aspose.pdf.engine.collections.HashDictionary< String , Font > getHash()
```



### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

コレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。

**Returns:**
同期用オブジェクト

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

コレクションが読み取り専用かどうかを示す値を取得します

**Returns:**
ブール値

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。

**Returns:**
ブール値

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

コレクション全体の列挙子を返します。

**Returns:**
Enumerator オブジェクト。

### iterator {#iterator--}
```
public Iterator < Font > iterator()
```

コレクション全体の列挙子を返します。

**Returns:**
Enumerator オブジェクト。

### remove {#remove-com.aspose.pdf.Font-}
コレクションから指定された項目を削除します。

### size {#size--}
```
public int size()
```

コレクションに実際に含まれる {@code Font} オブジェクト要素の数を取得します。

**Returns:**
int 値です。
