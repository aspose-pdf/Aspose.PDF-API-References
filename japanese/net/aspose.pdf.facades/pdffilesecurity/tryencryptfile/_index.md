---
title: "PdfFileSecurity.TryEncryptFile"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileSecurity メソッド。ユーザーパスワードと所有者パスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権限を設定します。ユーザーパスワードと所有者パスワードは null または空にできます。入力された所有者パスワードが null または空の場合、所有者パスワードはランダムな文字列に置き換えられます。処理が失敗しても例外はスローされません。"
type: docs
weight: 110
url: /ja/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile method

ユーザーパスワードとオーナーパスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権限を設定します。ユーザーパスワードとオーナーパスワードは null または空にすることができます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。処理が失敗しても例外はスローされません。

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワード。 |
| ownerPassword | String | 所有者パスワード。 |
| 権限 | DocumentPrivilege | 権限を設定します。 |
| keySize | KeySize | KeySize.x40 は 40 ビット暗号化、KeySize.x128 は 128 ビット暗号化、KeySize.x256 は 256 ビット暗号化に使用します。 |

### 戻り値

成功した場合は true、失敗した場合は false。

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

### 関連項目

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


