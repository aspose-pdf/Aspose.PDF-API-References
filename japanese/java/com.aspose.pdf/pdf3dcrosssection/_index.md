---
title: "PDF3DCrossSection"
linktitle: "PDF3DCrossSection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF3DCrossSection クラス。"
type: docs
weight: 3590
url: /ja/java/com.aspose.pdf/pdf3dcrosssection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DCrossSection

```
public class PDF3DCrossSection extends Object
```

PDF3DCrossSection クラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PDF3DCrossSection](#PDF3DCrossSection-com.aspose.pdf.Document-) | {@code PDF3DCrossSection} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCenter](#getCenter--) | 断面の回転中心を取得または設定します。 |
| [getCuttingPlaneColor](#getCuttingPlaneColor--) | 切断平面の色を取得または設定します。 |
| [getCuttingPlaneOpacity](#getCuttingPlaneOpacity--) | 切断平面の不透明度を取得または設定します。 |
| [getCuttingPlaneOrientation](#getCuttingPlaneOrientation--) | 切断平面の向きを取得または設定します。 |
| [getCuttingPlanesIntersectionColor](#getCuttingPlanesIntersectionColor--) | 切断平面の交差点の色を取得または設定します。 |
| [getVisibility](#getVisibility--) | 切断平面の交差点の可視性を示す値を取得または設定します。 |
| [setCenter](#setCenter-com.aspose.pdf.Point3D-) | 断面の回転中心を取得または設定します。 |
| [setCuttingPlaneColor](#setCuttingPlaneColor-com.aspose.pdf.Color-) | 切断平面の色を取得または設定します。 |
| [setCuttingPlaneOpacity](#setCuttingPlaneOpacity-double-) | 切断平面の不透明度を取得または設定します。 |
| [setCuttingPlaneOrientation](#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-) | 切断平面の向きを取得または設定します。 |
| [setCuttingPlanesIntersectionColor](#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-) | 切断平面の交差点の色を取得または設定します。 |
| [setVisibility](#setVisibility-boolean-) | 切断平面の交差点の可視性を示す値を取得または設定します。 |

### PDF3DCrossSection {#PDF3DCrossSection-com.aspose.pdf.Document-}
{@code PDF3DCrossSection} クラスの新しいインスタンスを初期化します。

### getCenter {#getCenter--}
```
public Point3D getCenter()
```

断面の回転中心を取得または設定します。

**Returns:**
Point3D オブジェクト: 中心。

### getCuttingPlaneColor {#getCuttingPlaneColor--}
```
public Color getCuttingPlaneColor()
```

切断平面の色を取得または設定します。

**Returns:**
com.aspose.pdf.Color オブジェクト: 切断平面の色。

### getCuttingPlaneOpacity {#getCuttingPlaneOpacity--}
```
public double getCuttingPlaneOpacity()
```

切断平面の不透明度を取得または設定します。

**Returns:**
double value: 切断平面の不透明度。 @throws Exception 数値は範囲 [0 , 1] 内でなければなりません

### getCuttingPlaneOrientation {#getCuttingPlaneOrientation--}
```
public PDF3DCuttingPlaneOrientation getCuttingPlaneOrientation()
```

切断平面の向きを取得または設定します。

**Returns:**
PDF3DCuttingPlaneOrientation オブジェクト: 切断平面の向き。 @throws Exception 値のうち1つだけが Null である必要があります。

### getCuttingPlanesIntersectionColor {#getCuttingPlanesIntersectionColor--}
```
public Color getCuttingPlanesIntersectionColor()
```

切断平面の交差点の色を取得または設定します。

**Returns:**
com.aspose.pdf.Color オブジェクト: 切断平面の交差点の色。

### getVisibility {#getVisibility--}
```
public boolean getVisibility()
```

切断平面の交差点の可視性を示す値を取得または設定します。

**Returns:**
: {@code true} が可視の場合; それ以外の場合は {@code false}。

### setCenter {#setCenter-com.aspose.pdf.Point3D-}
断面の回転中心を取得または設定します。

### setCuttingPlaneColor {#setCuttingPlaneColor-com.aspose.pdf.Color-}
切断平面の色を取得または設定します。

### setCuttingPlaneOpacity {#setCuttingPlaneOpacity-double-}
```
public void setCuttingPlaneOpacity(double value)
```

切断平面の不透明度を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double value: 切断平面の不透明度。 @throws Exception 数値は範囲 [0 , 1] 内でなければなりません |

### setCuttingPlaneOrientation {#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-}
切断平面の向きを取得または設定します。

### setCuttingPlanesIntersectionColor {#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-}
切断平面の交差点の色を取得または設定します。

### setVisibility {#setVisibility-boolean-}
```
public void setVisibility(boolean value)
```

切断平面の交差点の可視性を示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | : {@code true} が可視の場合; それ以外の場合は {@code false}。 |
