---
title: "Clase Aspose::Pdf::XpsSaveOptions"
linktitle: "XpsSaveOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::XpsSaveOptions. Opciones de guardado para exportar al formato Xps en C++."
type: docs
weight: 21100
url: /es/cpp/aspose.pdf/xpssaveoptions/
---
## XpsSaveOptions class


Opciones de guardado para exportar al formato Xps.

```cpp
class XpsSaveOptions : public Aspose::Pdf::UnifiedSaveOptions,
                       public Aspose::Pdf::IPipelineOptions
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_BatchSize](./get_batchsize/)() override | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [get_DefaultFont](./get_defaultfont/)() const | Obtiene/establece el nombre de la fuente predeterminada. Se usa si el nombre de la fuente incrustada no se encuentra en el sistema. |
| [get_SaveTransparentTexts](./get_savetransparenttexts/)() const | Indica si se debe preservar el texto transparente (OCR). |
| [get_UseEmbeddedTrueTypeFonts](./get_useembeddedtruetypefonts/)() const | Obtiene/establece la bandera para usar fuentes TrueType incrustadas. Evitar el uso de fuentes TrueType incrustadas puede reducir el tiempo de conversión. |
| [get_UseNewImagingEngine](./get_usenewimagingengine/)() const | Obtiene la opción UseNewImagingEngine. |
| [set_BatchSize](./set_batchsize/)(int32_t) override | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [set_DefaultFont](./set_defaultfont/)(const System::String\&) | Obtiene/establece el nombre de la fuente predeterminada. Se usa si el nombre de la fuente incrustada no se encuentra en el sistema. |
| [set_SaveTransparentTexts](./set_savetransparenttexts/)(bool) | Indica si se debe preservar el texto transparente (OCR). |
| [set_UseEmbeddedTrueTypeFonts](./set_useembeddedtruetypefonts/)(bool) | Obtiene/establece la bandera para usar fuentes TrueType incrustadas. Evitar el uso de fuentes TrueType incrustadas puede reducir el tiempo de conversión. |
| [set_UseNewImagingEngine](./set_usenewimagingengine/)(bool) | Establece la opción UseNewImagingEngine. |
| [XpsSaveOptions](./xpssaveoptions/)() | Constructor. |
## Ver también

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Class [IPipelineOptions](../ipipelineoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
