---
title: "ParagraphAbsorber"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "セクションや段落などのページ構造オブジェクトの吸収オブジェクトを表します。<br/>テキストのセクションと段落を検索し、テキスト座標空間でそれを記述する矩形やポリゴンへのアクセスを提供します。<br/>また、テキストセグメントの検索を実行し、構造要素でグループ化された TextFragments コレクションを介して検索結果へのアクセスを提供します。"
type: docs
weight: 240
url: /ja/python-net/aspose.pdf.text/paragraphabsorber/
---

## ParagraphAbsorber class

セクションや段落などのページ構造オブジェクトの吸収オブジェクトを表します。<br/>テキストのセクションと段落を検索し、テキスト座標空間でそれを記述する矩形やポリゴンへのアクセスを提供します。<br/>また、テキストセグメントの検索を実行し、構造要素でグループ化された TextFragments コレクションを介して検索結果へのアクセスを提供します。

ParagraphAbsorber 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| ParagraphAbsorber() | ドキュメントまたはページのセクション/段落を検索する [ParagraphAbsorber](/pdf/python-net/aspose.pdf.text/paragraphabsorber/) の新しいインスタンスを初期化します。 |
| ParagraphAbsorber(sections_search_depth) | ParagraphAbsorber クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| page_markups | 吸収された [PageMarkup](/pdf/python-net/aspose.pdf.text/pagemarkup/) のコレクションを取得します。 |
| sections_search_depth | 構造のより細かい要素に対して順次検索を実行する回数を指示する値を取得または設定します。<br/>            デフォルトの検索深度は 3 です。<br/>            これは、水平に分割されたセクション（ヘッダー、段落など）に対して 3 回の検索を行い、垂直に分割されたセクション（列）に対しても 3 回の検索を行うことを意味します。 |
| is_multicolumn_paragraphs_allowed | 次のセクションの開始テキスト行が前のセクションの最後の段落の続きとして扱われるかどうかを示す値を取得または設定します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| visit(doc) | 指定された [Document](/pdf/python-net/aspose.pdf/document/) 上でセクションと段落の検索を実行します。 |
| visit(page) | 指定された [Page](/pdf/python-net/aspose.pdf/page/) 上で検索を実行します。 |

### 関連項目

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

