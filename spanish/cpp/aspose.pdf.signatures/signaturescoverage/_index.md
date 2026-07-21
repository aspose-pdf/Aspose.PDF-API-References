---
title: "enumeración Aspose::Pdf::Signatures::SignaturesCoverage"
linktitle: "SignaturesCoverage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Enumeración Aspose::Pdf::Signatures::SignaturesCoverage. Representa una enumeración para el nivel de cobertura proporcionado por firmas digitales en un documento en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage enum


Representa un enum para el nivel de cobertura proporcionado por firmas digitales en un documento.

```cpp
enum class SignaturesCoverage
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Undefined | 0 | Indica que el estado de la cobertura de las firmas digitales en el documento es indefinido. Este valor se utiliza típicamente cuando una o más firmas en el documento están comprometidas o no pueden verificarse, lo que impide una evaluación definitiva de la cobertura de firmas del documento. |
| EntirelySigned | 1 | Indica que el documento está completamente cubierto por firmas digitales. Este valor significa que todas las partes requeridas del documento han sido firmadas y ninguna firma está comprometida. |
| PartiallySigned | 2 | Indica que el documento está parcialmente firmado, lo que significa que parte, pero no todo, de su contenido está cubierto por firmas digitales. Este valor se usa cuando ciertas partes del documento permanecen sin firmar o están excluidas de la cobertura de firmas. |

## Ver también

* Namespace [Aspose::Pdf::Signatures](../)
* Library [Aspose.PDF for C++](../../)
