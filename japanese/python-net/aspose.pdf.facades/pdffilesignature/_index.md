---
title: "PdfFileSignature"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "証明書でpdfファイルに署名するクラスを表します。"
type: docs
weight: 310
url: /ja/python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

証明書でpdfファイルに署名するクラスを表します。

PdfFileSignature 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfFileSignature() | PdfFileSignature クラスのコンストラクタです。 |
| PdfFileSignature(input_file) | PdfFileSignature クラスの新しいインスタンスを初期化します |
| PdfFileSignature(input_file, output_file) | PdfFileSignature クラスの新しいインスタンスを初期化します |
| PdfFileSignature(document) | PdfFileSignature クラスの新しいインスタンスを初期化します |
| PdfFileSignature(document, output_file) | PdfFileSignature クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
| signature_appearance | 署名のグラフィック外観を設定または取得します。プロパティ値は画像ファイル名を表します。 |
| is_ltv_enabled | LTV 有効フラグを取得します。 |
| is_certified | ドキュメントが認証されているかどうかを示すフラグを取得します。 |
| signature_appearance_stream | 署名のグラフィック外観を設定または取得します。プロパティ値は画像ストリームを表します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(input_file) | Pdf ファイルを編集用にバインドします。 |
| bind_pdf(input_stream) | Pdf ストリームを編集用にバインドします。 |
| bind_pdf(src_doc) | PDF ドキュメントを編集用にバインドします。 |
| save(output_file) | 結果の PDF をファイルに保存します。 |
| save(output_stream) | 結果の PDF をストリームに保存します。 |
| save() | 結果の PDF をファイルに保存します。 |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect) | PDF ドキュメントに署名を作成します。 |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | 指定されたタイプの署名でドキュメントに署名します。 |
| sign(page, visible, annot_rect, sig) | 指定されたタイプの署名でドキュメントに署名します。 |
| sign(sig_name, sig_reason, sig_contact, sig_location, sig) | 指定されたタイプの署名でドキュメントに署名します。 |
| sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | 指定されたタイプの署名でドキュメントに署名します。 |
| sign(sig_name, sig) | 指定されたタイプの署名でドキュメントに署名します。 |
| certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature) | MDP 署名で文書を認証します。<br/>署名理由、連絡先、場所などのデータは、Signature オブジェクト sig の対応するプロパティで提供する必要があります。 |
| certify(sig_name, doc_mdp_signature) | MDP 署名で文書を認証します。<br/>署名理由、連絡先、場所などのデータは、Signature オブジェクト sig の対応するプロパティで提供する必要があります。 |
| remove_signature(sign_name) | 署名の名前に基づいて署名を削除します。 |
| remove_signature(sign_name, remove_field) | 署名の名前に基づいて署名を削除します。 |
| close() | ファサードを閉じます。 |
| get_access_permissions() | MDP 署名タイプによって認証された文書のアクセス許可値を返します。 |
| get_sign_names(only_active) | 空でないすべての署名の名前を取得します。 |
| get_blank_sign_names() | 空の署名フィールドすべての名前を取得します。 |
| is_contain_signature() | PDF にデジタル署名があるかどうかを確認します。 |
| contains_signature() | PDF にデジタル署名があるかどうかを確認します。 |
| contains_usage_rights() | PDF に使用権があるかどうかを確認します。 |
| is_covers_whole_document(sign_name) | 署名が文書全体をカバーしているかどうかを確認します。 |
| covers_whole_document(sign_name) | 署名が文書全体をカバーしているかどうかを確認します。 |
| get_revision(sign_name) | 署名のリビジョンを取得します。 |
| get_total_revision() | 総リビジョンを取得します。 |
| remove_usage_rights() | 使用権エントリを削除します。 |
| verify_signed(sign_name) | 署名の有効性をチェックします。 |
| get_signer_name(sign_name) | PDF文書に署名した個人または組織の名前を取得します。 |
| get_date_time(sign_name) | 署名の日付と時刻を取得します。 |
| get_reason(sign_name) | 署名の理由を取得します。 |
| get_location(sign_name) | 署名の場所を取得します。 |
| get_contact_info(sign_name) | 署名の連絡先情報を取得します。 |
| verify_signature(sign_name) | 署名の有効性をチェックします。 |
| extract_image(sign_name) | 署名の画像を抽出します。 |
| extract_certificate(sign_name) | 署名の単一X.509証明書をストリームとして抽出します。 |
| set_certificate(pfx, pass) | 署名処理のために証明書ファイルとパスワードを設定します。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

