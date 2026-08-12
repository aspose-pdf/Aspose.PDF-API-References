---
title: "Aspose::Pdf::Security::VerificationResult clase"
linktitle: "VerificationResult"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::VerificationResult clase. Representa el resultado de verificar una firma digital en un archivo PDF en C++."
type: docs
weight: 1400
url: /es/cpp/aspose.pdf.security/verificationresult/
---
## VerificationResult class


Representa el resultado de verificar una firma digital en un archivo PDF.

```cpp
class VerificationResult : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_IsCompromised](./get_iscompromised/)() const | Indica si la estructura de la firma digital probablemente está comprometida. Esto significa un cambio para eludir la verificación de la firma por herramientas PDF. Vea [Message](../) para más detalles. |
| [get_Message](./get_message/)() const | Obtiene el mensaje asociado con el resultado de la verificación. El valor de la propiedad proporciona detalles adicionales sobre el resultado de la verificación, como descripciones de errores o mensajes de éxito. |
| [get_State](./get_state/)() const | Representa el estado de verificación de una firma digital en un archivo PDF. Indica si la firma es válida, inválida o indefinida. |
| [get_VerificationException](./get_verificationexception/)() const | Obtiene la excepción asociada al proceso de verificación si está presente. Esta propiedad proporciona detalles sobre errores o problemas encontrados durante la verificación de una firma digital en un archivo PDF. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
