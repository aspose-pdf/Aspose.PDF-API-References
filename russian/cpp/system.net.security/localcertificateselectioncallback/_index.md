---
title: "System::Net::Security::LocalCertificateSelectionCallback typedef"
linktitle: "LocalCertificateSelectionCallback"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Security::LocalCertificateSelectionCallback typedef. Пользовательский делегат, используемый для выбора локального SSL‑сертификата в C++."
type: docs
weight: 600
url: /ru/cpp/system.net.security/localcertificateselectioncallback/
---
## LocalCertificateSelectionCallback typedef


Делегат пользователя, используемый для выбора локального сертификата SSL.

```cpp
using System::Net::Security::LocalCertificateSelectionCallback = 
    System::MulticastDelegate<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>(
        System::SharedPtr<Object>, String,
        System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection>,
        System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>,
        System::ArrayPtr<String>)>
```

## См. также

* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
