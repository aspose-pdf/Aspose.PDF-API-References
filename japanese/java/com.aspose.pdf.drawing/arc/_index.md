---
title: "弧"
linktitle: "弧"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "弧を表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.drawing/arc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Arc, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Arc

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Arc extends Shape
```

弧を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Arc](#Arc--) | 内部使用のみ |
| [Arc](#Arc-double-double-double-double-double-) | {@code Arc} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 項目が指定されたコンテナの寸法（境界を含む）に収まるかどうかをチェックします。 |
| [getAlpha](#getAlpha--) | 弧の開始角度を示す float 値を取得します。 |
| [getBeta](#getBeta--) | 弧の終了角度を示す float 値を取得します。 |
| [getPosX](#getPosX--) | 円弧の中心の x 座標を示す float 値を取得します。 |
| [getPosY](#getPosY--) | 円弧の中心の y 座標を示す float 値を取得します。 |
| [getRadius](#getRadius--) | 弧の半径を示す float 値を取得します。 |
| [setAlpha](#setAlpha-double-) | 弧の開始角度を示す float 値を設定します。 |
| [setBeta](#setBeta-double-) | 弧の終了角度を示す float 値を設定します。 |
| [setPosX](#setPosX-double-) | 円弧の中心の x 座標を示す float 値を設定します。 |
| [setPosY](#setPosY-double-) | 円弧の中心の y 座標を示す float 値を設定します。 |
| [setRadius](#setRadius-double-) | 弧の半径を示す float 値を設定します。 |

### Arc {#Arc--}
```
public Arc()
```

内部使用のみ

### Arc {#Arc-double-double-double-double-double-}
```
public Arc(double posX, double posY, double radius, double alpha, double beta)
```

{@code Arc} クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| posX |  | 弧の中心点のx座標。 |
| posY |  | 弧の中心点のy座標。 |
| 半径 |  | 弧の半径値。 |
| alpha |  | 弧の開始角度の値。 |
| beta |  | 弧の終了角度の値。 |

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

### getAlpha {#getAlpha--}
```
public double getAlpha()
```

弧の開始角度を示す float 値を取得します。

**Returns:**
alpha 値。

### getBeta {#getBeta--}
```
public double getBeta()
```

弧の終了角度を示す float 値を取得します。

**Returns:**
beta 値

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

弧の半径を示す float 値を取得します。

**Returns:**
弧の半径を示す値。

### setAlpha {#setAlpha-double-}
```
public void setAlpha(double value)
```

弧の開始角度を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | alpha 値。 |

### setBeta {#setBeta-double-}
```
public void setBeta(double value)
```

弧の終了角度を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | beta 値 |

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

弧の半径を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 弧の半径を示す。 |
