---
title: "TabStops"
linktitle: "TabStops"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "{@code TabStop} オブジェクトのコレクションを表します。"
type: docs
weight: 4850
url: /ja/java/com.aspose.pdf/tabstops/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStops

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TabStops extends Object implements com.aspose.ms.System.ICloneable
```

{@code TabStop} オブジェクトのコレクションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TabStops](#TabStops--) | 新しい {@code TabStops} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add--) | 新しい {@code TabStop} クラスのインスタンスを初期化し、TabStops コレクションに追加します。 |
| [add](#add-float-) | 指定された位置で新しい {@code TabStop} クラスのインスタンスを初期化し、TabStops コレクションに追加します。 |
| [add](#add-float-int-) | 指定された位置とリーダータイプで新しい {@code TabStop} クラスのインスタンスを初期化し、TabStops コレクションに追加します。 |
| [add](#add-com.aspose.pdf.TabStop-) | 新しい {@code TabStop} クラスのインスタンスを初期化し、TabStops コレクションに追加します。 |
| [deepClone](#deepClone--) | 新しい {@code TabStops} オブジェクトをクローンします。 |
| [get_Item](#get_Item-int-) | TabStop インデックスに従ってコレクションから {@code TabStop} オブジェクトを取得します。 |
| [getCount](#getCount--) | tabStops のカウントを返します。 |
| [isReadOnly](#isReadOnly--) | この {@code TabStops} インスタンスがすでに {@code TextFragment} に添付され、読み取り専用になっていることを示す値を取得します。 |
| [set_Item](#set_Item-int-com.aspose.pdf.TabStop-) | TabStop インデックスに従ってコレクションから {@code TabStop} オブジェクトを設定します。 |

### TabStops {#TabStops--}
```
public TabStops()
```

新しい {@code TabStops} クラスのインスタンスを初期化します。

### add {#add--}
```
public TabStop add()
```

新しい {@code TabStop} クラスのインスタンスを初期化し、TabStops コレクションに追加します。

**Returns:**
新しい {@code TabStop} オブジェクトです。

### add {#add-float-}
```
public TabStop add(float position)
```

指定された位置で新しい {@code TabStop} クラスのインスタンスを初期化し、TabStops コレクションに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 位置 |  | タブストップの位置です。 |

**Returns:**
新しい {@code TabStop} オブジェクトです。

### add {#add-float-int-}
```
public TabStop add(float position, int leaderType)
```

指定された位置とリーダータイプで新しい {@code TabStop} クラスのインスタンスを初期化し、TabStops コレクションに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 位置 |  | タブストップの位置です。 |
| リーダータイプ |  | タブストップのリーダータイプです。 |

**Returns:**
新しい {@code TabStop} オブジェクトです。

### add {#add-com.aspose.pdf.TabStop-}
新しい {@code TabStop} クラスのインスタンスを初期化し、TabStops コレクションに追加します。

**Returns:**
新しい {@code TabStop} オブジェクトです。

### deepClone {#deepClone--}
```
public Object deepClone()
```

新しい {@code TabStops} オブジェクトをクローンします。

**Returns:**
新しい {@code TabStops} オブジェクトです。

### get_Item {#get_Item-int-}
```
public TabStop get_Item(int index)
```

TabStop インデックスに従ってコレクションから {@code TabStop} オブジェクトを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | {@code TabStops} コレクション内の要素のゼロベースインデックスです。 |

**Returns:**
{@code TabStop} オブジェクトです。

### getCount {#getCount--}
```
public int getCount()
```

tabStops のカウントを返します。

**Returns:**
int 値です。

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

この {@code TabStops} インスタンスがすでに {@code TextFragment} に添付され、読み取り専用になっていることを示す値を取得します。

**Returns:**
ブール値

### set_Item {#set_Item-int-com.aspose.pdf.TabStop-}
TabStop インデックスに従ってコレクションから {@code TabStop} オブジェクトを設定します。
