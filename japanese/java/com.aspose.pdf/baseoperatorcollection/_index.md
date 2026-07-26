---
title: "BaseOperatorCollection"
linktitle: "BaseOperatorCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "オペレーターコレクションの基底クラスを表します。"
type: docs
weight: 270
url: /ja/java/com.aspose.pdf/baseoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public abstract class BaseOperatorCollection extends Object implements Iterable < Operator >
```

オペレーターコレクションの基底クラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BaseOperatorCollection](#BaseOperatorCollection--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | コレクションに新しいオペレーターを追加します。 |
| [cancelUpdate](#cancelUpdate--) | 最後の更新をキャンセルします。このメソッドは、変更がコンテンツの更新を引き起こさないようにしたい場合に呼び出すことができます。 |
| [clear](#clear--) | コレクションをクリアします。 |
| [contains](#contains-com.aspose.pdf.Operator-) | アイテムがコレクションに含まれているか確認します。 |
| [deleteUnrestricted](#deleteUnrestricted-int-) | 内部 |
| [get_Item](#get_Item-int-) | インデックスでオペレーターを取得します。 |
| [getUnrestricted](#getUnrestricted-int-) | 内部使用のみです。 |
| [insert](#insert-int-com.aspose.pdf.Operator-) | コレクションにオペレーターを挿入します。 |
| [isEmpty](#isEmpty--) | コレクションが空の場合は TRUE を返します。 |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | コレクションが高速テキスト抽出に限定されているかどうかを示します |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用の場合は true を返します。 |
| [iterator](#iterator--) | コレクションの列挙子を返します |
| [remove](#remove-com.aspose.pdf.Operator-) | コレクションからオペレーターを削除します。 |
| [resumeUpdate](#resumeUpdate--) | ドキュメントの更新を再開します。保留中の変更がある場合、コンテンツストリームを更新します。 |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | インデックスでオペレーターを設定します。 |
| [size](#size--) | コレクション内のオペレーター数を取得します。 |
| [suppressUpdate](#suppressUpdate--) | コンテンツ データの更新を抑制します。ResumeUpdate が呼び出されるまでコンテンツ ストリームは更新されません。 |
| [toList](#toList--) | オペレーター リストを返します。 |
| [updateData](#updateData--) | 内部 |

### BaseOperatorCollection {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```



### add {#add-com.aspose.pdf.Operator-}
コレクションに新しいオペレーターを追加します。

### cancelUpdate {#cancelUpdate--}
```
public abstract void cancelUpdate()
```

最後の更新をキャンセルします。このメソッドは、変更がコンテンツの更新を引き起こさないようにしたい場合に呼び出すことができます。

### clear {#clear--}
```
public abstract void clear()
```

コレクションをクリアします。

### contains {#contains-com.aspose.pdf.Operator-}
アイテムがコレクションに含まれているか確認します。

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```

内部

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | int 値です。 |

### get_Item {#get_Item-int-}
```
public abstract Operator get_Item(int index)
```

インデックスでオペレーターを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 演算子のインデックス。番号は 1 から始まります。 |

**Returns:**
要求されたインデックスの演算子

### getUnrestricted {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```

内部使用のみです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | int 値です。 |

**Returns:**
演算子オブジェクト

### insert {#insert-int-com.aspose.pdf.Operator-}
コレクションにオペレーターを挿入します。

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

コレクションが空の場合は TRUE を返します。

**Returns:**
ブール値

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```

コレクションが高速テキスト抽出に限定されているかどうかを示します

**Returns:**
ブール値

### isReadOnly {#isReadOnly--}
```
public abstract boolean isReadOnly()
```

コレクションが読み取り専用の場合は true を返します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public abstract Iterator < Operator > iterator()
```

コレクションの列挙子を返します

**Returns:**
コレクション列挙子

### remove {#remove-com.aspose.pdf.Operator-}
コレクションからオペレーターを削除します。

### resumeUpdate {#resumeUpdate--}
```
public abstract void resumeUpdate()
```

ドキュメントの更新を再開します。保留中の変更がある場合、コンテンツストリームを更新します。

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
インデックスでオペレーターを設定します。

### size {#size--}
```
public abstract int size()
```

コレクション内のオペレーター数を取得します。

**Returns:**
整数値

### suppressUpdate {#suppressUpdate--}
```
public abstract void suppressUpdate()
```

コンテンツ データの更新を抑制します。ResumeUpdate が呼び出されるまでコンテンツ ストリームは更新されません。

### toList {#toList--}
```
public abstract com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

オペレーター リストを返します。

**Returns:**
演算子リスト。

### updateData {#updateData--}
```
public abstract void updateData()
```

内部
