---
title: "AbsorbedRow"
linktitle: "AbsorbedRow"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページ上に存在するテーブルの行を表します"
type: docs
weight: 20
url: /ja/java/com.aspose.pdf/absorbedrow/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedRow

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedRow >

```
public class AbsorbedRow extends Object implements ITableElement , Comparable < AbsorbedRow >
```

ページ上に存在するテーブルの行を表します

## メソッド

| メソッド | 説明 |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedRow-) | 現在の AbsorbedRow オブジェクトを別の AbsorbedRow オブジェクトと比較し、現在のオブジェクトが前に来るか、後に来るか、または同じ位置にあるかを示す整数を返します。 |
| [getCellList](#getCellList--) | 行のセルを含む読み取り専用 IList を取得します |
| [getRectangle](#getRectangle--) | ページ上の行の位置を示す矩形を取得します |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedRow-}
現在の AbsorbedRow オブジェクトを別の AbsorbedRow オブジェクトと比較し、現在のオブジェクトが前に来るか、後に来るか、または同じ位置にあるかを示す整数を返します。

### getCellList {#getCellList--}
```
public List < AbsorbedCell > getCellList()
```

行のセルを含む読み取り専用 IList を取得します

**Returns:**
AbsorbedCell オブジェクトのリスト

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

ページ上の行の位置を示す矩形を取得します

**Returns:**
矩形インスタンス
