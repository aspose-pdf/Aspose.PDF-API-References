---
title: "Measure"
linktitle: "Measure"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "測定座標系を記述するクラスです。"
type: docs
weight: 2930
url: /ja/java/com.aspose.pdf/measure/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure

```
public class Measure extends Object
```

測定座標系を記述するクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Measure](#Measure-com.aspose.pdf.Annotation-) | 測定アノテーション用の Measure オブジェクトを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAngleFormat](#getAngleFormat--) | 角度測定用の数値書式配列。 |
| [getAreaFormat](#getAreaFormat--) | 面積測定用の数値書式配列。 |
| [getDistanceFormat](#getDistanceFormat--) | 任意の方向の距離測定用の数値書式配列。 |
| [getOrigin](#getOrigin--) | 測定座標系の原点をデフォルトユーザー空間座標で指定するポイント。 |
| [getScaleRatio](#getScaleRatio--) | 図面の縮尺比率を表すテキスト文字列。 |
| [getSlopeFormat](#getSlopeFormat--) | 直線の勾配測定用の数値書式配列。 |
| [getXFormat](#getXFormat--) | x 軸方向の変化測定用の数値書式配列、Y が存在しない場合は y 軸方向も同様に測定します。 |
| [getXYFactor](#getXYFactor--) | y 軸の最大単位を x 軸の最大単位に変換するために使用される係数。 |
| [getYFormat](#getYFormat--) | y 軸に沿った変化の測定のための数値形式配列です。 |
| [setAngleFormat](#setAngleFormat-com.aspose.pdf.Measure.NumberFormatList-) | 角度測定用の数値書式配列。 |
| [setAreaFormat](#setAreaFormat-com.aspose.pdf.Measure.NumberFormatList-) | 面積測定用の数値書式配列。 |
| [setDistanceFormat](#setDistanceFormat-com.aspose.pdf.Measure.NumberFormatList-) | 任意の方向の距離測定用の数値書式配列。 |
| [setOrigin](#setOrigin-com.aspose.pdf.Point-) | 測定座標系の原点をデフォルトユーザー空間座標で指定するポイント。 |
| [setScaleRatio](#setScaleRatio-java.lang.String-) |  |
| [setSlopeFormat](#setSlopeFormat-com.aspose.pdf.Measure.NumberFormatList-) | 直線の勾配測定用の数値書式配列。 |
| [setXFormat](#setXFormat-com.aspose.pdf.Measure.NumberFormatList-) | x 軸方向の変化測定用の数値書式配列、Y が存在しない場合は y 軸方向も同様に測定します。 |
| [setXYFactor](#setXYFactor-double-) | y 軸の最大単位を x 軸の最大単位に変換するために使用される係数。 |
| [setYFormat](#setYFormat-com.aspose.pdf.Measure.NumberFormatList-) | y 軸に沿った変化の測定のための数値形式配列です。 |

### Measure {#Measure-com.aspose.pdf.Annotation-}
測定アノテーション用の Measure オブジェクトを作成します。

### getAngleFormat {#getAngleFormat--}
```
public Measure.NumberFormatList getAngleFormat()
```

角度測定用の数値書式配列。

**Returns:**
NumberFormatList の値

### getAreaFormat {#getAreaFormat--}
```
public Measure.NumberFormatList getAreaFormat()
```

面積測定用の数値書式配列。

**Returns:**
NumberFormatList の値

### getDistanceFormat {#getDistanceFormat--}
```
public Measure.NumberFormatList getDistanceFormat()
```

任意の方向の距離測定用の数値書式配列。

**Returns:**
NumberFormatList の値

### getOrigin {#getOrigin--}
```
public Point getOrigin()
```

測定座標系の原点をデフォルトユーザー空間座標で指定するポイント。

**Returns:**
Point オブジェクト

### getScaleRatio {#getScaleRatio--}
```
public String getScaleRatio()
```

図面の縮尺比率を表すテキスト文字列。

**Returns:**
string オブジェクト

### getSlopeFormat {#getSlopeFormat--}
```
public Measure.NumberFormatList getSlopeFormat()
```

直線の勾配測定用の数値書式配列。

**Returns:**
NumberFormatList の値

### getXFormat {#getXFormat--}
```
public Measure.NumberFormatList getXFormat()
```

x 軸方向の変化測定用の数値書式配列、Y が存在しない場合は y 軸方向も同様に測定します。

**Returns:**
NumberFormatList の値

### getXYFactor {#getXYFactor--}
```
public double getXYFactor()
```

y 軸の最大単位を x 軸の最大単位に変換するために使用される係数。

**Returns:**
double 値

### getYFormat {#getYFormat--}
```
public Measure.NumberFormatList getYFormat()
```

y 軸に沿った変化の測定のための数値形式配列です。

**Returns:**
NumberFormatList の値

### setAngleFormat {#setAngleFormat-com.aspose.pdf.Measure.NumberFormatList-}
角度測定用の数値書式配列。

### setAreaFormat {#setAreaFormat-com.aspose.pdf.Measure.NumberFormatList-}
面積測定用の数値書式配列。

### setDistanceFormat {#setDistanceFormat-com.aspose.pdf.Measure.NumberFormatList-}
任意の方向の距離測定用の数値書式配列。

### setOrigin {#setOrigin-com.aspose.pdf.Point-}
測定座標系の原点をデフォルトユーザー空間座標で指定するポイント。

### setScaleRatio {#setScaleRatio-java.lang.String-}


### setSlopeFormat {#setSlopeFormat-com.aspose.pdf.Measure.NumberFormatList-}
直線の勾配測定用の数値書式配列。

### setXFormat {#setXFormat-com.aspose.pdf.Measure.NumberFormatList-}
x 軸方向の変化測定用の数値書式配列、Y が存在しない場合は y 軸方向も同様に測定します。

### setXYFactor {#setXYFactor-double-}
```
public void setXYFactor(double value)
```

y 軸の最大単位を x 軸の最大単位に変換するために使用される係数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setYFormat {#setYFormat-com.aspose.pdf.Measure.NumberFormatList-}
y 軸に沿った変化の測定のための数値形式配列です。
