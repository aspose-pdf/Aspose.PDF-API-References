---
title: "セル"
linktitle: "セル"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テーブル行のセルを表します。"
type: docs
weight: 510
url: /ja/java/com.aspose.pdf/cell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Cell

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Cell extends Object implements com.aspose.ms.System.ICloneable
```

テーブル行のセルを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Cell](#Cell--) | Cell クラスの新しいインスタンスを初期化します。 |
| [Cell](#Cell-com.aspose.pdf.Rectangle-) | Cell クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone](#deepClone--) | セルを複製します。 |
| [getAlignment](#getAlignment--) | 配置を取得します。 |
| [getBackgroundColor](#getBackgroundColor--) | 背景色を取得します。 |
| [getBackgroundImage](#getBackgroundImage--) | 背景画像を取得または設定します |
| [getBackgroundImageFile](#getBackgroundImageFile--) | 背景画像ファイルを取得します。 |
| [getBorder](#getBorder--) | 境界線を取得します。 |
| [getColSpan](#getColSpan--) | 列のスパンを取得または設定します。 |
| [getDefaultCellTextState](#getDefaultCellTextState--) | デフォルトのセルテキスト状態を取得します。 |
| [getMargin](#getMargin--) | 余白を取得します。 |
| [getParagraphs](#getParagraphs--) | セルの書式設定されたテキストを取得します。 |
| [getRowSpan](#getRowSpan--) | 行のスパンを取得します。 |
| [getVerticalAlignment](#getVerticalAlignment--) | 垂直配置を取得します。 |
| [getWidth](#getWidth--) | 列幅を取得します。 |
| [isNoBorder](#isNoBorder--) | セルに枠線があるか取得します。 |
| [isOverrideByFragment](#isOverrideByFragment--) | セルの TextState プロパティは TextFragment の TextState プロパティに上書きされます。 |
| [isWordWrapped](#isWordWrapped--) | セルのテキストの折り返し設定を取得します。 |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | 配置を設定します。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 背景色を取得または設定します。 |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | 背景画像を取得または設定します |
| [setBackgroundImageFile](#setBackgroundImageFile-java.lang.String-) | 背景画像ファイルを設定します。 |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | 境界線を設定します。 |
| [setColSpan](#setColSpan-int-) | 列のスパンを設定します。 |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | デフォルトのセルテキスト状態を設定します。 |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | 余白を設定します。 |
| [setNoBorder](#setNoBorder-boolean-) | セルに枠線があるか設定します。 |
| [setOverrideByFragment](#setOverrideByFragment-boolean-) | セルの TextState プロパティは TextFragment の TextState プロパティに上書きされます。 |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | セルの書式設定されたテキストを設定します。 |
| [setRowSpan](#setRowSpan-int-) | 行のスパンを設定します。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 垂直方向の配置を設定します。 |
| [setWidth](#setWidth-double-) | 列の幅を設定します。 |
| [setWordWrapped](#setWordWrapped-boolean-) | セルのテキストを折り返し設定します。 |

### Cell {#Cell--}
```
public Cell()
```

Cell クラスの新しいインスタンスを初期化します。

### Cell {#Cell-com.aspose.pdf.Rectangle-}
Cell クラスの新しいインスタンスを初期化します。

### deepClone {#deepClone--}
```
public Object deepClone()
```

セルを複製します。

**Returns:**
クローンされたオブジェクト

### getAlignment {#getAlignment--}
```
public HorizontalAlignment getAlignment()
```

配置を取得します。

**Returns:**
HorizontalAlignment 要素 @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

背景色を取得します。

**Returns:**
Color オブジェクト

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

背景画像を取得または設定します

**Returns:**
Image インスタンス

### getBackgroundImageFile {#getBackgroundImageFile--}
```
@Deprecated public String getBackgroundImageFile()
```

背景画像ファイルを取得します。

**Returns:**
文字列値 @deprecated プロパティが拡張されました。BackgroundImage を使用してください。

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

境界線を取得します。

**Returns:**
BorderInfo オブジェクト

### getColSpan {#getColSpan--}
```
public int getColSpan()
```

列のスパンを取得または設定します。

**Returns:**
int 値です。

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

デフォルトのセルテキスト状態を取得します。

**Returns:**
TextState オブジェクト

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

余白を取得します。

**Returns:**
MarginInfo オブジェクト

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

セルの書式設定されたテキストを取得します。

**Returns:**
Paragraphs オブジェクト

### getRowSpan {#getRowSpan--}
```
public int getRowSpan()
```

行のスパンを取得します。

**Returns:**
int 値です。

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

垂直配置を取得します。

**Returns:**
VerticalAlignment 要素 @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

列幅を取得します。

**Returns:**
double 値

### isNoBorder {#isNoBorder--}
```
public boolean isNoBorder()
```

セルに枠線があるか取得します。

**Returns:**
ブール値

### isOverrideByFragment {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```

セルの TextState プロパティは TextFragment の TextState プロパティに上書きされます。

**Returns:**
ブール値

### isWordWrapped {#isWordWrapped--}
```
public boolean isWordWrapped()
```

セルのテキストの折り返し設定を取得します。

**Returns:**
ブール値

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
配置を設定します。

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
背景色を取得または設定します。

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
背景画像を取得または設定します

### setBackgroundImageFile {#setBackgroundImageFile-java.lang.String-}
背景画像ファイルを設定します。

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
境界線を設定します。

### setColSpan {#setColSpan-int-}
```
public void setColSpan(int value)
```

列のスパンを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
デフォルトのセルテキスト状態を設定します。

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
余白を設定します。

### setNoBorder {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```

セルに枠線があるか設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setOverrideByFragment {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```

セルの TextState プロパティは TextFragment の TextState プロパティに上書きされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
セルの書式設定されたテキストを設定します。

### setRowSpan {#setRowSpan-int-}
```
public void setRowSpan(int value)
```

行のスパンを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
垂直方向の配置を設定します。

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

列の幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setWordWrapped {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```

セルのテキストを折り返し設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
