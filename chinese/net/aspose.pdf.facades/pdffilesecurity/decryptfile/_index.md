---
title: "PdfFileSecurity.DecryptFile"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileSecurity 方法。通过所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。处理失败时抛出异常"
type: docs
weight: 60
url: /zh/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile method

通过所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。若处理失败，则抛出异常。

```csharp
public bool DecryptFile(string ownerPassword)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | String | 所有者密码。 |

### 返回值

成功时返回 true。

## 示例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.DecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.DecryptFile("ownerpass")
```

### 另请参见

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


