---
title: SetPrivilege
second_title: Aspose.PDF for .NET API 参考
description: 使用空的用户/所有者密码设置 Pdf 文件安全性 所有者密码将由随机字符串添加 如果进程失败则抛出异常
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

使用空的用户/所有者密码设置 Pdf 文件安全性。 所有者密码将由随机字符串添加。 如果进程失败则抛出异常。

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| privilege | DocumentPrivilege | 设置权限。 |

### 返回值

真正的成功。

### 例子

```csharp
[C#]
string inFile = "D:\\input.pdf"; //TestPath 可能会被重新分配。
string outFile = "D:\\output.pdf"; //TestPath 可能会被重新分配。
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### 也可以看看

* class [DocumentPrivilege](../../documentprivilege)
* class [PdfFileSecurity](../../pdffilesecurity)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilesecurity)
* 部件 [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

使用原始密码设置 Pdf 文件安全性。 如果处理失败，则抛出异常。

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | String | 原始用户密码。 |
| ownerPassword | String | 原始所有者密码。 |
| privilege | DocumentPrivilege | 设置权限。 |

### 返回值

真正的成功。

### 例子

```csharp
[C#]
string inFile = "D:\\input.pdf"; //TestPath 可能会被重新分配。
string outFile = "D:\\output.pdf"; //TestPath 可能会被重新分配。
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### 也可以看看

* class [DocumentPrivilege](../../documentprivilege)
* class [PdfFileSecurity](../../pdffilesecurity)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilesecurity)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->