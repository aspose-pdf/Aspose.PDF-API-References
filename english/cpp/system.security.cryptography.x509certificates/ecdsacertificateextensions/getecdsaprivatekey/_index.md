---
title: System::Security::Cryptography::X509Certificates::ECDsaCertificateExtensions::GetECDsaPrivateKey method
linktitle: GetECDsaPrivateKey
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::X509Certificates::ECDsaCertificateExtensions::GetECDsaPrivateKey method. Gets ECDsa private key from the certificate in C++.'
type: docs
weight: 100
url: /cpp/system.security.cryptography.x509certificates/ecdsacertificateextensions/getecdsaprivatekey/
---
## ECDsaCertificateExtensions::GetECDsaPrivateKey method


Gets [ECDsa](../../../system.security.cryptography/ecdsa/) private key from the certificate.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::X509Certificates::ECDsaCertificateExtensions::GetECDsaPrivateKey(const SharedPtr<X509Certificate2> &certificate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| certificate | const SharedPtr\<X509Certificate2\>\& | The certificate. |

### ReturnValue

[ECDsa](../../../system.security.cryptography/ecdsa/) private key or nullptr if the certificate doesn't have [ECDsa](../../../system.security.cryptography/ecdsa/) private key.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ECDsa](../../../system.security.cryptography/ecdsa/)
* Class [X509Certificate2](../../x509certificate2/)
* Class [ECDsaCertificateExtensions](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
