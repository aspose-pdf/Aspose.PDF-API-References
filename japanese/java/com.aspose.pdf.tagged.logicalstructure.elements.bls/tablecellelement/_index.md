---
title: "TableCellElement"
linktitle: "TableCellElement"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "論理構造におけるテーブルセル要素 (TH と TD) の基底クラスを表します。"
type: docs
weight: 150
url: /ja/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class TableCellElement extends TableChildElement implements ITextElement , IAdjustPosition
```

論理構造におけるテーブルセル要素 (TH と TD) の基底クラスを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | 位置を調整します。 |
| [getAlignment](#getAlignment--) | セルの配置を取得または設定します。 |
| [getBackgroundColor](#getBackgroundColor--) | セルの背景色を取得または設定します。 |
| [getBorder](#getBorder--) | セルの境界線を取得または設定します。 |
| [getCell](#getCell--) |  |
| [getColSpan](#getColSpan--) | 列のスパンを取得または設定します。 |
| [getDefaultCellTextState](#getDefaultCellTextState--) | デフォルトのセルテキスト状態を取得または設定します。 |
| [getMargin](#getMargin--) | 余白を取得または設定します。 |
| [getRowSpan](#getRowSpan--) | 行のスパンを取得または設定します。 |
| [getStructureTextState](#getStructureTextState--) | 現在の要素の {@code /Aspose.Pdf.LogicalStructure.StructureTextState} オブジェクトを取得します。値: 現在の要素の {@code /Aspose.Pdf.LogicalStructure.StructureTextState} オブジェクトです。 |
| [getVerticalAlignment](#getVerticalAlignment--) | 垂直方向の配置を取得または設定します。 |
| [isNoBorder](#isNoBorder--) | セルの罫線を取得または設定します。 |
| [isWordWrapped](#isWordWrapped--) | セルのテキストの折り返しを取得または設定します。 |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | セルの配置を取得または設定します。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | セルの背景色を取得または設定します。 |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | セルの境界線を取得または設定します。 |
| [setColSpan](#setColSpan-int-) | 列のスパンを取得または設定します。 |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | デフォルトのセルテキスト状態を取得または設定します。 |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | 余白を取得または設定します。 |
| [setNoBorder](#setNoBorder-boolean-) | セルの罫線を取得または設定します。 |
| [setRowSpan](#setRowSpan-int-) | 行のスパンを取得または設定します。 |
| [setText](#setText-java.lang.String-) | 現在のテキスト要素にテキストコンテンツを追加します。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 垂直方向の配置を取得または設定します。 |
| [setWordWrapped](#setWordWrapped-boolean-) | セルのテキストの折り返しを取得または設定します。 |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
位置を調整します。

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

セルの配置を取得または設定します。

**Returns:**
HorizontalAlignment 要素

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

セルの背景色を取得または設定します。

**Returns:**
Color インスタンス

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

セルの境界線を取得または設定します。

**Returns:**
BorderInfo インスタンス

### getCell {#getCell--}
```
public final Cell getCell()
```



### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

列のスパンを取得または設定します。

**Returns:**
int 値です。

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

デフォルトのセルテキスト状態を取得または設定します。

**Returns:**
TextState インスタンス

### getMargin {#getMargin--}
```
public final MarginInfo getMargin()
```

余白を取得または設定します。

**Returns:**
MarginInfo インスタンス

### getRowSpan {#getRowSpan--}
```
public final int getRowSpan()
```

行のスパンを取得または設定します。

**Returns:**
int 値です。

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

現在の要素の {@code /Aspose.Pdf.LogicalStructure.StructureTextState} オブジェクトを取得します。値: 現在の要素の {@code /Aspose.Pdf.LogicalStructure.StructureTextState} オブジェクトです。

**Returns:**
StructureTextState インスタンス

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

垂直方向の配置を取得または設定します。

**Returns:**
VerticalAlignment 要素

### isNoBorder {#isNoBorder--}
```
public final boolean isNoBorder()
```

セルの罫線を取得または設定します。

**Returns:**
ブール値

### isWordWrapped {#isWordWrapped--}
```
public final boolean isWordWrapped()
```

セルのテキストの折り返しを取得または設定します。

**Returns:**
ブール値

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
セルの配置を取得または設定します。

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
セルの背景色を取得または設定します。

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
セルの境界線を取得または設定します。

### setColSpan {#setColSpan-int-}
```
public final void setColSpan(int value)
```

列のスパンを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
デフォルトのセルテキスト状態を取得または設定します。

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
余白を取得または設定します。

### setNoBorder {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```

セルの罫線を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRowSpan {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```

行のスパンを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setText {#setText-java.lang.String-}
現在のテキスト要素にテキストコンテンツを追加します。

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
垂直方向の配置を取得または設定します。

### setWordWrapped {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```

セルのテキストの折り返しを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
