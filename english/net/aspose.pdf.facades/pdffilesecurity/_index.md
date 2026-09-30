---
title: "PdfFileSecurity Class"
linktitle: "PdfFileSecurity"
articleTitle: "PdfFileSecurity"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfFileSecurity class. Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and passw..."
type: docs
weight: 430
url: "/net/aspose.pdf.facades/pdffilesecurity/"
keywords: "PdfFileSecurity, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfFileSecurity class

Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and password.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileSecurity](./pdffilesecurity/#constructor)() | Initialize the object of PdfFileSecurity. |
| [PdfFileSecurity](./pdffilesecurity/#constructor_1)(Document) | Initializes new [`PdfFileSecurity`](../../aspose.pdf.facades/pdffilesecurity/) object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [LastException](./lastexception/) { get; } | Returns exception which was thrown by last operation. |

## Methods

| Name | Description |
| --- | --- |
| override [BindPdf](./bindpdf/)(Stream) | Initializes the facade. |
| override [BindPdf](./bindpdf/)(string) | Initializes the facade. |
| [ChangePassword](./changepassword/)(string, string, string) | Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Throws an exception if process failed. |
| [ChangePassword](./changepassword/)(string, string, string, DocumentPrivilege, KeySize) | Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Throws an exception if process failed. |
| [ChangePassword](./changepassword/)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed. |
| override [Close](./close/)() | Closes the facade. |
| [DecryptFile](./decryptfile/)(string) | Decrypts an encrypted Pdf document by owner password. If the document hasn't owner password, it is allow to use user password. Throws an exception if process failed. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [EncryptFile](./encryptfile/)(string, string, DocumentPrivilege, KeySize) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Throws exception if process failed. |
| [EncryptFile](./encryptfile/)(string, string, DocumentPrivilege, KeySize, Algorithm) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Saves the PDF document to the specified file. |
| [SetPrivilege](./setprivilege/)(DocumentPrivilege) | Sets Pdf file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed. |
| [SetPrivilege](./setprivilege/)(string, string, DocumentPrivilege) | Sets Pdf file security with original password. Throws an exception if process failed. |
| [TryChangePassword](./trychangepassword/)(string, string, string) | Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced Does not throw an exception if process failed. with a random string if the new owner password is null or empty. |
| [TryChangePassword](./trychangepassword/)(string, string, string, DocumentPrivilege, KeySize) | Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Does not throw an exception if process failed. |
| [TryChangePassword](./trychangepassword/)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Does not throw an exception if process failed. |
| [TryDecryptFile](./trydecryptfile/)(string) | Decrypts an encrypted Pdf document by owner password. If the document hasn't owner password, it is allow to use user password. Does not throw an exception if process failed. |
| [TryEncryptFile](./tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Does not throw an exception if process failed. |
| [TrySetPrivilege](./trysetprivilege/)(string, string, DocumentPrivilege) | Sets Pdf file security with original password. Does not throw an exception if process failed. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

