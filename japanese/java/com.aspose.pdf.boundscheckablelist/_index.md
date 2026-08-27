---
title: "com.aspose.pdf.boundscheckablelist"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "BoundsCheckableList を表します - System.Collections.Generic.List のラッパーです。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.boundscheckablelist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.boundscheckablelist.BoundsCheckableList<T>

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<T>, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T>, com.aspose.ms.System.Collections.Generic.IGenericList<T>, com.aspose.ms.System.Collections.IEnumerable<T>, Iterable <T>

```
public class BoundsCheckableList<T extends IBoundsCheckableItem > extends Object implements com.aspose.ms.System.Collections.Generic.IGenericList<T>
```

BoundsCheckableList を表します - System.Collections.Generic.List のラッパーです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BoundsCheckableList](#BoundsCheckableList--) | BoundsCheckableList クラスの新しいインスタンスを初期化します。 |
| [BoundsCheckableList](#BoundsCheckableList-int-double-double-) | BoundsCheckableList クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addItem](#addItem-T-) | 「boundsCheckMode」パラメータに応じて、System.Collections.Generic.List の末尾にオブジェクトを追加します。 |
| [clear](#clear--) | System.Collections.Generic.List からすべての要素を削除します。 |
| [containsItem](#containsItem-T-) | 要素が System.Collections.Generic.List に含まれているかどうかを判定します。 |
| [copyToTArray](#copyToTArray-T:A-int-) | System.Collections.Generic.List 全体を互換性のある一次元配列にコピーし、対象配列の指定インデックスから開始します。 |
| [get_Item](#get_Item-int-) | コレクションから段落を取得または設定します。 |
| [indexOfItem](#indexOfItem-T-) | 指定されたオブジェクトを検索し、System.Collections.Generic.List 全体で最初に出現する位置のゼロベースインデックスを返します。 |
| [insertItem](#insertItem-int-T-) | 指定インデックスに要素を System.Collections.Generic.List に挿入します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [iterator](#iterator--) | System.Collections.Generic.List を反復処理する列挙子を返します。 |
| [removeAt](#removeAt-int-) | System.Collections.Generic.List の指定インデックスにある要素を削除します。 |
| [removeItem](#removeItem-T-) | System.Collections.Generic.List から特定のオブジェクトの最初の出現を削除します。 |
| [set_Item](#set_Item-int-T-) | コレクションから段落を取得または設定します。 |
| [size](#size--) | System.Collections.Generic.List に含まれる要素数を取得します。 |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-) | 初期化されたコレクションの boundsCheckMode パラメーターを更新します。 |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-double-double-) | 初期化されたコレクションの boundsCheckMode パラメーターを更新します。 |

### BoundsCheckableList {#BoundsCheckableList--}
```
public BoundsCheckableList()
```

BoundsCheckableList クラスの新しいインスタンスを初期化します。

### BoundsCheckableList {#BoundsCheckableList-int-double-double-}
```
public BoundsCheckableList(int boundsCheckMode, double containerWidth, double containerHeight)
```

BoundsCheckableList クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| boundsCheckMode |  | bounds cCheck モードです。 |
| containerWidth |  | コンテナの幅です。 |
| containerHeight |  | コンテナの高さです。 |

### addItem {#addItem-T-}
```
public final void addItem( T item)
```

「boundsCheckMode」パラメータに応じて、System.Collections.Generic.List の末尾にオブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item |  | System.Collections.Generic.List の末尾に追加されるオブジェクトです。参照型の場合、値は "null" にできます。 |

### clear {#clear--}
```
public final void clear()
```

System.Collections.Generic.List からすべての要素を削除します。

### containsItem {#containsItem-T-}
```
public final boolean containsItem( T item)
```

要素が System.Collections.Generic.List に含まれているかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item |  | System.Collections.Generic.List で検索するオブジェクトです。参照型の場合、値は null にできます。 |

**Returns:**
System.Collections.Generic.List に itemitem が見つかった場合は true、そうでなければ false。

### copyToTArray {#copyToTArray-T:A-int-}
```
public final void copyToTArray( T [] array, int arrayIndex)
```

System.Collections.Generic.List 全体を互換性のある一次元配列にコピーし、対象配列の指定インデックスから開始します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array |  | System.Collections.Generic.List からコピーされた要素の宛先となる一次元の System.Array です。System.Array はゼロベースインデックスである必要があります。 |
| arrayIndex |  | コピーが開始される配列内のゼロベースインデックス。 |

### get_Item {#get_Item-int-}
```
public final T get_Item(int index)
```

コレクションから段落を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 段落インデックス。 |

**Returns:**
指定されたインデックスの要素。

### indexOfItem {#indexOfItem-T-}
```
public final int indexOfItem( T item)
```

指定されたオブジェクトを検索し、System.Collections.Generic.List 全体で最初に出現する位置のゼロベースインデックスを返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item |  | System.Collections.Generic.List で検索するオブジェクトです。参照型の場合、値は null にできます。 |

**Returns:**
System.Collections.Generic.List 全体で itemitem が最初に出現するゼロベースインデックス（見つかった場合）。見つからない場合は –1。

### insertItem {#insertItem-int-T-}
```
public final void insertItem(int index, T item)
```

指定インデックスに要素を System.Collections.Generic.List に挿入します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | item を挿入すべきゼロベースインデックス。 |
| item |  | 挿入するオブジェクト。参照型の場合、値は null にできる。 |

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

コレクションが読み取り専用かどうかを示す値を取得します。

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< T > iterator()
```

System.Collections.Generic.List を反復処理する列挙子を返します。

**Returns:**
System.Collections.Generic.List 用の列挙子。

### removeAt {#removeAt-int-}
```
public final void removeAt(int index)
```

System.Collections.Generic.List の指定インデックスにある要素を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 削除する要素のゼロベースインデックス。 |

### removeItem {#removeItem-T-}
```
public final boolean removeItem( T item)
```

System.Collections.Generic.List から特定のオブジェクトの最初の出現を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item |  | System.Collections.Generic.List から削除するオブジェクト。参照型の場合、値は null にできる。 |

**Returns:**
itemitem が正常に削除された場合は true、そうでない場合は false。このメソッドは、System.Collections.Generic.List に itemitem が見つからなかった場合も false を返す。

### set_Item {#set_Item-int-T-}
```
public final void set_Item(int index, T value)
```

コレクションから段落を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 段落インデックス。 |

### size {#size--}
```
public final int size()
```

System.Collections.Generic.List に含まれる要素数を取得します。

**Returns:**
System.Collections.Generic.List に含まれる要素数。

### updateBoundsCheckMode {#updateBoundsCheckMode-int-}
```
public final void updateBoundsCheckMode(int boundsCheckMode)
```

初期化されたコレクションの boundsCheckMode パラメーターを更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| boundsCheckMode |  | 境界チェックモード。 |

### updateBoundsCheckMode {#updateBoundsCheckMode-int-double-double-}
```
public final void updateBoundsCheckMode(int boundsCheckMode, double containerWidth, double containerHeight)
```

初期化されたコレクションの boundsCheckMode パラメーターを更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| boundsCheckMode |  | 境界チェックモード。 |
| containerWidth |  | コンテナの幅です。 |
| containerHeight |  | コンテナの高さです。 |
