---
title: "PdfBookmarkEditor"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF ファイルのブックマークを作成、変更、エクスポート、インポート、削除する機能を含むクラスを表します。"
type: docs
weight: 180
url: /ja/python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

PDF ファイルのブックマークを作成、変更、エクスポート、インポート、削除する機能を含むクラスを表します。

PdfBookmarkEditor 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfBookmarkEditor() | 新しい [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/) オブジェクトを初期化します。 |
| PdfBookmarkEditor(document) | PdfBookmarkEditor クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(src_file) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_stream) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_doc) | PDF ドキュメントを編集用にバインドします。 |
| save(dest_file) | 指定されたファイルに PDF ドキュメントを保存します。 |
| save(dest_stream) | 指定されたストリームに PDF ドキュメントを保存します。 |
| create_bookmarks() | すべてのページのブックマークを作成します。 |
| create_bookmarks(bookmark) | すべてのページのブックマークを作成します。 |
| create_bookmarks(color, bold_flag, italic_flag) | 指定された色とスタイル（太字、斜体）で、すべてのページのブックマークを作成します。 |
| create_bookmark_of_page(bookmark_name, page_number) | 指定されたページのブックマークを作成します。 |
| create_bookmark_of_page(bookmark_name, page_number) | 指定されたページ群のブックマークを作成します。 |
| delete_bookmarks() | PDF ドキュメントのすべてのブックマークを削除します。 |
| delete_bookmarks(title) | PDF ドキュメントのブックマークを削除します。 |
| extract_bookmarks() | ドキュメントからすべてのレベルのブックマークを抽出します。 |
| extract_bookmarks(upper_level) | ドキュメントからすべてのレベルのブックマークを抽出します。 |
| extract_bookmarks(title) | 指定されたタイトルのブックマークを抽出します。 |
| extract_bookmarks(bookmark) | ドキュメントからすべてのレベルのブックマークを抽出します。 |
| export_bookmarks_to_xml(xml_file) | ブックマークをXMLファイルにエクスポートします。 |
| export_bookmarks_to_xml(stream) | ブックマークをXMLストリームにエクスポートします。 |
| import_bookmarks_with_xml(xml_file) | XMLファイルからドキュメントへブックマークをインポートします。 |
| import_bookmarks_with_xml(stream) | XMLファイルからドキュメントへブックマークをインポートします。 |
| close() | 現在のファサードに関連付けられたリソースを解放します。 |
| modify_bookmarks(s_title, d_title) | 指定されたブックマークタイトルに従ってブックマークのタイトルを変更します。 |
| extract_bookmarks_to_html(pdf_file, css_file) | ブックマークをHTMLファイルにエクスポートします。 |
| export_bookmarks_to_html(in_pdf_file, out_html_file) | ブックマークをHTMLファイルにエクスポートします。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

