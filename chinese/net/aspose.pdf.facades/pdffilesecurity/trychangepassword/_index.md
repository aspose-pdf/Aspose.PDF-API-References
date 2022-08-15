---
title: TryChangePassword
second_title: Aspose.PDF for .NET API 参考
description: 通过所有者密码更改用户密码和所有者密码保留原来的安全设置 新用户密码和新所有者密码可以为空或为空所有者密码将被替换 如果进程失败不会引发异常 如果新所有者密码为空或为空则使用随机字符串
type: docs
weight: 90
url: /zh/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

通过所有者密码更改用户密码和所有者密码，保留原来的安全设置。 新用户密码和新所有者密码可以为空或为空。所有者密码将被替换 如果进程失败不会引发异常。 如果新所有者密码为空或为空，则使用随机字符串。

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | String | 原始所有者密码。 |
| newUserPassword | String | 新用户密码。 |
| newOwnerPassword | String | 新所有者密码。 |

### 返回值

真为成功，或为假。

### 例子

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //TestPath 可能会被重新分配。
 string outFile = "D:\\output.pdf";	//TestPath 可能会被重新分配。
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### 也可以看看

* class [PdfFileSecurity](../../pdffilesecurity)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilesecurity)
* 部件 [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。 新用户密码和新所有者密码可以为空或空。如果新的所有者密码为空或空，所有者密码将被替换为随机字符串 。 如果处理失败不抛出异常。

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | String | 原始所有者密码。 |
| newUserPassword | String | 新用户密码。 |
| newOwnerPassword | String | 新所有者密码。 |
| privilege | DocumentPrivilege | 重置安全性。 |
| keySize | KeySize | KeySize.x40 用于 40 位加密，KeySize.x128 用于 128 位加密， KeySize.x256 用于 256 位加密。 |

### 返回值

真为成功，或为假。

### 例子

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //TestPath 可能会被重新分配。
string outFile = "D:\\output.pdf";	//TestPath 可能会被重新分配。
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### 也可以看看

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* class [PdfFileSecurity](../../pdffilesecurity)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilesecurity)
* 部件 [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。 新用户密码和新所有者密码可以为空或空。如果新的所有者密码为 null 或为空，所有者密码将被替换为随机字符串 。 KeySize 和 Algorithm 值有 6 种可能的组合。 但是 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 无效，如果 kit 遇到这种组合，将引发相应的 异常。 如果进程失败，则不抛出异常。

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | String | 原始所有者密码。 |
| newUserPassword | String | 新用户密码。 |
| newOwnerPassword | String | 新所有者密码。 |
| privilege | DocumentPrivilege | 重置安全性。 |
| keySize | KeySize | KeySize.x40 用于 40 位加密，KeySize.x128 用于 128 位加密， KeySize.x256 用于 256 位加密。 |
| cipher | Algorithm | 使用 AES 算法进行加密的 Algorithm.AES 或用于 RC4 加密的 Algorithm.RC4。 |

### 返回值

真为成功，或为假。

### 例子

```csharp
[C#]
string inFile = "D:\\input.pdf"; //TestPath 可能会被重新分配。
string outFile = "D:\\output.pdf";	//TestPath 可能会被重新分配。
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### 也可以看看

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* enum [Algorithm](../../algorithm)
* class [PdfFileSecurity](../../pdffilesecurity)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilesecurity)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
