---
title: "Aspose::Pdf::Security::ValidationMode enum"
linktitle: "ValidationMode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::ValidationMode enum. Especifica el modo de validación para los procesos de validación de firmas PDF en C++."
type: docs
weight: 1800
url: /es/cpp/aspose.pdf.security/validationmode/
---
## ValidationMode enum


Especifica el modo de validación para los procesos de validación de firmas PDF.

```cpp
enum class ValidationMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | Representa un modo donde no se realiza la validación. |
| OnlyCheck | 1 | Representa el modo en el que se realiza la validación, pero su resultado no afecta la validación de la firma digital. Puedes comprobar el resultado de la validación tú mismo. |
| Strict | 2 | Representa el modo en el que se realiza la validación y su resultado afecta la validación de la firma digital. Si el certificado no pudo ser verificado, entonces la firma digital se considerará inválida. Puedes comprobar el resultado de la validación tú mismo. |

## Ver también

* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
