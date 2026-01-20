---
title: Aspose::Pdf::Security::ValidationOptions::set_CheckCertificateChain method
linktitle: set_CheckCertificateChain
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::ValidationOptions::set_CheckCertificateChain method. Sets a value indicating whether the certificate chain should be checked during the validation process in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.security/validationoptions/set_checkcertificatechain/
---
## ValidationOptions::set_CheckCertificateChain method


Sets a value indicating whether the certificate chain should be checked during the validation process.

```cpp
void Aspose::Pdf::Security::ValidationOptions::set_CheckCertificateChain(bool value)
```

## Remarks


When the property is set, the existence of a chain of certificates will be checked, if it is absent, then the result of the verification will be [ValidationStatus::Undefined](../../validationstatus/), which corresponds to the behavior of Adobe Acrobat. If you just want to check the status of revocation online, then set the field in **false**. The default value is **false**. 
## See Also

* Class [ValidationOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
