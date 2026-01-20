---
title: System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo method
linktitle: GetNameInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo method. Gets subject or issuer name from certificate in C++.'
type: docs
weight: 2100
url: /cpp/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo method


Gets subject or issuer name from certificate.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| name_type | X509NameType | Name formatting options. |
| for_issuer | bool | If true, returns issuer name, else returns subject name. |

### ReturnValue

Formatted issuer or subject name.

## See Also

* Class [String](../../../system/string/)
* Enum [X509NameType](../../x509nametype/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
