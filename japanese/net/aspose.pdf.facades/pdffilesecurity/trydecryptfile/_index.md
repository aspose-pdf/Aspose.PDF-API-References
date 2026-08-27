---
title: "PdfFileSecurity.TryDecryptFile"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileSecurity メソッド。所有者パスワードで暗号化された Pdf ドキュメントを復号化します。ドキュメントに所有者パスワードがない場合はユーザーパスワードを使用できます。処理が失敗しても例外はスローされません。"
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile method

オーナーパスワードで暗号化された Pdf ドキュメントを復号化します。ドキュメントにオーナーパスワードが設定されていない場合は、ユーザーパスワードを使用できます。処理が失敗しても例外はスローされません。

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ownerPassword | String | 所有者パスワード。 |

### 戻り値

成功した場合は True、失敗した場合は false。

## 例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryDecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryDecryptFile("ownerpass")
```

### 関連項目

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


