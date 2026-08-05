---
title: "PdfFileEditor"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDFファイルの結合、分割、ページ抽出、ブックレット作成などの操作を実装します。"
type: docs
weight: 220
url: /ja/python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

PDF ファイルの操作を実装します：結合、分割、ページ抽出、ブックレット作成など。

PdfFileEditor 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfFileEditor() | PdfFileEditor クラスの新しいインスタンスを初期化します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| conversion_log | 変換プロセスのログを取得します。 |
| merge_duplicate_layers | このプロパティが true の場合、同名の結合されたドキュメントのオプションコンテンツは結果ドキュメントの1つのレイヤーにマージされます。 <br/>            それ以外の場合、同名のレイヤーは別々のレイヤーとして結果ドキュメントに保存されます。 |
| copy_outlines | true の場合、アウトラインがコピーされます。 |
| copy_logical_structure | true の場合、結合が実行されるとファイルの論理構造がコピーされます。 |
| merge_duplicate_outlines | true の場合、重複するアウトラインがマージされます。 |
| preserve_user_rights | true の場合、最初のドキュメントのユーザー権限が結合されたドキュメントに適用されます。他のすべてのドキュメントのユーザー権限は無視されます。 |
| incremental_updates | true の場合、結合中に増分更新が行われます。 |
| optimize_size | 最適化フラグを取得または設定します。このフラグが設定されている場合、結果ファイル内の同一リソースストリームは 1 つの PDF オブジェクトにマージされます。<br/>            これにより結果ファイルのサイズを減少させることができますが、実行が遅くなりメモリ使用量が増加する可能性があります。<br/>            デフォルト値: false. |
| corrupted_items | 結合が実行されたときに発生した問題の配列です。Concatenate() に渡された各破損ドキュメントについて <br/>            新しい CorruptedItem エントリが作成されます。<br/>            このプロパティは CorruptedFileAction が ConcatenateIgnoringCorrupted の場合にのみ使用できます。 |
| corrupted_file_action | このプロパティは、結合処理中に破損したファイルに遭遇したときの動作を定義します。<br/>            使用可能な値は: StopWithError と ConcatenateIgnoringCorrupted です。 |
| owner_password | ソース入力 PDF ファイルが暗号化されている場合、所有者のパスワードを設定します。<br/>            このプロパティはまだ実装されていません。 |
| allow_concatenate_exceptions | true に設定すると、エラーが発生した場合に例外がスローされます。false に設定すると、例外はスローされず、失敗した場合はメソッドが false を返します。 |
| close_concatenated_streams | true に設定すると、操作後にストリームが閉じられます。 |
| unique_suffix | フォームを結合する際にフィールド名を一意にするために追加されるサフィックスの形式です。<br/>            この文字列は %NUM% サブストリングを含んでいる必要があり、数字に置き換えられます。<br/>            例として、UniqueSuffix = "ABC%NUM%" の場合、フィールド "fieldName" の名前は以下のようになります。<br/>            fieldNameABC1, fieldNameABC2, fieldNameABC3 など。 |
| keep_actions | true の場合、アクションがソースドキュメントからコピーされます。デフォルト値: true。 |
| keep_fields_unique | true の場合、フォームが連結されるとフィールド名が一意にされます。<br/>            サフィックスがフィールド名に追加され、サフィックステンプレートは UniqueSuffix プロパティで指定できます。 |
| remove_signatures | true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）；それ以外の場合、無効な署名が発生する可能性があります。 |
| use_disk_buffer | このオプションを使用すると、宛先ドキュメントが定期的にディスクに保存され、以降の連結は増分更新として適用されます。 |
| concatenation_packet_size | UseDiskBuffer が true に設定されている間に連結中に新しい増分更新が行われるまでに連結されたドキュメントの数。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| try_concatenate(first_input_file, sec_input_file, output_file) | 2つのファイルを連結します。 |
| try_concatenate(src, dest) | ドキュメントを連結します。 |
| try_concatenate(input_files, output_file) | ファイルを1つのファイルに連結します。 |
| try_concatenate(input_stream, output_stream) | ファイルを連結します |
| try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | 2つのファイルを連結します。 |
| try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | ファイルを連結します |
| try_append(input_stream, port_streams, start_page, end_page, output_stream) | portStreams のドキュメント配列から選択されたページを追加します。<br/>            結果のドキュメントには firstInputFile と、portStreams のすべてのドキュメントページが startPage から endPage の範囲で含まれます。 |
| try_append(input_file, port_files, start_page, end_page, output_file) | portFiles のドキュメントから選択されたページを追加します。 <br/>            結果のドキュメントには firstInputFile と、portFiles のすべてのドキュメントページが startPageから endPage の範囲で含まれます。 |
| try_insert(input_file, insert_location, port_file, page_number, output_file) | 別のファイルからページを挿入して、入力 PDF ファイルに追加します。 |
| try_insert(input_stream, insert_location, port_stream, page_number, output_stream) | 別のファイルからページを挿入して、入力 PDF ファイルに追加します。 |
| try_delete(input_file, page_number, output_file) | 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 |
| try_delete(input_stream, page_number, output_stream) | 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 |
| try_extract(input_file, start_page, end_page, output_file) | 入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。 |
| try_extract(input_file, page_number, output_file) | 番号配列で指定されたページを抽出し、新しい PDF ファイルとして保存します。 |
| try_extract(input_stream, page_number, output_stream) | 番号配列で指定されたページを抽出し、新しい Pdf ファイルとして保存します。 |
| try_split_from_first(input_file, location, output_file) | Pdf ファイルを最初のページから指定された位置まで分割し、前半部分を新しいファイルとして保存します。 |
| try_split_from_first(input_stream, location, output_stream) | 開始位置から指定された位置まで分割し、前半部分を出力ストリームに保存します。 |
| try_split_to_end(input_file, location, output_file) | 指定された位置から分割し、後半部分を新しいファイルとして保存します。 |
| try_split_to_end(input_stream, location, output_stream) | 指定された位置から分割し、後半部分を新しいファイルストリームとして保存します。 |
| try_make_booklet(input_file, output_file) | 入力ファイルから出力ファイルへブックレットを作成します。 |
| try_make_booklet(input_stream, output_stream) | InputStream から outputStream へブックレットを作成します。 |
| try_make_booklet(input_file, output_file, page_size) | inputFile から outputFile へブックレットを作成します。 |
| try_make_booklet(input_stream, output_stream, page_size) | 入力ストリームからブックレットを作成し、結果を出力ストリームに保存します。 |
| try_make_booklet(input_file, output_file, left_pages, right_pages) | 最初のfirstInputFileからoutputFileへ、カスタマイズされた小冊子を作成します。 |
| try_make_booklet(input_stream, output_stream, left_pages, right_pages) | 最初のfirstInputStreamからoutputStreamへ、カスタマイズされた小冊子を作成します。 |
| try_make_booklet(input_file, output_file, page_size, left_pages, right_pages) | 最初のfirstInputFileからoutputFileへ、カスタマイズされた小冊子を作成します。 |
| try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | 最初のfirstInputStreamからoutputStreamへ、小冊子を作成します。 |
| try_make_n_up(input_file, output_file, x, y) | 最初のfirstInputFileからoutputFileへ、N-Upドキュメントを作成します。 |
| try_make_n_up(input_stream, output_stream, x, y) | 入力ストリームからN-Upドキュメントを作成し、結果をoutputStreamに保存します。 |
| try_make_n_up(input_stream, output_stream, x, y, page_size) | 最初の入力ストリームからoutputStreamへ、N-Upドキュメントを作成します。 |
| try_make_n_up(first_input_file, second_input_file, output_file) | 最初のfirstInputFileからoutputFileへ、N-Upドキュメントを作成します。 |
| try_make_n_up(first_input_stream, second_input_stream, output_stream) | 入力ストリームからN-Upドキュメントを作成し、結果をoutputStreamに保存します。 |
| try_make_n_up(input_files, output_file, is_sidewise) | 複数の入力PDFファイルからoutputFileへN-Upドキュメントを作成します。 <br/>            outputFileの各ページには、同じページ番号の入力ファイル内のページを組み合わせた複数ページが含まれます。 isSidewiseがtrueの場合は横方向に、falseの場合は縦方向にページが積み重ねられます。 |
| try_make_n_up(input_streams, output_stream, is_sidewise) | 複数の入力PDFストリームからoutputStreamへN-Upドキュメントを作成します。<br/>            outputStreamの各ページには、同じページ番号の入力ストリーム内のページを組み合わせた複数ページが含まれます。 isSidewiseがtrueの場合は横方向に、falseの場合は縦方向にページが積み重ねられます。 |
| try_make_n_up(input_file, output_file, x, y, page_size) | 入力ファイルからoutputFileへN-Upドキュメントを作成します。 |
| try_resize_contents(source, destination, pages, parameters) | ドキュメントのページ内容のサイズを変更します。 |
| try_resize_contents(source, destination, pages, new_width, new_height) | ドキュメントページの内容のサイズを変更します。<br/>            ページの内容を縮小し、余白を追加します。<br/>            内容の新しいサイズはデフォルトの空間単位で指定されます。 |
| try_resize_contents(source, destination, pages, parameters) | ドキュメント内のページの内容のサイズを変更します。ページが縮小された場合、ページの周囲に空白の余白が追加されます。 |
| concatenate(first_input_file, sec_input_file, output_file) | ファイルを連結し、結果を HttpResposnse オブジェクトに保存します。 |
| concatenate(first_input_stream, sec_input_stream, output_stream) | ファイルを連結し、結果を HttpResponse オブジェクトに格納します。 |
| concatenate(src, dest) | ドキュメントを連結します。 |
| concatenate(input_files, output_file) | ファイルを連結し、結果を HttpResposnse オブジェクトに保存します。 |
| concatenate(input_stream, output_stream) | ファイルを連結し、結果を HttpResponse オブジェクトに格納します。 |
| concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | ファイルを連結し、結果を HttpResposnse オブジェクトに保存します。 |
| concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | ファイルを連結し、結果を HttpResponse オブジェクトに格納します。 |
| append(input_stream, port_streams, start_page, end_page, output_stream) | ドキュメントをソースドキュメントに追加し、結果を response オブジェクトに保存します。 |
| append(input_file, port_files, start_page, end_page, output_file) | ドキュメントをソースドキュメントに追加し、結果を HttpResponse オブジェクトに保存します。 |
| append(input_file, port_file, start_page, end_page, output_file) | ドキュメントをソースドキュメントに追加し、結果を HttpResponse オブジェクトに保存します。 |
| append(input_stream, port_stream, start_page, end_page, output_stream) | ドキュメントをソースドキュメントに追加し、結果を response オブジェクトに保存します。 |
| insert(input_file, insert_location, port_file, start_page, end_page, output_file) | ファイルの内容をソースファイルに挿入し、結果を HttpResponse オブジェクトに格納します。 |
| insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream) | ドキュメントを別のドキュメントに挿入し、結果を response オブジェクトに格納します。 |
| insert(input_file, insert_location, port_file, page_number, output_file) | ファイルの内容をソースファイルに挿入し、結果を HttpResponse オブジェクトに格納します。 |
| insert(input_stream, insert_location, port_stream, page_number, output_stream) | ドキュメントを別のドキュメントに挿入し、結果を response オブジェクトに格納します。 |
| delete(input_file, page_number, output_file) | ドキュメントから指定されたページを削除し、結果を HttpResponse オブジェクトに格納します。 |
| delete(input_stream, page_number, output_stream) | 指定されたページをドキュメントから削除し、結果を HttpResponse オブジェクトに保存します。 |
| extract(input_file, start_page, end_page, output_file) | ソースファイルから指定されたページを抽出し、結果を HttpResponse オブジェクトに格納します。 |
| extract(input_file, page_number, output_file) | ソースファイルから指定されたページを抽出し、結果を HttpResponse オブジェクトに格納します。 |
| extract(input_stream, start_page, end_page, output_stream) | ソースファイルから指定されたページを抽出し、結果を HttpResponse オブジェクトに格納します。 |
| extract(input_stream, page_number, output_stream) | ソースファイルから指定されたページを抽出し、結果を HttpResponse オブジェクトに格納します。 |
| split_from_first(input_file, location, output_file) | ドキュメントを最初のページから指定位置まで分割し、結果を HttpResponse オブジェクトに保存します。 |
| split_from_first(input_stream, location, output_stream) | ドキュメントを開始位置から指定された位置まで分割し、結果を HttpResponse オブジェクトに格納します。 |
| split_to_end(input_file, location, output_file) | 指定された位置から分割し、後半部分を HttpResponse オブジェクトに保存します。 |
| split_to_end(input_stream, location, output_stream) | 指定された位置から分割し、後半部分を HttpResponse オブジェクトに保存します。 |
| make_booklet(input_file, output_file) | ソースファイルからブックレットを作成し、結果を HttpResponse オブジェクトに格納します。 |
| make_booklet(input_stream, output_stream) | PDF ファイルからブックレットを作成し、HttpResponse に格納します。 |
| make_booklet(input_file, output_file, page_size) | ソースファイルからブックレットを作成し、結果を HttpResponse オブジェクトに格納します。 |
| make_booklet(input_stream, output_stream, page_size) | PDF ファイルからブックレットを作成し、HttpResponse に格納します。 |
| make_booklet(input_file, output_file, left_pages, right_pages) | ソースファイルからブックレットを作成し、結果を HttpResponse オブジェクトに格納します。 |
| make_booklet(input_stream, output_stream, left_pages, right_pages) | PDF ファイルからブックレットを作成し、HttpResponse に格納します。 |
| make_booklet(input_file, output_file, page_size, left_pages, right_pages) | ソースファイルからブックレットを作成し、結果を HttpResponse オブジェクトに格納します。 |
| make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | PDF ファイルからブックレットを作成し、HttpResponse に格納します。 |
| make_n_up(input_file, output_file, x, y) | N-up ドキュメントを作成し、結果を HttpResponse オブジェクトに格納します。 |
| make_n_up(input_stream, output_stream, x, y) | N-up ドキュメントを作成し、結果を HttpResponse オブジェクトに格納します。 |
| make_n_up(input_stream, output_stream, x, y, page_size) | N-up ドキュメントを作成し、結果を HttpResponse オブジェクトに格納します。 |
| make_n_up(first_input_file, second_input_file, output_file) | N-up ドキュメントを作成し、結果を HttpResponse オブジェクトに格納します。 |
| make_n_up(first_input_stream, second_input_stream, output_stream) | N-up ドキュメントを作成し、結果を HttpResponse オブジェクトに格納します。 |
| make_n_up(input_files, output_file, is_sidewise) | 複数の入力PDFファイルからoutputFileへN-Upドキュメントを作成します。 <br/>            outputFileの各ページには、同じページ番号の入力ファイル内のページを組み合わせた複数ページが含まれます。 isSidewiseがtrueの場合は横方向に、falseの場合は縦方向にページが積み重ねられます。 |
| make_n_up(input_streams, output_stream, is_sidewise) | 複数の入力PDFストリームからoutputStreamへN-Upドキュメントを作成します。<br/>            outputStreamの各ページには、同じページ番号の入力ストリーム内のページを組み合わせた複数ページが含まれます。 isSidewiseがtrueの場合は横方向に、falseの場合は縦方向にページが積み重ねられます。 |
| make_n_up(input_file, output_file, x, y, page_size) | N-up ドキュメントを作成し、結果を HttpResponse オブジェクトに格納します。 |
| split_to_pages(input_file, file_name_template) | PDF ファイルを単一ページのドキュメントに分割します。 |
| split_to_pages(input_stream, file_name_template) | Pdf ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。パスはフィールド名テンプレートで指定されます。 |
| resize_contents(source, destination, pages, parameters) | ドキュメント内のページの内容のサイズを変更します。ページが縮小された場合、ページの周囲に空白の余白が追加されます。結果は HttpResponse オブジェクトに格納されます。 |
| resize_contents(source, destination, pages, new_width, new_height) | ドキュメントページの内容のサイズを変更します。<br/>            ページの内容を縮小し、余白を追加します。<br/>            内容の新しいサイズはデフォルトの空間単位で指定されます。 |
| resize_contents(source, destination, pages, new_width, new_height) | ドキュメントページの内容のサイズを変更します。<br/>            ページの内容を縮小し、余白を追加します。<br/>            内容の新しいサイズはデフォルトの空間単位で指定されます。 |
| resize_contents(source, destination, pages, parameters) | ドキュメント内のページの内容のサイズを変更します。ページが縮小された場合、ページの周囲に空白の余白が追加されます。結果は HttpResponse オブジェクトに格納されます。 |
| resize_contents(source, pages, parameters) | ドキュメントのページのサイズを変更します。縮小されたページの周囲に空白の余白が追加されます。 |
| resize_contents(source, parameters) | ドキュメントのページのサイズを変更します。縮小されたページの周囲に空白の余白が追加されます。 |
| resize_contents_pct(source, destination, pages, new_width, new_height) | ドキュメントページの内容のサイズを変更します。<br/>            ページの内容を縮小し、余白を追加します。<br/>            新しい内容のサイズはパーセントで指定されます。 |
| resize_contents_pct(source, destination, pages, new_width, new_height) | ドキュメントページの内容のサイズを変更します。<br/>            ページの内容を縮小し、余白を追加します。<br/>            新しい内容のサイズはパーセントで指定されます。 |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | ページの内容のサイズを変更し、指定された余白を追加します。 <br/>            余白はデフォルトの空間単位で指定されます。 |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | ページの内容のサイズを変更し、指定された余白を追加します。 <br/>            余白はデフォルトの空間単位で指定されます。 |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | ページの内容のサイズを変更し、指定された余白を追加します。<br/>            余白は初期ページサイズのパーセントで指定されます。 |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | ページの内容のサイズを変更し、指定された余白を追加します。<br/>            余白は初期ページサイズのパーセントで指定されます。 |
| add_page_break(src, dest, page_breaks) | 文書ページに改ページを追加します。 |
| add_page_break(src, dest, page_breaks) | 文書ページに改ページを追加します。 |
| add_page_break(src, dest, page_breaks) | 文書ページに改ページを追加します。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

