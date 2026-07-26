---
title: "GraphInfo"
linktitle: "GraphInfo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "グラフィック情報を表します。"
type: docs
weight: 1840
url: /ja/java/com.aspose.pdf/graphinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.GraphInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class GraphInfo extends Object implements com.aspose.ms.System.ICloneable
```

グラフィック情報を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [GraphInfo](#GraphInfo--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone](#deepClone--) | グラフィック情報をクローンします。 |
| [getColor](#getColor--) | グラフの色を示す {@code Color} オブジェクトを取得します。 |
| [getDashArray](#getDashArray--) | ダッシュ配列を取得します。 |
| [getDashPhase](#getDashPhase--) | ダッシュ位相を取得します。 |
| [getFillColor](#getFillColor--) | グラフの塗りつぶし色を示す {@code Color} オブジェクトを取得します。 |
| [getLineWidth](#getLineWidth--) | グラフの線幅を示す float 値を取得します。 |
| [getRotationAngle](#getRotationAngle--) | 座標系を変換する際の回転角度を示す float 値を取得します。 |
| [getScalingRateX](#getScalingRateX--) | 座標系を変換する際の x 座標の拡大率を示す float 値を取得します。 |
| [getScalingRateY](#getScalingRateY--) | 座標系を変換する際の y 座標の拡大率を示す float 値を取得します。 |
| [getSkewAngleX](#getSkewAngleX--) | 座標系を変換する際の x 座標のせん断角度を示す float 値を取得します。 |
| [getSkewAngleY](#getSkewAngleY--) | 座標系を変換する際の y 座標のせん断角度を示す float 値を取得します。 |
| [getX](#getX--) | TableAbsorber を使用する際、垂直境界の X 座標を取得し、水平境界の場合は "-1" を返します。 |
| [getY](#getY--) | TableAbsorber を使用する際、水平境界の Y 座標を取得し、垂直境界の場合は "-1" を返します。 |
| [isDoubled](#isDoubled--) | 境界が二重かどうかを取得します。 |
| [setColor](#setColor-com.aspose.pdf.Color-) | グラフの色を示す {@code Color} オブジェクトを設定します。 |
| [setDashArray](#setDashArray-int:A-) | ダッシュ配列を設定します。 |
| [setDashPhase](#setDashPhase-int-) | ダッシュ位相を設定します。 |
| [setDoubled](#setDoubled-boolean-) | 境界が二重かどうかを設定します。 |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | グラフの塗りつぶし色を示す {@code Color} オブジェクトを設定します。 |
| [setLineWidth](#setLineWidth-float-) | グラフの線幅を示す float 値を設定します。 |
| [setRotationAngle](#setRotationAngle-double-) | 座標系を変換する際の回転角度を示す float 値を設定します。 |
| [setScalingRateX](#setScalingRateX-double-) | 座標系を変換する際の x 座標の拡大率を示す float 値を設定します。 |
| [setScalingRateY](#setScalingRateY-double-) | 座標系を変換する際の y 座標の拡大率を示す float 値を設定します。 |
| [setSkewAngleX](#setSkewAngleX-double-) | 座標系を変換する際の x 座標のせん断角度を示す float 値を設定します。 |
| [setSkewAngleY](#setSkewAngleY-double-) | 座標系を変換する際の y 座標のせん断角度を示す float 値を設定します。 |

### GraphInfo {#GraphInfo--}
```
public GraphInfo()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

グラフィック情報をクローンします。

**Returns:**
クローンされたオブジェクト

### getColor {#getColor--}
```
public Color getColor()
```

グラフの色を示す {@code Color} オブジェクトを取得します。

**Returns:**
色を示すオブジェクト

### getDashArray {#getDashArray--}
```
public int[] getDashArray()
```

ダッシュ配列を取得します。

**Returns:**
ダッシュ配列

### getDashPhase {#getDashPhase--}
```
public int getDashPhase()
```

ダッシュ位相を取得します。

**Returns:**
ダッシュ位相。

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

グラフの塗りつぶし色を示す {@code Color} オブジェクトを取得します。

**Returns:**
塗りつぶし色を示すオブジェクト

### getLineWidth {#getLineWidth--}
```
public float getLineWidth()
```

グラフの線幅を示す float 値を取得します。

**Returns:**
線幅を示す値。

### getRotationAngle {#getRotationAngle--}
```
public double getRotationAngle()
```

座標系を変換する際の回転角度を示す float 値を取得します。

**Returns:**
double 値

### getScalingRateX {#getScalingRateX--}
```
public double getScalingRateX()
```

座標系を変換する際の x 座標の拡大率を示す float 値を取得します。

**Returns:**
double 値

### getScalingRateY {#getScalingRateY--}
```
public double getScalingRateY()
```

座標系を変換する際の y 座標の拡大率を示す float 値を取得します。

**Returns:**
double 値

### getSkewAngleX {#getSkewAngleX--}
```
public double getSkewAngleX()
```

座標系を変換する際の x 座標のせん断角度を示す float 値を取得します。

**Returns:**
double 値

### getSkewAngleY {#getSkewAngleY--}
```
public double getSkewAngleY()
```

座標系を変換する際の y 座標のせん断角度を示す float 値を取得します。

**Returns:**
double 値

### getX {#getX--}
```
public final double getX()
```

TableAbsorber を使用する際、垂直境界の X 座標を取得し、水平境界の場合は "-1" を返します。

**Returns:**
double 値

### getY {#getY--}
```
public final double getY()
```

TableAbsorber を使用する際、水平境界の Y 座標を取得し、垂直境界の場合は "-1" を返します。

**Returns:**
double 値

### isDoubled {#isDoubled--}
```
public boolean isDoubled()
```

境界が二重かどうかを取得します。

**Returns:**
ブール値

### setColor {#setColor-com.aspose.pdf.Color-}
グラフの色を示す {@code Color} オブジェクトを設定します。

### setDashArray {#setDashArray-int:A-}
```
public void setDashArray(int[] value)
```

ダッシュ配列を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ダッシュ配列 |

### setDashPhase {#setDashPhase-int-}
```
public void setDashPhase(int value)
```

ダッシュ位相を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ダッシュ位相。 |

### setDoubled {#setDoubled-boolean-}
```
public void setDoubled(boolean value)
```

境界が二重かどうかを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
グラフの塗りつぶし色を示す {@code Color} オブジェクトを設定します。

### setLineWidth {#setLineWidth-float-}
```
public void setLineWidth(float value)
```

グラフの線幅を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 線幅を示す値。 |

### setRotationAngle {#setRotationAngle-double-}
```
public void setRotationAngle(double value)
```

座標系を変換する際の回転角度を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setScalingRateX {#setScalingRateX-double-}
```
public void setScalingRateX(double value)
```

座標系を変換する際の x 座標の拡大率を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setScalingRateY {#setScalingRateY-double-}
```
public void setScalingRateY(double value)
```

座標系を変換する際の y 座標の拡大率を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setSkewAngleX {#setSkewAngleX-double-}
```
public void setSkewAngleX(double value)
```

座標系を変換する際の x 座標のせん断角度を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setSkewAngleY {#setSkewAngleY-double-}
```
public void setSkewAngleY(double value)
```

座標系を変換する際の y 座標のせん断角度を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |
