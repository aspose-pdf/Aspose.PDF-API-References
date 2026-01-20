---
title: Aspose::Pdf::Forms::Signature class
linktitle: Signature
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Signature class. An abstract class which represents signature object in the pdf document. Signatures are fields with values of signature objects, the last contain data which is used to verify the document validity in C++.'
type: docs
weight: 2400
url: /cpp/aspose.pdf.forms/signature/
---
## Signature class


An abstract class which represents signature object in the pdf document. [Signatures](../../aspose.pdf.signatures/) are fields with values of signature objects, the last contain data which is used to verify the document validity.

```cpp
class Signature : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Authority](./get_authority/)() const | The name of the person or authority signing the document. |
| [get_AvoidEstimatingSignatureLength](./get_avoidestimatingsignaturelength/)() const | Gets and sets an option means whether to avoid estimating the length of a signature. |
| [get_ByteRange](./get_byterange/)() const | An array of pairs of integers (starting byte offset, length in bytes) that shall describe the exact byte range for the digest calculation. |
| [get_ContactInfo](./get_contactinfo/)() const | Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [get_CustomAppearance](./get_customappearance/)() const | Gets/sets the custom appearance. |
| [get_CustomSignHash](./get_customsignhash/)() const | The delegate for custom sign the document hash. |
| [get_Date](./get_date/)() const | The time of signing. |
| [get_DefaultSignatureLength](./get_defaultsignaturelength/)() const | Gets the default length for the signature data in bytes. |
| [get_Location](./get_location/)() const | The CPU host name or physical location of the signing. |
| [get_OcspSettings](./get_ocspsettings/)() const | Gets/sets ocsp settings. |
| [get_Reason](./get_reason/)() const | The reason for the signing, such as (I agree, Pip B.). |
| [get_ShowProperties](./get_showproperties/)() const | Force to show/hide signature properties. |
| [get_TimestampSettings](./get_timestampsettings/)() const | Gets/sets timestamp settings. |
| [get_UseLtv](./get_useltv/)() const | Gets/sets ltv validation flag. |
| [GetSignatureAlgorithmInfo](./getsignaturealgorithminfo/)() | Retrieves information about the signature algorithm used in the signature. |
| [set_Authority](./set_authority/)(System::String) | The name of the person or authority signing the document. |
| [set_AvoidEstimatingSignatureLength](./set_avoidestimatingsignaturelength/)(bool) | Gets and sets an option means whether to avoid estimating the length of a signature. |
| [set_ContactInfo](./set_contactinfo/)(System::String) | Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [set_CustomAppearance](./set_customappearance/)(System::SharedPtr\<SignatureCustomAppearance\>) | Gets/sets the custom appearance. |
| [set_CustomSignHash](./set_customsignhash/)(SignHash) | The delegate for custom sign the document hash. |
| [set_Date](./set_date/)(System::DateTime) | The time of signing. |
| [set_DefaultSignatureLength](./set_defaultsignaturelength/)(int32_t) | Sets the default length for the signature data in bytes. |
| [set_Location](./set_location/)(System::String) | The CPU host name or physical location of the signing. |
| [set_OcspSettings](./set_ocspsettings/)(System::SharedPtr\<Aspose::Pdf::OcspSettings\>) | Gets/sets ocsp settings. |
| [set_Reason](./set_reason/)(System::String) | The reason for the signing, such as (I agree, Pip B.). |
| [set_ShowProperties](./set_showproperties/)(bool) | Force to show/hide signature properties. |
| [set_TimestampSettings](./set_timestampsettings/)(System::SharedPtr\<Aspose::Pdf::TimestampSettings\>) | Gets/sets timestamp settings. |
| [set_UseLtv](./set_useltv/)(bool) | Gets/sets ltv validation flag. |
| [Signature](./signature/)() | Inititalizes new instance of the [Signature](./) class. |
| [Signature](./signature/)(System::String, System::String) | Inititalizes new instance of the [Signature](./) class. |
| [Signature](./signature/)(System::SharedPtr\<System::IO::Stream\>, System::String) | Inititalizes new instance of the [Signature](./) class. |
| [Verify](./verify/)() | Verify the document regarding this signature and return true if document is valid or otherwise false. |
| [Verify](./verify/)(System::SharedPtr\<Security::ValidationOptions\>, System::SharedPtr\<Security::ValidationResult\>\&) | Verify the document regarding this signature and return true if document is valid or otherwise false. |
| [Verify](./verify/)(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>, System::SharedPtr\<Security::ValidationOptions\>, System::SharedPtr\<Security::ValidationResult\>\&) | Verify the document regarding this signature and return true if document is valid or otherwise false. Verification is performed using the external public key certificate. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
