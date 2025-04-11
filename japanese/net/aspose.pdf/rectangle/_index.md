---
title: Class Rectangle
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Rectangle クラス。クラスは矩形を表します
type: docs
weight: 9750
url: /ja/net/aspose.pdf/rectangle/
---
## Rectangle クラス

クラスは矩形を表します。

```csharp
public sealed class Rectangle : ICloneable
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Rectangle のコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | 空の矩形 |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | トリビアルな矩形を初期化します。すなわち、位置とサイズがゼロの矩形。 |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | 矩形の高さ。 |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | 矩形が空かどうかをチェックします。 |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | 矩形が点かどうかをチェックします。すなわち、LLX が URX と等しく、LLY が URY と等しい。 |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | 矩形がトリビアルかどうかをチェックします。すなわち、サイズと位置がゼロである。 |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | 左下隅の X 座標。 |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | 左下隅の Y 座標。 |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | 右上隅の X 座標。 |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | 右上隅の Y 座標。 |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | 矩形の幅。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | 指定された System.Drawing.Rectangle のインスタンスから新しい矩形を初期化します。 |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | 指定された System.Drawing.Rectangle のインスタンスから新しい矩形を初期化します。 |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | 文字列を解析し、矩形のコンポーネント llx, lly, urx, ury を抽出しようとします。 |
| [Center](../../aspose.pdf/rectangle/center/)() | 矩形の中心の座標を返します。 |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Rectangle オブジェクトをクローンします。 |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | 指定された点が矩形内にあるかどうかを判断します。 |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | 矩形が二つの点で表される線を含むかどうかを判断します。 |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | 指定された点が矩形内に含まれているかどうかを判断します。 |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | 矩形が等しいかどうかをチェックします。すなわち、同じ位置とサイズを持つ。 |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | 矩形を交差させます。 |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | この矩形が他の矩形と交差するかどうかを判断します。 |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | 矩形を結合します。 |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | 指定されたデルタによって矩形を移動します。 |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | 矩形が近似等しいかどうかをチェックします。すなわち、ほぼ同じ（デルタまで）位置とサイズを持つ。 |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | 指定された角度で矩形を回転させます。 |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | 指定された角度で矩形を回転させます。 |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | 矩形を点の配列（"QuadPoints"）に変換します。 |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | 矩形を System.Drawing.Rectangle のインスタンスに変換します。浮動小数点の位置とサイズは切り捨てられます。 |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | 矩形の文字列表現を取得します。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)