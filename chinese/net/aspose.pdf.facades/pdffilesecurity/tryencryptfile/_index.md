---
title: "PdfFileSecurity.TryEncryptFile"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileSecurity 方法。使用用户密码和所有者密码加密 Pdf 文件并设置文档的访问权限。用户密码和所有者密码可以为 null 或空。如果输入的所有者密码为 null 或空，所有者密码将被随机字符串替代。处理失败时不抛出异常"
type: docs
weight: 110
url: /zh/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile method

使用 userpassword 和 ownerpassword 加密 Pdf 文件并设置文档的访问权限。user password 和 owner password 可以为 null 或为空。如果输入的 owner password 为 null 或为空，owner password 将被随机字符串替代。处理失败时不抛出异常。

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | String | 用户密码。 |
| ownerPassword | String | 所有者密码。 |
| 特权 | DocumentPrivilege | 设置特权。 |
| keySize | KeySize | KeySize.x40 表示 40 位加密，KeySize.x128 表示 128 位加密，KeySize.x256 表示 256 位加密。 |

### 返回值

成功返回 true，否则返回 false。

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

### 另请参见

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


