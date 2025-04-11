---
title: PdfFileSecurity.TrySetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity メソッド。元のパスワードで Pdf ファイルのセキュリティを設定します。プロセスが失敗した場合は例外をスローしません。
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## PdfFileSecurity.TrySetPrivilege メソッド

元のパスワードで Pdf ファイルのセキュリティを設定します。プロセスが失敗した場合は例外をスローしません。

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| userPassword | 文字列 | 元のユーザーパスワード。 |
| ownerPassword | 文字列 | 元のオーナーパスワード。 |
| privilege | DocumentPrivilege | 権限を設定します。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### 関連項目

* クラス [DocumentPrivilege](../../documentprivilege/)
* クラス [PdfFileSecurity](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)