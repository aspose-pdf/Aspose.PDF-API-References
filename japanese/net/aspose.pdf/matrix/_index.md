---
title: Class Matrix
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Matrix クラス。クラスは変換マトリックスを表します
type: docs
weight: 6920
url: /ja/net/aspose.pdf/matrix/
---
## マトリックス クラス

クラスは変換マトリックスを表します。

```csharp
public sealed class Matrix
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Matrix](matrix/#constructor)() | コンストラクタは標準の 1 対 1 マトリックスを作成します: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | コンストラクタは次の配列表現を持つマトリックスを受け入れます: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | コンストラクタは次の配列表現を持つマトリックスを受け入れます: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | コンストラクタはコピーを作成するためにマトリックスを受け入れます |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | 指定された係数で変換マトリックスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | 変換マトリックスの A メンバー。 |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | 変換マトリックスの B メンバー。 |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | 変換マトリックスの C メンバー。 |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | 変換マトリックスの D メンバー。 |
| [Data](../../aspose.pdf/matrix/data/) { get; } | マトリックスのデータを配列として取得します。 |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | 変換マトリックスの E メンバー。 |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | マトリックスの要素。 |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | 変換マトリックスの F メンバー。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | 指定された回転角度のマトリックスを作成します。 |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | 指定された回転のマトリックスを作成します。 |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | 指定されたマトリックスにスケーリングを適用します。 |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | 指定された回転角度のマトリックスを作成します。 |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | 指定された量だけ x および y 方向にマトリックスを移動します。 |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | 他のマトリックスにマトリックスを追加します。 |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | マトリックスを他のオブジェクトと比較します。 |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | フリッピングマトリックスを取得します。 |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | オブジェクトのハッシュコード。 |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | マトリックスを他のマトリックスで乗算します。 |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | 逆マトリックスを計算します。 |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | 次の式を使用してマトリックスで x と y をスケーリングします: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | マトリックスのテキスト表現を返します。 |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | このマトリックスを使用して点を変換します。 |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | 矩形を変換します。角度が 90 * N 度でない場合、バウンディング矩形が返されます。 |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | このマトリックスを使用して座標を変換します。 |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | x1 と y1 を元に戻し、次の式を使用してマトリックス変換前の x と y を返します: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | x1 と y1 を元に戻し、次の式を使用してマトリックス変換前の x と y を返します: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B)。 |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | 回転を角度 (度) に変換します。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)