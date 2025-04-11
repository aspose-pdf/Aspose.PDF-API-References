---
title: PdfFileSecurity.TryDecryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity 方法。通过所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。如果处理失败，则不会抛出异常。
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile 方法

通过所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。如果处理失败，则不会抛出异常。

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | 字符串 | 所有者密码。 |

### 返回值

成功返回 true，失败返回 false。

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

### 另请参阅

* 类 [PdfFileSecurity](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)