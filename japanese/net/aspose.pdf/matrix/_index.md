---
title: "クラス Matrix"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Matrix クラス。クラスは変換行列を表します。"
type: docs
weight: 7060
url: /ja/net/aspose.pdf/matrix/
---
## Matrix class

クラスは変換行列を表します。

```csharp
public sealed class Matrix
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Matrix](matrix/#constructor)() | コンストラクタは標準の 1 対 1 行列を作成します: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | コンストラクタは次の配列表現の行列を受け取ります: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | コンストラクタは次の配列表現の行列を受け取ります: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | コンストラクタはコピーを作成するための行列を受け取ります |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | 指定された係数で変換行列を初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | 変換行列の A メンバーです。 |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | 変換行列の B メンバーです。 |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | 変換行列の C メンバーです。 |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | 変換行列の D メンバーです。 |
| [Data](../../aspose.pdf/matrix/data/) { get; } | Matrix のデータを配列として取得します。 |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | 変換行列の E メンバーです。 |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Matrix の要素です。 |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | 変換行列の F メンバーです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | 指定された回転角度の Matrix を作成します。 |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | 指定された回転の Matrix を作成します。 |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | 指定された Matrix にスケーリングを適用します。 |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | 指定された回転角度の Matrix を作成します。 |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | 指定された量で Matrix を x および y 方向に平行移動します。 |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | Matrix を別の Matrix に加算します。 |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | Matrix を他のオブジェクトと比較します。 |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | 反転 Matrix を取得します。 |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | オブジェクトのハッシュコードです。 |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | 行列を他の行列で乗算します。 |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | 逆行列を計算します。 |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | 次の式を使用して行列で x と y をスケーリングします: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | 行列のテキスト表現を返します。 |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | この行列を使用して点を変換します。 |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | 矩形を変換します。角度が 90 * N 度でない場合、バウンディング矩形が返されます。 |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | この行列を使用して座標を変換します。 |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | 次の式を使用して x1 と y1 を元に戻し、行列変換前の x と y を返します: x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | 次の式を使用して x1 と y1 を逆変換し、行列変換前の x と y を返します: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B)。 |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | 回転を角度（度）に変換します。 |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


