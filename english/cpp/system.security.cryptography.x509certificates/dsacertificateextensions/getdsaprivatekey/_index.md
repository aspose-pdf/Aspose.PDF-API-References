---
title: System::Security::Cryptography::X509Certificates::DSACertificateExtensions::GetDSAPrivateKey method
linktitle: GetDSAPrivateKey
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::X509Certificates::DSACertificateExtensions::GetDSAPrivateKey method. Gets DSA private key from the certificate in C++.'
type: docs
weight: 100
url: /cpp/system.security.cryptography.x509certificates/dsacertificateextensions/getdsaprivatekey/
---
## DSACertificateExtensions::GetDSAPrivateKey method


Gets [DSA](../../../system.security.cryptography/dsa/) private key from the certificate.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::X509Certificates::DSACertificateExtensions::GetDSAPrivateKey(const SharedPtr<X509Certificate2> &certificate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| certificate | const SharedPtr\<X509Certificate2\>\& | The certificate. |

### ReturnValue

[DSA](../../../system.security.cryptography/dsa/) private key or nullptr if the certificate doesn't have [DSA](../../../system.security.cryptography/dsa/) private key.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DSA](../../../system.security.cryptography/dsa/)
* Class [X509Certificate2](../../x509certificate2/)
* Class [DSACertificateExtensions](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
