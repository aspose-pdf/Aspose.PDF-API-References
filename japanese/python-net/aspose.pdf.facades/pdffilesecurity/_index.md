---
title: "PdfFileSecurity"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "所有者またはユーザーパスワードでPdfファイルを暗号化または復号化し、セキュリティ設定とパスワードを変更することを表します。"
type: docs
weight: 300
url: /ja/python-net/aspose.pdf.facades/pdffilesecurity/
---

## PdfFileSecurity class

所有者またはユーザーパスワードでPdfファイルを暗号化または復号化し、セキュリティ設定とパスワードを変更することを表します。

PdfFileSecurity 型は次のメンバーを公開します。
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfFileSecurity(input_stream, output_stream) | PdfFileSecurity クラスの新しいインスタンスを初期化します。 |
| PdfFileSecurity(input_file, output_file) | PdfFileSecurity クラスの新しいインスタンスを初期化します。 |
| PdfFileSecurity() | PdfFileSecurity のオブジェクトを初期化します。 |
| PdfFileSecurity(document) | PdfFileSecurity クラスの新しいインスタンスを初期化します。 |
| PdfFileSecurity(document, output_file) | PdfFileSecurity クラスの新しいインスタンスを初期化します。 |
| PdfFileSecurity(document, output_stream) | PdfFileSecurity クラスの新しいインスタンスを初期化します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
| allow_exceptions | この値が true に設定されている場合、操作失敗時に例外がスローされます。false の場合、失敗時にメソッドは false を返し、最後の例外は LastException プロパティで確認できます。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(src_file) | ファサードを初期化します。 |
| bind_pdf(src_stream) | ファサードを初期化します。 |
| bind_pdf(src_doc) | PDF ドキュメントを編集用にバインドします。 |
| save(dest_file) | 指定されたファイルに PDF ドキュメントを保存します。 |
| save(dest_stream) | 指定されたストリームに PDF ドキュメントを保存します。 |
| encrypt_file(user_password, owner_password, privilege, key_size) | ユーザーパスワードとオーナーパスワードで PDF ファイルを暗号化し、ドキュメントのアクセス権限を設定します。<br/>            ユーザーパスワードとオーナーパスワードは null または空にできます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。<br/>            処理に失敗した場合は例外がスローされます。 |
| encrypt_file(user_password, owner_password, privilege, key_size, cipher) | ユーザーパスワードとオーナーパスワードで PDF ファイルを暗号化し、ドキュメントのアクセス権限を設定します。<br/>            ユーザーパスワードとオーナーパスワードは null または空にできます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。<br/>            KeySize と Algorithm の組み合わせは 6 通り可能です。<br/>            ただし (KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効であり、該当する組み合わせが検出された場合は例外が発生します。<br/>            処理に失敗した場合は例外がスローされます。 |
| set_privilege(privilege) | ユーザー/オーナーパスワードを空にして PDF ファイルのセキュリティを設定します。<br/>            オーナーパスワードはランダムな文字列が追加されます。<br/>            処理に失敗した場合は例外がスローされます。 |
| set_privilege(user_password, owner_password, privilege) | 元のパスワードで PDF ファイルのセキュリティを設定します。<br/>            処理に失敗した場合は例外がスローされます。 |
| change_password(owner_password, new_user_password, new_owner_password) | オーナーパスワードを使用してユーザーパスワードとオーナーパスワードを変更し、元のセキュリティ設定を保持します。<br/>             新しいユーザーパスワードと新しいオーナーパスワードは null または空にできます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。<br/>             処理に失敗した場合は例外がスローされます。 |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | オーナーパスワードでユーザーパスワードとパスワードを変更し、PDF ドキュメントのセキュリティをリセットできるようにします。<br/>            新しいユーザーパスワードと新しいオーナーパスワードは null または空にできます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。<br/>            処理に失敗した場合は例外がスローされます。 |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | オーナーパスワードでユーザーパスワードとパスワードを変更し、PDF ドキュメントのセキュリティをリセットできるようにします。<br/>            新しいユーザーパスワードと新しいオーナーパスワードは null または空にできます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。<br/>            KeySize と Algorithm の組み合わせは 6 通り可能です。<br/>            ただし (KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効であり、該当する組み合わせが検出された場合は例外が発生します。<br/>            処理に失敗した場合は例外がスローされます。 |
| try_change_password(owner_password, new_user_password, new_owner_password) | オーナーパスワードでユーザーパスワードとオーナーパスワードを変更し、元のセキュリティ設定を保持します。<br/>             新しいユーザーパスワードと新しいオーナーパスワードは null または空にできます。オーナーパスワードは<br/>             新しいオーナーパスワードが null または空の場合、ランダムな文字列に置き換えられます。<br/>             処理に失敗しても例外はスローされません。 |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | オーナーパスワードでユーザーパスワードとパスワードを変更し、PDF ドキュメントのセキュリティをリセットできるようにします。<br/>            新しいユーザーパスワードと新しいオーナーパスワードは null または空にできます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。<br/>            処理に失敗しても例外はスローされません。 |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | オーナーパスワードでユーザーパスワードとパスワードを変更し、PDF ドキュメントのセキュリティをリセットできるようにします。<br/>            新しいユーザーパスワードと新しいオーナーパスワードは null または空にできます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。<br/>            KeySize と Algorithm の組み合わせは 6 通り可能です。<br/>            ただし (KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効であり、該当する組み合わせが検出された場合は例外が発生します。<br/>            処理に失敗しても例外はスローされません。 |
| close() | ファサードを閉じます。 |
| try_encrypt_file(user_password, owner_password, privilege, key_size) | ユーザーパスワードとオーナーパスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権限を設定します。<br/>            ユーザーパスワードとオーナーパスワードは null または空にすることができます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。<br/>            処理が失敗しても例外はスローされません。 |
| decrypt_file(owner_password) | オーナーパスワードで暗号化された Pdf ドキュメントを復号化します。 <br/>            ドキュメントにオーナーパスワードが設定されていない場合、ユーザーパスワードを使用できます。<br/>            処理が失敗した場合は例外がスローされます。 |
| try_decrypt_file(owner_password) | オーナーパスワードで暗号化された Pdf ドキュメントを復号化します。 <br/>            ドキュメントにオーナーパスワードが設定されていない場合、ユーザーパスワードを使用できます。<br/>            処理が失敗しても例外はスローされません。 |
| try_set_privilege(user_password, owner_password, privilege) | 元のパスワードで Pdf ファイルのセキュリティを設定します。<br/>            処理が失敗しても例外はスローされません。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

