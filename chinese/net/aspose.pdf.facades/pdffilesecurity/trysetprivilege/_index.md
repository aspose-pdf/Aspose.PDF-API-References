---
title: "PdfFileSecurity.TrySetPrivilege"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileSecurity 方法。使用原始密码设置 Pdf 文件的安全性。处理失败时不抛出异常"
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## PdfFileSecurity.TrySetPrivilege method

使用原始密码设置 Pdf 文件的安全性。处理失败时不抛出异常。

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | String | 原始用户密码。 |
| ownerPassword | String | 原始所有者密码。 |
| 特权 | DocumentPrivilege | 设置特权。 |

### 返回值

成功返回 true，否则返回 false。

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

### 另请参见

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


