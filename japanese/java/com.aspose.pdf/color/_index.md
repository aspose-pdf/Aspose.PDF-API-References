---
title: "Color"
linktitle: "Color"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "さまざまなカラースペースで表現できるカラー値のクラスを表します。"
type: docs
weight: 670
url: /ja/java/com.aspose.pdf/color/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Color

```
public final class Color extends Object
```

さまざまなカラースペースで表現できるカラー値のクラスを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Default](#Default) | デフォルトの色を表します。 |
| [Empty](#Empty) | 空の色を表します。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Color](#Color--) | デフォルトコンストラクタ。 |
| [Color](#Color-double:A-) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone](#deepClone--) | このインスタンスをクローンします |
| [equals](#equals-java.lang.Object-) | 2つの Color が等しい場合に true を返します。 |
| [fromArgb](#fromArgb-int-int-int-) | RGB カラーコンポーネントから有効な pdf Color オブジェクトを取得します。 |
| [fromArgb](#fromArgb-int-int-int-int-) | RGB カラーコンポーネントから有効な pdf Color オブジェクトを取得します。 |
| [fromCmyk](#fromCmyk-double-double-double-double-) | CMYK カラーコンポーネントから有効な pdf Color オブジェクトを取得します。 |
| [fromGray](#fromGray-double-) | Gray カラーコンポーネントから有効な pdf Color オブジェクトを取得します。 |
| [fromRgb](#fromRgb-java.awt.Color-) | java.awt.Color 値から有効な pdf Color オブジェクトを取得します。 |
| [fromRgb](#fromRgb-double-double-double-) | RGB カラーコンポーネントから有効な pdf Color オブジェクトを取得します。 |
| [getA](#getA--) | アルファコンポーネントの値を取得します |
| [getAliceBlue](#getAliceBlue--) | ARGB 値が #FFF0F8FF のシステム定義色を取得します。 |
| [getAntiqueWhite](#getAntiqueWhite--) | ARGB 値が #FFFAEBD7 のシステム定義色を取得します。 |
| [getAqua](#getAqua--) | ARGB 値が #FF00FFFF のシステム定義色を取得します。 |
| [getAquamarine](#getAquamarine--) | ARGB 値が #FF7FFFD4 のシステム定義色を取得します。 |
| [getAzure](#getAzure--) | ARGB 値が #FFF0FFFF のシステム定義色を取得します。 |
| [getBeige](#getBeige--) | ARGB 値が #FFF5F5DC のシステム定義色を取得します。 |
| [getBisque](#getBisque--) | ARGB 値が #FFFFE4C4 のシステム定義色を取得します。 |
| [getBlack](#getBlack--) | ARGB 値が #FF000000 のシステム定義色を取得します。 |
| [getBlanchedAlmond](#getBlanchedAlmond--) | ARGB 値が #FFFFEBCD のシステム定義色を取得します。 |
| [getBlue](#getBlue--) | ARGB 値が #FF0000FF のシステム定義色を取得します。 |
| [getBlueViolet](#getBlueViolet--) | ARGB 値が #FF8A2BE2 のシステム定義色を取得します。 |
| [getBrown](#getBrown--) | ARGB 値が #FFA52A2A のシステム定義色を取得します。 |
| [getBurlyWood](#getBurlyWood--) | ARGB 値が #FFDEB887 のシステム定義色を取得します。 |
| [getCadetBlue](#getCadetBlue--) | ARGB 値が #FF5F9EA0 のシステム定義色を取得します。 |
| [getChartreuse](#getChartreuse--) | ARGB 値が #FF7FFF00 のシステム定義色を取得します。 |
| [getChocolate](#getChocolate--) | ARGB 値が #FFD2691E のシステム定義色を取得します。 |
| [getColorSpace](#getColorSpace--) | カラーが表す色空間を取得します。 |
| [getCoral](#getCoral--) | ARGB 値が #FFFF7F50 のシステム定義色を取得します。 |
| [getCornflowerBlue](#getCornflowerBlue--) | ARGB 値が #FF6495ED のシステム定義カラーを取得します。 |
| [getCornsilk](#getCornsilk--) | ARGB 値が #FFFFF8DC のシステム定義カラーを取得します。 |
| [getCrimson](#getCrimson--) | ARGB 値が #FFDC143C のシステム定義カラーを取得します。 |
| [getCyan](#getCyan--) | ARGB 値が #FF00FFFF のシステム定義色を取得します。 |
| [getDarkBlue](#getDarkBlue--) | ARGB 値が #FF00008B のシステム定義カラーを取得します。 |
| [getDarkCyan](#getDarkCyan--) | ARGB 値が #FF008B8B のシステム定義カラーを取得します。 |
| [getDarkGoldenrod](#getDarkGoldenrod--) | ARGB 値が #FFB8860B のシステム定義カラーを取得します。 |
| [getDarkGray](#getDarkGray--) | ARGB 値が #FFA9A9A9 のシステム定義カラーを取得します。 |
| [getDarkGreen](#getDarkGreen--) | ARGB 値が #FF006400 のシステム定義カラーを取得します。 |
| [getDarkKhaki](#getDarkKhaki--) | ARGB 値が #FFBDB76B のシステム定義カラーを取得します。 |
| [getDarkMagenta](#getDarkMagenta--) | ARGB 値が #FF8B008B のシステム定義カラーを取得します。 |
| [getDarkOliveGreen](#getDarkOliveGreen--) | ARGB 値が #FF556B2F のシステム定義カラーを取得します。 |
| [getDarkOrange](#getDarkOrange--) | ARGB 値が #FFFF8C00 のシステム定義カラーを取得します。 |
| [getDarkOrchid](#getDarkOrchid--) | ARGB 値が #FF9932CC のシステム定義カラーを取得します。 |
| [getDarkRed](#getDarkRed--) | ARGB 値が #FF8B0000 のシステム定義カラーを取得します。 |
| [getDarkSalmon](#getDarkSalmon--) | ARGB 値が #FFE9967A のシステム定義カラーを取得します。 |
| [getDarkSeaGreen](#getDarkSeaGreen--) | ARGB 値が #FF8FBC8F のシステム定義カラーを取得します。 |
| [getDarkSlateBlue](#getDarkSlateBlue--) | ARGB 値が #FF483D8B のシステム定義カラーを取得します。 |
| [getDarkSlateGray](#getDarkSlateGray--) | ARGB 値が #FF2F4F4F のシステム定義カラーを取得します。 |
| [getDarkTurquoise](#getDarkTurquoise--) | ARGB 値が #FF00CED1 のシステム定義カラーを取得します。 |
| [getDarkViolet](#getDarkViolet--) | ARGB 値が #FF9400D3 のシステム定義カラーを取得します。 |
| [getData](#getData--) | カラー値。 |
| [getDeepPink](#getDeepPink--) | ARGB 値が #FFFF1493 のシステム定義カラーを取得します。 |
| [getDeepSkyBlue](#getDeepSkyBlue--) | ARGB 値が #FF00BFFF のシステム定義カラーを取得します。 |
| [getDimGray](#getDimGray--) | ARGB 値が #FF696969 のシステム定義カラーを取得します。 |
| [getDodgerBlue](#getDodgerBlue--) | ARGB 値が #FF1E90FF のシステム定義カラーを取得します。 |
| [getFirebrick](#getFirebrick--) | ARGB 値が #FFB22222 のシステム定義色を取得します。 |
| [getFloralWhite](#getFloralWhite--) | ARGB 値が #FFFFFAF0 のシステム定義色を取得します。 |
| [getForestGreen](#getForestGreen--) | ARGB 値が #FF228B22 のシステム定義色を取得します。 |
| [getFuchsia](#getFuchsia--) | ARGB 値が #FFFF00FF のシステム定義色を取得します。 |
| [getGainsboro](#getGainsboro--) | ARGB 値が #FFDCDCDC のシステム定義色を取得します。 |
| [getGhostWhite](#getGhostWhite--) | ARGB 値が #FFF8F8FF のシステム定義色を取得します。 |
| [getGold](#getGold--) | ARGB 値が #FFFFD700 のシステム定義色を取得します。 |
| [getGoldenrod](#getGoldenrod--) | ARGB 値が #FFDAA520 のシステム定義色を取得します。 |
| [getGray](#getGray--) | ARGB 値が #FF808080 のシステム定義色を取得します。 |
| [getGreen](#getGreen--) | ARGB 値が #FF008000 のシステム定義色を取得します。 |
| [getGreenYellow](#getGreenYellow--) | ARGB 値が #FFADFF2F のシステム定義色を取得します。 |
| [getHoneydew](#getHoneydew--) | ARGB 値が #FFF0FFF0 のシステム定義色を取得します。 |
| [getHotPink](#getHotPink--) | ARGB 値が #FFFF69B4 のシステム定義色を取得します。 |
| [getIndianRed](#getIndianRed--) | ARGB 値が #FFCD5C5C のシステム定義色を取得します。 |
| [getIndigo](#getIndigo--) | ARGB 値が #FF4B0082 のシステム定義色を取得します。 |
| [getIvory](#getIvory--) | ARGB 値が #FFFFFFF0 のシステム定義色を取得します。 |
| [getKhaki](#getKhaki--) | ARGB 値が #FFF0E68C のシステム定義色を取得します。 |
| [getLavender](#getLavender--) | ARGB 値が #FFE6E6FA のシステム定義色を取得します。 |
| [getLavenderBlush](#getLavenderBlush--) | ARGB 値が #FFFFF0F5 のシステム定義色を取得します。 |
| [getLawnGreen](#getLawnGreen--) | ARGB 値が #FF7CFC00 のシステム定義色を取得します。 |
| [getLemonChiffon](#getLemonChiffon--) | ARGB 値が #FFFFFACD のシステム定義色を取得します。 |
| [getLightBlue](#getLightBlue--) | ARGB 値が #FFADD8E6 のシステム定義色を取得します。 |
| [getLightCoral](#getLightCoral--) | ARGB 値が #FFF08080 のシステム定義色を取得します。 |
| [getLightCyan](#getLightCyan--) | ARGB 値が #FFE0FFFF のシステム定義色を取得します。 |
| [getLightGoldenrodYellow](#getLightGoldenrodYellow--) | ARGB 値が #FFFAFAD2 のシステム定義色を取得します。 |
| [getLightGray](#getLightGray--) | ARGB 値が #FFD3D3D3 のシステム定義カラーを取得します。 |
| [getLightGreen](#getLightGreen--) | ARGB 値が #FF90EE90 のシステム定義カラーを取得します。 |
| [getLightPink](#getLightPink--) | ARGB 値が #FFFFB6C1 のシステム定義カラーを取得します。 |
| [getLightSalmon](#getLightSalmon--) | ARGB 値が #FFFFA07A のシステム定義カラーを取得します。 |
| [getLightSeaGreen](#getLightSeaGreen--) | ARGB 値が #FF20B2AA のシステム定義カラーを取得します。 |
| [getLightSkyBlue](#getLightSkyBlue--) | ARGB 値が #FF87CEFA のシステム定義カラーを取得します。 |
| [getLightSlateGray](#getLightSlateGray--) | ARGB 値が #FF778899 のシステム定義カラーを取得します。 |
| [getLightSteelBlue](#getLightSteelBlue--) | ARGB 値が #FFB0C4DE のシステム定義カラーを取得します。 |
| [getLightYellow](#getLightYellow--) | ARGB 値が #FFFFFFE0 のシステム定義カラーを取得します。 |
| [getLime](#getLime--) | ARGB 値が #FF00FF00 のシステム定義カラーを取得します。 |
| [getLimeGreen](#getLimeGreen--) | ARGB 値が #FF32CD32 のシステム定義カラーを取得します。 |
| [getLinen](#getLinen--) | ARGB 値が #FFFAF0E6 のシステム定義カラーを取得します。 |
| [getMagenta](#getMagenta--) | ARGB 値が #FFFF00FF のシステム定義色を取得します。 |
| [getMaroon](#getMaroon--) | ARGB 値が #FF800000 のシステム定義カラーを取得します。 |
| [getMediumAquamarine](#getMediumAquamarine--) | ARGB 値が #FF66CDAA のシステム定義カラーを取得します。 |
| [getMediumBlue](#getMediumBlue--) | ARGB 値が #FF0000CD のシステム定義カラーを取得します。 |
| [getMediumOrchid](#getMediumOrchid--) | ARGB 値が #FFBA55D3 のシステム定義カラーを取得します。 |
| [getMediumPurple](#getMediumPurple--) | ARGB 値が #FF9370DB のシステム定義カラーを取得します。 |
| [getMediumSeaGreen](#getMediumSeaGreen--) | ARGB 値が #FF3CB371 のシステム定義カラーを取得します。 |
| [getMediumSlateBlue](#getMediumSlateBlue--) | ARGB 値が #FF7B68EE のシステム定義カラーを取得します。 |
| [getMediumSpringGreen](#getMediumSpringGreen--) | ARGB 値が #FF00FA9A のシステム定義カラーを取得します。 |
| [getMediumTurquoise](#getMediumTurquoise--) | ARGB 値が #FF48D1CC のシステム定義カラーを取得します。 |
| [getMediumVioletRed](#getMediumVioletRed--) | ARGB 値が #FFC71585 のシステム定義カラーを取得します。 |
| [getMidnightBlue](#getMidnightBlue--) | ARGB 値が #FF191970 のシステム定義カラーを取得します。 |
| [getMintCream](#getMintCream--) | ARGB 値が #FFF5FFFA のシステム定義カラーを取得します。 |
| [getMistyRose](#getMistyRose--) | ARGB 値が #FFFFE4E1 のシステム定義カラーを取得します。 |
| [getMoccasin](#getMoccasin--) | ARGB 値が #FFFFE4B5 のシステム定義カラーを取得します。 |
| [getNavajoWhite](#getNavajoWhite--) | ARGB 値が #FFFFDEAD のシステム定義カラーを取得します。 |
| [getNavy](#getNavy--) | ARGB 値が #FF000080 のシステム定義カラーを取得します。 |
| [getOldLace](#getOldLace--) | ARGB 値が #FFFDF5E6 のシステム定義カラーを取得します。 |
| [getOlive](#getOlive--) | ARGB 値が #FF808000 のシステム定義カラーを取得します。 |
| [getOliveDrab](#getOliveDrab--) | ARGB 値が #FF6B8E23 のシステム定義カラーを取得します。 |
| [getOrange](#getOrange--) | ARGB 値が #FFFFA500 のシステム定義カラーを取得します。 |
| [getOrangeRed](#getOrangeRed--) | ARGB 値が #FFFF4500 のシステム定義カラーを取得します。 |
| [getOrchid](#getOrchid--) | ARGB 値が #FFDA70D6 のシステム定義カラーを取得します。 |
| [getPaleGoldenrod](#getPaleGoldenrod--) | ARGB 値が #FFEEE8AA のシステム定義カラーを取得します。 |
| [getPaleGreen](#getPaleGreen--) | ARGB 値が #FF98FB98 のシステム定義カラーを取得します。 |
| [getPaleTurquoise](#getPaleTurquoise--) | ARGB 値が #FFAFEEEE のシステム定義カラーを取得します。 |
| [getPaleVioletRed](#getPaleVioletRed--) | ARGB 値が #FFDB7093 のシステム定義カラーを取得します。 |
| [getPapayaWhip](#getPapayaWhip--) | ARGB 値が #FFFFEFD5 のシステム定義カラーを取得します。 |
| [getPatternColorSpace](#getPatternColorSpace--) | パターン カラースペースを示すオブジェクトを取得します。内部使用のみ |
| [getPeachPuff](#getPeachPuff--) | ARGB 値が #FFFFDAB9 のシステム定義カラーを取得します。 |
| [getPeru](#getPeru--) | ARGB 値が #FFCD853F のシステム定義カラーを取得します。 |
| [getPink](#getPink--) | ARGB 値が #FFFFC0CB のシステム定義カラーを取得します。 |
| [getPlum](#getPlum--) | ARGB 値が #FFDDA0DD のシステム定義カラーを取得します。 |
| [getPowderBlue](#getPowderBlue--) | ARGB 値が #FFB0E0E6 のシステム定義カラーを取得します。 |
| [getPurple](#getPurple--) | ARGB 値が #FF800080 のシステム定義カラーを取得します。 |
| [getRed](#getRed--) | ARGB 値が #FFFF0000 のシステム定義カラーを取得します。 |
| [getRosyBrown](#getRosyBrown--) | ARGB 値が #FFBC8F8F のシステム定義カラーを取得します。 |
| [getRoyalBlue](#getRoyalBlue--) | ARGB 値が #FF4169E1 のシステム定義カラーを取得します。 |
| [getSaddleBrown](#getSaddleBrown--) | ARGB 値が #FF8B4513 のシステム定義カラーを取得します。 |
| [getSalmon](#getSalmon--) | ARGB 値が #FFFA8072 のシステム定義色を取得します。 |
| [getSandyBrown](#getSandyBrown--) | ARGB 値が #FFF4A460 のシステム定義色を取得します。 |
| [getSeaGreen](#getSeaGreen--) | ARGB 値が #FF2E8B57 のシステム定義色を取得します。 |
| [getSeaShell](#getSeaShell--) | ARGB 値が #FFFFF5EE のシステム定義色を取得します。 |
| [getSienna](#getSienna--) | ARGB 値が #FFA0522D のシステム定義色を取得します。 |
| [getSilver](#getSilver--) | ARGB 値が #FFC0C0C0 のシステム定義色を取得します。 |
| [getSkyBlue](#getSkyBlue--) | ARGB 値が #FF87CEEB のシステム定義色を取得します。 |
| [getSlateBlue](#getSlateBlue--) | ARGB 値が #FF6A5ACD のシステム定義色を取得します。 |
| [getSlateGray](#getSlateGray--) | ARGB 値が #FF708090 のシステム定義色を取得します。 |
| [getSnow](#getSnow--) | ARGB 値が #FFFFFAFA のシステム定義色を取得します。 |
| [getSpringGreen](#getSpringGreen--) | ARGB 値が #FF00FF7F のシステム定義色を取得します。 |
| [getSteelBlue](#getSteelBlue--) | ARGB 値が #FF4682B4 のシステム定義色を取得します。 |
| [getTan](#getTan--) | ARGB 値が #FFD2B48C のシステム定義色を取得します。 |
| [getTeal](#getTeal--) | ARGB 値が #FF008080 のシステム定義色を取得します。 |
| [getThistle](#getThistle--) | ARGB 値が #FFD8BFD8 のシステム定義色を取得します。 |
| [getTomato](#getTomato--) | ARGB 値が #FFFF6347 のシステム定義色を取得します。 |
| [getTransparent](#getTransparent--) | システム定義色を取得します。 |
| [getTurquoise](#getTurquoise--) | ARGB 値が #FF40E0D0 のシステム定義色を取得します。 |
| [getViolet](#getViolet--) | ARGB 値が #FFEE82EE のシステム定義色を取得します。 |
| [getWheat](#getWheat--) | ARGB 値が #FFF5DEB3 のシステム定義色を取得します。 |
| [getWhite](#getWhite--) | ARGB 値が #FFFFFFFF のシステム定義色を取得します。 |
| [getWhiteSmoke](#getWhiteSmoke--) | ARGB 値が #FFF5F5F5 のシステム定義色を取得します。 |
| [getYellow](#getYellow--) | ARGB 値が #FFFFFF00 のシステム定義色を取得します。 |
| [getYellowGreen](#getYellowGreen--) | ARGB 値が #FF9ACD32 のシステム定義色を取得します。 |
| [hashCode](#hashCode--) | オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} が提供するようなハッシュテーブルのためにサポートされています。<p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクト上の {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。 <li>二つのオブジェクトが {@code equals(Object)} メソッドで等しいと判断される場合、両方のオブジェクトで {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li>二つのオブジェクトが {@link java.lang.Object#equals(java.lang.Object)} メソッドで等しくない場合でも、{@code hashCode} メソッドが異なる整数結果を返すことは <em>必ずしも</em> 必要ではありません。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語では必須ではありません。） |
| [op_Equality](#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | 2つの Color が等しい場合に true を返します。 |
| [op_Inequality](#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | 2つの Color が等しくない場合に true を返します。 |
| [parse](#parse-java.lang.String-) | 文字列から色成分を抽出します。 |
| [setPatternColorSpace](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | パターンのカラースペースを示すオブジェクトを設定します。内部使用のみ |
| [toRgb](#toRgb--) | 色を rgb に変換します。 |
| [toString](#toString--) | 文字列に変換します。 |

### Default {#Default}
```
public static final Color Default
```

デフォルトの色を表します。

### Empty {#Empty}
```
public static final Color Empty
```

空の色を表します。

### Color {#Color--}
```
public Color()
```

デフォルトコンストラクタ。

### Color {#Color-double:A-}
```
public Color(double[] vector)
```

コンストラクタ

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ベクトル |  | double[] 配列 |

### deepClone {#deepClone--}
```
public Color deepClone()
```

このインスタンスをクローンします

**Returns:**
Color オブジェクト

### equals {#equals-java.lang.Object-}
2つの Color が等しい場合に true を返します。

### fromArgb {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```

RGB カラーコンポーネントから有効な pdf Color オブジェクトを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| r |  | 赤色成分 (値 0 - 255)。 |
| g |  | 緑色成分 (値 0 - 255)。 |
| b |  | 青色成分 (値 0 - 255)。 |

**Returns:**
[0..255] の範囲で各成分の値を持つ Color オブジェクトです。

### fromArgb {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```

RGB カラーコンポーネントから有効な pdf Color オブジェクトを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a |  | アルファ成分の値 (値 0 - 255)。 |
| r |  | 赤色成分 (値 0 - 255)。 |
| g |  | 緑色成分 (値 0 - 255)。 |
| b |  | 青色成分 (値 0 - 255)。 |

**Returns:**
[0..255] の範囲で各成分の値を持つ Color オブジェクトです。

### fromCmyk {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```

CMYK カラーコンポーネントから有効な pdf Color オブジェクトを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c |  | シアン成分 (値 0 - 1)。 |
| m |  | マゼンタ成分 (値 0 - 1)。 |
| y |  | イエロー成分 (値 0 - 1)。 |
| k |  | キー成分 (値 0 - 1)。 |

**Returns:**
[0..1] の範囲で各成分の値を持つ Color オブジェクトです。

### fromGray {#fromGray-double-}
```
public static Color fromGray(double g)
```

Gray カラーコンポーネントから有効な pdf Color オブジェクトを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| g |  | この Gray カラー コンポーネント (値 0 - 1)。 |

**Returns:**
[0..1] の範囲で各成分の値を持つ Color オブジェクトです。

### fromRgb {#fromRgb-java.awt.Color-}
java.awt.Color 値から有効な pdf Color オブジェクトを取得します。

### fromRgb {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```

RGB カラーコンポーネントから有効な pdf Color オブジェクトを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| r |  | この Red カラー コンポーネント (値 0 - 1)。 |
| g |  | この Green カラー コンポーネント (値 0 - 1)。 |
| b |  | この Blue カラー コンポーネント (値 0 - 1)。 |

**Returns:**
[0..1] の範囲で各成分の値を持つ Color オブジェクトです。

### getA {#getA--}
```
public double getA()
```

アルファコンポーネントの値を取得します

**Returns:**
double 値

### getAliceBlue {#getAliceBlue--}
```
public static Color getAliceBlue()
```

ARGB 値が #FFF0F8FF のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getAntiqueWhite {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```

ARGB 値が #FFFAEBD7 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getAqua {#getAqua--}
```
public static Color getAqua()
```

ARGB 値が #FF00FFFF のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getAquamarine {#getAquamarine--}
```
public static Color getAquamarine()
```

ARGB 値が #FF7FFFD4 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getAzure {#getAzure--}
```
public static Color getAzure()
```

ARGB 値が #FFF0FFFF のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getBeige {#getBeige--}
```
public static Color getBeige()
```

ARGB 値が #FFF5F5DC のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getBisque {#getBisque--}
```
public static Color getBisque()
```

ARGB 値が #FFFFE4C4 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getBlack {#getBlack--}
```
public static Color getBlack()
```

ARGB 値が #FF000000 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getBlanchedAlmond {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```

ARGB 値が #FFFFEBCD のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getBlue {#getBlue--}
```
public static Color getBlue()
```

ARGB 値が #FF0000FF のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getBlueViolet {#getBlueViolet--}
```
public static Color getBlueViolet()
```

ARGB 値が #FF8A2BE2 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getBrown {#getBrown--}
```
public static Color getBrown()
```

ARGB 値が #FFA52A2A のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getBurlyWood {#getBurlyWood--}
```
public static Color getBurlyWood()
```

ARGB 値が #FFDEB887 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getCadetBlue {#getCadetBlue--}
```
public static Color getCadetBlue()
```

ARGB 値が #FF5F9EA0 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getChartreuse {#getChartreuse--}
```
public static Color getChartreuse()
```

ARGB 値が #FF7FFF00 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getChocolate {#getChocolate--}
```
public static Color getChocolate()
```

ARGB 値が #FFD2691E のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

カラーが表す色空間を取得します。

**Returns:**
ColorSpace オブジェクト

### getCoral {#getCoral--}
```
public static Color getCoral()
```

ARGB 値が #FFFF7F50 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getCornflowerBlue {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```

ARGB 値が #FF6495ED のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getCornsilk {#getCornsilk--}
```
public static Color getCornsilk()
```

ARGB 値が #FFFFF8DC のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getCrimson {#getCrimson--}
```
public static Color getCrimson()
```

ARGB 値が #FFDC143C のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getCyan {#getCyan--}
```
public static Color getCyan()
```

ARGB 値が #FF00FFFF のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getDarkBlue {#getDarkBlue--}
```
public static Color getDarkBlue()
```

ARGB 値が #FF00008B のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkCyan {#getDarkCyan--}
```
public static Color getDarkCyan()
```

ARGB 値が #FF008B8B のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkGoldenrod {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```

ARGB 値が #FFB8860B のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkGray {#getDarkGray--}
```
public static Color getDarkGray()
```

ARGB 値が #FFA9A9A9 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkGreen {#getDarkGreen--}
```
public static Color getDarkGreen()
```

ARGB 値が #FF006400 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkKhaki {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```

ARGB 値が #FFBDB76B のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkMagenta {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```

ARGB 値が #FF8B008B のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkOliveGreen {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```

ARGB 値が #FF556B2F のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkOrange {#getDarkOrange--}
```
public static Color getDarkOrange()
```

ARGB 値が #FFFF8C00 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkOrchid {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```

ARGB 値が #FF9932CC のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkRed {#getDarkRed--}
```
public static Color getDarkRed()
```

ARGB 値が #FF8B0000 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkSalmon {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```

ARGB 値が #FFE9967A のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkSeaGreen {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```

ARGB 値が #FF8FBC8F のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkSlateBlue {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```

ARGB 値が #FF483D8B のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkSlateGray {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```

ARGB 値が #FF2F4F4F のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkTurquoise {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```

ARGB 値が #FF00CED1 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDarkViolet {#getDarkViolet--}
```
public static Color getDarkViolet()
```

ARGB 値が #FF9400D3 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getData {#getData--}
```
public double[] getData()
```

カラー値。

**Returns:**
double 値の配列

### getDeepPink {#getDeepPink--}
```
public static Color getDeepPink()
```

ARGB 値が #FFFF1493 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDeepSkyBlue {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```

ARGB 値が #FF00BFFF のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDimGray {#getDimGray--}
```
public static Color getDimGray()
```

ARGB 値が #FF696969 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getDodgerBlue {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```

ARGB 値が #FF1E90FF のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getFirebrick {#getFirebrick--}
```
public static Color getFirebrick()
```

ARGB 値が #FFB22222 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getFloralWhite {#getFloralWhite--}
```
public static Color getFloralWhite()
```

ARGB 値が #FFFFFAF0 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getForestGreen {#getForestGreen--}
```
public static Color getForestGreen()
```

ARGB 値が #FF228B22 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getFuchsia {#getFuchsia--}
```
public static Color getFuchsia()
```

ARGB 値が #FFFF00FF のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getGainsboro {#getGainsboro--}
```
public static Color getGainsboro()
```

ARGB 値が #FFDCDCDC のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getGhostWhite {#getGhostWhite--}
```
public static Color getGhostWhite()
```

ARGB 値が #FFF8F8FF のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getGold {#getGold--}
```
public static Color getGold()
```

ARGB 値が #FFFFD700 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getGoldenrod {#getGoldenrod--}
```
public static Color getGoldenrod()
```

ARGB 値が #FFDAA520 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getGray {#getGray--}
```
public static Color getGray()
```

ARGB 値が #FF808080 のシステム定義色を取得します。

**Returns:**
システム定義色を表す構造体。

### getGreen {#getGreen--}
```
public static Color getGreen()
```

ARGB 値が #FF008000 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getGreenYellow {#getGreenYellow--}
```
public static Color getGreenYellow()
```

ARGB 値が #FFADFF2F のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getHoneydew {#getHoneydew--}
```
public static Color getHoneydew()
```

ARGB 値が #FFF0FFF0 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getHotPink {#getHotPink--}
```
public static Color getHotPink()
```

ARGB 値が #FFFF69B4 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getIndianRed {#getIndianRed--}
```
public static Color getIndianRed()
```

ARGB 値が #FFCD5C5C のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getIndigo {#getIndigo--}
```
public static Color getIndigo()
```

ARGB 値が #FF4B0082 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getIvory {#getIvory--}
```
public static Color getIvory()
```

ARGB 値が #FFFFFFF0 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getKhaki {#getKhaki--}
```
public static Color getKhaki()
```

ARGB 値が #FFF0E68C のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getLavender {#getLavender--}
```
public static Color getLavender()
```

ARGB 値が #FFE6E6FA のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getLavenderBlush {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```

ARGB 値が #FFFFF0F5 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getLawnGreen {#getLawnGreen--}
```
public static Color getLawnGreen()
```

ARGB 値が #FF7CFC00 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getLemonChiffon {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```

ARGB 値が #FFFFFACD のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getLightBlue {#getLightBlue--}
```
public static Color getLightBlue()
```

ARGB 値が #FFADD8E6 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getLightCoral {#getLightCoral--}
```
public static Color getLightCoral()
```

ARGB 値が #FFF08080 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getLightCyan {#getLightCyan--}
```
public static Color getLightCyan()
```

ARGB 値が #FFE0FFFF のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getLightGoldenrodYellow {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```

ARGB 値が #FFFAFAD2 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getLightGray {#getLightGray--}
```
public static Color getLightGray()
```

ARGB 値が #FFD3D3D3 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getLightGreen {#getLightGreen--}
```
public static Color getLightGreen()
```

ARGB 値が #FF90EE90 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getLightPink {#getLightPink--}
```
public static Color getLightPink()
```

ARGB 値が #FFFFB6C1 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getLightSalmon {#getLightSalmon--}
```
public static Color getLightSalmon()
```

ARGB 値が #FFFFA07A のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getLightSeaGreen {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```

ARGB 値が #FF20B2AA のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getLightSkyBlue {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```

ARGB 値が #FF87CEFA のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getLightSlateGray {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```

ARGB 値が #FF778899 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getLightSteelBlue {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```

ARGB 値が #FFB0C4DE のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getLightYellow {#getLightYellow--}
```
public static Color getLightYellow()
```

ARGB 値が #FFFFFFE0 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getLime {#getLime--}
```
public static Color getLime()
```

ARGB 値が #FF00FF00 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getLimeGreen {#getLimeGreen--}
```
public static Color getLimeGreen()
```

ARGB 値が #FF32CD32 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getLinen {#getLinen--}
```
public static Color getLinen()
```

ARGB 値が #FFFAF0E6 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMagenta {#getMagenta--}
```
public static Color getMagenta()
```

ARGB 値が #FFFF00FF のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getMaroon {#getMaroon--}
```
public static Color getMaroon()
```

ARGB 値が #FF800000 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMediumAquamarine {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```

ARGB 値が #FF66CDAA のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMediumBlue {#getMediumBlue--}
```
public static Color getMediumBlue()
```

ARGB 値が #FF0000CD のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMediumOrchid {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```

ARGB 値が #FFBA55D3 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMediumPurple {#getMediumPurple--}
```
public static Color getMediumPurple()
```

ARGB 値が #FF9370DB のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMediumSeaGreen {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```

ARGB 値が #FF3CB371 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMediumSlateBlue {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```

ARGB 値が #FF7B68EE のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMediumSpringGreen {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```

ARGB 値が #FF00FA9A のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMediumTurquoise {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```

ARGB 値が #FF48D1CC のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMediumVioletRed {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```

ARGB 値が #FFC71585 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMidnightBlue {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```

ARGB 値が #FF191970 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMintCream {#getMintCream--}
```
public static Color getMintCream()
```

ARGB 値が #FFF5FFFA のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMistyRose {#getMistyRose--}
```
public static Color getMistyRose()
```

ARGB 値が #FFFFE4E1 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getMoccasin {#getMoccasin--}
```
public static Color getMoccasin()
```

ARGB 値が #FFFFE4B5 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getNavajoWhite {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```

ARGB 値が #FFFFDEAD のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getNavy {#getNavy--}
```
public static Color getNavy()
```

ARGB 値が #FF000080 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getOldLace {#getOldLace--}
```
public static Color getOldLace()
```

ARGB 値が #FFFDF5E6 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getOlive {#getOlive--}
```
public static Color getOlive()
```

ARGB 値が #FF808000 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getOliveDrab {#getOliveDrab--}
```
public static Color getOliveDrab()
```

ARGB 値が #FF6B8E23 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getOrange {#getOrange--}
```
public static Color getOrange()
```

ARGB 値が #FFFFA500 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getOrangeRed {#getOrangeRed--}
```
public static Color getOrangeRed()
```

ARGB 値が #FFFF4500 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getOrchid {#getOrchid--}
```
public static Color getOrchid()
```

ARGB 値が #FFDA70D6 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getPaleGoldenrod {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```

ARGB 値が #FFEEE8AA のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getPaleGreen {#getPaleGreen--}
```
public static Color getPaleGreen()
```

ARGB 値が #FF98FB98 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getPaleTurquoise {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```

ARGB 値が #FFAFEEEE のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getPaleVioletRed {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```

ARGB 値が #FFDB7093 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getPapayaWhip {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```

ARGB 値が #FFFFEFD5 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getPatternColorSpace {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```

パターン カラースペースを示すオブジェクトを取得します。内部使用のみ

**Returns:**
PatternColorSpace オブジェクト

### getPeachPuff {#getPeachPuff--}
```
public static Color getPeachPuff()
```

ARGB 値が #FFFFDAB9 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getPeru {#getPeru--}
```
public static Color getPeru()
```

ARGB 値が #FFCD853F のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getPink {#getPink--}
```
public static Color getPink()
```

ARGB 値が #FFFFC0CB のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getPlum {#getPlum--}
```
public static Color getPlum()
```

ARGB 値が #FFDDA0DD のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getPowderBlue {#getPowderBlue--}
```
public static Color getPowderBlue()
```

ARGB 値が #FFB0E0E6 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getPurple {#getPurple--}
```
public static Color getPurple()
```

ARGB 値が #FF800080 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getRed {#getRed--}
```
public static Color getRed()
```

ARGB 値が #FFFF0000 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getRosyBrown {#getRosyBrown--}
```
public static Color getRosyBrown()
```

ARGB 値が #FFBC8F8F のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getRoyalBlue {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```

ARGB 値が #FF4169E1 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getSaddleBrown {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```

ARGB 値が #FF8B4513 のシステム定義カラーを取得します。

**Returns:**
システム定義色を表すもの。

### getSalmon {#getSalmon--}
```
public static Color getSalmon()
```

ARGB 値が #FFFA8072 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getSandyBrown {#getSandyBrown--}
```
public static Color getSandyBrown()
```

ARGB 値が #FFF4A460 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getSeaGreen {#getSeaGreen--}
```
public static Color getSeaGreen()
```

ARGB 値が #FF2E8B57 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getSeaShell {#getSeaShell--}
```
public static Color getSeaShell()
```

ARGB 値が #FFFFF5EE のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getSienna {#getSienna--}
```
public static Color getSienna()
```

ARGB 値が #FFA0522D のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getSilver {#getSilver--}
```
public static Color getSilver()
```

ARGB 値が #FFC0C0C0 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getSkyBlue {#getSkyBlue--}
```
public static Color getSkyBlue()
```

ARGB 値が #FF87CEEB のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getSlateBlue {#getSlateBlue--}
```
public static Color getSlateBlue()
```

ARGB 値が #FF6A5ACD のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getSlateGray {#getSlateGray--}
```
public static Color getSlateGray()
```

ARGB 値が #FF708090 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getSnow {#getSnow--}
```
public static Color getSnow()
```

ARGB 値が #FFFFFAFA のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getSpringGreen {#getSpringGreen--}
```
public static Color getSpringGreen()
```

ARGB 値が #FF00FF7F のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getSteelBlue {#getSteelBlue--}
```
public static Color getSteelBlue()
```

ARGB 値が #FF4682B4 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getTan {#getTan--}
```
public static Color getTan()
```

ARGB 値が #FFD2B48C のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getTeal {#getTeal--}
```
public static Color getTeal()
```

ARGB 値が #FF008080 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getThistle {#getThistle--}
```
public static Color getThistle()
```

ARGB 値が #FFD8BFD8 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getTomato {#getTomato--}
```
public static Color getTomato()
```

ARGB 値が #FFFF6347 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getTransparent {#getTransparent--}
```
public static Color getTransparent()
```

システム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getTurquoise {#getTurquoise--}
```
public static Color getTurquoise()
```

ARGB 値が #FF40E0D0 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getViolet {#getViolet--}
```
public static Color getViolet()
```

ARGB 値が #FFEE82EE のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getWheat {#getWheat--}
```
public static Color getWheat()
```

ARGB 値が #FFF5DEB3 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getWhite {#getWhite--}
```
public static Color getWhite()
```

ARGB 値が #FFFFFFFF のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getWhiteSmoke {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```

ARGB 値が #FFF5F5F5 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getYellow {#getYellow--}
```
public static Color getYellow()
```

ARGB 値が #FFFFFF00 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### getYellowGreen {#getYellowGreen--}
```
public static Color getYellowGreen()
```

ARGB 値が #FF9ACD32 のシステム定義色を取得します。

**Returns:**
システム定義色を表すもの。

### hashCode {#hashCode--}
```
public int hashCode()
```

オブジェクトのハッシュコード値を返します。このメソッドは {@link java.util.HashMap} が提供するようなハッシュテーブルのためにサポートされています。<p> {@code hashCode} の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、オブジェクト上の {@code equals} 比較に使用される情報が変更されていない限り、{@code hashCode} メソッドは常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。 <li>二つのオブジェクトが {@code equals(Object)} メソッドで等しいと判断される場合、両方のオブジェクトで {@code hashCode} メソッドを呼び出すと同じ整数結果が得られなければなりません。 <li>二つのオブジェクトが {@link java.lang.Object#equals(java.lang.Object)} メソッドで等しくない場合でも、{@code hashCode} メソッドが異なる整数結果を返すことは <em>必ずしも</em> 必要ではありません。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があることをプログラマは認識すべきです。 </ul> <p> 実用的に可能な限り、クラス {@code Object} によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語では必須ではありません。）

**Returns:**
このオブジェクトのハッシュコード値。 @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
2つの Color が等しい場合に true を返します。

### op_Inequality {#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
2つの Color が等しくない場合に true を返します。

### parse {#parse-java.lang.String-}
文字列から色成分を抽出します。

### setPatternColorSpace {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
パターンのカラースペースを示すオブジェクトを設定します。内部使用のみ

### toRgb {#toRgb--}
```
public Color toRgb()
```

色を rgb に変換します。

**Returns:**
Rgb カラー値。

### toString {#toString--}
```
public String toString()
```

文字列に変換します。

**Returns:**
Color オブジェクトの文字列表現。
