---
title: "PdfConverter"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF ファイルの各ページを画像に変換するクラスを表します。現在、BMP、JPEG、PNG、TIFF をサポートしています。<br/>            PDF の画像、フォーム、コメントをサポートします。"
type: docs
weight: 200
url: /ja/python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

PDF ファイルの各ページを画像に変換するクラスを表します。現在、BMP、JPEG、PNG、TIFF をサポートしています。<br/>            PDF のサポート対象コンテンツ：画像、フォーム、コメント。

PdfConverter 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfConverter() | 新しい [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/) オブジェクトを初期化します。 |
| PdfConverter(document) | PdfConverter クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
| coordinate_type | ページ座標タイプ（Media/Crop ボックス）を取得または設定します。デフォルトでは CropBox の値が使用されます。 |
| show_hidden_areas | ページ上の非表示領域の表示を制御するフラグを取得または設定します。 |
| rendering_options | レンダリングオプションを取得または設定します。 |
| form_presentation_mode | フォーム表示モードを取得または設定します。 |
| resolution | 変換中の解像度を取得または設定します。解像度が高いほど、変換速度は遅くなります。既定値は 150 です。 |
| start_page | 変換したい開始位置を取得または設定します。最小値は 1 です。 |
| end_page | 変換したい終了位置を取得または設定します。 |
| password | ドキュメントの OwnerPassword を取得または設定します。 |
| user_password | ドキュメントの UserPassword を取得または設定します。 |
| page_count | ページ数を取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(input_file) | 変換用に Pdf ファイルをバインドします。 |
| bind_pdf(input_stream) | 変換用に Pdf ストリームをバインドします。 |
| bind_pdf(src_doc) | ファサードを初期化します。 |
| save_as_tiff(output_file) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| save_as_tiff(output_file, compression_type) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| save_as_tiff(output_file, image_width, image_height) | PDF ドキュメントの各ページを寸法付きの画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| save_as_tiff(output_file, page_size) | PDF ドキュメントの各ページをページサイズの画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| save_as_tiff(output_file, page_size, settings) | PDF ドキュメントの各ページをページサイズの画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| save_as_tiff(output_file, image_width, image_height, compression_type) | PDF ドキュメントの各ページを寸法付きの画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| save_as_tiff(output_file, image_width, image_height, settings) | PDF ドキュメントの各ページを寸法付きの画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| save_as_tiff(output_file, image_width, image_height, settings, converter) | PDF ドキュメントの各ページを寸法付きの画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| save_as_tiff(output_stream) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。 |
| save_as_tiff(output_stream, compression_type) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| save_as_tiff(output_stream, page_size) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。 |
| save_as_tiff(output_stream, page_size, settings) | PDF ドキュメントの各ページをページサイズの画像に変換し、画像を単一の TIFF ストリームに保存します。 |
| save_as_tiff(output_stream, image_width, image_height) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。 |
| save_as_tiff(output_stream, image_width, image_height, compression_type) | PDF ドキュメントの各ページを寸法付きの画像に変換し、画像を単一の TIFF ストリームに保存します。 |
| save_as_tiff(output_stream, image_width, image_height, settings) | PDF ドキュメントの各ページを寸法付きの画像に変換し、画像を単一の TIFF ストリームに保存します。 |
| save_as_tiff(output_stream, image_width, image_height, settings, converter) | PDF ドキュメントの各ページを寸法付きの画像に変換し、画像を単一の TIFF ストリームに保存します。 |
| save_as_tiff(output_file, settings) | PDF ドキュメントの各ページをページサイズの画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| save_as_tiff(output_file, settings, converter) | PDF ドキュメントの各ページを寸法付きの画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| save_as_tiff(output_stream, settings) | PDF ドキュメントの各ページをページサイズの画像に変換し、画像を単一の TIFF ストリームに保存します。 |
| save_as_tiff(output_stream, settings, converter) | PDF ドキュメントの各ページを寸法付きの画像に変換し、画像を単一の TIFF ストリームに保存します。 |
| save_as_tiff_class_f(output_file, image_width, image_height) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。 |
| save_as_tiff_class_f(output_file, page_size) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。 |
| save_as_tiff_class_f(output_stream, image_width, image_height) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。 |
| save_as_tiff_class_f(output_stream, page_size) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。 |
| save_as_tiff_class_f(output_file) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。 |
| save_as_tiff_class_f(output_stream) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。 |
| get_next_image(output_file) | 画像をデフォルトの画像形式（jpeg）でファイルに保存します。 |
| get_next_image(output_file, page_size) | 指定されたページサイズで、デフォルトの画像形式（jpeg）で画像をファイルに保存します。 |
| get_next_image(output_file, format) | 指定された画像形式で画像をファイルに保存します。 |
| get_next_image(output_file, page_size, format) | 指定されたページサイズと画像形式で画像をファイルに保存します。 |
| get_next_image(output_stream) | 画像をデフォルトの画像形式（jpeg）でストリームに保存します。 |
| get_next_image(output_stream, page_size) | 指定されたページサイズで画像をストリームに保存します。 |
| get_next_image(output_stream, format) | 指定された画像形式で画像をストリームに保存します。 |
| get_next_image(output_stream, page_size, format) | 指定されたページサイズで画像をストリームに保存します。 |
| get_next_image(output_file, format, image_width, image_height, quality) | 指定された画像形式、サイズ、品質で画像をファイルに保存します。 |
| get_next_image(output_stream, format, image_width, image_height, quality) | 画像をストリームに保存します。指定された画像形式、寸法、および品質を使用します。 |
| get_next_image(output_file, format, image_width, image_height, quality) | 画像をファイルに保存します。指定された画像形式、画像サイズ、そして品質を使用します。 |
| get_next_image(output_stream, format, image_width, image_height, quality) | 画像をストリームに保存します。指定された画像形式、サイズ、そして品質を使用します。 |
| get_next_image(output_file, format, image_width, image_height) | 指定された画像形式、サイズ、品質で画像をファイルに保存します。 |
| get_next_image(output_stream, format, image_width, image_height) | 画像をストリームに保存します。指定された画像形式、寸法、および品質を使用します。 |
| get_next_image(output_stream, format, quality) | 画像をストリームに保存します。指定された画像形式、寸法、および品質を使用します。 |
| get_next_image(output_stream, page_size, format, quality) | 画像をストリームに保存します。指定されたページサイズ、画像形式、品質を使用します。 |
| get_next_image(output_file, format, quality) | 指定された画像形式、サイズ、品質で画像をファイルに保存します。 |
| get_next_image(output_file, page_size, format, quality) | 画像をファイルに保存します。指定されたページサイズ、画像形式、品質を使用します。 |
| close() | PdfConverter のインスタンスを閉じ、リソースを解放します。 |
| do_convert() | PDF ドキュメントを画像に変換するための初期作業を行います。 |
| has_next_image() | PDF ファイルにさらに画像があるかどうかを示します。 |
| merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical) | None |
| merge_images_as_tiff(input_images_streams) | 複数の TIFF ストリームのリストを 1 つのマルチフレーム TIFF ストリームに結合します。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

