---
title: "SetDash"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "線の破線パターンを設定する d 演算子を表すクラス。"
type: docs
weight: 580
url: /ja/python-net/aspose.pdf.operators/setdash/
---

## SetDash class

線の破線パターンを設定する d 演算子を表すクラス。

SetDash 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| SetDash(pattern, phase) | SetDash クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| index | ページの演算子リストにおける演算子インデックス。 |
| パターン | ダッシュパターン。配列の要素は、交互のダッシュとギャップの長さを指定する数値でなければなりません。<br/>            要素が1つだけの配列の場合、ダッシュとギャップの長さは同じになります。 |
| フェーズ | ダッシュフェーズ。パスの描画を開始する前に、ダッシュ配列を循環させて、ダッシュとギャップの長さを合計します。<br/>            合計長さがダッシュフェーズで指定された値に等しくなると、パスの描画が開始され、<br/>            その時点からダッシュ配列は循環的に使用されます。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| accept(visitor) | 演算子を処理するためにビジターオブジェクトを受け入れます。 |
| is_text_show_operator(op) | 演算子がテキスト出力（Tj、TJ など）を担当するかどうかを判定します。 |

### 関連項目

* namespace [aspose.pdf.operators](/pdf/python-net/aspose.pdf.operators/)
* assembly [Aspose.PDF](/pdf/python-net/)

