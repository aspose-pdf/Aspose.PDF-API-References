---
title: TryDecryptFile
second_title: Aspose.PDF for .NET API 参考
description: 通过所有者密码解密加密的 Pdf 文档 如果文档没有所有者密码则允许使用用户密码 处理失败不抛出异常
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile method

通过所有者密码解密加密的 Pdf 文档。 如果文档没有所有者密码，则允许使用用户密码。 处理失败不抛出异常。

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | String | 所有者密码。 |

### 返回值

真为成功，或为假。

### 例子

```csharp
[C#]
string inFile = "D:\\input.pdf"; //TestPath 可能会被重新分配。
string outFile = "D:\\output.pdf"; //TestPath 可能会被重新分配。	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryDecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryDecryptFile("ownerpass")
```

### 也可以看看

* class [PdfFileSecurity](../../pdffilesecurity)
* 命名空间 [Aspose.Pdf.Facades](../../pdffilesecurity)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
