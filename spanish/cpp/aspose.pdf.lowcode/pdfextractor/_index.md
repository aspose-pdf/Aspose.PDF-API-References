---
title: "Clase Aspose::Pdf::LowCode::PdfExtractor"
linktitle: "PdfExtractor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::LowCode::PdfExtractor. Representa la funcionalidad base para extraer texto, imágenes y otros tipos de contenido que pueden aparecer en las páginas de documentos PDF en C++."
type: docs
weight: 5900
url: /es/cpp/aspose.pdf.lowcode/pdfextractor/
---
## PdfExtractor class


Representa la funcionalidad base para extraer texto, imágenes y otros tipos de contenido que pueden aparecer en las páginas de documentos PDF.

```cpp
class PdfExtractor : public Aspose::Pdf::LowCode::IPlugin,
                     public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Dispose](./dispose/)() override | Implementación de IDisposable. En realidad, no es necesario para [PdfExtractor](./). |
| [Process](./process/)(System::SharedPtr\<IPluginOptions\>) override | Inicia el procesamiento de [PdfExtractor](./) con los parámetros especificados. |
## Observaciones


El objeto [TextExtractor](../textextractor/) se usa para extraer texto, o [ImageExtractor](../imageextractor/) para extraer imágenes.
## Ver también

* Class [IPlugin](../iplugin/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
