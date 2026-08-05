---
title: "TextSearchOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "テキスト検索オプションを表します"
type: docs
weight: 460
url: /ja/python-net/aspose.pdf.text/textsearchoptions/
---

## TextSearchOptions class

テキスト検索オプションを表します

TextSearchOptions 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| TextSearchOptions(is_regular_expression_used) | TextSearchOptions クラスの新しいインスタンスを初期化します |
| TextSearchOptions(rectangle) | TextSearchOptions クラスの新しいインスタンスを初期化します |
| TextSearchOptions(rectangle, is_regular_expression_used) | TextSearchOptions クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| is_regular_expression_used | 正規表現が使用されているかどうかの指示を取得または設定します。 |
| limit_to_page_bounds | テキストがページ境界内で検索されるかどうかの指示を取得または設定します。 |
| rectangle | 検索対象テキストを囲む矩形を取得または設定します。 |
| use_font_engine_encoding | テキストがフォントエンジンのエンコーディングを使用して検索されるかどうかの指示を取得または設定します。<br/>            true - フォントエンジンのエンコーディングが使用されることを意味します（文書のエンコーディングが不完全で検索が失敗する場合に試してください）<br/>            false - 文書のフォントエンコーディングが使用されることを意味します（既定値） |
| ignore_shadow_text | 検索時に通常テキストの影を表すテキストフラグメントを無視するかどうかの指示を取得または設定します。<br/>            true - 影のテキストが見つからないことを意味します（検索結果が近接位置で重複フラグメントになる場合に試してください）<br/>            false - 影のテキストも通常テキストと同様に検出されることを意味します（既定値） |
| log_text_extraction_errors | テキスト（フラグメント）吸収器でテキスト抽出（デコード）エラーが記録されるかどうかの指示を取得または設定します。<br/>            true - テキスト抽出（デコード）エラーが記録されることを意味します。パフォーマンスが低下する可能性があります。<br/>            false（既定） - エラーは記録されません。 |
| ignore_resource_font_errors | テキスト（フラグメント）吸収器でフォントが存在しないことに関連するエラーを無視するかどうかの指示を取得または設定します。<br/>            true - フォントが存在しないエラーが無視されることを意味します。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。<br/>            false（既定） - フォントが存在しないエラーが例外をスローして処理を終了させます。 |
| search_for_text_related_graphics | テキスト検索中にテキスト関連のグラフィック（下線、背景など）を検索できるかどうかの値を取得または設定します。<br/>            true - テキスト関連のグラフィックの検索が実行されます（既定値）。<br/>            false - ソース文書に存在する可能性のあるグラフィック要素が無視されます。パフォーマンス上の問題がある場合や、下線・背景・クリッピングを処理する必要がない場合に設定してください。 |
| stored_graphic_elements_max_count | ページ上でテキスト関連のグラフィック（下線、背景など）を検索する要素数を制限する値を取得または設定します。<br/>            デフォルトは 250 です。パフォーマンスに問題がある場合は小さい値を設定し、グラフィック要素が見つからない場合は大きい値を試してください。 |
| search_in_annotations | アノテーション内のテキストを検索できるかどうかの値を取得または設定します。<br/>            true - アノテーション内のテキストが検索されます。<br/>            false - アノテーション内のテキストは TextFragmentAbsorber によって解析されません。 |

### 関連項目

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

