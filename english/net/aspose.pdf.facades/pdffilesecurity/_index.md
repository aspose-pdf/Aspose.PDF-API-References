---
title: "PdfFileSecurity Class"
linktitle: "PdfFileSecurity"
articleTitle: "PdfFileSecurity"
second_title: "Aspose.PDF for .NET"
description: "Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and password."
type: docs
weight: 440
url: "/net/aspose.pdf.facades/pdffilesecurity/"
keywords: "PdfFileSecurity, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfFileSecurity class

Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and password.

```csharp
public sealed class PdfFileSecurity : SaveableFacade, IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileSecurity](./pdffilesecurity/#constructor) | Initialize the object of PdfFileSecurity. |
| [PdfFileSecurity](./pdffilesecurity/#constructor_1)(*[Document](../../aspose.pdf/document/)*) | Initializes new [`PdfFileSecurity`](../../aspose.pdf.facades/pdffilesecurity/) object on base of the . |
| [PdfFileSecurity](./pdffilesecurity/#constructor_2)(*Stream, Stream*) | Initialize the object of PdfFileSecurity with input and output stream. |
| [PdfFileSecurity](./pdffilesecurity/#constructor_3)(*string, string*) | Initializes the object of PdfFileSecurity with input and output file. |
| [PdfFileSecurity](./pdffilesecurity/#constructor_4)(*[Document](../../aspose.pdf/document/), string*) | Initializes new [`PdfFileSecurity`](../../aspose.pdf.facades/pdffilesecurity/) object on base of the . |
| [PdfFileSecurity](./pdffilesecurity/#constructor_5)(*[Document](../../aspose.pdf/document/), Stream*) | Initializes new [`PdfFileSecurity`](../../aspose.pdf.facades/pdffilesecurity/) object on base of the . |

## Properties

| Name | Description |
| --- | --- |
| [AllowExceptions](./allowexceptions/) { get; set; } | If this value set to true, exception will be thrown on opearation failure. Else, method returns false on failure and last exception can be checked with LastException property. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. *(Inherited from Facade)* |
| [InputFile](./inputfile/) { set; } | Sets the input file. |
| [InputStream](./inputstream/) { set; } | Sets the input stream. |
| [LastException](./lastexception/) { get; } | Returns exception which was thrown by last operation. |
| [OutputFile](./outputfile/) { set; } | Sets the output file. |
| [OutputStream](./outputstream/) { set; } | Sets the output stream. |

## Methods

| Name | Description |
| --- | --- |
| [AssertDocument](../../aspose.pdf.facades/facade/assertdocument/) | Asserts if the facade is initialized. *(Inherited from Facade)* |
| [BindPdf](./bindpdf/)(*string*) | Initializes the facade. |
| [BindPdf](./bindpdf/)(*Stream*) | Initializes the facade. |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string, string*) | Initializes the facade. *(Inherited from Facade)* |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string, string, ICustomSecurityHandler*) | Initializes the facade. *(Inherited from Facade)* |
| [ChangePassword](./changepassword/)(*string, string, string*) | Changes the user password and owner password by owner password, keeps the original security settings. |
| [ChangePassword](./changepassword/)(*string, string, string, DocumentPrivilege, KeySize*) | Changes the user password and password by owner password, allows to reset Pdf documnent security. |
| [ChangePassword](./changepassword/)(*string, string, string, DocumentPrivilege, KeySize, Algorithm*) | Changes the user password and password by owner password, allows to reset Pdf documnent security. |
| [Close](./close/) | Closes the facade. |
| [DecryptFile](./decryptfile/)(*string*) | Decrypts an encrypted Pdf document by owner password. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/) | Disposes the facade. *(Inherited from Facade)* |
| [EncryptFile](./encryptfile/)(*string, string, DocumentPrivilege, KeySize*) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. |
| [EncryptFile](./encryptfile/)(*string, string, DocumentPrivilege, KeySize, Algorithm*) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. |
| [Save](../../aspose.pdf.facades/saveablefacade/save/)(*string*) | Saves the PDF document to the specified file. *(Inherited from SaveableFacade)* |
| [SetPrivilege](./setprivilege/)(*DocumentPrivilege*) | Sets Pdf file security with empty user/owner passwords. |
| [SetPrivilege](./setprivilege/)(*string, string, DocumentPrivilege*) | Sets Pdf file security with original password. |
| [TryChangePassword](./trychangepassword/)(*string, string, string*) | Changes the user password and owner password by owner password, keeps the original security settings. |
| [TryChangePassword](./trychangepassword/)(*string, string, string, DocumentPrivilege, KeySize*) | Changes the user password and password by owner password, allows to reset Pdf documnent security. |
| [TryChangePassword](./trychangepassword/)(*string, string, string, DocumentPrivilege, KeySize, Algorithm*) | Changes the user password and password by owner password, allows to reset Pdf documnent security. |
| [TryDecryptFile](./trydecryptfile/)(*string*) | Decrypts an encrypted Pdf document by owner password. |
| [TryEncryptFile](./tryencryptfile/)(*string, string, DocumentPrivilege, KeySize*) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. |
| [TrySetPrivilege](./trysetprivilege/)(*string, string, DocumentPrivilege*) | Sets Pdf file security with original password. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

