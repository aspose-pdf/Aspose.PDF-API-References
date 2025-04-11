---
title: PdfFileSecurity.EncryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity 方法。使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。用户密码和所有者密码可以为 null 或空。如果输入的所有者密码为 null 或空，则所有者密码将被随机字符串替换。如果处理失败，将抛出异常。
type: docs
weight: 70
url: /zh/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。用户密码和所有者密码可以为 null 或空。如果输入的所有者密码为 null 或空，则所有者密码将被随机字符串替换。如果处理失败，将抛出异常。

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | String | 用户密码。 |
| ownerPassword | String | 所有者密码。 |
| privilege | DocumentPrivilege | 设置权限。 |
| keySize | KeySize | KeySize.x40 用于 40 位加密，KeySize.x128 用于 128 位加密，KeySize.x256 用于 256 位加密。 |

### 返回值

成功返回 true。

## 示例

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

### 另请参阅

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。用户密码和所有者密码可以为 null 或空。如果输入的所有者密码为 null 或空，则所有者密码将被随机字符串替换。KeySize 和 Algorithm 值有 6 种可能的组合。然而 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果遇到这种组合，将引发相应的异常。如果处理失败，将抛出异常。

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | String | 用户密码。 |
| ownerPassword | String | 所有者密码。 |
| privilege | DocumentPrivilege | 设置权限。 |
| keySize | KeySize | KeySize.x40 用于 40 位加密，KeySize.x128 用于 128 位加密，KeySize.x256 用于 256 位加密。 |
| cipher | Algorithm | Algorithm.AES 使用 AES 算法加密或 Algorithm.RC4 进行 RC4 加密。 |

### 返回值

成功返回 true。

## 示例

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

### 另请参阅

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)