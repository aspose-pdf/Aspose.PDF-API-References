---
title: PdfFileSecurity.ChangePassword
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity method. Changes the user password and owner password by owner password keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Throws an exception if process failed
type: docs
weight: 40
url: /net/aspose.pdf.facades/pdffilesecurity/changepassword/
---
## ChangePassword(string, string, string) {#changepassword}

Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Throws an exception if process failed.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | String | Original Owner password. |
| newUserPassword | String | New User password. |
| newOwnerPassword | String | New Owner password. |

### Return Value

True for success.

## Examples

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 fileSecurity.ChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 fileSecurity.ChangePassword("owner","newuser","newowner")	
```

### See Also

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize) {#changepassword_1}

Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Throws an exception if process failed.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | String | Original owner password. |
| newUserPassword | String | New User password. |
| newOwnerPassword | String | New Owner password. |
| privilege | DocumentPrivilege | Reset security. |
| keySize | KeySize | KeySize.x40 for 40 bits encryption, KeySize.x128 for 128 bits encryption and KeySize.x256 for 256 bits encryption. |

### Return Value

True for success.

## Examples

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### See Also

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#changepassword_2}

Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | String | Original owner password. |
| newUserPassword | String | New User password. |
| newOwnerPassword | String | New Owner password. |
| privilege | DocumentPrivilege | Reset security. |
| keySize | KeySize | KeySize.x40 for 40 bits encryption, KeySize.x128 for 128 bits encryption and KeySize.x256 for 256 bits encryption. |
| cipher | Algorithm | Algorithm.AES to encrypt using AES algorithm or Algorithm.RC4 for RC4 encryption. |

### Return Value

True for success.

## Examples

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### See Also

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


