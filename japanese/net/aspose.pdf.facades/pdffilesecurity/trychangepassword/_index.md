---
title: PdfFileSecurity.TryChangePassword
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity メソッド。ユーザーパスワードとオーナーパスワードを変更し、オーナーパスワードが元のセキュリティ設定を保持します。新しいユーザーパスワードと新しいオーナーパスワードは null または空であることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。プロセスが失敗した場合は例外をスローしません。
type: docs
weight: 90
url: /ja/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

オーナーパスワードによってユーザーパスワードとオーナーパスワードを変更し、元のセキュリティ設定を保持します。新しいユーザーパスワードと新しいオーナーパスワードは null または空であることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。プロセスが失敗した場合は例外をスローしません。

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ownerPassword | String | 元のオーナーパスワード。 |
| newUserPassword | String | 新しいユーザーパスワード。 |
| newOwnerPassword | String | 新しいオーナーパスワード。 |

### 戻り値

成功の場合は true、失敗の場合は false。

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

### 参照

* クラス [PdfFileSecurity](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

オーナーパスワードによってユーザーパスワードとパスワードを変更し、Pdf ドキュメントのセキュリティをリセットします。新しいユーザーパスワードと新しいオーナーパスワードは null または空であることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。プロセスが失敗した場合は例外をスローしません。

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ownerPassword | String | 元のオーナーパスワード。 |
| newUserPassword | String | 新しいユーザーパスワード。 |
| newOwnerPassword | String | 新しいオーナーパスワード。 |
| privilege | DocumentPrivilege | セキュリティをリセットします。 |
| keySize | KeySize | KeySize.x40 は 40 ビット暗号化、KeySize.x128 は 128 ビット暗号化、KeySize.x256 は 256 ビット暗号化です。 |

### 戻り値

成功の場合は true、失敗の場合は false。

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

### 参照

* クラス [DocumentPrivilege](../../documentprivilege/)
* 列挙 [KeySize](../../keysize/)
* クラス [PdfFileSecurity](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

オーナーパスワードによってユーザーパスワードとパスワードを変更し、Pdf ドキュメントのセキュリティをリセットします。新しいユーザーパスワードと新しいオーナーパスワードは null または空であることができます。新しいオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。KeySize と Algorithm の値の組み合わせは 6 通りあります。ただし、(KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効であり、この組み合わせに遭遇した場合は対応する例外が発生します。プロセスが失敗した場合は例外をスローしません。

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ownerPassword | String | 元のオーナーパスワード。 |
| newUserPassword | String | 新しいユーザーパスワード。 |
| newOwnerPassword | String | 新しいオーナーパスワード。 |
| privilege | DocumentPrivilege | セキュリティをリセットします。 |
| keySize | KeySize | KeySize.x40 は 40 ビット暗号化、KeySize.x128 は 128 ビット暗号化、KeySize.x256 は 256 ビット暗号化です。 |
| cipher | Algorithm | Algorithm.AES は AES アルゴリズムを使用して暗号化するため、Algorithm.RC4 は RC4 暗号化のためです。 |

### 戻り値

成功の場合は true、失敗の場合は false。

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

### 参照

* クラス [DocumentPrivilege](../../documentprivilege/)
* 列挙 [KeySize](../../keysize/)
* 列挙 [Algorithm](../../algorithm/)
* クラス [PdfFileSecurity](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)