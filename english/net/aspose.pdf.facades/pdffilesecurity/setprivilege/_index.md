---
title: "PdfFileSecurity.SetPrivilege"
linktitle: "SetPrivilege"
articleTitle: "SetPrivilege"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileSecurity method. Sets Pdf file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if p..."
type: docs
weight: 120
url: "/net/aspose.pdf.facades/pdffilesecurity/setprivilege/"
product_version: "26.9.0"
---
## SetPrivilege([DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)) {#setprivilege}

Sets Pdf file security with empty user/owner passwords.
 The owner password will be added by a random string.
 Throws an exception if process failed.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parameter | Type | Description |
| --- | --- | --- |
| privilege | DocumentPrivilege | Set privilege. |

### Return Value

bool

True for success.

## Examples

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); 
 fileSecurity.SetPrivilege(DocumentPrivilege.Print);
 
 [Visual Basic]
 Dim inFile As String = "D:\\input.pdf" 'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf" 'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### See Also

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)) {#setprivilege_1}

Sets Pdf file security with original password.
 Throws an exception if process failed.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | string | Original user password. |
| ownerPassword | string | Original owner password. |
| privilege | DocumentPrivilege | Set privilege. |

### Return Value

bool

True for success.

## Examples

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); 
 fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
 
 [Visual Basic]
 Dim inFile As String = "D:\\input.pdf" 'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf" 'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### See Also

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

