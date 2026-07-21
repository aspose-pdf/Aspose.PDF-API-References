---
title: "Clase Aspose::Pdf::Devices::BmpDevice"
linktitle: "BmpDevice"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Devices::BmpDevice. Representa un dispositivo de imagen que ayuda a guardar las páginas de documentos pdf en bmp en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class


Representa un dispositivo de imagen que ayuda a guardar las páginas del documento PDF en bmp.

```cpp
class BmpDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BmpDevice](./bmpdevice/)() | Inicializa una nueva instancia de la clase [BmpDevice](./) con resolución predeterminada. |
| [BmpDevice](./bmpdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [BmpDevice](./). |
| [BmpDevice](./bmpdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [BmpDevice](./) con las dimensiones de imagen y la resolución proporcionadas. |
| [BmpDevice](./bmpdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [BmpDevice](./) con el tamaño de página y la resolución proporcionados. |
| [BmpDevice](./bmpdevice/)(int32_t, int32_t) | Inicializa una nueva instancia de la clase [BmpDevice](./) con las dimensiones de imagen proporcionadas, resolución predeterminada (=150). |
| [BmpDevice](./bmpdevice/)(const System::SharedPtr\<PageSize\>\&) | Inicializa una nueva instancia de la clase [BmpDevice](./) con el tamaño de página proporcionado, resolución predeterminada (=150). |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Convierte la página a bmp y la guarda en el flujo de salida. |
## Ver también

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
