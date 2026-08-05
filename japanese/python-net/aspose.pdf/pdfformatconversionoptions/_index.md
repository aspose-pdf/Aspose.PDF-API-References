---
title: "PdfFormatConversionOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF 文書を変換するためのオプションセットを表します。"
type: docs
weight: 1220
url: /ja/python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

PDF 文書を変換するためのオプションセットを表します。

PdfFormatConversionOptions 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfFormatConversionOptions(output_log_file_name, format, action) | PdfFormatConversionOptions クラスの新しいインスタンスを初期化します |
| PdfFormatConversionOptions(output_log_file_name, format) | PdfFormatConversionOptions クラスの新しいインスタンスを初期化します |
| PdfFormatConversionOptions(format) | PdfFormatConversionOptions クラスの新しいインスタンスを初期化します |
| PdfFormatConversionOptions(format, action) | PdfFormatConversionOptions クラスの新しいインスタンスを初期化します |
| PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action) | PdfFormatConversionOptions クラスの新しいインスタンスを初期化します |
| PdfFormatConversionOptions(output_log_stream, format, action) | PdfFormatConversionOptions クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| is_async_image_streams_conversion_mode | 非同期モードで画像ストリームの実行を取得/設定します。 |
| is_low_memory_mode | 低メモリ変換モードが有効かどうか |
| format | PDF フォーマット。 |
| log_file_name | コメントが保存されるファイルへのパス。 |
| log_stream | コメントが保存されるストリーム。 |
| error_action | 変換できないオブジェクトに対するアクション |
| transparency_action | 画像マスクされたオブジェクトに対するアクション |
| convert_soft_mask_action | ソフトマスク付き画像に対するアクション。 |
| デフォルト | デフォルトパラメータで PdfFormatConversionOptions オブジェクトを取得します |
| non_specification_cases | ソース文書が PDF/A 仕様に合致しないケースにおける PDF/A 変換プロセスを制御するフラグを保持します。<br/>             |
| symbolic_font_encoding_strategy | シンボリック TrueType フォントが複数のエンコーディングサブテーブルを持つ場合に、<br/>            シンボリックフォントのエンコーディングデータをコピーする戦略です。 |
| align_text | このフラグは変換されたドキュメントのテキスト配置を制御します。デフォルトでは、ドキュメント変換 <br/>            テキスト配置に影響せず、テキストはそのまま残ります。ですが、フォント置換が原因で<br/>            変換されたドキュメントでテキストが重なったり余分なスペースが入ったりすることがあります。このフラグが設定されると<br/>            特別な配置操作が実行されます。このフラグは、テキストが重なっている、または余分なスペースがあるドキュメントにのみ設定すべきです。フラグの使用はパフォーマンスを低下させ、場合によってはテキスト内容が破損する可能性があります。 |
| pua_text_processing_strategy | Unicode Private Use Area (PUA) のシンボルを処理する戦略。 |
| optimize_file_size | PDF/A ドキュメントのファイルサイズを削減するための特別な変換モードを有効化/無効化するフラグを取得または設定します。<br/>            現在、このフラグは PDF ドキュメントで使用されるフォントの最適化に影響し、将来的にはこのフラグ <br/>            がグラフィックなどの他のデータ構造の最適化をオンにするためにも使用される可能性があります。  <br/>            このフラグとモードの組み合わせはファイルサイズを大幅に削減できますが、同時に変換のパフォーマンスを<br/>            大幅に低下させる可能性があります。 |
| exclude_fonts_strategy | 余分なフォントを除外し、ドキュメントのファイルサイズを削減する戦略（複数可）。 <br/>            このパラメータはフラグ [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) が true に設定されている場合にのみ意味があります。<br/>            デフォルトでは、戦略の組み合わせとして [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) と<br/>            [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) が使用されます。 |
| font_embedding_options | PDF ドキュメントに一部のフォントを埋め込めない場合のオプション。 |
| unicode_processing_rules | Unicode マッピングの問題を解決するためのルール。null に設定可能です。 |
| icc_profile_file_name | ICC プロファイル名のファイル名を取得または設定します。null の場合はデフォルトの ICC プロファイルが使用されます。 |
| not_accessible_fonts | このプロパティは出力プロパティです。コンピュータ上で見つからなかったすべてのフォント（フォント名）を保持します <br/>            最後の PDF/A 変換時に。 |
| is_transfer_info | PDF 2.0 に変換する際に Info から Metadata へデータを渡すかどうかを取得または設定します。デフォルトは true です。 |
| align_strategy | テキストを配置する戦略。このパラメータはフラグ [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) が true に設定されている場合にのみ意味があります。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

