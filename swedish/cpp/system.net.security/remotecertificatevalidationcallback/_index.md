---
title: "System::Net::Security::RemoteCertificateValidationCallback typedef"
linktitle: "RemoteCertificateValidationCallback"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Security::RemoteCertificateValidationCallback typedef. En användardelegat som används för att verifiera fjärr‑SSL‑certifikat i C++."
type: docs
weight: 700
url: /sv/cpp/system.net.security/remotecertificatevalidationcallback/
---
## RemoteCertificateValidationCallback typedef


En användardelegat som används för att verifiera fjärr‑SSL‑certifikat.

```cpp
using System::Net::Security::RemoteCertificateValidationCallback =  System::MulticastDelegate<bool(
    System::SharedPtr<Object>, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>,
    System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Chain>, SslPolicyErrors)>
```

## Se även

* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
