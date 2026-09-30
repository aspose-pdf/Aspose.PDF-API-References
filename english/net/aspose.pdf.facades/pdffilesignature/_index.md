---
title: "PdfFileSignature Class"
linktitle: "PdfFileSignature"
articleTitle: "PdfFileSignature"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfFileSignature class. Represents a class to sign a pdf file with a certificate."
type: docs
weight: 440
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
| [PdfFileSignature](./pdffilesignature/#constructor)() | The constructor of PdfFileSignature class. |
| [PdfFileSignature](./pdffilesignature/#constructor_1)(Document) | Initializes new [`PdfFileSignature`](../../aspose.pdf.facades/pdffilesignature/) object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [IsCertified](./iscertified/) { get; } | Gets the flag determining whether a document is certified or not. |
| [IsLtvEnabled](./isltvenabled/) { get; } | Gets the LTV enabled flag. |
| [SignatureAppearance](./signatureappearance/) { get; set; } | Sets or gets a graphic appearance for the signature. Property value represents image file name. |
| [SignatureAppearanceStream](./signatureappearancestream/) { get; set; } | Sets or gets a graphic appearance for the signature. Property value represents image stream. |

## Methods

| Name | Description |
| --- | --- |
| override [BindPdf](./bindpdf/)(Stream) | Binds a Pdf stream for editing. |
| override [BindPdf](./bindpdf/)(string) | Binds a Pdf file for editing. |
| [Certify](./certify/)(string, DocMDPSignature) | Certify the document with the MDP signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see sigName parameter). |
| [Certify](./certify/)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certify the document with the MDP signature. Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig. |
| override [Close](./close/)() | Closes the facade. |
| [ContainsSignature](./containssignature/)() | Checks if the pdf has a digital signature or not. |
| [ContainsUsageRights](./containsusagerights/)() | Checks if the pdf has a usage rights or not. |
| [CoversWholeDocument](./coverswholedocument/)(SignatureName) | Checks if the signature covers the whole document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [ExtractCertificate](./extractcertificate/)(SignatureName) | Extracts signature's single X.509 certificate as a stream. |
| [ExtractImage](./extractimage/)(SignatureName) | Extracts signature's image. |
| [GetAccessPermissions](./getaccesspermissions/)() | Returns the access permissions value of certified document by the MDP signature type. |
| [GetBlankSignatureNames](./getblanksignaturenames/)() | Gets the names of all empty signature fields. |
| [GetContactInfo](./getcontactinfo/)(SignatureName) | Gets the contact information of a signature. |
| [GetDateTime](./getdatetime/)(SignatureName) | Gets the signature's datetime. |
| [GetLocation](./getlocation/)(SignatureName) | Gets the location of a signature. |
| [GetReason](./getreason/)(SignatureName) | Gets the reason of a signature. |
| [GetRevision](./getrevision/)(SignatureName) | Gets the revision of a signature. |
| [GetSignatureNames](./getsignaturenames/)(bool) | Gets the names of all not empty signatures. |
| [GetSignaturesInfo](./getsignaturesinfo/)() | Retrieves information about all signatures algorithm present in the PDF document. |
| [GetSignerName](./getsignername/)(SignatureName) | Gets the name of person or organization who signing the pdf document. |
| [GetTotalRevision](./gettotalrevision/)() | Gets the toltal revision. |
| [RemoveSignature](./removesignature/)(SignatureName) | Remove the signature according to the name of the signature. |
| [RemoveSignature](./removesignature/)(SignatureName, bool) | Removes the signature according to the name of the signature. |
| [RemoveSignatures](./removesignatures/)() | Removes all signatures. |
| [RemoveUsageRights](./removeusagerights/)() | Removes the usage rights entry. |
| override [Save](./save/)(Stream) | Saves the result PDF to stream. |
| override [Save](./save/)(string) | Saves the result PDF to file. |
| [SetCertificate](./setcertificate/)(string, string) | Set certificate file and password for signing routine. |
| [Sign](./sign/)(string, Signature) | Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig. |
| [Sign](./sign/)(int, bool, Rectangle, Signature) | Sign the document with the given type signature. |
| [Sign](./sign/)(string, string, string, string, Signature) | Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). |
| [Sign](./sign/)(int, string, string, string, bool, Rectangle) | Make a signature on the pdf document. |
| [Sign](./sign/)(int, string, string, string, bool, Rectangle, Signature) | Sign the document with the given type signature. |
| [Sign](./sign/)(int, string, string, string, string, bool, Rectangle, Signature) | Sign the document with the given type signature which is placed in already presented signature field. Before signing pdf document should already has signature field, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). |
| [TryExtractCertificate](./tryextractcertificate/)(SignatureName, out Stream) | Extracts signature's single X.509 certificate as a stream. |
| [TryExtractCertificate](./tryextractcertificate/)(SignatureName, out X509Certificate2) | Extracts signature's single X.509 certificate. |
| [TryVerifySignature](./tryverifysignature/)(SignatureName, out VerificationResult) | Try to check the validity of a signature. |
| [TryVerifySignature](./tryverifysignature/)(SignatureName, X509Certificate2, out VerificationResult) | Try to check the validity of a signature. Verification is performed using the external public key certificate. |
| [TryVerifySignature](./tryverifysignature/)(SignatureName, ValidationOptions, out ValidationResult, out VerificationResult) | Try to check the validity of a signature. |
| [TryVerifySignature](./tryverifysignature/)(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult, out VerificationResult) | Try to check the validity of a signature. Verification is performed using the external public key certificate. |
| [VerifySignature](./verifysignature/)(SignatureName) | Checks the validity of a signature. |
| [VerifySignature](./verifysignature/)(SignatureName, X509Certificate2) | Checks the validity of a signature. Verification is performed using the external public key certificate. |
| [VerifySignature](./verifysignature/)(SignatureName, ValidationOptions, out ValidationResult) | Checks the validity of a signature. |
| [VerifySignature](./verifysignature/)(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) | Checks the validity of a signature. Verification is performed using the external public key certificate. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

