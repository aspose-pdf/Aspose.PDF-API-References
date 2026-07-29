---
title: "Table"
linktitle: "Table"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページに追加できるテーブルを表します。"
type: docs
weight: 4790
url: /ja/java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Table, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Table

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Table extends BaseParagraph
```

ページに追加できるテーブルを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Table](#Table--) | デフォルト ctor |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone](#deepClone--) | / * / * 一次元配列のデータをテーブルにインポートします。インポートは配列の各項目につき1セルずつ行われ、/ * パラメータで定義された行と列から開始します。インポート中に、必要な行がまだ存在しないことが検出された場合（例：対象テーブルがデータ全体を収容するには小さすぎる）、必要な行が作成されます。/ * / * |
| [drawRoundedRectangle](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-) | 矩形の演算子を追加します。 |
| [getAlignment](#getAlignment--) | テーブルの配置を取得します。 |
| [getBackgroundColor](#getBackgroundColor--) | テーブルの背景色を取得します |
| [getBorder](#getBorder--) | 境界線を取得します。 |
| [getBreakText](#getBreakText--) | テーブルの改行テキストを取得します |
| [getBroken](#getBroken--) | テーブルの垂直分割を取得または設定します； |
| [getColumnAdjustment](#getColumnAdjustment--) | テーブルの列調整を取得します。 |
| [getColumnWidth](#getColumnWidth-java.lang.String-) | 列幅を取得します |
| [getColumnWidths](#getColumnWidths--) | テーブルの列幅を取得します。 |
| [getCornerStyle](#getCornerStyle--) | 境界角のスタイルを取得します |
| [getDefaultCellBorder](#getDefaultCellBorder--) | デフォルトのセル境界線を取得します； |
| [getDefaultCellPadding](#getDefaultCellPadding--) | デフォルトのセル余白を取得します。 |
| [getDefaultCellTextState](#getDefaultCellTextState--) | デフォルトのセルテキスト状態を取得します。 |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | デフォルトのセル境界線を取得します； |
| [getHeight](#getHeight--) | 高さを取得します。 |
| [getHeight](#getHeight-com.aspose.pdf.Page-) | 高さを取得します。 |
| [getLeft](#getLeft--) | テーブルの左座標を取得します。 |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | テーブルの最大列数を取得または設定します |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | 複数ページにわたって繰り返される最初の行数を取得します |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | 繰り返し行のスタイルを取得します |
| [getRows](#getRows--) | テーブルの行を取得します。 |
| [getTop](#getTop--) | テーブルの上座標を取得します。 |
| [getWidth](#getWidth--) | 幅を取得します。 |
| [isBordersIncluded](#isBordersIncluded--) | 列幅に含まれる境界線を取得します。 |
| [isBroken](#isBroken--) | テーブルが分割されているか取得します - 次のページで切り捨てられます。 |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | テーブルの配置を設定します。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | テーブルの背景色を設定します |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | 境界線を設定します。 |
| [setBordersIncluded](#setBordersIncluded-boolean-) | 列幅に含まれる境界線を設定します。 |
| [setBreakText](#setBreakText-com.aspose.pdf.TextFragment-) | テーブルの改行テキストを設定します |
| [setBroken](#setBroken-boolean-) | テーブルが壊れているかを設定します - 次のページに切り捨てられます。 |
| [setBroken](#setBroken-int-) | テーブルの垂直分割を取得または設定します； |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | テーブル列の調整を設定します。 |
| [setColumnTextState](#setColumnTextState-int-com.aspose.pdf.TextState-) | 高さを設定します。 |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | テーブルの列幅を取得します。 |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | 境界角のスタイルを取得または設定します |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | デフォルトのセル境界線を取得します； |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | デフォルトのセル余白を設定します。 |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | デフォルトのセルテキスト状態を設定します。 |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | デフォルトのセル境界線を取得します； |
| [setLeft](#setLeft-float-) | テーブルの左座標を設定します。 |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | テーブルの最大列数を取得または設定します |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | 複数ページにわたって繰り返される最初の行数を取得します |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | 繰り返し行のスタイルを取得します |
| [setTop](#setTop-float-) | テーブルの上端座標を設定します。 |

### Table {#Table--}
```
public Table()
```

デフォルト ctor

### deepClone {#deepClone--}
```
public Object deepClone()
```

/ * / * 一次元配列のデータをテーブルにインポートします。インポートは配列の各項目につき1セルずつ行われ、/ * パラメータで定義された行と列から開始します。インポート中に、必要な行がまだ存在しないことが検出された場合（例：対象テーブルがデータ全体を収容するには小さすぎる）、必要な行が作成されます。/ * / *

**Returns:**
クローンされたオブジェクト

### drawRoundedRectangle {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-}
矩形の演算子を追加します。

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

テーブルの配置を取得します。

**Returns:**
HorizontalAlignment 値 @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

テーブルの背景色を取得します

**Returns:**
Color オブジェクト

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

境界線を取得します。

**Returns:**
BorderInfo オブジェクト

### getBreakText {#getBreakText--}
```
public final TextFragment getBreakText()
```

テーブルの改行テキストを取得します

**Returns:**
TextFragment オブジェクト

### getBroken {#getBroken--}
```
public final int getBroken()
```

テーブルの垂直分割を取得または設定します；

**Returns:**
TableBroken の値 @see TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

テーブルの列調整を取得します。

**Returns:**
ColumnAdjustment の値 @see ColumnAdjustment

### getColumnWidth {#getColumnWidth-java.lang.String-}
列幅を取得します

### getColumnWidths {#getColumnWidths--}
```
public final String getColumnWidths()
```

テーブルの列幅を取得します。

**Returns:**
文字列値

### getCornerStyle {#getCornerStyle--}
```
public final BorderCornerStyle getCornerStyle()
```

境界角のスタイルを取得します

**Returns:**
BorderCornerStyle の値 @see BorderCornerStyle

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

デフォルトのセル境界線を取得します；

**Returns:**
BorderInfo オブジェクト

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

デフォルトのセル余白を取得します。

**Returns:**
MarginInfo オブジェクト

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

デフォルトのセルテキスト状態を取得します。

**Returns:**
TextState の値

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

デフォルトのセル境界線を取得します；

**Returns:**
String オブジェクト

### getHeight {#getHeight--}
```
public double getHeight()
```

高さを取得します。

**Returns:**
テーブルの高さ

### getHeight {#getHeight-com.aspose.pdf.Page-}
高さを取得します。

**Returns:**
テーブルの高さ

### getLeft {#getLeft--}
```
public final float getLeft()
```

テーブルの左座標を取得します。

**Returns:**
float 値

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

テーブルの最大列数を取得または設定します

**Returns:**
int 値です。

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

複数ページにわたって繰り返される最初の行数を取得します

**Returns:**
int 値です。

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

繰り返し行のスタイルを取得します

**Returns:**
TextState オブジェクト

### getRows {#getRows--}
```
public final Rows getRows()
```

テーブルの行を取得します。

**Returns:**
Rows オブジェクト

### getTop {#getTop--}
```
public final float getTop()
```

テーブルの上座標を取得します。

**Returns:**
float 値

### getWidth {#getWidth--}
```
public double getWidth()
```

幅を取得します。

**Returns:**
テーブルの幅

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

列幅に含まれる境界線を取得します。

**Returns:**
ブール値

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

テーブルが分割されているか取得します - 次のページで切り捨てられます。

**Returns:**
ブール値

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
テーブルの配置を設定します。

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
テーブルの背景色を設定します

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
境界線を設定します。

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

列幅に含まれる境界線を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setBreakText {#setBreakText-com.aspose.pdf.TextFragment-}
テーブルの改行テキストを設定します

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

テーブルが壊れているかを設定します - 次のページに切り捨てられます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

テーブルの垂直分割を取得または設定します；

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | TableBroken の値 @see TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
テーブル列の調整を設定します。

### setColumnTextState {#setColumnTextState-int-com.aspose.pdf.TextState-}
高さを設定します。

### setColumnWidths {#setColumnWidths-java.lang.String-}
テーブルの列幅を取得します。

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
境界角のスタイルを取得または設定します

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
デフォルトのセル境界線を取得します；

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
デフォルトのセル余白を設定します。

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
デフォルトのセルテキスト状態を設定します。

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
デフォルトのセル境界線を取得します；

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

テーブルの左座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

テーブルの最大列数を取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

複数ページにわたって繰り返される最初の行数を取得します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
繰り返し行のスタイルを取得します

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

テーブルの上端座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |
