---
title: "BaseOperatorCollection"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "演算子コレクションの基底クラスを表します。"
type: docs
weight: 70
url: /ja/python-net/aspose.pdf/baseoperatorcollection/
---

## BaseOperatorCollection class

演算子コレクションの基底クラスを表します。

BaseOperatorCollection 型は次のメンバーを公開します：
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
| suppress_update() | コンテンツデータの更新を抑制します。<br/>            ResumeUpdate が呼び出されるまでコンテンツストリームは更新されません。 |
| resume_update() | ドキュメントの更新を再開します。<br/>            保留中の変更がある場合、コンテンツストリームを更新します。 |
| insert(index, op) | 演算子をコレクションに挿入します。 |
| cancel_update() | 最後の更新をキャンセルします。<br/>            変更がコンテンツの更新を引き起こさない場合にこのメソッドを呼び出すことができます。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

