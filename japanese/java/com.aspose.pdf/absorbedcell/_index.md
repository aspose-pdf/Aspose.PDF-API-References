---
title: "AbsorbedCell"
linktitle: "AbsorbedCell"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページ上に存在するテーブルのセルを表します"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf/absorbedcell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedCell

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedCell >

```
public class AbsorbedCell extends Object implements ITableElement , Comparable < AbsorbedCell >
```

ページ上に存在するテーブルのセルを表します

## メソッド

| メソッド | 説明 |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedCell-) | 現在の AbsorbedCell オブジェクトを別の AbsorbedCell オブジェクトと比較し、現在のオブジェクトがソート順で前に来るか、後に来るか、または同じ位置にあるかを示す整数を返します。 |
| [getBorderInfo](#getBorderInfo--) | FlowEngine.TableAbsorber.UseFlowEngine プロパティが true に設定されている場合、セルの境界情報を返します。 |
| [getColSpan](#getColSpan--) | TableAbsorber.UseFlowEngine プロパティが true に設定されている場合、セルが跨ぐべき列数を返します。 |
| [getRectangle](#getRectangle--) | ページ上のセルの位置を示す矩形を取得します |
| [getTextFragments](#getTextFragments--) | セルに含まれるテキストを記述する {@code TextFragment} オブジェクトのコレクションを取得します |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedCell-}
現在の AbsorbedCell オブジェクトを別の AbsorbedCell オブジェクトと比較し、現在のオブジェクトがソート順で前に来るか、後に来るか、または同じ位置にあるかを示す整数を返します。

### getBorderInfo {#getBorderInfo--}
```
public final BorderInfo getBorderInfo()
```

FlowEngine.TableAbsorber.UseFlowEngine プロパティが true に設定されている場合、セルの境界情報を返します。

**Returns:**
BorderInfo インスタンス

### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

TableAbsorber.UseFlowEngine プロパティが true に設定されている場合、セルが跨ぐべき列数を返します。

**Returns:**
int 値です。

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

ページ上のセルの位置を示す矩形を取得します

**Returns:**
Rectangle オブジェクト

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

セルに含まれるテキストを記述する {@code TextFragment} オブジェクトのコレクションを取得します

**Returns:**
TextFragmentCollection オブジェクト
