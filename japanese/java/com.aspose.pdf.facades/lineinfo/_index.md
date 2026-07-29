---
title: "LineInfo"
linktitle: "LineInfo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "行の情報を表します。"
type: docs
weight: 350
url: /ja/java/com.aspose.pdf.facades/lineinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.LineInfo

```
public final class LineInfo extends Object
```

行の情報を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [LineInfo](#LineInfo--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBorderStyle](#getBorderStyle--) | 線の枠線スタイルを取得します。0 は実線、1 は破線、2 はベベル、3 はインサート、4 は下線を表します。 |
| [getLineColor](#getLineColor--) | 線の色を取得します。 |
| [getLineDashPattern](#getLineDashPattern--) | 線の破線パターンを取得します。 |
| [getLineWidth](#getLineWidth--) | 線の幅を取得または設定します。 |
| [getVerticeCoordinate](#getVerticeCoordinate--) | 各頂点の水平座標と垂直座標が交互に並んだ数値の配列を取得します。 |
| [getVisibility](#getVisibility--) | 線の可視性を取得します。 |
| [setBorderStyle](#setBorderStyle-com.aspose.pdf.BorderStyle-) | 線の枠線スタイルを設定します。0 は実線、1 は破線、2 はベベル、3 はインサート、4 は下線を表します。 |
| [setBorderStyle](#setBorderStyle-int-) | 線の枠線スタイルを設定します。0 は実線、1 は破線、2 はベベル、3 はインサート、4 は下線を表します。 |
| [setLineColor](#setLineColor-java.awt.Color-) | 線の色を設定します。 |
| [setLineDashPattern](#setLineDashPattern-int:A-) | 線の破線パターンを設定します。 |
| [setLineWidth](#setLineWidth-int-) | 線の幅を設定します。 |
| [setVerticeCoordinate](#setVerticeCoordinate-float:A-) | 各頂点の水平座標と垂直座標が交互に並んだ数値の配列を設定します。 |
| [setVisibility](#setVisibility-boolean-) | 線の可視性を設定します。 |

### LineInfo {#LineInfo--}
```
public LineInfo()
```



### getBorderStyle {#getBorderStyle--}
```
public BorderStyle getBorderStyle()
```

線の枠線スタイルを取得します。0 は実線、1 は破線、2 はベベル、3 はインサート、4 は下線を表します。

**Returns:**
int 値です。

### getLineColor {#getLineColor--}
```
public Color getLineColor()
```

線の色を取得します。

**Returns:**
色要素

### getLineDashPattern {#getLineDashPattern--}
```
public int[] getLineDashPattern()
```

線の破線パターンを取得します。

**Returns:**
int 値の配列

### getLineWidth {#getLineWidth--}
```
public int getLineWidth()
```

線の幅を取得または設定します。

**Returns:**
int 値です。

### getVerticeCoordinate {#getVerticeCoordinate--}
```
public float[] getVerticeCoordinate()
```

各頂点の水平座標と垂直座標が交互に並んだ数値の配列を取得します。

**Returns:**
float 値の配列

### getVisibility {#getVisibility--}
```
public boolean getVisibility()
```

線の可視性を取得します。

**Returns:**
ブール値

### setBorderStyle {#setBorderStyle-com.aspose.pdf.BorderStyle-}
線の枠線スタイルを設定します。0 は実線、1 は破線、2 はベベル、3 はインサート、4 は下線を表します。

### setBorderStyle {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```

線の枠線スタイルを設定します。0 は実線、1 は破線、2 はベベル、3 はインサート、4 は下線を表します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setLineColor {#setLineColor-java.awt.Color-}
線の色を設定します。

### setLineDashPattern {#setLineDashPattern-int:A-}
```
public void setLineDashPattern(int[] value)
```

線の破線パターンを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値の配列 |

### setLineWidth {#setLineWidth-int-}
```
public void setLineWidth(int value)
```

線の幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setVerticeCoordinate {#setVerticeCoordinate-float:A-}
```
public void setVerticeCoordinate(float[] value)
```

各頂点の水平座標と垂直座標が交互に並んだ数値の配列を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値の配列 |

### setVisibility {#setVisibility-boolean-}
```
public void setVisibility(boolean value)
```

線の可視性を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
