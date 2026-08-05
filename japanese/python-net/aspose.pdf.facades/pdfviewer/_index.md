---
title: "PdfViewer"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "pdfを表示または印刷するクラスを表します。"
type: docs
weight: 370
url: /ja/python-net/aspose.pdf.facades/pdfviewer/
---

## PdfViewer class

pdfを表示または印刷するクラスを表します。

PdfViewer 型は以下のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfViewer() | 新しい [PdfViewer](/pdf/python-net/aspose.pdf.facades/pdfviewer/) オブジェクトを初期化します。 |
| PdfViewer(document) | PdfViewer クラスの新しいインスタンスを初期化します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| show_hidden_areas | ページ上の非表示領域の表示を制御するフラグを取得または設定します。 |
| print_status | 印刷ジョブの結果を取得します。成功した場合は null、そうでない場合は例外オブジェクトです。 |
| use_intermidiate_image | ファイルモードで印刷中に pdf ページを中間 PNG ファイルに変換する使用を取得/設定します。出力ファイルのサイズが重要な場合に使用してください。 |
| coordinate_type | ページ座標タイプ（Media/Crop ボックス）を取得または設定します。デフォルトでは CropBox の値が使用されます。 |
| print_as_image | PdfViewer が画像として印刷するモードを設定または取得します。 |
| page_count | 現在の Pdf ファイルのページ数を取得します。 |
| password | 入力ドキュメントのパスワードを取得または設定します。 |
| print_page_dialog | 印刷時にページ番号ダイアログを表示するかどうかを示す bool 値を取得または設定します。 |
| print_as_grayscale | ページがグレースケールで印刷されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。 |
| printer_job_name | ドキュメントが印刷される際のプリンターキュー内のドキュメント名を取得または設定します。デフォルト値はファイル名です。 |
| form_presentation_mode | フォーム表示モードを取得または設定します。 |
| rendering_options | レンダリングオプションを取得または設定します。 |
| vertical_alignment | 垂直方向の配置を示す値を取得または設定します |
| horizontal_alignment | 水平方向の配置を示す値を取得または設定します |
| auto_resize | ファイルが最適化されたサイズで印刷されるかどうかを示す bool 値を取得または設定します。 |
| auto_rotate | 自動回転でファイルが印刷されるかどうかを示す bool 値を取得または設定します |
| auto_rotate_mode | 回転方向を示す AutoRotateMode 値を取得または設定します |
| resolution | 表示および印刷時の解像度を取得または設定します。解像度が高いほど速度が遅くなります。デフォルト値は 150 です。 |
| scale_factor | スケール係数を示す浮動小数点値を取得または設定します。デフォルト値は 1.0 です。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| print_large_pdf(file_path) | 大きな Pdf ファイルを開いて印刷します。Pdf ファイルが数百ページ以上、またはサイズが <br/>             3 MB を超える場合、このメソッドの使用を推奨します。 |
| print_large_pdf(input_stream) | 大きな Pdf ストリームを開いて印刷します。Pdf ファイルが数百ページ以上、またはサイズが <br/>             3 MB を超える場合、このメソッドの使用を推奨します。 |
| print_large_pdf(file_path, printer_settings) | 指定されたプリンター設定で大きな Pdf ファイルを開いて印刷します。Pdf ファイルが数百ページ以上、<br/>             またはサイズが 3 MB を超える場合、このメソッドの使用を推奨します。 |
| print_large_pdf(input_stream, printer_settings) | 指定されたプリンター設定で大きな Pdf ストリームを開いて印刷します。Pdf ファイルが数百ページ以上、<br/>             またはサイズが 3 MB を超える場合、このメソッドの使用を推奨します。 |
| print_large_pdf(file_path, page_settings, printer_settings) | 指定されたページ設定とプリンター設定で大きな Pdf ファイルを開いて印刷します。Pdf <br/>             ファイルが数百ページ以上、またはサイズが 3 MB を超える場合、このメソッドの使用を <br/>             推奨します。 |
| print_large_pdf(input_stream, page_settings, printer_settings) | 指定されたページ設定とプリンター設定で大きな Pdf ストリームを開いて印刷します。Pdf <br/>             ファイルが数百ページ以上、またはサイズが 3 MB を超える場合、このメソッドの使用を <br/>             推奨します。 |
| print_document_with_settings(page_settings, printer_settings) | 設定を使用して Pdf ドキュメントを印刷します。ドキュメントのサイズがページサイズに合わない場合、pdf.kit がページサイズに合わせて拡張します。 |
| print_document_with_settings(printer_settings) | 設定を使用して Pdf ドキュメントを印刷します。ドキュメントのサイズがページサイズに合わない場合、pdf.kit がページサイズに合わせて拡張します。 |
| open_pdf_file(file_path) | Pdf ファイルを開きますが、実際には Pdf ファイルのページをデコードしません。 |
| open_pdf_file(input_stream) | Pdf ファイルストリームを開きます。ただし、実際には Pdf ファイルのページをデコードしません。 |
| bind_pdf(src_file) | ファサードを初期化します。 |
| bind_pdf(src_stream) | ファサードを初期化します。 |
| bind_pdf(src_doc) | ファサードを初期化します。 |
| save(dest_file) | 結果の PDF ドキュメントをファイルに保存します。 |
| save(dest_stream) | 結果の PDF ドキュメントをストリームに保存します。 |
| decode_all_pages() | 現在の pdf ファイルのページを取得します。 |
| decode_page(page_number) | Pdf ファイルのページをデコードします。 |
| print_document_with_setup() | 設定ダイアログを使用して Pdf ドキュメントを印刷します。ダイアログでプリンターを選択してください。 |
| print_document() | 設定ダイアログを使用して Pdf ドキュメントを印刷します。ダイアログでプリンターを選択してください。 |
| get_default_page_settings() | デフォルトのページ設定を取得します。 |
| get_default_printer_settings() | デフォルトのプリンター設定を取得します。 |
| close_pdf_file() | 現在の Pdf ファイルを閉じます。 |
| close() | 現在の Pdf ファイルを閉じます。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

