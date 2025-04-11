---
title: PdfFileSecurity.TryEncryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity 方法。使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。用户密码和所有者密码可以为 null 或空。如果输入的所有者密码为 null 或空，则所有者密码将被随机字符串替换。如果处理失败，则不会抛出异常。
type: docs
weight: 110
url: /zh/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile 方法

使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。用户密码和所有者密码可以为 null 或空。如果输入的所有者密码为 null 或空，则所有者密码将被随机字符串替换。如果处理失败，则不会抛出异常。

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | 字符串 | 用户密码。 |
| ownerPassword | 字符串 | 所有者密码。 |
| privilege | DocumentPrivilege | 设置权限。 |
| keySize | KeySize | KeySize.x40 用于 40 位加密，KeySize.x128 用于 128 位加密，KeySize.x256 用于 256 位加密。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### 另请参阅

* 类 [DocumentPrivilege](../../documentprivilege/)
* 枚举 [KeySize](../../keysize/)
* 类 [PdfFileSecurity](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)