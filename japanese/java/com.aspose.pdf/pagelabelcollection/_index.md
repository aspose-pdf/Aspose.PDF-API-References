---
title: "PageLabelCollection"
linktitle: "PageLabelCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページラベルコレクションを表すクラス。"
type: docs
weight: 3400
url: /ja/java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageLabelCollection

```
public class PageLabelCollection extends Object
```

ページラベルコレクションを表すクラス。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLabel](#getLabel-int-) | ページインデックス（ページインデックスは0から開始）でページラベルを取得します。 |
| [getPages](#getPages--) | コレクション内のページインデックスを取得します。 |
| [removeLabel](#removeLabel-int-) | ページインデックス（ページインデックスは0から開始）でラベルを削除します。 |
| [updateLabel](#updateLabel-int-com.aspose.pdf.PageLabel-) | 指定されたページインデックス（ページインデックスは0から開始）のラベルを更新します。 |

### getLabel {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```

ページインデックス（ページインデックスは0から開始）でページラベルを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageIndex |  | ページのインデックス。 |

**Returns:**
指定されたページインデックスのページラベル、存在しない場合は null。

### getPages {#getPages--}
```
public int[] getPages()
```

コレクション内のページインデックスを取得します。

**Returns:**
ページのインデックスを含む整数の配列。

### removeLabel {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```

ページインデックス（ページインデックスは0から開始）でラベルを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageIndex |  | ラベルを削除するページのインデックス。 |

**Returns:**
操作が正常に実行された場合は true。

### updateLabel {#updateLabel-int-com.aspose.pdf.PageLabel-}
指定されたページインデックス（ページインデックスは0から開始）のラベルを更新します。
