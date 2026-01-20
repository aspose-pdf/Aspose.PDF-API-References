---
title: Aspose::Pdf::Facades::PdfFileSignature class
linktitle: PdfFileSignature
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSignature class. Represents a class to sign a pdf file with a certificate in C++.'
type: docs
weight: 2500
url: /cpp/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class


Represents a class to sign a pdf file with a certificate.

```cpp
class PdfFileSignature : public Aspose::Pdf::Facades::SaveableFacade
```

## Methods

| Method | Description |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Binds a [Pdf](../../aspose.pdf/) file for editing. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Binds a [Pdf](../../aspose.pdf/) stream for editing. |
| [Certify](./certify/)(int32_t, System::String, System::String, System::String, bool, System::Drawing::Rectangle, System::SharedPtr\<Forms::DocMDPSignature\>) | Certify the document with the MDP signature. Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig. |
| [Certify](./certify/)(System::String, System::SharedPtr\<Forms::DocMDPSignature\>) | Certify the document with the MDP signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see sigName parameter). |
| [Close](./close/)() override | Closes the facade. |
| [ContainsSignature](./containssignature/)() | Checks if the pdf has a digital signature or not. |
| [ContainsUsageRights](./containsusagerights/)() | Checks if the pdf has a usage rights or not. |
| [CoversWholeDocument](./coverswholedocument/)(System::String) | Checks if the signature covers the whole document. |
| [CoversWholeDocument](./coverswholedocument/)(System::SharedPtr\<SignatureName\>) | Checks if the signature covers the whole document. |
| [ExtractCertificate](./extractcertificate/)(System::String) | Extracts signature's single X.509 certificate as a stream. |
| [ExtractCertificate](./extractcertificate/)(System::SharedPtr\<SignatureName\>) | Extracts signature's single X.509 certificate as a stream. |
| [ExtractImage](./extractimage/)(System::String) | Extracts signature's image. |
| [ExtractImage](./extractimage/)(System::SharedPtr\<SignatureName\>) | Extracts signature's image. |
| [get_IsCertified](./get_iscertified/)() | Gets the flag determining whether a document is certified or not. |
| [get_IsLtvEnabled](./get_isltvenabled/)() | Gets the LTV enabled flag. |
| [get_SignatureAppearance](./get_signatureappearance/)() const | Sets or gets a graphic appearance for the signature. Property value represents image file name. |
| [get_SignatureAppearanceStream](./get_signatureappearancestream/)() const | Sets or gets a graphic appearance for the signature. Property value represents image stream. |
| [GetAccessPermissions](./getaccesspermissions/)() | Returns the access permissions value of certified document by the MDP signature type. |
| [GetBlankSignatureNames](./getblanksignaturenames/)() | Gets the names of all empty signature fields. |
| [GetBlankSignNames](./getblanksignnames/)() | Gets the names of all empty signature fields. |
| [GetContactInfo](./getcontactinfo/)(System::String) | Gets the contact information of a signature. |
| [GetContactInfo](./getcontactinfo/)(System::SharedPtr\<SignatureName\>) | Gets the contact information of a signature. |
| [GetDateTime](./getdatetime/)(System::String) | Gets the signature's datetime. |
| [GetDateTime](./getdatetime/)(System::SharedPtr\<SignatureName\>) | Gets the signature's datetime. |
| [GetLocation](./getlocation/)(System::String) | Gets the location of a signature. |
| [GetLocation](./getlocation/)(System::SharedPtr\<SignatureName\>) | Gets the location of a signature. |
| [GetReason](./getreason/)(System::String) | Gets the reason of a signature. |
| [GetReason](./getreason/)(System::SharedPtr\<SignatureName\>) | Gets the reason of a signature. |
| [GetRevision](./getrevision/)(System::String) | Gets the revision of a signature. |
| [GetRevision](./getrevision/)(System::SharedPtr\<SignatureName\>) | Gets the revision of a signature. |
| [GetSignatureNames](./getsignaturenames/)(bool) | Gets the names of all not empty signatures. |
| [GetSignaturesInfo](./getsignaturesinfo/)() | Retrieves information about all signatures algorithm present in the PDF document. |
| [GetSignerName](./getsignername/)(System::String) | Gets the name of person or organization who signing the pdf document. |
| [GetSignerName](./getsignername/)(System::SharedPtr\<SignatureName\>) | Gets the name of person or organization who signing the pdf document. |
| [GetSignNames](./getsignnames/)(bool) | Gets the names of all not empty signatures. |
| [GetTotalRevision](./gettotalrevision/)() | Gets the toltal revision. |
| [IsContainSignature](./iscontainsignature/)() | Checks if the pdf has a digital signature or not. |
| [IsCoversWholeDocument](./iscoverswholedocument/)(System::String) | Checks if the signature covers the whole document. |
| [PdfFileSignature](./pdffilesignature/)() | The constructor of [PdfFileSignature](./) class. |
| [PdfFileSignature](./pdffilesignature/)(System::String) | The constructor of [PdfFileSignature](./) class. |
| [PdfFileSignature](./pdffilesignature/)(System::String, System::String) | The constructor of [PdfFileSignature](./) class. |
| [PdfFileSignature](./pdffilesignature/)(System::SharedPtr\<Aspose::Pdf::Document\>) | Initializes new [PdfFileSignature](./) object on base of the *document* . |
| [PdfFileSignature](./pdffilesignature/)(System::SharedPtr\<Aspose::Pdf::Document\>, System::String) | Initializes new [PdfFileSignature](./) object on base of the *document* . |
| [RemoveSignature](./removesignature/)(System::String) | Remove the signature according to the name of the signature. |
| [RemoveSignature](./removesignature/)(System::SharedPtr\<SignatureName\>) | Remove the signature according to the name of the signature. |
| [RemoveSignature](./removesignature/)(System::String, bool) | Removes the signature according to the name of the signature. |
| [RemoveSignature](./removesignature/)(System::SharedPtr\<SignatureName\>, bool) | Removes the signature according to the name of the signature. |
| [RemoveSignatures](./removesignatures/)() | Removes all signatures. |
| [RemoveUsageRights](./removeusagerights/)() | Removes the usage rights entry. |
| [Save](./save/)(System::String) override | Saves the result PDF to file. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Saves the result PDF to stream. |
| [Save](./save/)() | Save signed pdf file. Output filename must be provided before with the help of coresponding [PdfFileSignature](./) constructor. |
| [set_SignatureAppearance](./set_signatureappearance/)(System::String) | Sets or gets a graphic appearance for the signature. Property value represents image file name. |
| [set_SignatureAppearanceStream](./set_signatureappearancestream/)(System::SharedPtr\<System::IO::Stream\>) | Sets or gets a graphic appearance for the signature. Property value represents image stream. |
| [SetCertificate](./setcertificate/)(System::String, System::String) | Set certificate file and password for signing routine. |
| [Sign](./sign/)(int32_t, System::String, System::String, System::String, bool, System::Drawing::Rectangle) | Make a signature on the pdf document. |
| [Sign](./sign/)(int32_t, System::String, System::String, System::String, bool, System::Drawing::Rectangle, System::SharedPtr\<Forms::Signature\>) | Sign the document with the given type signature. |
| [Sign](./sign/)(int32_t, bool, System::Drawing::Rectangle, System::SharedPtr\<Forms::Signature\>) | Sign the document with the given type signature. |
| [Sign](./sign/)(System::String, System::String, System::String, System::String, System::SharedPtr\<Forms::Signature\>) | Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). |
| [Sign](./sign/)(int32_t, System::String, System::String, System::String, System::String, bool, System::Drawing::Rectangle, System::SharedPtr\<Forms::Signature\>) | Sign the document with the given type signature which is placed in already presented signature field. Before signing pdf document should already has signature field, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). |
| [Sign](./sign/)(System::String, System::SharedPtr\<Forms::Signature\>) | Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig. |
| [TryExtractCertificate](./tryextractcertificate/)(System::SharedPtr\<SignatureName\>, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) | Extracts signature's single X.509 certificate. |
| [TryExtractCertificate](./tryextractcertificate/)(System::SharedPtr\<SignatureName\>, System::SharedPtr\<System::IO::Stream\>\&) | Extracts signature's single X.509 certificate as a stream. |
| [VerifySignature](./verifysignature/)(System::String) | Checks the validity of a signature. |
| [VerifySignature](./verifysignature/)(System::SharedPtr\<SignatureName\>) | Checks the validity of a signature. |
| [VerifySignature](./verifysignature/)(System::String, System::SharedPtr\<Security::ValidationOptions\>, System::SharedPtr\<Security::ValidationResult\>\&) | Checks the validity of a signature. |
| [VerifySignature](./verifysignature/)(System::SharedPtr\<SignatureName\>, System::SharedPtr\<Security::ValidationOptions\>, System::SharedPtr\<Security::ValidationResult\>\&) | Checks the validity of a signature. |
| [VerifySignature](./verifysignature/)(System::SharedPtr\<SignatureName\>, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>, System::SharedPtr\<Security::ValidationOptions\>, System::SharedPtr\<Security::ValidationResult\>\&) | Checks the validity of a signature. Verification is performed using the external public key certificate. |
| [VerifySignature](./verifysignature/)(System::SharedPtr\<SignatureName\>, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) | Checks the validity of a signature. Verification is performed using the external public key certificate. |
| [VerifySigned](./verifysigned/)(System::String) | Checks the validity of a signature. The method is deprecated and will be deleted in 25.1 version. Use VerifySignature method instead. |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
