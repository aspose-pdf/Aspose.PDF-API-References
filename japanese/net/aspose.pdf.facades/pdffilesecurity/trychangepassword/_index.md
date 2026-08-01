---
title: "PdfFileSecurity.TryChangePassword"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileSecurity メソッド。オーナーパスワードでユーザーパスワードとオーナーパスワードを変更し、元のセキュリティ設定を保持します。新しいユーザーパスワードと新しいオーナーパスワードは null または空にすることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。処理が失敗しても例外はスローされません。"
type: docs
weight: 90
url: /ja/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

オーナーパスワードを使用してユーザーパスワードとオーナーパスワードを変更し、元のセキュリティ設定を保持します。新しいユーザーパスワードと新しいオーナーパスワードは null または空にすることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。処理が失敗しても例外はスローされません。

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ownerPassword | String | 元のオーナーパスワード。 |
| newUserPassword | String | 新しいユーザーパスワード。 |
| newOwnerPassword | String | 新しいオーナーパスワード。 |

### 戻り値

成功した場合は True、失敗した場合は false。

## 例

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### 関連項目

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

オーナーパスワードでユーザーパスワードとオーナーパスワードを変更し、Pdf ドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードと新しいオーナーパスワードは null または空にすることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。処理が失敗しても例外はスローされません。

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ownerPassword | String | 元のオーナーパスワード。 |
| newUserPassword | String | 新しいユーザーパスワード。 |
| newOwnerPassword | String | 新しいオーナーパスワード。 |
| 権限 | DocumentPrivilege | セキュリティをリセットします。 |
| keySize | KeySize | KeySize.x40 は 40 ビット暗号化、KeySize.x128 は 128 ビット暗号化、KeySize.x256 は 256 ビット暗号化に使用します。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 例

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### 関連項目

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

オーナーパスワードでユーザーパスワードとオーナーパスワードを変更し、Pdf ドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードと新しいオーナーパスワードは null または空にすることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。KeySize と Algorithm の組み合わせは 6 通り可能です。ただし (KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効で、キットがこの組み合わせに遭遇した場合は対応する例外が発生します。処理が失敗しても例外はスローされません。

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ownerPassword | String | 元のオーナーパスワード。 |
| newUserPassword | String | 新しいユーザーパスワード。 |
| newOwnerPassword | String | 新しいオーナーパスワード。 |
| 権限 | DocumentPrivilege | セキュリティをリセットします。 |
| keySize | KeySize | KeySize.x40 は 40 ビット暗号化、KeySize.x128 は 128 ビット暗号化、KeySize.x256 は 256 ビット暗号化に使用します。 |
| cipher | Algorithm | Algorithm.AES は AES アルゴリズムを使用して暗号化し、Algorithm.RC4 は RC4 暗号化に使用します。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### 関連項目

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


