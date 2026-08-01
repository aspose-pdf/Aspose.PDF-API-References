---
title: "クラス PdfFileSecurity"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfFileSecurity クラス。所有者またはユーザーパスワードで PDF ファイルを暗号化または復号化し、セキュリティ設定とパスワードを変更することを表します。"
type: docs
weight: 4670
url: /ja/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

所有者またはユーザー パスワードで PDF ファイルを暗号化または復号し、セキュリティ設定やパスワードを変更することを表します。

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | PdfFileSecurity オブジェクトを初期化します。 |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) |  *document* を基に新しい `PdfFileSecurity` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業対象の document ファサードを取得します。 |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | 最後の操作でスローされた例外を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | ファサードを初期化します。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | ファサードを初期化します。 |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | 所有者パスワードでユーザーパスワードと所有者パスワードを変更し、元のセキュリティ設定を保持します。新しいユーザーパスワードおよび新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダム文字列に置き換えられます。処理が失敗した場合は例外をスローします。 |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | 所有者パスワードでユーザーパスワードとパスワードを変更し、Pdf ドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードおよび新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダム文字列に置き換えられます。処理が失敗した場合は例外をスローします。 |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | 所有者パスワードでユーザーパスワードとパスワードを変更し、Pdf ドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードおよび新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダム文字列に置き換えられます。KeySize と Algorithm の組み合わせは 6 通り可能です。ただし (KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効であり、キットがこの組み合わせに遭遇した場合、対応する例外が発生します。処理が失敗した場合は例外をスローします。 |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | ファサードを閉じます。 |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | 所有者パスワードで暗号化された Pdf ドキュメントを復号化します。ドキュメントに所有者パスワードが設定されていない場合は、ユーザーパスワードの使用が許可されます。処理が失敗した場合は例外をスローします。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | ユーザーパスワードとオーナーパスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権限を設定します。ユーザーパスワードとオーナーパスワードは null または空にすることができます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。処理が失敗した場合は例外をスローします。 |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | ユーザーパスワードとオーナーパスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権限を設定します。ユーザーパスワードとオーナーパスワードは null または空にすることができます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。KeySize と Algorithm の組み合わせは 6 通り可能です。ただし (KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効で、キットがこの組み合わせに遭遇した場合は対応する例外が発生します。処理が失敗した場合は例外をスローします。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF ドキュメントを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF ドキュメントを指定されたファイルに保存します。 |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | ユーザー/オーナーパスワードを空にして Pdf ファイルのセキュリティを設定します。オーナーパスワードはランダムな文字列が追加されます。処理が失敗した場合は例外をスローします。 |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | 元のパスワードで Pdf ファイルのセキュリティを設定します。処理が失敗した場合は例外をスローします。 |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | オーナーパスワードを使用してユーザーパスワードとオーナーパスワードを変更し、元のセキュリティ設定を保持します。新しいユーザーパスワードと新しいオーナーパスワードは null または空にすることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。処理が失敗しても例外はスローされません。 |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | オーナーパスワードでユーザーパスワードとオーナーパスワードを変更し、Pdf ドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードと新しいオーナーパスワードは null または空にすることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。処理が失敗しても例外はスローされません。 |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | オーナーパスワードでユーザーパスワードとオーナーパスワードを変更し、Pdf ドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードと新しいオーナーパスワードは null または空にすることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。KeySize と Algorithm の組み合わせは 6 通り可能です。ただし (KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効で、キットがこの組み合わせに遭遇した場合は対応する例外が発生します。処理が失敗しても例外はスローされません。 |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | オーナーパスワードで暗号化された Pdf ドキュメントを復号化します。ドキュメントにオーナーパスワードが設定されていない場合は、ユーザーパスワードを使用できます。処理が失敗しても例外はスローされません。 |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | ユーザーパスワードとオーナーパスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権限を設定します。ユーザーパスワードとオーナーパスワードは null または空にすることができます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。処理が失敗しても例外はスローされません。 |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | 元のパスワードで Pdf ファイルのセキュリティを設定します。処理が失敗しても例外はスローされません。 |

### 関連項目

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


