---
title: Class PdfFileSecurity
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSecurity クラス。オーナーまたはユーザーパスワードで Pdf ファイルを暗号化または復号化し、セキュリティ設定とパスワードを変更します。
type: docs
weight: 4550
url: /ja/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity クラス

オーナーまたはユーザーパスワードで Pdf ファイルを暗号化または復号化し、セキュリティ設定とパスワードを変更します。

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | PdfFileSecurity のオブジェクトを初期化します。 |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | *document* に基づいて新しい `PdfFileSecurity` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業中のドキュメントファサードを取得します。 |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | 最後の操作によってスローされた例外を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | ファサードを初期化します。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | ファサードを初期化します。 |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | ユーザーパスワードとオーナーパスワードをオーナーパスワードで変更し、元のセキュリティ設定を保持します。新しいユーザーパスワードと新しいオーナーパスワードは null または空にすることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。プロセスが失敗した場合は例外がスローされます。 |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | ユーザーパスワードとオーナーパスワードをオーナーパスワードで変更し、Pdf ドキュメントのセキュリティをリセットします。新しいユーザーパスワードと新しいオーナーパスワードは null または空にすることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。プロセスが失敗した場合は例外がスローされます。 |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | ユーザーパスワードとオーナーパスワードをオーナーパスワードで変更し、Pdf ドキュメントのセキュリティをリセットします。新しいユーザーパスワードと新しいオーナーパスワードは null または空にすることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。KeySize と Algorithm の値の組み合わせは 6 通りあります。ただし、(KeySize.x40, Algorithm.AES) および (KeySize.x256, Algorithm.RC4) は無効であり、この組み合わせに遭遇した場合は対応する例外が発生します。プロセスが失敗した場合は例外がスローされます。 |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | ファサードを閉じます。 |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | オーナーパスワードで暗号化された Pdf ドキュメントを復号化します。ドキュメントにオーナーパスワードがない場合は、ユーザーパスワードを使用できます。プロセスが失敗した場合は例外がスローされます。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | ユーザーパスワードとオーナーパスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権を設定します。ユーザーパスワードとオーナーパスワードは null または空にすることができます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。プロセスが失敗した場合は例外がスローされます。 |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | ユーザーパスワードとオーナーパスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権を設定します。ユーザーパスワードとオーナーパスワードは null または空にすることができます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。KeySize と Algorithm の値の組み合わせは 6 通りあります。ただし、(KeySize.x40, Algorithm.AES) および (KeySize.x256, Algorithm.RC4) は無効であり、この組み合わせに遭遇した場合は対応する例外が発生します。プロセスが失敗した場合は例外がスローされます。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF ドキュメントを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF ドキュメントを指定されたファイルに保存します。 |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | 空のユーザー/オーナーパスワードで Pdf ファイルのセキュリティを設定します。オーナーパスワードはランダムな文字列で追加されます。プロセスが失敗した場合は例外がスローされます。 |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | 元のパスワードで Pdf ファイルのセキュリティを設定します。プロセスが失敗した場合は例外がスローされます。 |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | ユーザーパスワードとオーナーパスワードをオーナーパスワードで変更し、元のセキュリティ設定を保持します。新しいユーザーパスワードと新しいオーナーパスワードは null または空にすることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。プロセスが失敗した場合は例外をスローしません。 |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | ユーザーパスワードとオーナーパスワードをオーナーパスワードで変更し、Pdf ドキュメントのセキュリティをリセットします。新しいユーザーパスワードと新しいオーナーパスワードは null または空にすることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。プロセスが失敗した場合は例外をスローしません。 |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | ユーザーパスワードとオーナーパスワードをオーナーパスワードで変更し、Pdf ドキュメントのセキュリティをリセットします。新しいユーザーパスワードと新しいオーナーパスワードは null または空にすることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。KeySize と Algorithm の値の組み合わせは 6 通りあります。ただし、(KeySize.x40, Algorithm.AES) および (KeySize.x256, Algorithm.RC4) は無効であり、この組み合わせに遭遇した場合は対応する例外が発生します。プロセスが失敗した場合は例外をスローしません。 |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | オーナーパスワードで暗号化された Pdf ドキュメントを復号化します。ドキュメントにオーナーパスワードがない場合は、ユーザーパスワードを使用できます。プロセスが失敗した場合は例外をスローしません。 |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | ユーザーパスワードとオーナーパスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権を設定します。ユーザーパスワードとオーナーパスワードは null または空にすることができます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。プロセスが失敗した場合は例外をスローしません。 |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | 元のパスワードで Pdf ファイルのセキュリティを設定します。プロセスが失敗した場合は例外をスローしません。 |

### 参照

* クラス [SaveableFacade](../saveablefacade/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)