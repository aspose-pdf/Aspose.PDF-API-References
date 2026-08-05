---
title: "PdfContentEditor"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF ファイルのコンテンツを編集するクラスを表します。"
type: docs
weight: 190
url: /ja/python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

PDF ファイルのコンテンツを編集するクラスを表します。

PdfContentEditor 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfContentEditor() | PdfContentEditor オブジェクトのコンストラクタです。 |
| PdfContentEditor(document) | PdfContentEditor クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
| text_search_options | テキスト検索オプションを取得または設定します。 |
| text_edit_options | テキスト編集オプションを取得または設定します。 |
| text_replace_options | テキスト置換オプションを取得または設定します。 |
| replace_text_strategy | テキスト置換操作のためのパラメータセット |
| DOCUMENT_OPEN | ドキュメントイベントタイプです。ドキュメントを開きます。 |
| DOCUMENT_CLOSE | ドキュメントイベントタイプです。ドキュメントを閉じます。 |
| DOCUMENT_WILL_SAVE | ドキュメントイベントタイプです。保存前にアクションを実行します。 |
| DOCUMENT_SAVED | ドキュメントイベントタイプです。保存後にアクションを実行します。 |
| DOCUMENT_WILL_PRINT | ドキュメントイベントタイプです。印刷前にアクションを実行します。 |
| DOCUMENT_PRINTED | ドキュメントイベントタイプです。印刷後にアクションを実行します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(input_file) | PDFファイルを編集用にバインドします。 |
| bind_pdf(input_stream) | PDFストリームを編集用にバインドします。 |
| bind_pdf(src_doc) | PDF ドキュメントを編集用にバインドします。 |
| save(dest_file) | 指定されたファイルに PDF ドキュメントを保存します。 |
| save(dest_stream) | 指定されたストリームに PDF ドキュメントを保存します。 |
| create_web_link(rect, url, original_page, clr) | PDFドキュメントにウェブリンクを作成します。 |
| create_web_link(rect, url, original_page) | PDFドキュメントにウェブリンクを作成します。 |
| create_local_link(rect, des_page, original_page, clr) | PDFドキュメントにローカルリンクを作成します。 |
| create_local_link(rect, des_page, original_page) | PDFドキュメントにローカルリンクを作成します。 |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr) | 別の PDF ドキュメントページへのリンクを作成します。 |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page) | 別の PDF ドキュメントページへのリンクを作成します。 |
| create_application_link(rect, application, page, clr) | PDF ドキュメント内でアプリケーションを起動するリンクを作成します。 |
| create_application_link(rect, application, page) | PDF ドキュメント内でアプリケーションを起動するリンクを作成します。 |
| create_file_attachment(rect, contents, file_path, page, name) | ファイル添付注釈を作成します。 |
| create_file_attachment(rect, contents, file_path, page, name, opacity) | ファイル添付注釈を作成します。 |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name) | ファイル添付注釈を作成します。 |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity) | ファイル添付注釈を作成します。 |
| add_document_attachment(file_attachment_path, description) | 注釈なしでドキュメント添付を追加します。 |
| add_document_attachment(file_attachment_stream, file_attachment_name, description) | 注釈なしでドキュメント添付を追加します。 |
| create_rubber_stamp(page, annot_rect, icon, annot_contents, color) | ゴム印注釈を作成します。 |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file) | ゴム印注釈を作成します。 |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream) | ゴム印注釈を作成します。 |
| delete_image(page_number, index) | 指定されたページの指定された画像を削除します。 |
| delete_image() | 指定されたページの指定された画像を削除します。 |
| replace_text(src_string, the_page, dest_string, text_state) | 指定されたページの PDF ファイル内のテキストを置換します。 [TextState](/pdf/python-net/aspose.pdf.text/textstate/) オブジェクト（フォントファミリー、色）を指定してテキストを置換できます。 |
| replace_text(src_string, dest_string) | 指定されたページの PDF ファイル内のテキストを置換します。 [TextState](/pdf/python-net/aspose.pdf.text/textstate/) オブジェクト（フォントファミリー、色）を指定してテキストを置換できます。 |
| replace_text(src_string, the_page, dest_string) | 指定されたページの PDF ファイル内のテキストを置換します。 [TextState](/pdf/python-net/aspose.pdf.text/textstate/) オブジェクト（フォントファミリー、色）を指定してテキストを置換できます。 |
| replace_text(src_string, dest_string, text_state) | 指定されたページの PDF ファイル内のテキストを置換します。 [TextState](/pdf/python-net/aspose.pdf.text/textstate/) オブジェクト（フォントファミリー、色）を指定してテキストを置換できます。 |
| replace_text(src_string, dest_string, font_size) | 指定されたページの PDF ファイル内のテキストを置換します。 [TextState](/pdf/python-net/aspose.pdf.text/textstate/) オブジェクト（フォントファミリー、色）を指定してテキストを置換できます。 |
| delete_stamp_by_ids(stamp_ids) | ドキュメントのすべてのページから、指定された ID のスタンプを削除します。 |
| delete_stamp_by_ids(page_number, stamp_ids) | ドキュメントのすべてのページから、指定された ID のスタンプを削除します。 |
| delete_stamp_by_id(page_number, stamp_id) | ドキュメントのすべてのページから、指定された ID のスタンプを削除します。 |
| delete_stamp_by_id(stamp_id) | ドキュメントのすべてのページから、指定された ID のスタンプを削除します。 |
| close() | 開かれたドキュメントを閉じます。 |
| extract_link() | PDF ドキュメントに含まれる Link インスタンスのコレクションを抽出します。 |
| create_java_script_link(code, rect, original_page, color) | PDF ドキュメントに JavaScript へのリンクを作成します。 |
| create_text(rect, title, contents, open, icon, page) | PDF ドキュメントにテキスト注釈を作成します |
| create_free_text(rect, contents, page) | PDF ドキュメントにフリーテキスト注釈を作成します |
| create_markup(rect, contents, type, page, clr) | PDF ドキュメントにマークアップ注釈を作成します。 |
| create_popup(rect, contents, open, page) | PDF ドキュメントにポップアップ注釈を作成します。 |
| delete_attachments() | PDF ドキュメント内のすべての添付ファイルを削除します。 |
| create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array) | 線注釈を作成します。 |
| create_square_circle(rect, contents, clr, square, page, border_width) | 四角形・円形注釈を作成します。 |
| draw_curve(line_info, page, annot_rect, annot_contents) | 曲線注釈を作成します。 |
| create_polygon(line_info, page, annot_rect, annot_contents) | ポリゴン注釈を作成します。 |
| create_poly_line(line_info, page, annot_rect, annot_contents) | ポリライン注釈を作成します。 |
| create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color) | キャレット注釈を作成します。 |
| create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination) | 指定されたアクションでブックマークを作成します。 |
| add_document_additional_action(event_type, code) | ドキュメントイベントに追加アクションを追加します。 |
| remove_document_open_action() | ドキュメントからオープンアクションを削除します。この操作は、起動時に明示的な 'GoTo' アクションを使用する複数のドキュメントを連結する際に便利です。 |
| change_viewer_preference(viewer_attribution) | ビュー設定を変更します。 |
| get_viewer_preference() | ビュー設定を返します。 |
| replace_image(page_number, index, image_file) | PDF ドキュメントの指定ページにある指定された画像を別の画像に置き換えます。 |
| create_movie(rect, file_path, page) | ムービー注釈を作成します。 |
| create_sound(rect, file_path, name, page, rate) | サウンド注釈を作成します。 |
| delete_stamp(page_number, index) | 指定されたページのスタンプインデックスで複数のスタンプを削除します。 |
| hide_stamp_by_id(page_number, stamp_id) | スタンプを非表示にします。非表示にした後、ShowStampById メソッドでスタンプの表示を復元できる場合があります。 |
| show_stamp_by_id(page_number, stamp_id) | HiddenStampById によって非表示にされたスタンプを表示します。 |
| move_stamp_by_id(page_number, stamp_id, x, y) | ページ上のスタンプの位置を変更します。 |
| move_stamp(page_number, stamp_index, x, y) | ページ上のスタンプの位置を変更します。 |
| get_stamps(page_number) | ページ上のスタンプの配列を返します。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

