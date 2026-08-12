---
title: "Clase Aspose::Pdf::Security::ValidationOptions"
linktitle: "ValidationOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Security::ValidationOptions. Representa opciones para validar una firma digital en un documento PDF en C++."
type: docs
weight: 1200
url: /es/cpp/aspose.pdf.security/validationoptions/
---
## ValidationOptions class


Representa opciones para validar una firma digital en un documento PDF.

```cpp
class ValidationOptions : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_CheckCertificateChain](./get_checkcertificatechain/)() const | Obtiene un valor que indica si la cadena de certificados debe verificarse durante el proceso de validación. |
| [get_RequestTimeout](./get_requesttimeout/)() const | Obtiene la duración del tiempo de espera, en milisegundos, para operaciones de red durante el proceso de validación. La propiedad RequestTimeout define el tiempo máximo que el sistema debe esperar una respuesta de red al acceder a recursos en línea, como el estado de revocación o servidores OCSP. |
| [get_ValidationMethod](./get_validationmethod/)() const | Obtiene el método utilizado para validar un certificado. |
| [get_ValidationMode](./get_validationmode/)() const | Obtiene el modo de validación de firmas digitales en un documento PDF. La propiedad [ValidationMode](../validationmode/) determina el nivel de rigurosidad del proceso de validación. |
| [set_CheckCertificateChain](./set_checkcertificatechain/)(bool) | Establece un valor que indica si la cadena de certificados debe verificarse durante el proceso de validación. |
| [set_RequestTimeout](./set_requesttimeout/)(int32_t) | Establece la duración del tiempo de espera, en milisegundos, para operaciones de red durante el proceso de validación. La propiedad RequestTimeout define el tiempo máximo que el sistema debe esperar una respuesta de red al acceder a recursos en línea, como el estado de revocación o servidores OCSP. |
| [set_ValidationMethod](./set_validationmethod/)(Aspose::Pdf::Security::ValidationMethod) | Establece el método utilizado para validar un certificado. |
| [set_ValidationMode](./set_validationmode/)(Aspose::Pdf::Security::ValidationMode) | Establece el modo de validación de firmas digitales en un documento PDF. La propiedad [ValidationMode](../validationmode/) determina el nivel de rigurosidad del proceso de validación. |
| [ValidationOptions](./validationoptions/)() | Crea una instancia de la clase [ValidationOptions](./). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
