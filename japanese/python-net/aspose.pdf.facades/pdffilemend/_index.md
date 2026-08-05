---
title: "PdfFileMend"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "既存の PDF ドキュメントのページにテキストと画像を追加するクラスを表します。"
type: docs
weight: 280
url: /ja/python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

既存の PDF ドキュメントのページにテキストと画像を追加するクラスを表します。

PdfFileMend 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfFileMend() | コンストラクタ。 |
| PdfFileMend(input_file_name, output_file_name) | PdfFileMend クラスの新しいインスタンスを初期化します |
| PdfFileMend(input_stream, output_stream) | PdfFileMend クラスの新しいインスタンスを初期化します |
| PdfFileMend(document) | PdfFileMend クラスの新しいインスタンスを初期化します |
| PdfFileMend(document, output_file_name) | PdfFileMend クラスの新しいインスタンスを初期化します |
| PdfFileMend(document, dest_stream) | PdfFileMend クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
| input_stream | 入力ストリームを設定します。 |
| output_stream | 出力ストリームを設定します。 |
| input_file | 入力ファイルを設定します。 |
| output_file | 出力ファイルを設定します。 |
| wrap_mode | 単語折り返しアルゴリズムを設定または取得します。WordWrapMode と IsWordWrap を参照してください。 |
| text_positioning_mode | テキスト配置戦略を設定または取得します。[PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            デフォルトモードは Legacy です。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(src_file) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_stream) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_doc) | PDF ドキュメントを編集用にバインドします。 |
| save(dest_file) | 指定されたファイルに PDF ドキュメントを保存します。 |
| save(dest_stream) | 指定されたストリームに PDF ドキュメントを保存します。 |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 指定された座標で PDF ドキュメントの指定されたページに画像を追加します。 |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | 指定された座標で PDF ドキュメントの指定されたページに画像を追加します。 |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | 指定された座標で PDF ドキュメントの指定ページに画像を追加します。 |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 指定された座標で PDF ドキュメントの指定されたページに画像を追加します。 |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | 指定された座標で PDF ドキュメントの指定されたページに画像を追加します。 |
| add_text(text, page_num, lower_left_x, lower_left_y) | 未実装です。 |
| add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 未実装です。 |
| add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 未実装です。 |
| close() | PdfFileMend オブジェクトを閉じます。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

