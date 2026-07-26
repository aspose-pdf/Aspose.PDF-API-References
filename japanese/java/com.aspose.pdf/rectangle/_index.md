---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "矩形を表すクラスです。"
type: docs
weight: 4100
url: /ja/java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Rectangle

**All Implemented Interfaces:**
Cloneable, Comparable < Object >

```
public final class Rectangle extends Object implements Comparable < Object >, Cloneable
```

矩形を表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Rectangle](#Rectangle-double-double-double-double-) | Rectangle のコンストラクタです。 |
| [Rectangle](#Rectangle-double-double-double-double-boolean-) | Rectangle のコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [_Intersect](#Z:Z_Intersect-com.aspose.pdf.Rectangle-) | 矩形が交差します。廃止されたメソッドです。代わりに Intersect を使用してください。 |
| [center](#center--) | 矩形の中心座標を返します。 |
| [clone](#clone--) | Rectangle オブジェクトをクローンします。 |
| [compareTo](#compareTo-java.lang.Object-) | CompareTo |
| [contains](#contains-com.aspose.pdf.Point-) | 指定された点が矩形の内部にあるかどうかを判定します。 |
| [contains](#contains-com.aspose.pdf.Point-boolean-) | 指定された点が矩形の内部にあるかどうかを判定します。 |
| [containsLine](#containsLine-double-double-double-double-) | 矩形が2点で表される線分を含むかどうかを判定します。 |
| [containsPoint](#containsPoint-double-double-) | 指定された点が矩形内に含まれるかどうかを判定します。 |
| [deepClone](#deepClone--) | Rectangle オブジェクトをクローンします。 |
| [equals](#equals-java.lang.Object-) | 矩形が等しいか、すなわち同じ位置とサイズを持つかどうかを確認します。 |
| [fromRect](#fromRect-java.awt.Rectangle-) | System.Drawing.Rectangle のインスタンスから新しい矩形を初期化します。 |
| [fromRect](#fromRect-java.awt.geom.Rectangle2D.Float-) | System.Drawing.Rectangle のインスタンスから新しい矩形を初期化します。 |
| [fromRectInternal](#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getArea](#getArea--) | 矩形の面積を計算します。 |
| [getEmpty](#getEmpty--) | 空の矩形を取得します |
| [getHeight](#getHeight--) | 矩形の高さを取得します。 |
| [getLLX](#getLLX--) | 左下隅の X 座標を取得します。 |
| [getLLY](#getLLY--) | 左下隅の Y 座標を取得します。 |
| [getTrivial](#getTrivial--) | 位置とサイズがゼロの矩形、すなわち自明な矩形を初期化します。 |
| [getURX](#getURX--) | 右上隅の X 座標を取得します。 |
| [getURY](#getURY--) | 右上隅の Y 座標を取得します。 |
| [getWidth](#getWidth--) | 矩形の幅を取得します。 |
| [hashCode](#hashCode--) | オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} などが提供するハッシュテーブルのためにサポートされています。<p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクトの {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。 <li>二つのオブジェクトが {@code equals(Object)} メソッドによって等しいと判断される場合、両方のオブジェクトに対して {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li>{@link java.lang.Object#equals(java.lang.Object)} メソッドによって等しくないと判断されたオブジェクトに対して、{@code hashCode} メソッドが必ずしも異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語では必須ではありません。） |
| [intersect](#intersect-com.aspose.pdf.Rectangle-) | 矩形が交差するかを判定します。 |
| [isEmpty](#isEmpty--) | 矩形が空かどうかを確認します。 |
| [isInclude](#isInclude-com.aspose.pdf.Rectangle-double-) | この矩形が別の矩形全体を含むかどうかを確認します。すなわち、別の矩形全体がこの矩形の内部にあるかどうかです。IsIntersect メソッドとの違いは、IsIntersect は部分的に交差した矩形でも true を返しますが、IsInclude は false を返す点です。 |
| [isIntersect](#isIntersect-com.aspose.pdf.Rectangle-) | この矩形が他の矩形と交差するかどうかを判定します。 |
| [isPoint](#isPoint--) | 矩形が点であるかどうかを確認します。すなわち、LLX が URX と等しく、LLY が URY と等しい場合です。 |
| [isTrivial](#isTrivial--) | 矩形が自明かどうかを確認します。すなわち、サイズと位置がゼロである場合です。 |
| [join](#join-com.aspose.pdf.Rectangle-) | 矩形を結合します。 |
| [moveBy](#moveBy-double-double-) | 指定された増分で矩形をシフトします。 |
| [nearEquals](#nearEquals-com.aspose.pdf.Rectangle-double-) | 矩形がほぼ等しいかどうか、すなわち位置とサイズが（デルタまで）ほぼ同じかを確認します。 |
| [parse](#parse-java.lang.String-) | 文字列を解析し、そこから矩形のコンポーネント llx、lly、urx、ury を抽出しようとします。 |
| [rotate](#rotate-com.aspose.pdf.Rotation-) | 矩形を指定された角度で回転させます。 |
| [rotateAngle](#rotateAngle-int-) | 矩形を指定された角度で回転させます。 |
| [setLLX](#setLLX-double-) | 左下隅の X 座標を設定します。 |
| [setLLY](#setLLY-double-) | 左下隅の Y 座標を設定します。 |
| [setURX](#setURX-double-) | 右上隅の X 座標を設定します。 |
| [setURY](#setURY-double-) | 右上隅の Y 座標を設定します。 |
| [toArray](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints](#toPoints--) | 矩形をポイントの配列 (\"QuadPoints\") に変換します。 |
| [toRect](#toRect--) | 矩形を System.Drawing.Rectangle のインスタンスに変換します。浮動小数点の位置とサイズは切り捨てられます。 |
| [toString](#toString--) | 矩形の文字列表現を取得します。 |

### Rectangle {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```

Rectangle のコンストラクタです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| llx |  | 左下隅の X。 |
| lly |  | 左下隅の Y。 |
| urx |  | 右上隅の X。 |
| ury |  | 右上隅の Y。 |

### Rectangle {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```

Rectangle のコンストラクタです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| llx |  | 左下隅の X。 |
| lly |  | 左下隅の Y。 |
| urx |  | 右上隅の X。 |
| ury |  | 右上隅の Y。 |
| normalizeCoordinates |  | 矩形の座標を正規化します。 |

### _Intersect {#Z:Z_Intersect-com.aspose.pdf.Rectangle-}
矩形が交差します。廃止されたメソッドです。代わりに Intersect を使用してください。

### center {#center--}
```
public Point center()
```

矩形の中心座標を返します。

**Returns:**
矩形の中心となる点。

### clone {#clone--}
```
public Rectangle clone()
```

Rectangle オブジェクトをクローンします。

**Returns:**
オブジェクトをクローンします。

### compareTo {#compareTo-java.lang.Object-}
CompareTo

### contains {#contains-com.aspose.pdf.Point-}
指定された点が矩形の内部にあるかどうかを判定します。

### contains {#contains-com.aspose.pdf.Point-boolean-}
指定された点が矩形の内部にあるかどうかを判定します。

### containsLine {#containsLine-double-double-double-double-}
```
public final boolean containsLine(double x1, double y1, double x2, double y2)
```

矩形が2点で表される線分を含むかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x1 |  | 線の開始点の X 座標。 |
| y1 |  | 線の開始点の Y 座標。 |
| x2 |  | 線の終点の X 座標。 |
| y2 |  | 線の終点の Y 座標。 |

**Returns:**
{@code true} if the rectangle contains the line; otherwise, {@code false}.

### containsPoint {#containsPoint-double-double-}
```
public final boolean containsPoint(double x, double y)
```

指定された点が矩形内に含まれるかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x |  | 点の X 座標。 |
| y |  | 点の Y 座標。 |

**Returns:**
{@code true} if the point is contained within the rectangle; otherwise, {@code false}.

### deepClone {#deepClone--}
```
public Rectangle deepClone()
```

Rectangle オブジェクトをクローンします。

**Returns:**
オブジェクトをクローンします。

### equals {#equals-java.lang.Object-}
矩形が等しいか、すなわち同じ位置とサイズを持つかどうかを確認します。

### fromRect {#fromRect-java.awt.Rectangle-}
System.Drawing.Rectangle のインスタンスから新しい矩形を初期化します。

### fromRect {#fromRect-java.awt.geom.Rectangle2D.Float-}
System.Drawing.Rectangle のインスタンスから新しい矩形を初期化します。

### fromRectInternal {#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-}


### getArea {#getArea--}
```
public final double getArea()
```

矩形の面積を計算します。

**Returns:**
幅と高さを掛け合わせて計算した、矩形の面積（double 型）。

### getEmpty {#getEmpty--}
```
public static Rectangle getEmpty()
```

空の矩形を取得します

**Returns:**
新しい Rectangle オブジェクト

### getHeight {#getHeight--}
```
public double getHeight()
```

矩形の高さを取得します。

**Returns:**
double 値

### getLLX {#getLLX--}
```
public double getLLX()
```

左下隅の X 座標を取得します。

**Returns:**
double 値

### getLLY {#getLLY--}
```
public double getLLY()
```

左下隅の Y 座標を取得します。

**Returns:**
double 値

### getTrivial {#getTrivial--}
```
public static Rectangle getTrivial()
```

位置とサイズがゼロの矩形、すなわち自明な矩形を初期化します。

**Returns:**
新しい Rectangle オブジェクト

### getURX {#getURX--}
```
public double getURX()
```

右上隅の X 座標を取得します。

**Returns:**
double 値

### getURY {#getURY--}
```
public double getURY()
```

右上隅の Y 座標を取得します。

**Returns:**
double 値

### getWidth {#getWidth--}
```
public double getWidth()
```

矩形の幅を取得します。

**Returns:**
double 値

### hashCode {#hashCode--}
```
public int hashCode()
```

オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} などが提供するハッシュテーブルのためにサポートされています。<p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクトの {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。 <li>二つのオブジェクトが {@code equals(Object)} メソッドによって等しいと判断される場合、両方のオブジェクトに対して {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li>{@link java.lang.Object#equals(java.lang.Object)} メソッドによって等しくないと判断されたオブジェクトに対して、{@code hashCode} メソッドが必ずしも異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語では必須ではありません。）

**Returns:**
このオブジェクトのハッシュコード値。 @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### intersect {#intersect-com.aspose.pdf.Rectangle-}
矩形が交差するかを判定します。

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

矩形が空かどうかを確認します。

**Returns:**
ブール値

### isInclude {#isInclude-com.aspose.pdf.Rectangle-double-}
この矩形が別の矩形全体を含むかどうかを確認します。すなわち、別の矩形全体がこの矩形の内部にあるかどうかです。IsIntersect メソッドとの違いは、IsIntersect は部分的に交差した矩形でも true を返しますが、IsInclude は false を返す点です。

### isIntersect {#isIntersect-com.aspose.pdf.Rectangle-}
この矩形が他の矩形と交差するかどうかを判定します。

### isPoint {#isPoint--}
```
public boolean isPoint()
```

矩形が点であるかどうかを確認します。すなわち、LLX が URX と等しく、LLY が URY と等しい場合です。

**Returns:**
ブール値

### isTrivial {#isTrivial--}
```
public boolean isTrivial()
```

矩形が自明かどうかを確認します。すなわち、サイズと位置がゼロである場合です。

**Returns:**
ブール値

### join {#join-com.aspose.pdf.Rectangle-}
矩形を結合します。

### moveBy {#moveBy-double-double-}
```
public final void moveBy(double dx, double dy)
```

指定された増分で矩形をシフトします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx |  | X 軸方向のシフト値。 |
| dy |  | Y 軸方向のシフト値。 |

### nearEquals {#nearEquals-com.aspose.pdf.Rectangle-double-}
矩形がほぼ等しいかどうか、すなわち位置とサイズが（デルタまで）ほぼ同じかを確認します。

### parse {#parse-java.lang.String-}
文字列を解析し、そこから矩形のコンポーネント llx、lly、urx、ury を抽出しようとします。

### rotate {#rotate-com.aspose.pdf.Rotation-}
矩形を指定された角度で回転させます。

### rotateAngle {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```

矩形を指定された角度で回転させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 |  | 0 から 360 度の範囲での回転角度（度）。 |

### setLLX {#setLLX-double-}
```
public void setLLX(double value)
```

左下隅の X 座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setLLY {#setLLY-double-}
```
public void setLLY(double value)
```

左下隅の Y 座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setURX {#setURX-double-}
```
public void setURX(double value)
```

右上隅の X 座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setURY {#setURY-double-}
```
public void setURY(double value)
```

右上隅の Y 座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### toArray {#toArray-com.aspose.pdf.engine.data.ITrailerable-}


### toPoints {#toPoints--}
```
public final Point [] toPoints()
```

矩形をポイントの配列 (\"QuadPoints\") に変換します。

**Returns:**
点の配列。

### toRect {#toRect--}
```
public Rectangle toRect()
```

矩形を System.Drawing.Rectangle のインスタンスに変換します。浮動小数点の位置とサイズは切り捨てられます。

**Returns:**
変換結果。

### toString {#toString--}
```
public String toString()
```

矩形の文字列表現を取得します。

**Returns:**
文字列の形式は llx,lly,urx,ury です。
