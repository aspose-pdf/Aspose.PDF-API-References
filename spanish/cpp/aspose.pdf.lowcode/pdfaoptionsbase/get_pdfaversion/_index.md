---
title: "Aspose::Pdf::LowCode::PdfAOptionsBase::get_PdfAVersion method"
linktitle: "get_PdfAVersion"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LowCode::PdfAOptionsBase::get_PdfAVersion method. Obtiene la versión del estándar PDF/A que se utilizará para la validación o conversión en C++."
type: docs
weight: 1300
url: /es/cpp/aspose.pdf.lowcode/pdfaoptionsbase/get_pdfaversion/
---
## PdfAOptionsBase::get_PdfAVersion method


Obtiene la versión del estándar PDF/A que se utilizará para la validación o conversión.

```cpp
PdfAStandardVersion Aspose::Pdf::LowCode::PdfAOptionsBase::get_PdfAVersion() const
```

## Observaciones


La versión del estándar PDF/A. Puede ser uno de los valores de la enumeración [PdfAStandardVersion](../../pdfastandardversion/).

La versión del estándar PDF/A se utiliza para determinar el nivel de cumplimiento para la validación y conversión de PDF/A. Si la versión se establece en [PdfAStandardVersion::Auto](../../pdfastandardversion/), el sistema determinará automáticamente la versión adecuada del estándar PDF/A para la validación basada en los metadatos del documento. Para el proceso de conversión a PDF/A, [PdfAStandardVersion::Auto](../../pdfastandardversion/) por defecto corresponde a la versión del estándar PDF/A-1b.
## Ver también

* Enum [PdfAStandardVersion](../../pdfastandardversion/)
* Class [PdfAOptionsBase](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
