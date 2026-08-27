---
title: "Matrix3D クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Matrix3D クラス。変換行列を表すクラスです"
type: docs
weight: 7070
url: /ja/net/aspose.pdf/matrix3d/
---
## Matrix3D class

クラスは変換行列を表します。

```csharp
public sealed class Matrix3D
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Matrix3D](matrix3d/#constructor)() | コンストラクタは標準の 1 対 1 行列を作成します: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] |
| [Matrix3D](matrix3d/#constructor_3)(double[]) | コンストラクタは次の配列表現の行列を受け取ります: [ A B C D E F G H I Tx Ty Tz] |
| [Matrix3D](matrix3d/#constructor_1)(Matrix3D) | コンストラクタはコピーを作成するための行列を受け取ります |
| [Matrix3D](matrix3d/#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double) | 指定された係数で変換行列を初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [A](../../aspose.pdf/matrix3d/a/) { get; set; } | 変換行列の A メンバーです。 |
| [B](../../aspose.pdf/matrix3d/b/) { get; set; } | 変換行列の B メンバーです。 |
| [C](../../aspose.pdf/matrix3d/c/) { get; set; } | 変換行列の C メンバーです。 |
| [D](../../aspose.pdf/matrix3d/d/) { get; set; } | 変換行列の D メンバーです。 |
| [E](../../aspose.pdf/matrix3d/e/) { get; set; } | 変換行列の E メンバーです。 |
| [F](../../aspose.pdf/matrix3d/f/) { get; set; } | 変換行列の F メンバーです。 |
| [G](../../aspose.pdf/matrix3d/g/) { get; set; } | 変換行列の G 成分です。 |
| [H](../../aspose.pdf/matrix3d/h/) { get; set; } | 変換行列の H 成分です。 |
| [I](../../aspose.pdf/matrix3d/i/) { get; set; } | 変換行列の I 成分です。 |
| [Tx](../../aspose.pdf/matrix3d/tx/) { get; set; } | 変換行列の Tx 成分です。 |
| [Ty](../../aspose.pdf/matrix3d/ty/) { get; set; } | 変換行列の Ty 成分です。 |
| [Tz](../../aspose.pdf/matrix3d/tz/) { get; set; } | 変換行列の Tz 成分です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf/matrix3d/add/)(Matrix3D) | Matrix を別の Matrix に加算します。 |
| override [Equals](../../aspose.pdf/matrix3d/equals/)(object) | 行列を他のオブジェクトと比較します。 |
| override [GetHashCode](../../aspose.pdf/matrix3d/gethashcode/)() | オブジェクトのハッシュコードです。 |
| override [ToString](../../aspose.pdf/matrix3d/tostring/)() | 行列のテキスト表現を返します。 |
| static [GetAngle](../../aspose.pdf/matrix3d/getangle/)(Rotation) | 回転を角度（度）に変換します |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


