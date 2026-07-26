---
title: "ポイント"
linktitle: "ポイント"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "小数座標を持つ点を表します。"
type: docs
weight: 3870
url: /ja/java/com.aspose.pdf/point/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Point

```
public final class Point extends Object
```

小数座標を持つ点を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Point](#Point-double-double-) | 新しい {@code Point} のインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [distance](#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-) | 二つの点間の距離を計算します。 |
| [getTrivial](#getTrivial--) | 座標がすべて0の点を取得します。 |
| [getX](#getX--) | X 座標の値を取得します。 |
| [getY](#getY--) | Y 座標の値を取得します。 |
| [setX](#setX-double-) | X 座標の値を設定します。 |
| [setY](#setY-double-) | Y 座標の値を設定します。 |
| [toPoint](#toPoint--) | ポイントを java.awt.geom.Point2D.Float オブジェクトに変換します。 |
| [toString](#toString--) | 現在のポイントの文字列表現を返します。 |

### Point {#Point-double-double-}
```
public Point(double x, double y)
```

新しい {@code Point} のインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x |  | x 座標の値。 |
| y |  | y 座標の値。 |

### distance {#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-}
二つの点間の距離を計算します。

### getTrivial {#getTrivial--}
```
public static Point getTrivial()
```

座標がすべて0の点を取得します。

**Returns:**
Point オブジェクト

### getX {#getX--}
```
public double getX()
```

X 座標の値を取得します。

**Returns:**
double 値

### getY {#getY--}
```
public double getY()
```

Y 座標の値を取得します。

**Returns:**
double 値

### setX {#setX-double-}
```
public void setX(double value)
```

X 座標の値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setY {#setY-double-}
```
public void setY(double value)
```

Y 座標の値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### toPoint {#toPoint--}
```
public Point2D.Float toPoint()
```

ポイントを java.awt.geom.Point2D.Float オブジェクトに変換します。

**Returns:**
Float 構造体。

### toString {#toString--}
```
public String toString()
```

現在のポイントの文字列表現を返します。

**Returns:**
現在のポイントを表す文字列。
