---
title: "PdfFileSecurity.TrySetPrivilege"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileSecurity メソッド。元のパスワードで Pdf ファイルのセキュリティを設定します。処理が失敗しても例外はスローされません。"
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## PdfFileSecurity.TrySetPrivilege method

元のパスワードで Pdf ファイルのセキュリティを設定します。処理が失敗しても例外はスローされません。

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| userPassword | String | 元のユーザーパスワード。 |
| ownerPassword | String | 元のオーナーパスワード。 |
| 権限 | DocumentPrivilege | 権限を設定します。 |

### 戻り値

成功した場合は true、失敗した場合は false。

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

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


