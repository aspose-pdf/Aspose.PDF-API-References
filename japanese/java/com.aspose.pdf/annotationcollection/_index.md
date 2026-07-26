---
title: "AnnotationCollection"
linktitle: "AnnotationCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "アノテーションコレクションを表すクラスです。"
type: docs
weight: 80
url: /ja/java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationCollection

**All Implemented Interfaces:**
Iterable < Annotation >

```
public final class AnnotationCollection extends Object implements Iterable < Annotation >
```

アノテーションコレクションを表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [AnnotationCollection](#AnnotationCollection-com.aspose.pdf.Page-) | AnnotationCollection のコンストラクタ。指定されたページ上のアノテーションのコレクションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | アノテーションを処理するビジタを受け入れます。 |
| [add](#add-com.aspose.pdf.Annotation-) | コレクションにアノテーションを追加します。 |
| [add](#add-com.aspose.pdf.Annotation-boolean-) | コレクションにアノテーションを追加します。ページが回転している場合、アノテーションの矩形はそれに応じて再計算されます。 |
| [clear](#clear--) | コレクションからすべてのアノテーションを削除します。 |
| [contains](#contains-com.aspose.pdf.Annotation-) | 指定されたアノテーションがコレクションに属しているか確認します。 |
| [copyTo](#copyTo-com.aspose.pdf.Annotation:A-int-) | アノテーションの配列をコレクションにコピーします。 |
| [delete](#delete--) | コレクションからすべてのアノテーションを削除します。 |
| [delete](#delete-com.aspose.pdf.Annotation-) | コレクションからすべてのアノテーションを削除します。 |
| [delete](#delete-int-) | インデックスでコレクションからアノテーションを削除します。 |
| [findByName](#findByName-java.lang.String-) | 名前でアノテーションを返します。 |
| [get_Item](#get_Item-int-) | 取得する要素のインデックス。 |
| [getSyncRoot](#getSyncRoot--) | com.aspose.pdf.AnnotationCollection へのアクセスを同期させるために使用できるオブジェクトを取得します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [isSynchronized](#isSynchronized--) | com.aspose.pdf.AnnotationCollection へのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を取得します。 |
| [iterator](#iterator--) | コレクションの列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.Annotation-) | 指定されたアノテーションをコレクションから削除します。 |
| [size](#size--) | コレクション内のアノテーションの数を取得します。 |

### AnnotationCollection {#AnnotationCollection-com.aspose.pdf.Page-}
AnnotationCollection のコンストラクタ。指定されたページ上のアノテーションのコレクションを作成します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
アノテーションを処理するビジタを受け入れます。

### add {#add-com.aspose.pdf.Annotation-}
コレクションにアノテーションを追加します。

### add {#add-com.aspose.pdf.Annotation-boolean-}
コレクションにアノテーションを追加します。ページが回転している場合、アノテーションの矩形はそれに応じて再計算されます。

### clear {#clear--}
```
public void clear()
```

コレクションからすべてのアノテーションを削除します。

### contains {#contains-com.aspose.pdf.Annotation-}
指定されたアノテーションがコレクションに属しているか確認します。

### copyTo {#copyTo-com.aspose.pdf.Annotation:A-int-}
アノテーションの配列をコレクションにコピーします。

### delete {#delete--}
```
public void delete()
```

コレクションからすべてのアノテーションを削除します。

### delete {#delete-com.aspose.pdf.Annotation-}
コレクションからすべてのアノテーションを削除します。

### delete {#delete-int-}
```
public void delete(int index)
```

インデックスでコレクションからアノテーションを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 削除されるアノテーションのインデックス。 |

### findByName {#findByName-java.lang.String-}
名前でアノテーションを返します。

### get_Item {#get_Item-int-}
```
public Annotation get_Item(int index)
```

取得する要素のインデックス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | インデックス値は 1 から始まります。 |

**Returns:**
アノテーションオブジェクト

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

com.aspose.pdf.AnnotationCollection へのアクセスを同期させるために使用できるオブジェクトを取得します。

**Returns:**
同期用オブジェクト

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

com.aspose.pdf.AnnotationCollection へのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を取得します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Annotation > iterator()
```

コレクションの列挙子を返します。

**Returns:**
列挙子オブジェクト

### remove {#remove-com.aspose.pdf.Annotation-}
指定されたアノテーションをコレクションから削除します。

### size {#size--}
```
public int size()
```

コレクション内のアノテーションの数を取得します。

**Returns:**
int 値です。
