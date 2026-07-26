---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "矩形を表します。"
type: docs
weight: 120
url: /ja/java/com.aspose.pdf.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Rectangle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Rectangle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Rectangle extends Shape
```

矩形を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Rectangle](#Rectangle--) | コンストラクタ |
| [Rectangle](#Rectangle-float-float-float-float-) | {@code Rectangle} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 項目が指定されたコンテナの寸法（境界を含む）に収まるかどうかをチェックします。 |
| [getBottom](#getBottom--) | 矩形の下端位置を示す float 値を取得します。 |
| [getHeight](#getHeight--) | 矩形の高さを示す float 値を取得します。 |
| [getLeft](#getLeft--) | 矩形の左端位置を示す float 値を取得します。 |
| [getRoundedCornerRadius](#getRoundedCornerRadius--) | 矩形の角の半径を示す float 値を取得します。 |
| [getWidth](#getWidth--) | 矩形の幅を示す float 値を取得します。 |
| [setBottom](#setBottom-double-) | 矩形の下端位置を示す float 値を設定します。 |
| [setHeight](#setHeight-double-) | 矩形の高さを示す float 値を設定します。 |
| [setLeft](#setLeft-double-) | 矩形の左端位置を示す float 値を設定します。 |
| [setRoundedCornerRadius](#setRoundedCornerRadius-double-) | 矩形の角の半径を示す float 値を設定します。 |
| [setWidth](#setWidth-double-) | 矩形の幅を示す float 値を設定します。 |

### Rectangle {#Rectangle--}
```
public Rectangle()
```

コンストラクタ

### Rectangle {#Rectangle-float-float-float-float-}
```
public Rectangle(float left, float bottom, float width, float height)
```

{@code Rectangle} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left |  | 矩形の左端位置です。 |
| bottom |  | 矩形の下端位置です。 |
| 幅 |  | 矩形の幅です。 |
| 高さ |  | 矩形の高さです。 |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

項目が指定されたコンテナの寸法（境界を含む）に収まるかどうかをチェックします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
適合する場合は true、そうでない場合は false。

### getBottom {#getBottom--}
```
public double getBottom()
```

矩形の下端位置を示す float 値を取得します。

**Returns:**
矩形の下端位置を示す値です。

### getHeight {#getHeight--}
```
public double getHeight()
```

矩形の高さを示す float 値を取得します。

**Returns:**
矩形の高さを示す値です。

### getLeft {#getLeft--}
```
public double getLeft()
```

矩形の左端位置を示す float 値を取得します。

**Returns:**
矩形の左側位置を示す float 値です。

### getRoundedCornerRadius {#getRoundedCornerRadius--}
```
public double getRoundedCornerRadius()
```

矩形の角の半径を示す float 値を取得します。

**Returns:**
矩形の角の半径を示す値です。

### getWidth {#getWidth--}
```
public double getWidth()
```

矩形の幅を示す float 値を取得します。

**Returns:**
矩形の幅を示す値です。

### setBottom {#setBottom-double-}
```
public void setBottom(double value)
```

矩形の下端位置を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 矩形の下端位置を示す値です。 |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

矩形の高さを示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 矩形の高さを示す値です。 |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

矩形の左端位置を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 矩形の左側位置を示す float 値です。 |

### setRoundedCornerRadius {#setRoundedCornerRadius-double-}
```
public void setRoundedCornerRadius(double value)
```

矩形の角の半径を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 矩形の角の半径を示すものです。 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

矩形の幅を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 矩形の幅を示すものです。 |
