---
title: "Rectangle クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Rectangle クラス。クラスは矩形を表します。"
type: docs
weight: 9900
url: /ja/net/aspose.pdf/rectangle/
---
## Rectangle class

矩形を表すクラスです。

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
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | 空の Rectangle |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | 位置とサイズがゼロの単純な Rectangle を初期化します。 |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Rectangle の高さ。 |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Rectangle が空かどうかをチェックします。 |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Rectangle が点かどうかをチェックします。すなわち LLX が URX と等しく、LLY が URY と等しい場合です。 |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Rectangle が単純かどうかをチェックします。すなわちサイズと位置がゼロの場合です。 |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | 左下隅の X 座標。 |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | 左下隅の Y 座標。 |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | 右上隅の X 座標。 |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | 右上隅の Y 座標。 |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Rectangle の幅。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | 指定された System.Drawing.Rectangle インスタンスから新しい Rectangle を初期化します。 |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | 指定された System.Drawing.Rectangle インスタンスから新しい Rectangle を初期化します。 |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | 文字列を解析し、そこから llx、lly、urx、ury の Rectangle コンポーネントを抽出しようとします。 |
| [Center](../../aspose.pdf/rectangle/center/)() | Rectangle の中心座標を返します。 |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Rectangle オブジェクトをクローンします。 |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | 指定された点が Rectangle の内部にあるかどうかを判定します。 |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Rectangle が二点で表される線分を含むかどうかを判定します。 |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | 指定された点が Rectangle 内に含まれているかどうかを判定します。 |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Rectangle が等しいかどうかをチェックします。すなわち同じ位置とサイズを持つかどうかです。 |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | Rectangle 同士が交差します。 |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | この Rectangle が他の Rectangle と交差するかどうかを判定します。 |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Rectangle を結合します。 |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | 指定されたデルタで Rectangle をシフトします。 |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Rectangle がほぼ等しいかどうかをチェックします。すなわちデルタ以内でほぼ同じ位置とサイズを持つかどうかです。 |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | 指定された角度で矩形を回転させます。 |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | 指定された角度で矩形を回転させます。 |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | 矩形をポイントの配列（"QuadPoints"）に変換します。 |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | 矩形を System.Drawing.Rectangle のインスタンスに変換します。小数点以下の位置とサイズは切り捨てられます。 |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | 矩形の文字列表現を取得します。 |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


