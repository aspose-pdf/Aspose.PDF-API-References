---
title: PdfFileSecurity
second_title: Aspose.PDF for .NET API Reference
description: Represents encrypting or decrypting a Pdf file with owner or user password changing the security setting and password.
type: docs
weight: 2510
url: /net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and password.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity#constructor)() | Initialize the object of PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity#constructor_1)(Document) | Initializes new [`PdfFileSecurity`](../pdffilesecurity) object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Gets the document facade is working on. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception) { get; } | Returns exception which was thrown by last operation. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initializes the facade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_1)(Stream) | Initializes the facade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_2)(string) | Initializes the facade. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword)(string, string, string) | Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Throws an exception if process failed. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Throws an exception if process failed. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close)() | Closes the facade. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile)(string) | Decrypts an encrypted Pdf document by owner password. If the document hasn't owner password, it is allow to use user password. Throws an exception if process failed. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disposes the facade. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile)(string, string, DocumentPrivilege, KeySize) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Throws exception if process failed. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Saves the PDF document to the specified stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Saves the PDF document to the specified file. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege)(DocumentPrivilege) | Sets Pdf file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege_1)(string, string, DocumentPrivilege) | Sets Pdf file security with original password. Throws an exception if process failed. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword)(string, string, string) | Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced Does not throw an exception if process failed. with a random string if the new owner password is null or empty. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Does not throw an exception if process failed. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Does not throw an exception if process failed. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile)(string) | Decrypts an encrypted Pdf document by owner password. If the document hasn't owner password, it is allow to use user password. Does not throw an exception if process failed. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile)(string, string, DocumentPrivilege, KeySize) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Does not throw an exception if process failed. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege)(string, string, DocumentPrivilege) | Sets Pdf file security with original password. Does not throw an exception if process failed. |

### See Also

* class [SaveableFacade](../saveablefacade)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
