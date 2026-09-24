---
title: "PdfFileSecurity.TryDecryptFile"
linktitle: "TryDecryptFile"
articleTitle: "TryDecryptFile"
second_title: "Aspose.PDF for .NET"
description: "Decrypts an encrypted Pdf document by owner password. If the document hasn't owner password, it is allow to use user password. Does not throw an exception if..."
type: docs
weight: 110
url: "/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/"
product_version: "26.9.0"
---
## TryDecryptFile(string) {#trydecryptfile}

Decrypts an encrypted Pdf document by owner password. 
 If the document hasn't owner password, it is allow to use user password.
 Does not throw an exception if process failed.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | string | Owner password. |

### Return Value

bool

True for success,or false.

## Examples

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned. 
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); 
 bool result = fileSecurity.TryDecryptFile("ownerpass");
 
 [Visual Basic]
 Dim inFile As String = "D:\\input.pdf" 'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf" 'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryDecryptFile("ownerpass")
```

### See Also

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

