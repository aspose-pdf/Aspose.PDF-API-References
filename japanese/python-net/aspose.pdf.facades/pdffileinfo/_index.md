---
title: "PdfFileInfo"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF ドキュメントのメタ情報にアクセスするクラスを表します。"
type: docs
weight: 270
url: /ja/python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

PDF ドキュメントのメタ情報にアクセスするクラスを表します。

PdfFileInfo 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfFileInfo() | デフォルト値で Aspose.Pdf.Facades.PdfFileInfo クラスの新しいインスタンスを初期化します。 |
| PdfFileInfo(input_stream) | PdfFileInfo クラスの新しいインスタンスを初期化します |
| PdfFileInfo(input_stream, password) | PdfFileInfo クラスの新しいインスタンスを初期化します |
| PdfFileInfo(input_file) | PdfFileInfo クラスの新しいインスタンスを初期化します |
| PdfFileInfo(input_file, password) | PdfFileInfo クラスの新しいインスタンスを初期化します |
| PdfFileInfo(document) | PdfFileInfo クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
| author | PDF ドキュメントの Author 情報を取得または設定します。 |
| is_encrypted | PDF ドキュメントが暗号化されているかどうかをチェックします。 |
| is_pdf_file | ソース入力が有効な PDF ファイルかどうかをチェックします。 |
| use_strict_validation | [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) プロパティを使用して、厳格な検証ルールを適用します。 |
| creation_date | PDF ドキュメントの CreationDate 情報を取得または設定します。 |
| creator | PDF ドキュメントの Creator 情報を取得または設定します。 |
| has_collection | 現在の入力ファイルが PDF ファイルのコレクションを含む 'Portfolio' ファイルである場合、true を返します。 |
| input_file | 入力ファイルを取得または設定します。 |
| input_stream | 入力ストリームを取得または設定します。 |
| keywords | PDF ドキュメントの Keywords 情報を取得または設定します。 |
| mod_date | PDF ドキュメントの ModDate 日付情報を取得または設定します。 |
| number_of_pages | ドキュメントのページ数を取得します。 |
| producer | PDF ドキュメントの Producer 情報を取得します。 |
| subject | PDF ドキュメントの Subject 情報を取得または設定します。 |
| タイトル | PDF ドキュメントの Title 情報を取得または設定します。 |
| password_type | PdfFileInfo インスタンスの作成時に渡されたパスワードのタイプを返します。可能な値は [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) を参照してください。<br/>            注意: PDF ドキュメントはユーザー（またはオープン）パスワードと所有者（または権限、編集）パスワードの両方で開くことができます。 |
| has_open_password | パスワードで保護された PDF ドキュメントを開くのにパスワードが必要な場合は true を返します。 |
| has_edit_password | 権限またはドキュメントのセキュリティ プロパティを変更するのにパスワードが必要な場合は true を返します。<br/>            注意: このプロパティは、[PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) コンストラクタで有効なパスワードが提供された場合にのみ読み取ることができます。<br/>            PasswordType が Inaccessible（無効なパスワードが提供されたことを意味します）の場合、このプロパティの読み取りは [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/) で失敗します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(src_doc) | ファサードを初期化します。 |
| bind_pdf(src_file) | ファサードを初期化します。 |
| bind_pdf(src_stream) | ファサードを初期化します。 |
| save(dest_stream) | 更新された PDF ドキュメントを指定されたストリームに保存します。 |
| save(dest_file) | 更新された PDF ドキュメントを指定されたファイルに保存します。 |
| save_new_info(output_stream) | 更新された PDF ドキュメントを指定されたストリームに保存します。 |
| save_new_info(output_file) | 更新された PDF ドキュメントを指定されたファイルに保存します。 |
| close() | インスタンスをデ初期化します。 |
| clear_info() | PDF ドキュメントのすべてのメタ情報をクリアします。 |
| get_document_privilege() | PDF ドキュメントの権限設定を取得します。 |
| get_meta_info(name) | プロパティ名で PDF ドキュメントのカスタマイズ情報を取得します。該当するプロパティがない場合は空文字列を返します。 |
| get_page_height(page_num) | 指定されたページの高さを取得します。 |
| get_page_rotation(page_num) | 指定されたページの回転を取得します。 |
| get_page_width(page_num) | 指定されたページの幅を取得します。 |
| get_page_x_offset(page_num) | 指定されたページ表示領域の水平オフセットを取得します。 |
| get_page_y_offset(page_num) | 指定されたページ表示領域の垂直オフセットを取得します。 |
| get_pdf_version() | PDF ドキュメントのバージョン情報を取得します。 |
| set_meta_info(name, value) | PDF ドキュメントのカスタマイズされた情報を設定します。 |
| save_new_info_with_xmp(output_file_name) | ファイル情報を設定して明示的に指定されたプロパティを変更し、他のプロパティはそのまま残ります。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

