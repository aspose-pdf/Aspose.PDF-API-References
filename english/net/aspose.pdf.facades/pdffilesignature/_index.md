---
title: Class PdfFileSignature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSignature class. Represents a class to sign a pdf file with a certificate
type: docs
weight: 4680
url: /net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

Represents a class to sign a pdf file with a certificate.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | The constructor of PdfFileSignature class. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Initializes new `PdfFileSignature` object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Gets the flag determining whether a document is certified or not. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Gets the LTV enabled flag. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Sets or gets a graphic appearance for the signature. Property value represents image file name. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Sets or gets a graphic appearance for the signature. Property value represents image stream. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initializes the facade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Binds a Pdf stream for editing. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Binds a Pdf file for editing. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Certify the document with the MDP signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see sigName parameter). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certify the document with the MDP signature. Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Closes the facade. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Checks if the pdf has a digital signature or not. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Checks if the pdf has a usage rights or not. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Checks if the signature covers the whole document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Extracts signature's single X.509 certificate as a stream. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Extracts signature's image. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Returns the access permissions value of certified document by the MDP signature type. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Gets the names of all empty signature fields. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Gets the contact information of a signature. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Gets the signature's datetime. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Gets the location of a signature. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Gets the reason of a signature. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Gets the revision of a signature. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Gets the names of all not empty signatures. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Retrieves information about all signatures algorithm present in the PDF document. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Gets the name of person or organization who signing the pdf document. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Gets the toltal revision. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Remove the signature according to the name of the signature. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Removes the signature according to the name of the signature. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Removes all signatures. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Removes the usage rights entry. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Saves the result PDF to stream. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Saves the result PDF to file. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Set certificate file and password for signing routine. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Sign the document with the given type signature. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Make a signature on the pdf document. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Sign the document with the given type signature. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Sign the document with the given type signature which is placed in already presented signature field. Before signing pdf document should already has signature field, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate)(SignatureName, out Stream) | Extracts signature's single X.509 certificate as a stream. |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate_1)(SignatureName, out X509Certificate2) | Extracts signature's single X.509 certificate. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Checks the validity of a signature. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_2)(SignatureName, X509Certificate2) | Checks the validity of a signature. Verification is performed using the external public key certificate. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Checks the validity of a signature. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_3)(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) | Checks the validity of a signature. Verification is performed using the external public key certificate. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


