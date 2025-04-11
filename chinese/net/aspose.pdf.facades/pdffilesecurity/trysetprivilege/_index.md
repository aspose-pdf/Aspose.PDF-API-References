---
title: PdfFileSecurity.TrySetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity 方法。使用原始密码设置 Pdf 文件安全性。如果过程失败，则不会抛出异常
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## PdfFileSecurity.TrySetPrivilege 方法

使用原始密码设置 Pdf 文件安全性。如果过程失败，则不会抛出异常。

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | 字符串 | 原始用户密码。 |
| ownerPassword | 字符串 | 原始拥有者密码。 |
| privilege | DocumentPrivilege | 设置权限。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

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

### 另请参阅

* 类 [DocumentPrivilege](../../documentprivilege/)
* 类 [PdfFileSecurity](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)