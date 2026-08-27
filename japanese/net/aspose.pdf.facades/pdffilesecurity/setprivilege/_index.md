---
title: "PdfFileSecurity.SetPrivilege"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileSecurity メソッド。空のユーザー/オーナーパスワードで Pdf ファイルのセキュリティを設定します。オーナーパスワードはランダムな文字列で追加されます。処理が失敗した場合は例外がスローされます"
type: docs
weight: 80
url: /ja/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

ユーザー/オーナーパスワードを空にして Pdf ファイルのセキュリティを設定します。オーナーパスワードはランダムな文字列が追加されます。処理が失敗した場合は例外をスローします。

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 権限 | DocumentPrivilege | 権限を設定します。 |

### 戻り値

成功した場合は True。

## 例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### 関連項目

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

元のパスワードで Pdf ファイルのセキュリティを設定します。処理が失敗した場合は例外をスローします。

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| userPassword | String | 元のユーザーパスワード。 |
| ownerPassword | String | 元のオーナーパスワード。 |
| 権限 | DocumentPrivilege | 権限を設定します。 |

### 戻り値

成功した場合は True。

## 例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### 関連項目

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


