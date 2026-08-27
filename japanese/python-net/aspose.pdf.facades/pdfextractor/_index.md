---
title: "PdfExtractor"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF ドキュメントから画像とテキストを抽出するクラスです。"
type: docs
weight: 210
url: /ja/python-net/aspose.pdf.facades/pdfextractor/
---

## PdfExtractor class

PDF ドキュメントから画像とテキストを抽出するクラスです。

PdfExtractor型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfExtractor() | 新しい[PdfExtractor](/pdf/python-net/aspose.pdf.facades/pdfextractor/)オブジェクトを初期化します。 |
| PdfExtractor(document) | PdfExtractorクラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
| start_page | 抽出操作が実行されるページ範囲内の開始ページを取得または設定します。 |
| end_page | 抽出操作が実行されるページ範囲内の終了ページを取得または設定します。 |
| extract_text_mode | 抽出テキストの結果のモードを設定します。 |
| text_search_options | テキスト検索オプションを取得または設定します。 |
| extract_image_mode | 画像抽出プロセスのモードを設定します。 |
| is_bidi | テキストにヘブライ語またはアラビア語の記号が含まれる場合に true になります。このケースは特別に考慮する必要があります。なぜなら<br/>            文字列関数が動作を変え、テキストの処理を右から左へ開始するからです（数字や<br/>            その他の非テキスト文字は除く）。 |
| resolution | 抽出された画像の解像度を設定または取得します。<br/>            デフォルト値は 150 です。<br/>            解像度が高い画像はより鮮明になります。<br/>            ただし、解像度を上げると画像抽出に必要な時間とメモリが増加します。<br/>            通常、鮮明な画像を得るには解像度を 150 または 300 に設定すれば十分です。 |
| password | 入力ファイルのパスワードを取得または設定します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(input_file) | 入力 PDF ファイルをバインドします。 |
| bind_pdf(input_stream) | ストリームから PDF ドキュメントをバインドします。 |
| bind_pdf(src_doc) | ファサードを初期化します。 |
| extract_text() | Unicode エンコーディングを使用して PDF ドキュメントからテキストを抽出します。 |
| extract_text(encoding) | 指定されたエンコーディングを使用して PDF ドキュメントからテキストを抽出します。 |
| get_text(output_file) | テキストをファイルに保存します。参照:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream) | テキストをストリームに保存します。参照:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream, filter_not_ascii) | テキストをストリームに保存します。参照:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_next_image(output_file) | PDF ドキュメントから次の画像を取得します。注: このメソッドを使用する前に ExtractImage を呼び出す必要があります。 |
| get_next_image(output_file, format) | 指定された画像形式で PDF ドキュメントから次の画像を取得します。注: このメソッドを使用する前に ExtractImage を呼び出す必要があります。 |
| get_next_image(output_stream, format) | PDF ファイルから次の画像を取得し、指定された画像形式でストリームに保存します。 |
| get_next_image(output_stream) | PDF ファイルから次の画像を取得し、指定された画像形式でストリームに保存します。 |
| extract_attachment() | PDF ドキュメントから添付ファイルを抽出します。 |
| extract_attachment(attachment_file_name) | 添付ファイル名で PDF ファイルから添付ファイルを抽出します。 |
| get_next_page_text(output_file) | 1 ページのテキストをファイルに保存します。 |
| get_next_page_text(output_stream) | 1 ページのテキストをストリームに保存します。 |
| close() | ファサードにバインドされた Aspose.Pdf.Document を破棄します。 |
| extract_image() | PDF ファイルから画像を抽出します。 |
| has_next_image() | PDF ドキュメントでさらに画像が取得可能か確認します。注: このメソッドを使用する前に ExtractImage を呼び出す必要があります。 |
| get_attach_names() | PDF ファイル内の添付ファイルのリストを返します。注: このメソッドを使用する前に ExtractAttachments を呼び出す必要があります。 |
| get_attachment(output_path) | 添付ファイルをファイルに保存します。 |
| has_next_page_text() | さらにテキストを取得できるかどうかを示します。 |
| get_attachment_info() | 添付ファイルの一覧を取得します。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

