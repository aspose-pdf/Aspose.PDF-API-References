---
title: "PdfFileStamp"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDFファイルにスタンプ（透かしまたは背景）を追加するクラスです。"
type: docs
weight: 320
url: /ja/python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

PDFファイルにスタンプ（透かしまたは背景）を追加するクラスです。

PdfFileStamp 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfFileStamp(input_file, output_file) | PdfFileStamp クラスの新しいインスタンスを初期化します |
| PdfFileStamp(input_stream, output_stream) | PdfFileStamp クラスの新しいインスタンスを初期化します |
| PdfFileStamp(input_file, output_file, keep_security) | PdfFileStamp クラスの新しいインスタンスを初期化します |
| PdfFileStamp(input_stream, output_stream, keep_security) | PdfFileStamp クラスの新しいインスタンスを初期化します |
| PdfFileStamp() | PdfFileStamp のコンストラクタです。<br/>            入力ファイルと出力ファイルは対応するプロパティで指定できます。 |
| PdfFileStamp(document) | PdfFileStamp クラスの新しいインスタンスを初期化します |
| PdfFileStamp(document, output_file) | PdfFileStamp クラスの新しいインスタンスを初期化します |
| PdfFileStamp(document, output_stream) | PdfFileStamp クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
| optimize_size | 最適化フラグを取得または設定します。このフラグが設定されている場合、結果ファイル内の同一リソースストリームは 1 つの PDF オブジェクトにマージされます。<br/>            これにより結果ファイルのサイズを減少させることができますが、実行が遅くなりメモリ使用量が増加する可能性があります。<br/>            デフォルト値: false. |
| keep_security | true の場合、セキュリティを保持します。（この機能は次のバージョンで実装される予定です。） |
| input_file | 入力ファイルの名前とパスを取得または設定します。 |
| input_stream | 入力ストリームを取得または設定します。 |
| output_file | 出力ファイルの名前とパスを取得または設定します。 |
| output_stream | 出力ストリームを取得または設定します。 |
| page_number_rotation | ページ番号の回転を取得または設定します。回転は度数で指定されます。デフォルトは 0 です。 |
| page_height | ソースファイルの最初のページの高さを取得します。 |
| page_width | 入力ファイルの最初のページの幅を取得します。 |
| starting_number | 入力ファイルの最初のページの開始番号を取得または設定します。次のページはこの値から番号付けされます。 <br/>            例えば、StartingNumber を 100 に設定すると、ドキュメントのページ番号は 100、101、102 となります... |
| numbering_style | ページ番号付けスタイルを取得または設定します。可能な値: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| stamp_id | Stamp ID of next added stamp (incluiding page headers/hooters/page numbers). |
| POS_BOTTOM_MIDDLE | 下部中央の位置。 |
| POS_BOTTOM_RIGHT | 右下の位置。 |
| POS_UPPER_RIGHT | 右上の位置。 |
| POS_SIDES_RIGHT | 右側の位置。 |
| POS_UPPER_MIDDLE | 上部中央の位置。 |
| POS_BOTTOM_LEFT | 左下の位置。 |
| POS_SIDES_LEFT | 左側の位置。 |
| POS_UPPER_LEFT | 左上の位置。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(src_file) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_stream) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_doc) | PDF ドキュメントを編集用にバインドします。 |
| save(dest_file) | 結果を指定されたファイルに保存します。 |
| save(dest_stream) | 指定されたストリームにドキュメントを保存します。 |
| add_page_number(format_string) | ファイルにページ番号を追加します。ページ番号のテキストには # 記号を含めることができ、ページ番号に置き換えられます。 <br/>ページ番号はページの下部に水平中央に配置されます。 |
| add_page_number(formatted_text) | ページにページ番号を追加します。ページ番号には # 記号を含めることができ、ページ番号に置き換えられます。<br/>ページ番号はページの下部に水平中央に配置されます。 |
| add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin) | ドキュメントのページにページ番号を追加します。 |
| add_page_number(format_string, x, y) | ドキュメントのページにページ番号を追加します。 |
| add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin) | ドキュメントのページにページ番号を追加します。 |
| add_page_number(formatted_text, x, y) | ドキュメントのページにページ番号を追加します。 |
| add_page_number(format_string, position) | ドキュメントのページにページ番号を追加します。 |
| add_page_number(formatted_text, position) | ドキュメントのページにページ番号を追加します。 |
| add_header(formatted_text, top_margin) | ページにヘッダーを追加します。 |
| add_header(formatted_text, top_margin, left_margin, right_margin) | ページにヘッダーを追加します。 |
| add_header(image_file, top_margin) | ファイルのページに画像をヘッダーとして追加します。 |
| add_header(image_file, top_margin, left_margin, right_margin) | ファイルのページに画像をヘッダーとして追加します。 |
| add_header(image_stream, top_margin) | ページに画像をヘッダーとして追加します。 |
| add_header(input_stream, top_margin, left_margin, right_margin) | ページに画像をヘッダーとして追加します。 |
| add_footer(formatted_text, bottom_margin) | ドキュメントのページにフッターを追加します。 |
| add_footer(formatted_text, bottom_margin, left_margin, right_margin) | ドキュメントのページにフッターを追加します。 |
| add_footer(image_file, bottom_margin) | ドキュメントのページに画像をフッターとして追加します。 |
| add_footer(image_file, bottom_margin, left_margin, right_margin) | ドキュメントのページに画像をフッターとして追加します。 |
| add_footer(image_stream, bottom_margin) | ページのフッターとして画像を追加します。 |
| add_footer(image_stream, bottom_margin, left_margin, right_margin) | ページのフッターとして画像を追加します。 |
| close() | 開いているファイルを閉じ、変更を保存します。 <br/>            警告: 入力または出力ストリームが指定されている場合、Close() メソッドではそれらは閉じられません。 |
| add_stamp(stamp) | ファイルにスタンプを追加します。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

