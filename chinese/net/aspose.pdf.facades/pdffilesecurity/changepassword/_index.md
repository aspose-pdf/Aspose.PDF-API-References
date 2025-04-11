---
title: PdfFileSecurity.ChangePassword
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity 方法。通过所有者密码更改用户密码和所有者密码，同时保持原始安全设置。新用户密码和新所有者密码可以为 null 或空。如果新所有者密码为 null 或空，则所有者密码将被随机字符串替换。如果处理失败，则抛出异常。
type: docs
weight: 40
url: /zh/net/aspose.pdf.facades/pdffilesecurity/changepassword/
---
## ChangePassword(string, string, string) {#changepassword}

通过所有者密码更改用户密码和所有者密码，同时保持原始安全设置。新用户密码和新所有者密码可以为 null 或空。如果新所有者密码为 null 或空，则所有者密码将被随机字符串替换。如果处理失败，则抛出异常。

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | 字符串 | 原始所有者密码。 |
| newUserPassword | 字符串 | 新用户密码。 |
| newOwnerPassword | 字符串 | 新所有者密码。 |

### 返回值

成功返回 true。

## 示例

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 fileSecurity.ChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 fileSecurity.ChangePassword("owner","newuser","newowner")	
```

### 另请参阅

* 类 [PdfFileSecurity](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize) {#changepassword_1}

通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。新用户密码和新所有者密码可以为 null 或空。如果新所有者密码为 null 或空，则所有者密码将被随机字符串替换。如果处理失败，则抛出异常。

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | 字符串 | 原始所有者密码。 |
| newUserPassword | 字符串 | 新用户密码。 |
| newOwnerPassword | 字符串 | 新所有者密码。 |
| privilege | DocumentPrivilege | 重置安全性。 |
| keySize | KeySize | KeySize.x40 表示 40 位加密，KeySize.x128 表示 128 位加密，KeySize.x256 表示 256 位加密。 |

### 返回值

成功返回 true。

## 示例

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### 另请参阅

* 类 [DocumentPrivilege](../../documentprivilege/)
* 枚举 [KeySize](../../keysize/)
* 类 [PdfFileSecurity](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#changepassword_2}

通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。新用户密码和新所有者密码可以为 null 或空。如果新所有者密码为 null 或空，则所有者密码将被随机字符串替换。KeySize 和 Algorithm 值有 6 种可能的组合。然而 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果遇到这种组合，将引发相应的异常。如果处理失败，则抛出异常。

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | 字符串 | 原始所有者密码。 |
| newUserPassword | 字符串 | 新用户密码。 |
| newOwnerPassword | 字符串 | 新所有者密码。 |
| privilege | DocumentPrivilege | 重置安全性。 |
| keySize | KeySize | KeySize.x40 表示 40 位加密，KeySize.x128 表示 128 位加密，KeySize.x256 表示 256 位加密。 |
| cipher | Algorithm | Algorithm.AES 使用 AES 算法加密或 Algorithm.RC4 进行 RC4 加密。 |

### 返回值

成功返回 true。

## 示例

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### 另请参阅

* 类 [DocumentPrivilege](../../documentprivilege/)
* 枚举 [KeySize](../../keysize/)
* 枚举 [Algorithm](../../algorithm/)
* 类 [PdfFileSecurity](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)