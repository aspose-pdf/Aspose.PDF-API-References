---
title: Aspose::Pdf::Forms::ExternalSignature class
linktitle: ExternalSignature
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::ExternalSignature class. Creates a detached PKCS#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.forms/externalsignature/
---
## ExternalSignature class


Creates a detached PKCS#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.

```cpp
class ExternalSignature : public Aspose::Pdf::Forms::Signature
```

## Methods

| Method | Description |
| --- | --- |
| [ExternalSignature](./externalsignature/)(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) | Creates a detached PKCS#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys. |
| [ExternalSignature](./externalsignature/)(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>, bool) | Creates a detached PKCS#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys. |
| [ExternalSignature](./externalsignature/)(System::String, bool) | Creates a PKCS#7 (detached) signature using a X509Certificate2 as base64 string. |
| [get_Authority](../signature/get_authority/)() const | The name of the person or authority signing the document. |
| [get_ByteRange](../signature/get_byterange/)() const | An array of pairs of integers (starting byte offset, length in bytes) that shall describe the exact byte range for the digest calculation. |
| [get_Certificate](./get_certificate/)() const | The certificate with the private key. |
| [get_ContactInfo](../signature/get_contactinfo/)() const | Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [get_CustomAppearance](../signature/get_customappearance/)() const | Gets/sets the custom appearance. |
| [get_CustomSignHash](../signature/get_customsignhash/)() const | The delegate for custom sign the document hash (Beta). |
| [get_Date](../signature/get_date/)() const | The time of signing. |
| [get_Location](../signature/get_location/)() const | The CPU host name or physical location of the signing. |
| [get_OcspSettings](../signature/get_ocspsettings/)() const | Gets/sets ocsp settings. |
| [get_Reason](../signature/get_reason/)() const | The reason for the signing, such as (I agree, Pip B.). |
| [get_ShowProperties](../signature/get_showproperties/)() const | Force to show/hide signature properties. |
| [get_TimestampSettings](../signature/get_timestampsettings/)() const | Gets/sets timestamp settings. |
| [get_UseLtv](../signature/get_useltv/)() const | Gets/sets ltv validation flag. |
| [set_Authority](../signature/set_authority/)(System::String) | The name of the person or authority signing the document. |
| [set_ContactInfo](../signature/set_contactinfo/)(System::String) | Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [set_CustomAppearance](../signature/set_customappearance/)(System::SharedPtr\<SignatureCustomAppearance\>) | Gets/sets the custom appearance. |
| [set_CustomSignHash](../signature/set_customsignhash/)(SignHash) | The delegate for custom sign the document hash (Beta). |
| [set_Date](../signature/set_date/)(System::DateTime) | The time of signing. |
| [set_Location](../signature/set_location/)(System::String) | The CPU host name or physical location of the signing. |
| [set_OcspSettings](../signature/set_ocspsettings/)(System::SharedPtr\<Aspose::Pdf::OcspSettings\>) | Gets/sets ocsp settings. |
| [set_Reason](../signature/set_reason/)(System::String) | The reason for the signing, such as (I agree, Pip B.). |
| [set_ShowProperties](../signature/set_showproperties/)(bool) | Force to show/hide signature properties. |
| [set_TimestampSettings](../signature/set_timestampsettings/)(System::SharedPtr\<Aspose::Pdf::TimestampSettings\>) | Gets/sets timestamp settings. |
| [set_UseLtv](../signature/set_useltv/)(bool) | Gets/sets ltv validation flag. |
| [Signature](../signature/signature/)() | Inititalizes new instance of the [Signature](../signature/) class. |
| [Signature](../signature/signature/)(System::String, System::String) | Inititalizes new instance of the [Signature](../signature/) class. |
| [Signature](../signature/signature/)(System::SharedPtr\<System::IO::Stream\>, System::String) | Inititalizes new instance of the [Signature](../signature/) class. |
| [Verify](../signature/verify/)() | Verify the document regarding this signature and return true if document is valid or otherwise false. |
## See Also

* Class [Signature](../signature/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
