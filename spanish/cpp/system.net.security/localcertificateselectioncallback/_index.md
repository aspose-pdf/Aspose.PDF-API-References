---
title: "System::Net::Security::LocalCertificateSelectionCallback typedef"
linktitle: "LocalCertificateSelectionCallback"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Security::LocalCertificateSelectionCallback typedef. Un delegado de usuario utilizado para seleccionar el certificado SSL local en C++."
type: docs
weight: 600
url: /es/cpp/system.net.security/localcertificateselectioncallback/
---
## LocalCertificateSelectionCallback typedef


Un delegado de usuario utilizado para seleccionar el certificado SSL local.

```cpp
using System::Net::Security::LocalCertificateSelectionCallback = 
    System::MulticastDelegate<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>(
        System::SharedPtr<Object>, String,
        System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection>,
        System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>,
        System::ArrayPtr<String>)>
```

## Ver también

* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
