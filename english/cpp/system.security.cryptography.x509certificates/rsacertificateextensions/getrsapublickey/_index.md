---
title: System::Security::Cryptography::X509Certificates::RSACertificateExtensions::GetRSAPublicKey method
linktitle: GetRSAPublicKey
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::X509Certificates::RSACertificateExtensions::GetRSAPublicKey method. Gets RSA public key from the certificate in C++.'
type: docs
weight: 200
url: /cpp/system.security.cryptography.x509certificates/rsacertificateextensions/getrsapublickey/
---
## RSACertificateExtensions::GetRSAPublicKey method


Gets [RSA](../../../system.security.cryptography/rsa/) public key from the certificate.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::X509Certificates::RSACertificateExtensions::GetRSAPublicKey(const SharedPtr<X509Certificate2> &certificate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| certificate | const SharedPtr\<X509Certificate2\>\& | The certificate. |

### ReturnValue

[RSA](../../../system.security.cryptography/rsa/) public key or nullptr if the certificate doesn't have [RSA](../../../system.security.cryptography/rsa/) public key.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSA](../../../system.security.cryptography/rsa/)
* Class [X509Certificate2](../../x509certificate2/)
* Class [RSACertificateExtensions](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
