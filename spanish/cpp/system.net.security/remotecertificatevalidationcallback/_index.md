---
title: "System::Net::Security::RemoteCertificateValidationCallback typedef"
linktitle: "RemoteCertificateValidationCallback"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Security::RemoteCertificateValidationCallback typedef. Un delegado de usuario utilizado para verificar el certificado SSL remoto en C++."
type: docs
weight: 700
url: /es/cpp/system.net.security/remotecertificatevalidationcallback/
---
## RemoteCertificateValidationCallback typedef


Un delegado de usuario utilizado para verificar el certificado SSL remoto.

```cpp
using System::Net::Security::RemoteCertificateValidationCallback =  System::MulticastDelegate<bool(
    System::SharedPtr<Object>, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>,
    System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Chain>, SslPolicyErrors)>
```

## Ver también

* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
