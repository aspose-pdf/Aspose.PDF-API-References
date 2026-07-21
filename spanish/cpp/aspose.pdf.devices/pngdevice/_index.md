---
title: "Clase Aspose::Pdf::Devices::PngDevice"
linktitle: "PngDevice"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Devices::PngDevice. Representa un dispositivo de imagen que ayuda a guardar las páginas de documentos pdf en png en C++."
type: docs
weight: 1100
url: /es/cpp/aspose.pdf.devices/pngdevice/
---
## PngDevice class


Representa un dispositivo de imagen que ayuda a guardar páginas de documentos pdf en png.

```cpp
class PngDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_TransparentBackground](./get_transparentbackground/)() const | Obtiene si la imagen tiene fondo transparente. |
| [PngDevice](./pngdevice/)() | Inicializa una nueva instancia de la clase [PngDevice](./) con la resolución predeterminada. |
| [PngDevice](./pngdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [PngDevice](./). |
| [PngDevice](./pngdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [PngDevice](./) con las dimensiones de imagen y resolución proporcionadas. |
| [PngDevice](./pngdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [PngDevice](./) con el tamaño de página y resolución proporcionados. |
| [PngDevice](./pngdevice/)(int32_t, int32_t) | Inicializa una nueva instancia de la clase [PngDevice](./) con las dimensiones de imagen proporcionadas, resolución predeterminada (=150). |
| [PngDevice](./pngdevice/)(const System::SharedPtr\<PageSize\>\&) | Inicializa una nueva instancia de la clase [PngDevice](./) con el tamaño de página proporcionado, resolución predeterminada (=150). |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Convierte la página en png y la guarda en el flujo de salida. |
| [set_TransparentBackground](./set_transparentbackground/)(bool) | Establece si la imagen tiene fondo transparente. |
## Ver también

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
