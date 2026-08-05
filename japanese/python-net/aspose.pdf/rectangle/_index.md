---
title: "Rectangle"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "クラスは矩形を表します。"
type: docs
weight: 1320
url: /ja/python-net/aspose.pdf/rectangle/
---

## Rectangle class

クラスは矩形を表します。

Rectangle 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| Rectangle(llx, lly, urx, ury, normalize_coordinates) | Rectangle クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| width | 矩形の幅。 |
| height | 矩形の高さ。 |
| llx | 左下隅の X 座標。 |
| lly | 左下隅の Y 座標。 |
| urx | 右上隅の X 座標。 |
| ury | 右上隅の Y 座標。 |
| 自明 | 位置とサイズがゼロの、いわゆる自明な矩形を初期化します。 |
| is_trivial | 矩形が自明かどうか（サイズと位置がゼロか）をチェックします。 |
| is_empty | 矩形が空かどうかをチェックします。 |
| is_point | 矩形が点かどうか（LLX が URX と等しく、LLY が URY と等しいか）をチェックします。 |
| 空 | 空の矩形 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| rotate(angle) | 指定された角度で矩形を回転させます。 |
| rotate(angle) | 指定された角度で矩形を回転させます。 |
| to_rect() | 矩形を System.Drawing.Rectangle のインスタンスに変換します。浮動小数点の位置とサイズは切り捨てられます。 |
| from_rect(src) | 指定された System.Drawing.Rectangle のインスタンスから新しい矩形を初期化します。 |
| parse(value) | 文字列を解析し、矩形のコンポーネント llx、lly、urx、ury を抽出しようとします。 |
| equals(other) | 矩形が等しいか（位置とサイズが同じか）をチェックします。 |
| near_equals(other, delta) | 矩形がほぼ等しいかどうか、つまり位置とサイズがほぼ同じ（デルタまで）かを確認します。 |
| intersect(other_rect) | 矩形と交差します。 |
| join(other_rect) | 矩形を結合します。 |
| is_intersect(other_rect) | この矩形が他の矩形と交差するかどうかを判定します。 |
| contains(point) | 指定された点が矩形の内部にあるかどうかを判定します。 |
| center() | 矩形の中心座標を返します。 |
| clone() | Rectangle オブジェクトをクローンします。 |
| to_points() | 矩形をポイントの配列（"QuadPoints"）に変換します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

