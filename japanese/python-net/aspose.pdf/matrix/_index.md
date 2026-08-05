---
title: "Matrix"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "クラスは変換行列を表します。"
type: docs
weight: 900
url: /ja/python-net/aspose.pdf/matrix/
---

## Matrix class

クラスは変換行列を表します。

Matrix 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| Matrix() | コンストラクタ<br/>            標準的な 1 対 1 行列を作成します:<br/>            [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| Matrix(matrix_array) | Matrix クラスの新しいインスタンスを初期化します |
| Matrix(matrix_array) | Matrix クラスの新しいインスタンスを初期化します |
| Matrix(matrix) | Matrix クラスの新しいインスタンスを初期化します |
| Matrix(a, b, c, d, e, f) | Matrix クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| data | Matrix のデータを配列として取得します。 |
| a | 変換行列の A メンバーです。 |
| b | 変換行列の B メンバーです。 |
| c | 変換行列の C メンバーです。 |
| d | 変換行列の D メンバーです。 |
| e | 変換行列の E メンバーです。 |
| f | 変換行列の F メンバーです。 |
| 要素 | 行列の要素です。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| rotation(alpha) | 指定された回転角度の行列を作成します。 |
| rotation(rotation) | 指定された回転角度の行列を作成します。 |
| transform(p) | この行列を使用して点を変換します。 |
| transform(rect) | 矩形を変換します。<br/>            角度が 90 * N 度でない場合、バウンディング矩形が返されます。 |
| skew(alpha, beta) | 指定された回転角度の行列を作成します。 |
| get_angle(rotation) | 回転を角度（度）に変換します |
| multiply(other) | 行列を他の行列で乗算します。 |
| add(other) | 行列を他の行列に加算します。 |
| reverse() | 逆行列を計算します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

