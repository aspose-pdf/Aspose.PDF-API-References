---
title: Aspose::Pdf::Forms::ExternalSignature class
linktitle: ExternalSignature
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::ExternalSignature class. Creates a detached PKCS#7 signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.forms/externalsignature/
---
## ExternalSignature class


Creates a detached PKCS#7 signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.

```cpp
class ExternalSignature : public Aspose::Pdf::Forms::Signature
```

## Methods

| Method | Description |
| --- | --- |
| [ExternalSignature](./externalsignature/)(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) | Creates a detached PKCS#7 **(detached)** signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys. |
| [ExternalSignature](./externalsignature/)(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>, DigestHashAlgorithm) | Creates a detached PKCS#7 **(detached)** signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys. |
| [ExternalSignature](./externalsignature/)(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>, bool) | Creates a detached PKCS#7 signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys. |
| [ExternalSignature](./externalsignature/)(System::String, bool) | Creates a PKCS#7 signature using a X509Certificate2 as base64 string. |
| [ExternalSignature](./externalsignature/)(System::String, DigestHashAlgorithm) | Creates a PKCS#7 **(detached)** signature using a X509Certificate2 as base64 string. |
## See Also

* Class [Signature](../signature/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
