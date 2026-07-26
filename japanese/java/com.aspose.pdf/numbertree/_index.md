---
title: "NumberTree"
linktitle: "NumberTree"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ファイルのナンバーツリー構造を表すクラス。7.9.7 Number Trees"
type: docs
weight: 3150
url: /ja/java/com.aspose.pdf/numbertree/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.NumberTree

```
public class NumberTree extends Object
```

PDF ファイルのナンバーツリー構造を表すクラス。7.9.7 Number Trees

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get](#get-int-) | キーで項目を取得します。 |
| [getKeys](#getKeys--) | ツリー内のすべてのキーを取得します。 |
| [remove](#remove-int-) | ナンバーツリーからキーを削除します。 |

### get {#get-int-}
```
public com.aspose.pdf.engine.data.IPdfPrimitive get(int key)
```

キーで項目を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー |  | int 値です。 |

**Returns:**
IPdfPrimitive オブジェクト

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.List< Integer > getKeys()
```

ツリー内のすべてのキーを取得します。

**Returns:**
{@code List<Integer> object}

### remove {#remove-int-}
```
public boolean remove(int key)
```

ナンバーツリーからキーを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー |  | int 値です。 |

**Returns:**
ブール値
