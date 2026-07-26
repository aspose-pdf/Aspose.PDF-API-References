---
title: "CharInfoCollection"
linktitle: "CharInfoCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> CharInfo オブジェクトのコレクションを表します。 </p> <hr> <pre> この例は、すべての文字を反復処理し、文字を取得する方法を示しています //open document Document."
type: docs
weight: 570
url: /ja/java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CharInfoCollection

**All Implemented Interfaces:**
Iterable < CharInfo >

```
public final class CharInfoCollection extends Object implements Iterable < CharInfo >
```

<p> CharInfoオブジェクトのコレクションを表します。 </p> <hr> <pre> この例は、すべての文字を反復処理し、文字を取得する方法を示します //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> テキストセグメント文字の位置情報へのアクセスを提供します。 </p>

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.CharInfo-) | まだサポートされていません。コレクションは読み取り専用で、例外がスローされます。 |
| [clear](#clear--) | まだサポートされていません。コレクションは読み取り専用です。常に NotImplementedException がスローされます。 |
| [contains](#contains-com.aspose.pdf.CharInfo-) | コレクションが特定の値を含むかどうかを判断します。 |
| [copyTo](#copyTo-com.aspose.pdf.CharInfo:A-int-) | コレクション全体を互換性のある一次元配列にコピーし、対象配列の指定されたインデックスから開始します。 |
| [get_Item](#get_Item-int-) | 指定されたインデックス 1..n の CharInfo 要素を取得します。 |
| [getSyncRoot](#getSyncRoot--) | コレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します |
| [isSynchronized](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | コレクション全体の列挙子を返します。 |
| [iterator](#iterator--) | コレクション全体の列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.CharInfo-) | まだサポートされていません。コレクションは読み取り専用で、例外がスローされます。 |
| [size](#size--) | コレクションに実際に含まれる {@code CharInfo} オブジェクト要素の数を取得します。 |

### add {#add-com.aspose.pdf.CharInfo-}
まだサポートされていません。コレクションは読み取り専用で、例外がスローされます。

### clear {#clear--}
```
public void clear()
```

まだサポートされていません。コレクションは読み取り専用です。常に NotImplementedException がスローされます。

### contains {#contains-com.aspose.pdf.CharInfo-}
コレクションが特定の値を含むかどうかを判断します。

### copyTo {#copyTo-com.aspose.pdf.CharInfo:A-int-}
コレクション全体を互換性のある一次元配列にコピーし、対象配列の指定されたインデックスから開始します。

### get_Item {#get_Item-int-}
```
public CharInfo get_Item(int index)
```

指定されたインデックス 1..n の CharInfo 要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | コレクション内のインデックス。 |

**Returns:**
CharInfo オブジェクト。

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
public com.aspose.ms.System.Collections.IEnumerator< CharInfo > iterator()
```

コレクション全体の列挙子を返します。

**Returns:**
Enumerator オブジェクト。

### remove {#remove-com.aspose.pdf.CharInfo-}
まだサポートされていません。コレクションは読み取り専用で、例外がスローされます。

### size {#size--}
```
public int size()
```

コレクションに実際に含まれる {@code CharInfo} オブジェクト要素の数を取得します。

**Returns:**
int 値です。
