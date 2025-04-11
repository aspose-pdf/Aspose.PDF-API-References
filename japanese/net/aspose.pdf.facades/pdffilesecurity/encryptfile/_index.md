---
title: PdfFileSecurity.EncryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity メソッド。ユーザーパスワードとオーナーパスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権を設定します。ユーザーパスワードとオーナーパスワードは null または空にすることができます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。プロセスが失敗した場合は例外がスローされます。
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

ユーザーパスワードとオーナーパスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権を設定します。ユーザーパスワードとオーナーパスワードは null または空にすることができます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。プロセスが失敗した場合は例外がスローされます。

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワード。 |
| ownerPassword | String | オーナーパスワード。 |
| privilege | DocumentPrivilege | 権限を設定します。 |
| keySize | KeySize | KeySize.x40 は 40 ビット暗号化、KeySize.x128 は 128 ビット暗号化、KeySize.x256 は 256 ビット暗号化。 |

### 戻り値

成功の場合は True。

## 例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### 関連項目

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

ユーザーパスワードとオーナーパスワードで Pdf ファイルを暗号化し、ドキュメントのアクセス権を設定します。ユーザーパスワードとオーナーパスワードは null または空にすることができます。入力されたオーナーパスワードが null または空の場合、オーナーパスワードはランダムな文字列に置き換えられます。KeySize と Algorithm の値の組み合わせは 6 通りあります。ただし、(KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効であり、この組み合わせに遭遇した場合は対応する例外が発生します。プロセスが失敗した場合は例外がスローされます。

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワード。 |
| ownerPassword | String | オーナーパスワード。 |
| privilege | DocumentPrivilege | 権限を設定します。 |
| keySize | KeySize | KeySize.x40 は 40 ビット暗号化、KeySize.x128 は 128 ビット暗号化、KeySize.x256 は 256 ビット暗号化。 |
| cipher | Algorithm | Algorithm.AES を使用して AES アルゴリズムで暗号化するか、Algorithm.RC4 で RC4 暗号化を行います。 |

### 戻り値

成功の場合は True。

## 例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### 関連項目

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)