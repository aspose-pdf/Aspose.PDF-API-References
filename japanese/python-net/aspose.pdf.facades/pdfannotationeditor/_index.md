---
title: "PdfAnnotationEditor"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF ドキュメントの注釈（コメント）を扱うクラスを表します。"
type: docs
weight: 170
url: /ja/python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

PDF ドキュメントの注釈（コメント）を扱うクラスを表します。

PdfAnnotationEditor 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfAnnotationEditor() | 新しい [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/) オブジェクトを初期化します。 |
| PdfAnnotationEditor(document) | PdfAnnotationEditor クラスの新しいインスタンスを初期化します |
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
| import_annotations_from_xfdf(xfdf_file) | XFDF ファイルからすべての注釈をインポートします。 |
| import_annotations_from_xfdf(xfdf_stream) | XFDF データストリームからすべての注釈をインポートします。 |
| import_annotation_from_xfdf(xfdf_file) | XFDF ファイルからすべての注釈をインポートします。 |
| import_annotation_from_xfdf(xfdf_file, annot_type) | 指定された注釈を XFDF ファイルからインポートします。 |
| import_annotation_from_xfdf(xfdf_stream, annot_type) | 指定された注釈を XFDF データストリームからインポートします。 |
| import_annotation_from_xfdf(xfdf_stream) | 指定された注釈を XFDF データストリームからインポートします。 |
| import_annotations(annot_file, annot_type) | 別の PDF ドキュメントの配列から、指定された注釈をドキュメントにインポートします。 |
| import_annotations(annot_file) | 別の PDF ドキュメントの配列から、指定された注釈をドキュメントにインポートします。 |
| import_annotations(annot_file_stream, annot_type) | 別の PDF ドキュメントストリームの配列から、指定された注釈をドキュメントにインポートします。 |
| import_annotations(annot_file_stream) | 別の PDF ドキュメントストリームの配列から、指定された注釈をドキュメントにインポートします。 |
| flattening_annotations() | ドキュメント内のすべての注釈をフラット化します。 |
| flattening_annotations(flatten_settings) | ドキュメント内のすべての注釈をフラット化します。 |
| flattening_annotations(start, end, annot_type) | 指定されたタイプの注釈をフラット化します。 |
| delete_annotations() | ドキュメント内のすべての注釈を削除します。 |
| delete_annotations(annot_type) | 指定されたタイプのすべての注釈をドキュメントから削除します。 |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | 指定された注釈タイプの内容をXFDFにエクスポートします。 |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | 指定された注釈タイプの内容をXFDFにエクスポートします。 |
| extract_annotations(start, end, annot_types) | 指定されたタイプの注釈の一覧を取得します。 |
| extract_annotations(start, end, annot_types) | 指定されたタイプの注釈の一覧を取得します。 |
| close() | 現在のファサードに関連付けられたリソースを解放します。 |
| modify_annotations_author(start, end, src_author, des_author) | 指定されたページ範囲の注釈の作成者を変更します。 |
| delete_annotation(annot_name) | 指定されたタイプのすべての注釈をドキュメントから削除します。 |
| export_annotations_to_xfdf(xml_output_stream) | 注釈をストリームにエクスポートします。 |
| modify_annotations(start, end, annotation) | 指定されたページ範囲の指定されたタイプの注釈を変更します。<br/>            次の注釈プロパティの変更をサポートします: Modified, Title, Contents, Color, Subject, Open. |
| redact_area(page_index, rect, color) | 指定されたページの領域を編集します。すべての内容が削除されます。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

