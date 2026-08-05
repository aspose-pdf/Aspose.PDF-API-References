---
title: "PdfPageEditor"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "ページの回転、ズーム、位置の移動、ページサイズの変更など、PDFファイルのページを編集するクラスを表します。"
type: docs
weight: 340
url: /ja/python-net/aspose.pdf.facades/pdfpageeditor/
---

## PdfPageEditor class

ページの回転、ズーム、位置の移動、ページサイズの変更など、PDFファイルのページを編集するクラスを表します。

PdfPageEditor 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfPageEditor() | PdfPageEditor クラスのコンストラクタです。 |
| PdfPageEditor(document) | PdfPageEditor クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
| transition_duration | 遷移効果の期間を取得または設定します。 |
| transition_type | プレゼンテーション中に別のページからこのページへ移動する際に使用する遷移スタイルを取得または設定します。 |
| display_duration | ページの表示期間を取得または設定します。 |
| process_pages | 編集対象のページ番号を取得または設定します。デフォルトでは、すべてのページが編集されます。 |
| rotation | ページの回転を取得または設定します。回転は 0、90、180、または 270 のいずれかでなければなりません。<br/>            デフォルト値は 0 です。 |
| zoom | ズーム係数を取得または設定します。値 1.0 は 100% に相当します。<br/>            デフォルト値は 1.0 です。 |
| page_size | 出力ファイルのページサイズを取得または設定します。 |
| alignment | 結果ページ上の元の PDF コンテンツの水平揃えを取得または設定します。デフォルトは AlignmentType.Left です。 |
| horizontal_alignment | 結果ページ上の元の PDF コンテンツの水平揃えを取得または設定します。デフォルトは AlignmentType.Left です。 |
| vertical_alignment | 結果ページ上の元の PDF コンテンツの垂直揃えを取得または設定します。デフォルトは VerticalAlignmentType.Bottom です。 |
| vertical_alignment_type | 結果ページ上の元の PDF コンテンツの垂直揃えを取得または設定します。デフォルトは VerticalAlignmentType.Bottom です。 |
| SPLITVOUT | アウト 垂直分割 |
| 水平分割アウト | 外側水平分割 |
| 垂直分割イン | 内側垂直分割 |
| 水平分割イン | 内側水平分割 |
| ブラインド垂直 | 垂直ブラインド |
| ブラインド水平 | 垂直ブラインド |
| 受信箱 | 内向きボックス |
| 送信箱 | 外向きボックス |
| 左右ワイプ | 左から右へのワイプ |
| 右左ワイプ | 右から左へのワイプ |
| 下上ワイプ | 下から上へのワイプ |
| 上下ワイプ | 上から下へのワイプ |
| ディゾルブ | 古いページがディゾルブします |
| 左右グリッター | 左から右へのグリッター |
| TBGLITTER | 上下グリッター |
| DGLITTER | 対角グリッター |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(src_file) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_stream) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_doc) | PDF ドキュメントを編集用にバインドします。 |
| save(output_file) | 変更されたドキュメントをファイルに保存します。 |
| save(output_stream) | 変更されたドキュメントをストリームに保存します。 |
| close() | 現在のファサードに関連付けられたリソースを解放します。 |
| move_position(move_x, move_y) | 原点を (0, 0) から指定された点へ移動します。<br/>            原点は左下にあり、単位はポイントです（1インチ = 72ポイント）。 |
| get_pages() | ページ総数を返します。 |
| get_page_size(page) | 指定されたページのサイズを返します。 |
| get_page_rotation(page) | 指定されたページの回転角度を返します。 |
| get_page_box_size(page, page_box_name) | ドキュメント内の指定されたボックスのサイズを返します。 |
| apply_changes() | ドキュメントページに加えられた変更を適用します。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

