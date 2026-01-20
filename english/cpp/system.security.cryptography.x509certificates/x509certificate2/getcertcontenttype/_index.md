---
title: System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType method
linktitle: GetCertContentType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType method. Gets the type of certificate contained in the specified byte array in C++.'
type: docs
weight: 3100
url: /cpp/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) method


Gets the type of certificate contained in the specified byte array.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```


| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const ByteArrayPtr\& | Certificate data. |

### ReturnValue

Type of X.509 certificate.

## See Also

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
## X509Certificate2::GetCertContentType(const String\&) method


Gets the type of certificate contained in the specified file.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const String\& | Certificate file name. |

### ReturnValue

Type of X.509 certificate.

## See Also

* Enum [X509ContentType](../../x509contenttype/)
* Class [String](../../../system/string/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
