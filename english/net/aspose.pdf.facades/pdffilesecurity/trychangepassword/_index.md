---
title: "PdfFileSecurity.TryChangePassword"
linktitle: "TryChangePassword"
articleTitle: "TryChangePassword"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileSecurity method. Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the n..."
type: docs
weight: 160
url: "/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/"
product_version: "26.9.0"
---
## TryChangePassword(string, string, string) {#trychangepassword}

Changes the user password and owner password by owner password, keeps the original security settings.
 The new user password and the new owner password can be null or empty. The owner password will be replaced 
 Does not throw an exception if process failed.
 with a random string if the new owner password is null or empty.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | string | Original Owner password. |
| newUserPassword | string | New User password. |
| newOwnerPassword | string | New Owner password. |

### Return Value

bool

True for success,or false.

## Examples

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); 
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");
 
 [Visual Basic]
 Dim inFile As String = ".D:\\input.pdf" 'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf" 'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")
```

### See Also

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/), [KeySize](../../../aspose.pdf.facades/keysize/)) {#trychangepassword_1}

Changes the user password and password by owner password, allows to reset Pdf documnent security.
 The new user password and the new owner password can be null or empty. The owner password will be replaced 
 with a random string if the new owner password is null or empty.
 Does not throw an exception if process failed.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | string | Original owner password. |
| newUserPassword | string | New User password. |
| newOwnerPassword | string | New Owner password. |
| privilege | DocumentPrivilege | Reset security. |
| keySize | KeySize | KeySize.x40 for 40 bits encryption, KeySize.x128 for 128 bits encryption and KeySize.x256 for 256 bits encryption. |

### Return Value

bool

True for success, or false.

## Examples

```csharp
[C#]
 string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); 
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);
 
 [Visual Basic] 
 Dim inFile As String = ".D:\\input.pdf" 'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf" 'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### See Also

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/), [KeySize](../../../aspose.pdf.facades/keysize/), [Algorithm](../../../aspose.pdf.facades/algorithm/)) {#trychangepassword_2}

Changes the user password and password by owner password, allows to reset Pdf documnent security.
 The new user password and the new owner password can be null or empty. The owner password will be replaced 
 with a random string if the new owner password is null or empty.
 There are 6 possible combinations of KeySize and Algorithm values. 
 However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding 
 exception will be raised if kit encounters this combination.
 Does not throw an exception if process failed.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | string | Original owner password. |
| newUserPassword | string | New User password. |
| newOwnerPassword | string | New Owner password. |
| privilege | DocumentPrivilege | Reset security. |
| keySize | KeySize | KeySize.x40 for 40 bits encryption, KeySize.x128 for 128 bits encryption and KeySize.x256 for 256 bits encryption. |
| cipher | Algorithm | Algorithm.AES to encrypt using AES algorithm or Algorithm.RC4 for RC4 encryption. |

### Return Value

bool

True for success, or false.

## Examples

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); 
 bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);
 
 [Visual Basic] 
 Dim inFile As String = ".D:\\input.pdf" 'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf" 'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### See Also

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

