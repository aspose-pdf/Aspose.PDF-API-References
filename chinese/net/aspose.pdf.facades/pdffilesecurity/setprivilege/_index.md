---
title: "PdfFileSecurity.SetPrivilege"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileSecurity 方法。使用空的用户/所有者密码设置 Pdf 文件安全。所有者密码将由随机字符串添加。如果过程失败，将抛出异常"
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

使用空的用户/所有者密码设置 Pdf 文件的安全性。所有者密码将由随机字符串添加。处理失败时抛出异常。

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 特权 | DocumentPrivilege | 设置特权。 |

### 返回值

成功时返回 true。

## 示例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### 另请参见

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

使用原始密码设置 Pdf 文件的安全性。处理失败时抛出异常。

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | String | 原始用户密码。 |
| ownerPassword | String | 原始所有者密码。 |
| 特权 | DocumentPrivilege | 设置特权。 |

### 返回值

成功时返回 true。

## 示例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### 另请参见

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


