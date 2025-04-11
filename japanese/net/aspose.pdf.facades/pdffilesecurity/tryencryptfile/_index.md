---
title: PdfFileSecurity.TryEncryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity メソッド。ユーザーパスワードとオーナーパスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権限を設定します。ユーザーパスワードとオーナーパスワードは null または空にすることができます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。プロセスが失敗しても例外はスローされません。
type: docs
weight: 110
url: /ja/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile メソッド

ユーザーパスワードとオーナーパスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権限を設定します。ユーザーパスワードとオーナーパスワードは null または空にすることができます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。プロセスが失敗しても例外はスローされません。

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワード。 |
| ownerPassword | String | オーナーパスワード。 |
| privilege | DocumentPrivilege | 設定する権限。 |
| keySize | KeySize | 40 ビット暗号化には KeySize.x40、128 ビット暗号化には KeySize.x128、256 ビット暗号化には KeySize.x256。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### 参照

* クラス [DocumentPrivilege](../../documentprivilege/)
* 列挙型 [KeySize](../../keysize/)
* クラス [PdfFileSecurity](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)