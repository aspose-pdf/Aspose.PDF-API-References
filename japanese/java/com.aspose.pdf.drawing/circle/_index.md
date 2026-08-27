---
title: "円"
linktitle: "円"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "円を表します。"
type: docs
weight: 20
url: /ja/java/com.aspose.pdf.drawing/circle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Circle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Circle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Circle extends Shape
```

円を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Circle](#Circle--) | 内部使用のみ |
| [Circle](#Circle-float-float-float-) | {@code Circle} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 項目が指定されたコンテナの寸法（境界を含む）に収まるかどうかをチェックします。 |
| [getPosX](#getPosX--) | 円弧の中心の x 座標を示す float 値を取得します。 |
| [getPosY](#getPosY--) | 円弧の中心の y 座標を示す float 値を取得します。 |
| [getRadius](#getRadius--) | 円の半径を示す float 値を取得します。 |
| [setPosX](#setPosX-double-) | 円弧の中心の x 座標を示す float 値を設定します。 |
| [setPosY](#setPosY-double-) | 円弧の中心の y 座標を示す float 値を設定します。 |
| [setRadius](#setRadius-double-) | 円の半径を示す float 値を設定します。 |

### Circle {#Circle--}
```
public Circle()
```

内部使用のみ

### Circle {#Circle-float-float-float-}
```
public Circle(float posX, float posY, float radius)
```

{@code Circle} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| posX |  | 円の中心の x 座標です。 |
| posY |  | 円の中心の y 座標です。 |
| 半径 |  | 円の半径。 |

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

### getPosX {#getPosX--}
```
public double getPosX()
```

円弧の中心の x 座標を示す float 値を取得します。

**Returns:**
弧の中心のx座標。

### getPosY {#getPosY--}
```
public double getPosY()
```

円弧の中心の y 座標を示す float 値を取得します。

**Returns:**
弧の中心のy座標。

### getRadius {#getRadius--}
```
public double getRadius()
```

円の半径を示す float 値を取得します。

**Returns:**
円の半径を示す値。

### setPosX {#setPosX-double-}
```
public void setPosX(double value)
```

円弧の中心の x 座標を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 弧の中心のx座標。 |

### setPosY {#setPosY-double-}
```
public void setPosY(double value)
```

円弧の中心の y 座標を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 弧の中心のy座標。 |

### setRadius {#setRadius-double-}
```
public void setRadius(double value)
```

円の半径を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 円の半径を示す。 |
