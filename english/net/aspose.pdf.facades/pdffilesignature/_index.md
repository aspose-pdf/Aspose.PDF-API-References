---
title: "PdfFileSignature Class"
linktitle: "PdfFileSignature"
articleTitle: "PdfFileSignature"
second_title: "Aspose.PDF for .NET"
description: "Represents a class to sign a pdf file with a certificate."
type: docs
weight: 450
url: "/net/aspose.pdf.facades/pdffilesignature/"
keywords: "PdfFileSignature, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfFileSignature class

Represents a class to sign a pdf file with a certificate.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileSignature](./pdffilesignature/#constructor) | The constructor of PdfFileSignature class. |
| [PdfFileSignature](./pdffilesignature/#constructor_1)(*string*) | The constructor of PdfFileSignature class. |
| [PdfFileSignature](./pdffilesignature/#constructor_2)(*[Document](../../aspose.pdf/document/)*) | Initializes new [`PdfFileSignature`](../../aspose.pdf.facades/pdffilesignature/) object on base of the . |
| [PdfFileSignature](./pdffilesignature/#constructor_3)(*string, string*) | The constructor of PdfFileSignature class. |
| [PdfFileSignature](./pdffilesignature/#constructor_4)(*[Document](../../aspose.pdf/document/), string*) | Initializes new [`PdfFileSignature`](../../aspose.pdf.facades/pdffilesignature/) object on base of the . |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. *(Inherited from Facade)* |
| [IsCertified](./iscertified/) { get; } | Gets the flag determining whether a document is certified or not. |
| [IsLtvEnabled](./isltvenabled/) { get; } | Gets the LTV enabled flag. |
| [SignatureAppearance](./signatureappearance/) { get; set; } | Sets or gets a graphic appearance for the signature. Property value represents image file name. |
| [SignatureAppearanceStream](./signatureappearancestream/) { get; set; } | Sets or gets a graphic appearance for the signature. Property value represents image stream. |

## Methods

| Name | Description |
| --- | --- |
| [AssertDocument](../../aspose.pdf.facades/facade/assertdocument/) | Asserts if the facade is initialized. *(Inherited from Facade)* |
| [BindPdf](./bindpdf/)(*string*) | Binds a Pdf file for editing. |
| [BindPdf](./bindpdf/)(*Stream*) | Binds a Pdf stream for editing. |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string, string*) | Initializes the facade. *(Inherited from Facade)* |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string, string, ICustomSecurityHandler*) | Initializes the facade. *(Inherited from Facade)* |
| [Certify](./certify/)(*string, DocMDPSignature*) | Certify the document with the MDP signature which is placed in already presented signature field. |
| [Certify](./certify/)(*int, string, string, string, bool, Rectangle, DocMDPSignature*) | Certify the document with the MDP signature. |
| [Close](./close/) | Closes the facade. |
| [ContainsSignature](./containssignature/) | Checks if the pdf has a digital signature or not. |
| [ContainsUsageRights](./containsusagerights/) | Checks if the pdf has a usage rights or not. |
| [CoversWholeDocument](./coverswholedocument/)(*string*) | Checks if the signature covers the whole document. |
| [CoversWholeDocument](./coverswholedocument/)(*SignatureName*) | Checks if the signature covers the whole document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/) | Disposes the facade. *(Inherited from Facade)* |
| [ExtractCertificate](./extractcertificate/)(*string*) | Extracts signature's single X.509 certificate as a stream. |
| [ExtractCertificate](./extractcertificate/)(*SignatureName*) | Extracts signature's single X.509 certificate as a stream. |
| [ExtractImage](./extractimage/)(*string*) | Extracts signature's image. |
| [ExtractImage](./extractimage/)(*SignatureName*) | Extracts signature's image. |
| [GetAccessPermissions](./getaccesspermissions/) | Returns the access permissions value of certified document by the MDP signature type. |
| [GetBlankSignNames](./getblanksignnames/) | Gets the names of all empty signature fields. |
| [GetBlankSignatureNames](./getblanksignaturenames/) | Gets the names of all empty signature fields. |
| [GetContactInfo](./getcontactinfo/)(*string*) | Gets the contact information of a signature. |
| [GetContactInfo](./getcontactinfo/)(*SignatureName*) | Gets the contact information of a signature. |
| [GetDateTime](./getdatetime/)(*string*) | Gets the signature's datetime. |
| [GetDateTime](./getdatetime/)(*SignatureName*) | Gets the signature's datetime. |
| [GetLocation](./getlocation/)(*string*) | Gets the location of a signature. |
| [GetLocation](./getlocation/)(*SignatureName*) | Gets the location of a signature. |
| [GetReason](./getreason/)(*string*) | Gets the reason of a signature. |
| [GetReason](./getreason/)(*SignatureName*) | Gets the reason of a signature. |
| [GetRevision](./getrevision/)(*string*) | Gets the revision of a signature. |
| [GetRevision](./getrevision/)(*SignatureName*) | Gets the revision of a signature. |
| [GetSignNames](./getsignnames/)(*bool*) | Gets the names of all not empty signatures. |
| [GetSignatureNames](./getsignaturenames/)(*bool*) | Gets the names of all not empty signatures. |
| [GetSignaturesInfo](./getsignaturesinfo/) | Retrieves information about all signatures algorithm present in the PDF document. |
| [GetSignerName](./getsignername/)(*string*) | Gets the name of person or organization who signing the pdf document. |
| [GetSignerName](./getsignername/)(*SignatureName*) | Gets the name of person or organization who signing the pdf document. |
| [GetTotalRevision](./gettotalrevision/) | Gets the toltal revision. |
| [IsContainSignature](./iscontainsignature/) | Checks if the pdf has a digital signature or not. |
| [IsCoversWholeDocument](./iscoverswholedocument/)(*string*) | Checks if the signature covers the whole document. |
| [RemoveSignature](./removesignature/)(*string*) | Remove the signature according to the name of the signature. |
| [RemoveSignature](./removesignature/)(*SignatureName*) | Remove the signature according to the name of the signature. |
| [RemoveSignature](./removesignature/)(*string, bool*) | Removes the signature according to the name of the signature. |
| [RemoveSignature](./removesignature/)(*SignatureName, bool*) | Removes the signature according to the name of the signature. |
| [RemoveSignatures](./removesignatures/) | Removes all signatures. |
| [RemoveUsageRights](./removeusagerights/) | Removes the usage rights entry. |
| [Save](./save/) | Save signed pdf file. Output filename must be provided before with the help of coresponding PdfFileSignature constructor. |
| [Save](./save/)(*string*) | Saves the result PDF to file. |
| [Save](./save/)(*Stream*) | Saves the result PDF to stream. |
| [SetCertificate](./setcertificate/)(*string, string*) | Set certificate file and password for signing routine. |
| [Sign](./sign/)(*string, Signature*) | Sign the document with the given type signature which is placed in already presented signature field. |
| [Sign](./sign/)(*int, bool, Rectangle, Signature*) | Sign the document with the given type signature. |
| [Sign](./sign/)(*string, string, string, string, Signature*) | Sign the document with the given type signature which is placed in already presented signature field. |
| [Sign](./sign/)(*int, string, string, string, bool, Rectangle*) | Make a signature on the pdf document. |
| [Sign](./sign/)(*int, string, string, string, bool, Rectangle, Signature*) | Sign the document with the given type signature. |
| [Sign](./sign/)(*int, string, string, string, string, bool, Rectangle, Signature*) | Sign the document with the given type signature which is placed in already presented signature field. |
| [TryExtractCertificate](./tryextractcertificate/)(*SignatureName, X509Certificate2*) |  |
| [TryExtractCertificate](./tryextractcertificate/)(*SignatureName, Stream*) |  |
| [TryVerifySignature](./tryverifysignature/)(*SignatureName, VerificationResult*) |  |
| [TryVerifySignature](./tryverifysignature/)(*SignatureName, X509Certificate2, VerificationResult*) |  |
| [TryVerifySignature](./tryverifysignature/)(*SignatureName, ValidationOptions, ValidationResult, VerificationResult*) |  |
| [TryVerifySignature](./tryverifysignature/)(*SignatureName, X509Certificate2, ValidationOptions, ValidationResult, VerificationResult*) |  |
| [VerifySignature](./verifysignature/)(*string*) | Checks the validity of a signature. |
| [VerifySignature](./verifysignature/)(*SignatureName*) | Checks the validity of a signature. |
| [VerifySignature](./verifysignature/)(*SignatureName, X509Certificate2*) | Checks the validity of a signature. |
| [VerifySignature](./verifysignature/)(*string, ValidationOptions, ValidationResult*) |  |
| [VerifySignature](./verifysignature/)(*SignatureName, ValidationOptions, ValidationResult*) |  |
| [VerifySignature](./verifysignature/)(*SignatureName, X509Certificate2, ValidationOptions, ValidationResult*) |  |
| [VerifySigned](./verifysigned/)(*string*) | Checks the validity of a signature. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

