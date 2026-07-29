---
title: "TableTRElement"
linktitle: "TableTRElement"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テーブルの論理構造における TR 構造要素を表します。"
type: docs
weight: 240
url: /ja/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement

```
public final class TableTRElement extends TableChildElement
```

テーブルの論理構造における TR 構造要素を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TableTRElement](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | 内部使用のみを対象としたコンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [createTD](#createTD--) | {@link TableTHElement} を作成し、現在のテーブルに追加します。 |
| [createTH](#createTH--) | {@link TableTHElement} を作成し、現在のテーブルに追加します。 |
| [getBackgroundColor](#getBackgroundColor--) | 行の背景色を取得または設定します。 |
| [getBorder](#getBorder--) | 行の境界線を取得または設定します。 |
| [getDefaultCellBorder](#getDefaultCellBorder--) | デフォルトのセル罫線を取得します。 |
| [getDefaultCellPadding](#getDefaultCellPadding--) | 行セルのデフォルト余白を取得または設定します。 |
| [getDefaultCellTextState](#getDefaultCellTextState--) | 行セルのデフォルトテキスト状態を取得または設定します。 |
| [getFixedRowHeight](#getFixedRowHeight--) | 固定行高さを取得します - 行は固定高さになる場合があります。 |
| [getMinRowHeight](#getMinRowHeight--) | 行の高さを取得します。 |
| [getVerticalAlignment](#getVerticalAlignment--) | 垂直方向の配置を取得または設定します。 |
| [isInNewPage](#isInNewPage--) | 固定行が新しいページにあるかを取得します - このプロパティが設定されたページは次のページに印刷されるべきです。デフォルトは false です。 |
| [isRowBroken](#isRowBroken--) | 行が2ページ間で分割できるかどうかを取得します。 |
| [preSave](#preSave--) |  |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 行の背景色を取得または設定します。 |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | 行の境界線を取得または設定します。 |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | デフォルトのセル罫線を取得します。 |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | 行セルのデフォルト余白を取得または設定します。 |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 行セルのデフォルトテキスト状態を取得または設定します。 |
| [setFixedRowHeight](#setFixedRowHeight-double-) | 固定行高さを取得します - 行は固定高さになる場合があります。 |
| [setInNewPage](#setInNewPage-boolean-) | 固定行が新しいページにあるかを取得します - このプロパティが設定されたページは次のページに印刷されるべきです。デフォルトは false です。 |
| [setMinRowHeight](#setMinRowHeight-double-) | 行の高さを取得します。 |
| [setRowBroken](#setRowBroken-boolean-) | 行が2ページ間で分割できるかどうかを取得します。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 垂直方向の配置を取得または設定します。 |

### TableTRElement {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
内部使用のみを対象としたコンストラクタ

### createTD {#createTD--}
```
public final TableTDElement createTD()
```

{@link TableTHElement} を作成し、現在のテーブルに追加します。

**Returns:**
構造要素が作成されました。

### createTH {#createTH--}
```
public final TableTHElement createTH()
```

{@link TableTHElement} を作成し、現在のテーブルに追加します。

**Returns:**
構造要素が作成されました。

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

行の背景色を取得または設定します。

**Returns:**
Color インスタンス

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

行の境界線を取得または設定します。

**Returns:**
BorderInfo インスタンス

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

行セルのデフォルト余白を取得または設定します。

**Returns:**
MarginInfo インスタンス

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

行セルのデフォルトテキスト状態を取得または設定します。

**Returns:**
TextState インスタンス

### getFixedRowHeight {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```

固定行高さを取得します - 行は固定高さになる場合があります。

**Returns:**
double 値

### getMinRowHeight {#getMinRowHeight--}
```
public final double getMinRowHeight()
```

行の高さを取得します。

**Returns:**
double 値

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

垂直方向の配置を取得または設定します。

**Returns:**
VerticalAlignment 要素

### isInNewPage {#isInNewPage--}
```
public final boolean isInNewPage()
```

固定行が新しいページにあるかを取得します - このプロパティが設定されたページは次のページに印刷されるべきです。デフォルトは false です。

**Returns:**
ブール値

### isRowBroken {#isRowBroken--}
```
public final boolean isRowBroken()
```

行が2ページ間で分割できるかどうかを取得します。

**Returns:**
ブール値

### preSave {#preSave--}
```
public void preSave()
```



### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
行の背景色を取得または設定します。

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
行の境界線を取得または設定します。

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
デフォルトのセル罫線を取得します。

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
行セルのデフォルト余白を取得または設定します。

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
行セルのデフォルトテキスト状態を取得または設定します。

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```

固定行高さを取得します - 行は固定高さになる場合があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setInNewPage {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```

固定行が新しいページにあるかを取得します - このプロパティが設定されたページは次のページに印刷されるべきです。デフォルトは false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMinRowHeight {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```

行の高さを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setRowBroken {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```

行が2ページ間で分割できるかどうかを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
垂直方向の配置を取得または設定します。
