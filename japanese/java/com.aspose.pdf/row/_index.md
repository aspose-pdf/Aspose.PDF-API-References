---
title: "行"
linktitle: "行"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テーブルの行を表します。"
type: docs
weight: 4330
url: /ja/java/com.aspose.pdf/row/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Row

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Row extends Object implements com.aspose.ms.System.ICloneable
```

テーブルの行を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Row](#Row--) | Row クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone](#deepClone--) | 行をクローンします。 |
| [getBackgroundColor](#getBackgroundColor--) | 背景色を取得します。 |
| [getBorder](#getBorder--) | 境界線を取得します。 |
| [getCells](#getCells--) | 行の getCells() を取得します。 |
| [getDefaultCellBorder](#getDefaultCellBorder--) | デフォルトのセル境界線を取得します； |
| [getDefaultCellPadding](#getDefaultCellPadding--) | 行の getCells() のデフォルトマージンを取得します。 |
| [getDefaultCellTextState](#getDefaultCellTextState--) | 行の getCells() のデフォルトテキスト状態を取得または設定します。行の getCells() のデフォルトテキスト状態を取得します。 |
| [getFixedRowHeight](#getFixedRowHeight--) | 固定行の高さを取得します - 行は固定高さになる場合があります； |
| [getMinRowHeight](#getMinRowHeight--) | 行の高さを取得します； |
| [getVerticalAlignment](#getVerticalAlignment--) | 垂直方向の配置を取得または設定します。 |
| [isInNewPage](#isInNewPage--) | 固定行が新しいページにあるかを取得します - このプロパティが設定されたページは次のページに印刷されるべきです。デフォルトは falseです； |
| [isRowBroken](#isRowBroken--) | 行が2ページ間で分割できるかどうかを取得します |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 背景色を設定します。 |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | 境界線を設定します。 |
| [setCells](#setCells-com.aspose.pdf.Cells-) | 行の getCells() を設定します。 |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | デフォルトのセル境界線を設定します； |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | 行の getCells() のデフォルトマージンを設定します。 |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 行の getCells() のデフォルトテキスト状態を設定します。 |
| [setFixedRowHeight](#setFixedRowHeight-double-) | 固定行の高さを設定します - 行は固定高さになる場合があります； |
| [setInNewPage](#setInNewPage-boolean-) | 行が2ページ間で分割できるかどうかを設定します |
| [setMinRowHeight](#setMinRowHeight-double-) | 行の高さを設定します； |
| [setRowBroken](#setRowBroken-boolean-) | 行が2ページ間で分割できるかどうかを設定します |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 垂直方向の配置を取得または設定します。 |

### Row {#Row--}
```
public Row()
```

Row クラスの新しいインスタンスを初期化します。

### deepClone {#deepClone--}
```
public Object deepClone()
```

行をクローンします。

**Returns:**
クローンされたオブジェクト

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

背景色を取得します。

**Returns:**
カラー値

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

境界線を取得します。

**Returns:**
BorderInfo の値

### getCells {#getCells--}
```
public Cells getCells()
```

行の getCells() を取得します。

**Returns:**
getCells() の値

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public BorderInfo getDefaultCellBorder()
```

デフォルトのセル境界線を取得します；

**Returns:**
BorderInfo の値

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public MarginInfo getDefaultCellPadding()
```

行の getCells() のデフォルトマージンを取得します。

**Returns:**
MarginInfo 値

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

行の getCells() のデフォルトテキスト状態を取得または設定します。行の getCells() のデフォルトテキスト状態を取得します。

**Returns:**
TextState の値

### getFixedRowHeight {#getFixedRowHeight--}
```
public double getFixedRowHeight()
```

固定行の高さを取得します - 行は固定高さになる場合があります；

**Returns:**
double 値

### getMinRowHeight {#getMinRowHeight--}
```
public double getMinRowHeight()
```

行の高さを取得します；

**Returns:**
double 値

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

垂直方向の配置を取得または設定します。

**Returns:**
VerticalAlignment 要素 @see VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

固定行が新しいページにあるかを取得します - このプロパティが設定されたページは次のページに印刷されるべきです。デフォルトは falseです；

**Returns:**
ブール値

### isRowBroken {#isRowBroken--}
```
public boolean isRowBroken()
```

行が2ページ間で分割できるかどうかを取得します

**Returns:**
ブール値

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
背景色を設定します。

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
境界線を設定します。

### setCells {#setCells-com.aspose.pdf.Cells-}
行の getCells() を設定します。

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
デフォルトのセル境界線を設定します；

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
行の getCells() のデフォルトマージンを設定します。

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
行の getCells() のデフォルトテキスト状態を設定します。

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public void setFixedRowHeight(double value)
```

固定行の高さを設定します - 行は固定高さになる場合があります；

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

行が2ページ間で分割できるかどうかを設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMinRowHeight {#setMinRowHeight-double-}
```
public void setMinRowHeight(double value)
```

行の高さを設定します；

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setRowBroken {#setRowBroken-boolean-}
```
public void setRowBroken(boolean value)
```

行が2ページ間で分割できるかどうかを設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
垂直方向の配置を取得または設定します。
