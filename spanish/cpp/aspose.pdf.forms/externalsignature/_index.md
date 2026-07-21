---
title: "Aspose::Pdf::Forms::ExternalSignature clase"
linktitle: "ExternalSignature"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::ExternalSignature clase. Crea una firma PKCS#7 separada usando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables en C++."
type: docs
weight: 800
url: /es/cpp/aspose.pdf.forms/externalsignature/
---
## ExternalSignature class


Crea una firma PKCS#7 separada usando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables.

```cpp
class ExternalSignature : public Aspose::Pdf::Forms::Signature
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ExternalSignature](./externalsignature/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) | Crea una firma PKCS#7 **(detached)** separada usando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables. |
| [ExternalSignature](./externalsignature/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, DigestHashAlgorithm) | Crea una firma PKCS#7 **(detached)** separada usando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables. |
| [ExternalSignature](./externalsignature/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, bool) | Crea una firma PKCS#7 separada usando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables. |
| [ExternalSignature](./externalsignature/)(const System::String\&, bool) | Crea una firma PKCS#7 usando un X509Certificate2 como cadena base64. |
| [ExternalSignature](./externalsignature/)(const System::String\&, DigestHashAlgorithm) | Crea una firma PKCS#7 **(detached)** separada usando un X509Certificate2 como cadena base64. |
## Ver también

* Class [Signature](../signature/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
