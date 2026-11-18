---
title: System::Security::Cryptography::X509Certificates::RSACertificateExtensions::GetRSAPrivateKey method
linktitle: GetRSAPrivateKey
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::X509Certificates::RSACertificateExtensions::GetRSAPrivateKey method. Gets RSA private key from the certificate in C++.'
type: docs
weight: 100
url: /cpp/system.security.cryptography.x509certificates/rsacertificateextensions/getrsaprivatekey/
---
## RSACertificateExtensions::GetRSAPrivateKey method


Gets [RSA](../../../system.security.cryptography/rsa/) private key from the certificate.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::X509Certificates::RSACertificateExtensions::GetRSAPrivateKey(const SharedPtr<X509Certificate2> &certificate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| certificate | const SharedPtr\<X509Certificate2\>\& | The certificate. |

### ReturnValue

[RSA](../../../system.security.cryptography/rsa/) private key or nullptr if the certificate doesn't have [RSA](../../../system.security.cryptography/rsa/) private key.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSA](../../../system.security.cryptography/rsa/)
* Class [X509Certificate2](../../x509certificate2/)
* Class [RSACertificateExtensions](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
