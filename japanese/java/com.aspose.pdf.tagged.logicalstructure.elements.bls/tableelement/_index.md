---
title: "TableElement"
linktitle: "TableElement"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "論理構造における Table 構造要素を表します。"
type: docs
weight: 170
url: /ja/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement

**All Implemented Interfaces:**
IAdjustPosition

```
public final class TableElement extends BLSElement implements IAdjustPosition
```

論理構造における Table 構造要素を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TableElement](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | 内部使用のみを対象としたコンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | 位置を調整します。 |
| [createTBody](#createTBody--) | {@link TableTHeadElement} を作成し、現在のテーブルに追加します。 |
| [createTFoot](#createTFoot--) | {@link TableTFootElement} を作成し、現在のテーブルに追加します。 |
| [createTHead](#createTHead--) | {@link TableTHeadElement} を作成し、現在のテーブルに追加します。 |
| [getAlignment](#getAlignment--) | テーブルの配置を取得または設定します。 |
| [getBackgroundColor](#getBackgroundColor--) | テーブルの背景色を取得または設定します。 |
| [getBorder](#getBorder--) | テーブルの罫線を取得または設定します。 |
| [getBroken](#getBroken--) | テーブルの垂直分割を取得または設定します。 |
| [getColumnAdjustment](#getColumnAdjustment--) | テーブルの列調整を取得または設定します。 |
| [getColumnWidths](#getColumnWidths--) | テーブルの列幅を取得します。 |
| [getCornerStyle](#getCornerStyle--) | 境界角のスタイルを取得または設定します |
| [getDefaultCellBorder](#getDefaultCellBorder--) | デフォルトのセル罫線を取得します。 |
| [getDefaultCellPadding](#getDefaultCellPadding--) | デフォルトのセル余白を取得または設定します。 |
| [getDefaultCellTextState](#getDefaultCellTextState--) | デフォルトのセルテキスト状態を取得または設定します。 |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | デフォルト列幅を取得または設定します。 |
| [getLeft](#getLeft--) | テーブルの左座標を取得または設定します。 |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | テーブルの最大列数を取得または設定します。 |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | 複数ページにわたって繰り返される最初の行数を取得します。 |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | 繰り返し行のスタイルを取得します。 |
| [getTable](#getTable--) |  |
| [getTop](#getTop--) | テーブルの上座標を取得または設定します。 |
| [isBordersIncluded](#isBordersIncluded--) | 列幅に含まれる境界線を取得または設定します。 |
| [isBroken](#isBroken--) | テーブルが破損しているかどうかを取得または設定します - 次のページで切り捨てられます。 |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | テーブルの配置を取得または設定します。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | テーブルの背景色を取得または設定します。 |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | テーブルの罫線を取得または設定します。 |
| [setBordersIncluded](#setBordersIncluded-boolean-) | 列幅に含まれる境界線を取得または設定します。 |
| [setBroken](#setBroken-boolean-) | テーブルが破損しているかどうかを取得または設定します - 次のページで切り捨てられます。 |
| [setBroken](#setBroken-int-) | テーブルの垂直分割を取得または設定します。 |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | テーブルの列調整を取得または設定します。 |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | テーブルの列幅を取得します。 |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | 境界角のスタイルを取得または設定します |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | デフォルトのセル罫線を取得します。 |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | デフォルトのセル余白を取得または設定します。 |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | デフォルトのセルテキスト状態を取得または設定します。 |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | デフォルト列幅を取得または設定します。 |
| [setLeft](#setLeft-float-) | テーブルの左座標を取得または設定します。 |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | テーブルの最大列数を取得または設定します。 |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | 複数ページにわたって繰り返される最初の行数を取得します。 |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | 繰り返し行のスタイルを取得します。 |
| [setTop](#setTop-float-) | テーブルの上座標を取得または設定します。 |

### TableElement {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
内部使用のみを対象としたコンストラクタ

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
位置を調整します。

### createTBody {#createTBody--}
```
public final TableTBodyElement createTBody()
```

{@link TableTHeadElement} を作成し、現在のテーブルに追加します。

**Returns:**
構造要素が作成されました。

### createTFoot {#createTFoot--}
```
public final TableTFootElement createTFoot()
```

{@link TableTFootElement} を作成し、現在のテーブルに追加します。

**Returns:**
構造要素が作成されました。

### createTHead {#createTHead--}
```
public final TableTHeadElement createTHead()
```

{@link TableTHeadElement} を作成し、現在のテーブルに追加します。

**Returns:**
構造要素が作成されました。

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

テーブルの配置を取得または設定します。

**Returns:**
HorizontalAlignment 要素

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

テーブルの背景色を取得または設定します。

**Returns:**
Color インスタンス

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

テーブルの罫線を取得または設定します。

**Returns:**
BorderInfo インスタンス

### getBroken {#getBroken--}
```
public final int getBroken()
```

テーブルの垂直分割を取得または設定します。

**Returns:**
TableBroken 要素

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

テーブルの列調整を取得または設定します。

**Returns:**
ColumnAdjustment 要素

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

境界角のスタイルを取得または設定します

**Returns:**
BorderCornerStyle 要素

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

デフォルトのセル罫線を取得します。

**Returns:**
BorderInfo インスタンス

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

デフォルトのセル余白を取得または設定します。

**Returns:**
MarginInfo インスタンス

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

デフォルトのセルテキスト状態を取得または設定します。

**Returns:**
TextState インスタンス

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

デフォルト列幅を取得または設定します。

**Returns:**
文字列値

### getLeft {#getLeft--}
```
public final float getLeft()
```

テーブルの左座標を取得または設定します。

**Returns:**
float 値

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

テーブルの最大列数を取得または設定します。

**Returns:**
int 値です。

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

複数ページにわたって繰り返される最初の行数を取得します。

**Returns:**
int 値です。

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

繰り返し行のスタイルを取得します。

**Returns:**
TextState インスタンス

### getTable {#getTable--}
```
public final Table getTable()
```



### getTop {#getTop--}
```
public final float getTop()
```

テーブルの上座標を取得または設定します。

**Returns:**
float 値

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

列幅に含まれる境界線を取得または設定します。

**Returns:**
ブール値

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

テーブルが破損しているかどうかを取得または設定します - 次のページで切り捨てられます。

**Returns:**
ブール値

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
テーブルの配置を取得または設定します。

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
テーブルの背景色を取得または設定します。

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
テーブルの罫線を取得または設定します。

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

列幅に含まれる境界線を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

テーブルが破損しているかどうかを取得または設定します - 次のページで切り捨てられます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

テーブルの垂直分割を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | TableBroken 要素 |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
テーブルの列調整を取得または設定します。

### setColumnWidths {#setColumnWidths-java.lang.String-}
テーブルの列幅を取得します。

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
境界角のスタイルを取得または設定します

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
デフォルトのセル罫線を取得します。

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
デフォルトのセル余白を取得または設定します。

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
デフォルトのセルテキスト状態を取得または設定します。

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
デフォルト列幅を取得または設定します。

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

テーブルの左座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

テーブルの最大列数を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

複数ページにわたって繰り返される最初の行数を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
繰り返し行のスタイルを取得します。

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

テーブルの上座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |
