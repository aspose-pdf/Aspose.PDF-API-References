---
title: Class Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Matrix3D クラス。クラスは変換行列を表します
type: docs
weight: 6930
url: /ja/net/aspose.pdf/matrix3d/
---
## Matrix3D クラス

クラスは変換行列を表します。

```csharp
public sealed class Matrix3D
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Matrix3D](matrix3d/#constructor)() | コンストラクタは標準の1対1の行列を作成します: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] |
| [Matrix3D](matrix3d/#constructor_3)(double[]) | コンストラクタは次の配列表現を持つ行列を受け入れます: [ A B C D E F G H I Tx Ty Tz] |
| [Matrix3D](matrix3d/#constructor_1)(Matrix3D) | コンストラクタはコピーを作成するために行列を受け入れます |
| [Matrix3D](matrix3d/#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double) | 指定された係数で変換行列を初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [A](../../aspose.pdf/matrix3d/a/) { get; set; } | 変換行列のAメンバー。 |
| [B](../../aspose.pdf/matrix3d/b/) { get; set; } | 変換行列のBメンバー。 |
| [C](../../aspose.pdf/matrix3d/c/) { get; set; } | 変換行列のCメンバー。 |
| [D](../../aspose.pdf/matrix3d/d/) { get; set; } | 変換行列のDメンバー。 |
| [E](../../aspose.pdf/matrix3d/e/) { get; set; } | 変換行列のEメンバー。 |
| [F](../../aspose.pdf/matrix3d/f/) { get; set; } | 変換行列のFメンバー。 |
| [G](../../aspose.pdf/matrix3d/g/) { get; set; } | 変換行列のGメンバー。 |
| [H](../../aspose.pdf/matrix3d/h/) { get; set; } | 変換行列のHメンバー。 |
| [I](../../aspose.pdf/matrix3d/i/) { get; set; } | 変換行列のIメンバー。 |
| [Tx](../../aspose.pdf/matrix3d/tx/) { get; set; } | 変換行列のTxメンバー。 |
| [Ty](../../aspose.pdf/matrix3d/ty/) { get; set; } | 変換行列のTyメンバー。 |
| [Tz](../../aspose.pdf/matrix3d/tz/) { get; set; } | 変換行列のTzメンバー。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf/matrix3d/add/)(Matrix3D) | 行列を他の行列に加えます。 |
| override [Equals](../../aspose.pdf/matrix3d/equals/)(object) | 行列を他のオブジェクトと比較します。 |
| override [GetHashCode](../../aspose.pdf/matrix3d/gethashcode/)() | オブジェクトのハッシュコード。 |
| override [ToString](../../aspose.pdf/matrix3d/tostring/)() | 行列のテキスト表現を返します。 |
| static [GetAngle](../../aspose.pdf/matrix3d/getangle/)(Rotation) | 回転を角度（度）に変換します |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)