---
title: "PDF3DCrossSectionArray"
linktitle: "PDF3DCrossSectionArray"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF3DCrossSectionArray クラス。"
type: docs
weight: 3600
url: /ja/java/com.aspose.pdf/pdf3dcrosssectionarray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DCrossSectionArray

```
public class PDF3DCrossSectionArray extends Object
```

PDF3DCrossSectionArray クラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PDF3DCrossSectionArray](#PDF3DCrossSectionArray-com.aspose.pdf.IDocument-) | {@code PDF3DCrossSectionArray} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.PDF3DCrossSection-) | 指定されたクロスセクションをビュー配列に追加します。 |
| [get_Item](#get_Item-int-) | 指定されたインデックスの {@code PDF3DCrossSection} を取得または設定します。 |
| [getCount](#getCount--) | クロスセクションの数を取得します。 |
| [removeAll](#removeAll--) | 配列からすべてのクロスセクションを削除します。 |
| [removeAt](#removeAt-int-) | 指定されたインデックスの配列からクロスセクションを削除します。 |
| [set_Item](#set_Item-int-com.aspose.pdf.PDF3DCrossSection-) | 指定されたインデックスの {@code PDF3DCrossSection} を取得または設定します。 |

### PDF3DCrossSectionArray {#PDF3DCrossSectionArray-com.aspose.pdf.IDocument-}
{@code PDF3DCrossSectionArray} クラスの新しいインスタンスを初期化します。

### add {#add-com.aspose.pdf.PDF3DCrossSection-}
指定されたクロスセクションをビュー配列に追加します。

### get_Item {#get_Item-int-}
```
public PDF3DCrossSection get_Item(int index)
```

指定されたインデックスの {@code PDF3DCrossSection} を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | インデックス。 |

**Returns:**
クロスセクション。 @throws IndexOutOfRangeException 無効なインデックス: インデックスは [1..n] の範囲である必要があります (n はクロスセクションの数に等しい)。

### getCount {#getCount--}
```
public int getCount()
```

クロスセクションの数を取得します。

**Returns:**
int value: クロスセクションの数。

### removeAll {#removeAll--}
```
public void removeAll()
```

配列からすべてのクロスセクションを削除します。

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

指定されたインデックスの配列からクロスセクションを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 配列内で削除されたクロスセクションのインデックス。 @throws IndexOutOfRangeException 無効なインデックス: インデックスは [1..n] の範囲である必要があります (n はクロスセクションの数に等しい)。 |

### set_Item {#set_Item-int-com.aspose.pdf.PDF3DCrossSection-}
指定されたインデックスの {@code PDF3DCrossSection} を取得または設定します。
