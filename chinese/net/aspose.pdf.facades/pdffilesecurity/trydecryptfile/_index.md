---
title: "PdfFileSecurity.TryDecryptFile"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileSecurity 方法。通过所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。处理失败时不抛出异常"
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile method

使用所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。处理失败时不抛出异常。

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | String | 所有者密码。 |

### 返回值

成功时返回 true，或返回 false。

## 示例

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryDecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryDecryptFile("ownerpass")
```

### 另请参见

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


