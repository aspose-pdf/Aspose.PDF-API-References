---
title: "PdfFileSecurity.DecryptFile"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileSecurity メソッド。所有者パスワードで暗号化された Pdf ドキュメントを復号化します。ドキュメントに所有者パスワードがない場合はユーザーパスワードを使用できます。処理が失敗した場合は例外をスローします。"
type: docs
weight: 60
url: /ja/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile method

所有者パスワードで暗号化された Pdf ドキュメントを復号化します。ドキュメントに所有者パスワードが設定されていない場合は、ユーザーパスワードの使用が許可されます。処理が失敗した場合は例外をスローします。

```csharp
public bool DecryptFile(string ownerPassword)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ownerPassword | String | 所有者パスワード。 |

### 戻り値

成功した場合は True。

## 例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.DecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.DecryptFile("ownerpass")
```

### 関連項目

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


