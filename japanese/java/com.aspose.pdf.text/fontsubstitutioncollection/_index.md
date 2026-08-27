---
title: "FontSubstitutionCollection"
linktitle: "FontSubstitutionCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フォント置換戦略のコレクションを表します。"
type: docs
weight: 60
url: /ja/java/com.aspose.pdf.text/fontsubstitutioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitutionCollection

**All Implemented Interfaces:**
イテラブル < FontSubstitution >

```
public final class FontSubstitutionCollection extends Object implements Iterable < FontSubstitution >
```

フォント置換戦略のコレクションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontSubstitutionCollection](#FontSubstitutionCollection--) | コレクションオブジェクトを初期化します |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.text.FontSubstitution-) | 新しいフォント置換オブジェクトをコレクションに追加します。 |
| [clear](#clear--) | フォント置換コレクションをクリアします。 |
| [contains](#contains-com.aspose.pdf.text.FontSubstitution-) | 要素がコレクションに含まれているかどうかを判断します。 |
| [delete](#delete-com.aspose.pdf.text.FontSubstitution-) | 内部使用のみでフォント置換要素を削除します。 |
| [getItem](#getItem-int-) | 指定されたインデックスのフォント要素を取得します。 |
| [getSyncRoot](#getSyncRoot--) | コレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
| [isSynchronized](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。 |
| [iterator](#iterator--) | コレクション全体の列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.text.FontSubstitution-) | フォント置換要素を削除します。 |
| [size](#size--) | コレクションに実際に含まれる Font オブジェクト要素の数を取得します。 |

### FontSubstitutionCollection {#FontSubstitutionCollection--}
```
public FontSubstitutionCollection()
```

コレクションオブジェクトを初期化します

### add {#add-com.aspose.pdf.text.FontSubstitution-}
新しいフォント置換オブジェクトをコレクションに追加します。

### clear {#clear--}
```
public void clear()
```

フォント置換コレクションをクリアします。

### contains {#contains-com.aspose.pdf.text.FontSubstitution-}
要素がコレクションに含まれているかどうかを判断します。

### delete {#delete-com.aspose.pdf.text.FontSubstitution-}
内部使用のみでフォント置換要素を削除します。

### getItem {#getItem-int-}
```
public FontSubstitution getItem(int index)
```

指定されたインデックスのフォント要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | コレクション内のインデックス。 |

**Returns:**
FontSubstitution オブジェクト。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

コレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。

**Returns:**
同期用オブジェクト

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< FontSubstitution > iterator()
```

コレクション全体の列挙子を返します。

**Returns:**
列挙子オブジェクト

### remove {#remove-com.aspose.pdf.text.FontSubstitution-}
フォント置換要素を削除します。

### size {#size--}
```
public int size()
```

コレクションに実際に含まれる Font オブジェクト要素の数を取得します。

**Returns:**
int 値です。
