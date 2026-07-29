---
title: "LightweightOperatorCollection"
linktitle: "LightweightOperatorCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "軽量オペレーターコレクションです。基になるコンテンツストリームが添付されていないシナリオで、結果としてオペレーターコレクションだけが必要な場合に使用することを意図しています。"
type: docs
weight: 2700
url: /ja/java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.LightweightOperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.LightweightOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

軽量オペレーターコレクションです。基になるコンテンツストリームが添付されていないシナリオで、結果としてオペレーターコレクションだけが必要な場合に使用することを意図しています。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [LightweightOperatorCollection](#LightweightOperatorCollection--) | オブジェクトを初期化する |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-) | オブジェクトを初期化する |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | オブジェクトを初期化する |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | 演算子を追加する |
| [addRange](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | LightweightOperatorCollection を追加する |
| [cancelUpdate](#cancelUpdate--) | 最後の更新をキャンセルします。このメソッドは、変更がコンテンツの更新を引き起こさないようにしたい場合に呼び出すことができます。 |
| [clear](#clear--) | コレクションをクリアします。 |
| [contains](#contains-com.aspose.pdf.Operator-) | アイテムがコレクションに含まれているか確認します。 |
| [deleteUnrestricted](#deleteUnrestricted-int-) | 内部で Unrestrictedelement を削除する |
| [get_Item](#get_Item-int-) | <p> インデックスで演算子を取得します。 </p> <hr> <pre> 例は、インデックスでページコンテンツの演算子を取得する方法を示しています。 Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | 内部使用のための getUnrestricted 演算子 |
| [insert](#insert-int-com.aspose.pdf.Operator-) | 演算子を挿入する |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | コレクションが高速テキスト抽出に限定されているかどうかを示します |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [iterator](#iterator--) | イテレータを返す |
| [remove](#remove-com.aspose.pdf.Operator-) | コレクションからオペレーターを削除します。 |
| [resumeUpdate](#resumeUpdate--) | ドキュメントの更新を再開します。保留中の変更がある場合、コンテンツストリームを更新します。 |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | インデックスで演算子を設定します。 <hr> <pre> 例では、ページコンテンツからインデックスで演算子を取得する方法を示しています。 Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [size](#size--) | 演算子の数 |
| [suppressUpdate](#suppressUpdate--) | コンテンツ データの更新を抑制します。ResumeUpdate が呼び出されるまでコンテンツ ストリームは更新されません。 |
| [toList](#toList--) | 演算子のリストを返します。 |
| [updateData](#updateData--) | 内部 |

### LightweightOperatorCollection {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```

オブジェクトを初期化する

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-}
オブジェクトを初期化する

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
オブジェクトを初期化する

### add {#add-com.aspose.pdf.Operator-}
演算子を追加する

### addRange {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
LightweightOperatorCollection を追加する

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

最後の更新をキャンセルします。このメソッドは、変更がコンテンツの更新を引き起こさないようにしたい場合に呼び出すことができます。

### clear {#clear--}
```
public void clear()
```

コレクションをクリアします。

### contains {#contains-com.aspose.pdf.Operator-}
アイテムがコレクションに含まれているか確認します。

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

内部で Unrestrictedelement を削除する

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | int 値です。 |

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> インデックスで演算子を取得します。 </p> <hr> <pre> 例は、インデックスでページコンテンツの演算子を取得する方法を示しています。 Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 演算子のインデックス。番号は 1 から始まります。 |

**Returns:**
要求されたインデックスの演算子

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

内部使用のための getUnrestricted 演算子

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | int 値です。 |

**Returns:**
演算子オブジェクト

### insert {#insert-int-com.aspose.pdf.Operator-}
演算子を挿入する

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

コレクションが高速テキスト抽出に限定されているかどうかを示します

**Returns:**
ブール値

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

コレクションが読み取り専用かどうかを示す値を取得します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public Iterator < Operator > iterator()
```

イテレータを返す

**Returns:**
{@code IGenericEnumerator<Operator>} オブジェクト

### remove {#remove-com.aspose.pdf.Operator-}
コレクションからオペレーターを削除します。

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

ドキュメントの更新を再開します。保留中の変更がある場合、コンテンツストリームを更新します。

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
インデックスで演算子を設定します。 <hr> <pre> 例では、ページコンテンツからインデックスで演算子を取得する方法を示しています。 Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

### size {#size--}
```
public int size()
```

演算子の数

**Returns:**
int 値です。

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

コンテンツ データの更新を抑制します。ResumeUpdate が呼び出されるまでコンテンツ ストリームは更新されません。

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

演算子のリストを返します。

**Returns:**
演算子リスト。

### updateData {#updateData--}
```
public void updateData()
```

内部
