---
title: PdfFileSecurity.DecryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity メソッド。オーナーパスワードによって暗号化された Pdf ドキュメントを復号化します。ドキュメントにオーナーパスワードがない場合は、ユーザーパスワードを使用することが許可されています。プロセスが失敗した場合は例外をスローします。
type: docs
weight: 60
url: /ja/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile メソッド

オーナーパスワードによって暗号化された Pdf ドキュメントを復号化します。ドキュメントにオーナーパスワードがない場合は、ユーザーパスワードを使用することが許可されています。プロセスが失敗した場合は例外をスローします。

```csharp
public bool DecryptFile(string ownerPassword)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ownerPassword | 文字列 | オーナーパスワード。 |

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

* クラス [PdfFileSecurity](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)