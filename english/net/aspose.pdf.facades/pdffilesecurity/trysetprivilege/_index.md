---
title: "PdfFileSecurity.TrySetPrivilege"
linktitle: "TrySetPrivilege"
articleTitle: "TrySetPrivilege"
second_title: "Aspose.PDF for .NET"
description: "Sets Pdf file security with original password. Does not throw an exception if process failed."
type: docs
weight: 140
url: "/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/"
product_version: "26.9.0"
---
## TrySetPrivilege(string, string, [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)) {#trysetprivilege}

Sets Pdf file security with original password.
 Does not throw an exception if process failed.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | string | Original user password. |
| ownerPassword | string | Original owner password. |
| privilege | DocumentPrivilege | Set privilege. |

### Return Value

bool

True for success, or false.

## Examples

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); 
 bool result = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
 
 [Visual Basic]
 Dim inFile As String = "D:\\input.pdf" 'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf" 'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### See Also

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

