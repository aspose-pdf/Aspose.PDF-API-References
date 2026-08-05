---
title: "OperatorCollection"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "クラスは演算子のコレクションを表します"
type: docs
weight: 1010
url: /ja/python-net/aspose.pdf/operatorcollection/
---

## OperatorCollection class

クラスは演算子のコレクションを表します

OperatorCollection 型は次のメンバーを公開します：
## プロパティ
| 名前 | 説明 |
| :- | :- |
| is_fast_text_extraction_mode | コレクションが高速テキスト抽出に限定されているかどうかを示します |
## Indexer
| 名前 | 説明 |
| :- | :- |
| [index] | インデックスで演算子を取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| insert(index, op) | 演算子をコレクションに挿入します。 |
| insert(at, ops) | 指定された位置に演算子を挿入します。 |
| insert(at, ops) | 演算子をコレクションに挿入します。 |
| delete(index) | コレクションから演算子を削除します。 |
| delete(ops) | コレクションから演算子を削除します。 |
| delete(list) | None |
| add(ops) | コンテンツ演算子の末尾に演算子を追加します。 |
| add(ops) | 新しい演算子をコレクションに追加します。 |
| suppress_update() | コンテンツデータの更新を抑制します。<br/>            ResumeUpdate が呼び出されるまでコンテンツストリームは更新されません。 |
| resume_update() | ドキュメントの更新を再開します。<br/>            保留中の変更がある場合、コンテンツストリームを更新します。 |
| cancel_update() | 最後の更新をキャンセルします。<br/>            変更がコンテンツの更新を引き起こさない場合にこのメソッドを呼び出すことができます。 |
| accept(visitor) | 演算子を処理するための IOperatorSelector ビジターオブジェクトを受け入れます。 |
| replace(operators) | コレクション内の演算子を別の演算子に置き換えます。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

