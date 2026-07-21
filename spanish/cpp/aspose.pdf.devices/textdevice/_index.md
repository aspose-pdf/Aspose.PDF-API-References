---
title: "Clase Aspose::Pdf::Devices::TextDevice"
linktitle: "TextDevice"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Devices::TextDevice. Representa una clase para convertir páginas de documentos pdf a texto en C++."
type: docs
weight: 1300
url: /es/cpp/aspose.pdf.devices/textdevice/
---
## TextDevice class


Representa una clase para convertir páginas de documentos pdf en texto.

```cpp
class TextDevice : public Aspose::Pdf::Devices::PageDevice
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Encoding](./get_encoding/)() const | Obtiene la codificación del texto extraído. |
| [get_ExtractionOptions](./get_extractionoptions/)() const | Obtiene las opciones de extracción de texto. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Convierte la página y la guarda como flujo de texto. |
| [set_Encoding](./set_encoding/)(const System::SharedPtr\<System::Text::Encoding\>\&) | Establece la codificación del texto extraído. |
| [set_ExtractionOptions](./set_extractionoptions/)(const System::SharedPtr\<Text::TextExtractionOptions\>\&) | Establece las opciones de extracción de texto. |
| [TextDevice](./textdevice/)(const System::SharedPtr\<Text::TextExtractionOptions\>\&) | Inicializa una nueva instancia de [TextDevice](./) con opciones de extracción de texto. |
| [TextDevice](./textdevice/)() | Inicializa una nueva instancia de [TextDevice](./) con el modo de formato de texto sin procesar y la codificación Unicode. |
| [TextDevice](./textdevice/)(const System::SharedPtr\<System::Text::Encoding\>\&) | Inicializa una nueva instancia de [TextDevice](./) para la codificación especificada. |
| [TextDevice](./textdevice/)(const System::SharedPtr\<Text::TextExtractionOptions\>\&, const System::SharedPtr\<System::Text::Encoding\>\&) | Inicializa una nueva instancia de [TextDevice](./) para la codificación especificada con opciones de extracción de texto. |
## Observaciones


El objeto [TextDevice](./) se utiliza básicamente para extraer texto de una página pdf.
## Ver también

* Class [PageDevice](../pagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
