---
title: "TextFragmentAbsorber"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "テキストフラグメントの吸収オブジェクトを表します。<br/>テキスト検索を実行し、[text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) コレクションを介して検索結果へのアクセスを提供します。"
type: docs
weight: 400
url: /ja/python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

テキストフラグメントの吸収オブジェクトを表します。<br/>テキスト検索を実行し、[text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) コレクションを介して検索結果へのアクセスを提供します。

TextFragmentAbsorber 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| TextFragmentAbsorber() | ドキュメントまたはページのすべてのテキストセグメントの検索を実行する [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) の新しいインスタンスを初期化します。 |
| TextFragmentAbsorber(text_edit_options) | TextFragmentAbsorber クラスの新しいインスタンスを初期化します |
| TextFragmentAbsorber(phrase) | TextFragmentAbsorber クラスの新しいインスタンスを初期化します |
| TextFragmentAbsorber(phrase, text_search_options) | TextFragmentAbsorber クラスの新しいインスタンスを初期化します |
| TextFragmentAbsorber(phrase, text_search_options, text_edit_options) | TextFragmentAbsorber クラスの新しいインスタンスを初期化します |
| TextFragmentAbsorber(phrase, text_edit_options) | TextFragmentAbsorber クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| text | PDF ドキュメントまたはページから、[TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) が抽出したテキストを取得します。 |
| has_errors | この値はテキスト抽出中にエラーが見つかったかどうかを示します。<br/>            エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。 |
| errors | [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/) オブジェクトのリストです。テキスト抽出中に見つかったエラーに関する情報が含まれています。<br/>            エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。 |
| extraction_options | テキスト抽出オプションを取得または設定します。 |
| text_search_options | 検索オプションを取得または設定します。このオプションにより正規表現を使用した検索が可能になります。 |
| text_fragments | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) オブジェクトで表される検索結果のコレクションを取得します。 |
| phrase | [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) が PDF ドキュメントまたはページで検索するフレーズを取得または設定します。 |
| text_edit_options | テキスト編集オプションを取得または設定します。オプションは、要求されたシンボルがフォントで表現できない場合の特別な動作を定義します。 |
| text_replace_options | テキスト置換オプションを取得または設定します。オプションは、フラグメントテキストがより短くまたは長く置換される際の動作を定義します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| visit(page) | 指定されたページで検索を実行します。 |
| visit(pdf) | 指定されたドキュメントで検索を実行します。 |
| visit(x_form) | 指定されたフォームオブジェクトで検索を実行します。 |
| apply_for_all_fragments(font) | 吸収されたすべてのテキストフラグメントにフォントを適用します。ページ上のすべてのフラグメントが吸収されている場合、フラグメントをループ処理するよりも高速に動作します。そうでない場合は、ループ処理と同様に動作します。 |
| apply_for_all_fragments(font_size) | 吸収されたすべてのテキストフラグメントにフォントサイズを適用します。ページ上のすべてのフラグメントが吸収されている場合、フラグメントをループ処理するよりも高速に動作します。そうでない場合は、ループ処理と同様に動作します。 |
| apply_for_all_fragments(font, font_size) | 吸収されたすべてのテキストフラグメントにフォントとサイズを適用します。ページ上のすべてのフラグメントが吸収されている場合、フラグメントをループ処理するよりも高速に動作します。そうでない場合は、ループ処理と同様に動作します。 |
| remove_all_text(page) | 指定されたページからすべてのテキストを削除します。 |
| remove_all_text(page, rect) | 指定されたページの指定された矩形内のテキストを削除します。 |
| remove_all_text(document) | ドキュメントからすべてのテキストを削除します。 |
| reset() | この [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) オブジェクトの TextFragments コレクションをクリアします。 |

### 関連項目

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

