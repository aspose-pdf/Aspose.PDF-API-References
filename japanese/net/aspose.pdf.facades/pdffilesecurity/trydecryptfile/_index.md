---
title: PdfFileSecurity.TryDecryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity メソッド。オーナーパスワードによって暗号化された Pdf ドキュメントを復号化します。ドキュメントにオーナーパスワードがない場合は、ユーザーパスワードを使用することが許可されています。プロセスが失敗しても例外はスローされません。
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile メソッド

オーナーパスワードによって暗号化された Pdf ドキュメントを復号化します。ドキュメントにオーナーパスワードがない場合は、ユーザーパスワードを使用することが許可されています。プロセスが失敗しても例外はスローされません。

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ownerPassword | 文字列 | オーナーパスワード。 |

### 戻り値

成功の場合は true、失敗の場合は false。

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

### 参照

* クラス [PdfFileSecurity](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)