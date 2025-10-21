---
title: Aspose::Pdf::Security::ValidationOptions class
linktitle: ValidationOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::ValidationOptions class. Represents options for validating a digital signature in a PDF document in C++.'
type: docs
weight: 1100
url: /cpp/aspose.pdf.security/validationoptions/
---
## ValidationOptions class


Represents options for validating a digital signature in a PDF document.

```cpp
class ValidationOptions : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_CheckCertificateChain](./get_checkcertificatechain/)() const | Gets a value indicating whether the certificate chain should be checked during the validation process. |
| [get_RequestTimeout](./get_requesttimeout/)() const | Gets the timeout duration, in milliseconds, for network-related operations during the validation process. The RequestTimeout property defines the maximum time the system should wait for a network response when accessing online resources, such as revocation status or OCSP servers. |
| [get_ValidationMethod](./get_validationmethod/)() const | Gets the method used to validate a certificate. |
| [get_ValidationMode](./get_validationmode/)() const | Gets the mode of validation for digital signatures in a PDF document. The [ValidationMode](../validationmode/) property determines the strictness of the validation process. |
| [set_CheckCertificateChain](./set_checkcertificatechain/)(bool) | Sets a value indicating whether the certificate chain should be checked during the validation process. |
| [set_RequestTimeout](./set_requesttimeout/)(int32_t) | Sets the timeout duration, in milliseconds, for network-related operations during the validation process. The RequestTimeout property defines the maximum time the system should wait for a network response when accessing online resources, such as revocation status or OCSP servers. |
| [set_ValidationMethod](./set_validationmethod/)(Aspose::Pdf::Security::ValidationMethod) | Sets the method used to validate a certificate. |
| [set_ValidationMode](./set_validationmode/)(Aspose::Pdf::Security::ValidationMode) | Sets the mode of validation for digital signatures in a PDF document. The [ValidationMode](../validationmode/) property determines the strictness of the validation process. |
| [ValidationOptions](./validationoptions/)() | Creates an instance of [ValidationOptions](./) class. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
