---
title: "TextAbsorber"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "テキストの吸収オブジェクトを表します。<br/>テキスト抽出を実行し、[text](/pdf/python-net/aspose.pdf.text/textabsorber/) オブジェクトを介して結果へのアクセスを提供します。"
type: docs
weight: 320
url: /ja/python-net/aspose.pdf.text/textabsorber/
---

## TextAbsorber class

テキストの吸収オブジェクトを表します。<br/>テキスト抽出を実行し、[text](/pdf/python-net/aspose.pdf.text/textabsorber/) オブジェクトを介して結果へのアクセスを提供します。

TextAbsorber 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| TextAbsorber() | 新しい [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) のインスタンスを初期化します。 |
| TextAbsorber(extraction_options) | TextAbsorber クラスの新しいインスタンスを初期化します |
| TextAbsorber(extraction_options, text_search_options) | TextAbsorber クラスの新しいインスタンスを初期化します |
| TextAbsorber(text_search_options) | TextAbsorber クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| text | PDF ドキュメントまたはページから、[TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) が抽出したテキストを取得します。 |
| has_errors | この値はテキスト抽出中にエラーが見つかったかどうかを示します。<br/>            エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。 |
| errors | [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/) オブジェクトのリストです。テキスト抽出中に見つかったエラーに関する情報が含まれています。<br/>            エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。 |
| extraction_options | テキスト抽出オプションを取得または設定します。 |
| text_search_options | テキスト検索オプションを取得または設定します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| visit(page) | 指定されたページのテキストを抽出します |
| visit(form) | 指定された XForm のテキストを抽出します。 |
| visit(pdf) | 指定されたドキュメントのテキストを抽出します |

### 関連項目

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

