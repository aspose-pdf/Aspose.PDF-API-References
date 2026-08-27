---
title: "AbsorbedTable"
linktitle: "AbsorbedTable"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページ上に存在するテーブルを表します"
type: docs
weight: 30
url: /ja/java/com.aspose.pdf/absorbedtable/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedTable

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedTable >

```
public class AbsorbedTable extends Object implements ITableElement , Comparable < AbsorbedTable >
```

ページ上に存在するテーブルを表します

## メソッド

| メソッド | 説明 |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedTable-) | 現在の AbsorbedTable オブジェクトを別の AbsorbedTable オブジェクトと比較し、現在のオブジェクトが前にあるか、後にあるか、または同じ位置にあるかを示す整数を返します。 |
| [getPageNum](#getPageNum--) | このテーブルが含まれるページ番号を取得します。 |
| [getRectangle](#getRectangle--) | ページ上のテーブルの位置を示す矩形を取得します。 |
| [getRowList](#getRowList--) | <p> テーブルの行を含む読み取り専用 IList を取得します </p> |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedTable-}
現在の AbsorbedTable オブジェクトを別の AbsorbedTable オブジェクトと比較し、現在のオブジェクトが前にあるか、後にあるか、または同じ位置にあるかを示す整数を返します。

### getPageNum {#getPageNum--}
```
public int getPageNum()
```

このテーブルが含まれるページ番号を取得します。

**Returns:**
int 値です。

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

ページ上のテーブルの位置を示す矩形を取得します。

**Returns:**
Rectangle オブジェクト

### getRowList {#getRowList--}
```
public List < AbsorbedRow > getRowList()
```

<p> テーブルの行を含む読み取り専用 IList を取得します </p>

**Returns:**
{@code IGenericList<AbsorbedRow>} オブジェクト
