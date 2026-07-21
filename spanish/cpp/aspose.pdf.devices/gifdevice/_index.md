---
title: "Clase Aspose::Pdf::Devices::GifDevice"
linktitle: "GifDevice"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Devices::GifDevice. Representa un dispositivo de imagen que ayuda a guardar páginas de documentos pdf en gif en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf.devices/gifdevice/
---
## GifDevice class


Representa un dispositivo de imagen que ayuda a guardar las páginas del documento PDF en gif.

```cpp
class GifDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Métodos

| Método | Descripción |
| --- | --- |
| [GifDevice](./gifdevice/)() | Inicializa una nueva instancia de la clase [GifDevice](./) con resolución predeterminada. |
| [GifDevice](./gifdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [GifDevice](./). |
| [GifDevice](./gifdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [GifDevice](./) con dimensiones de imagen y resolución proporcionadas. |
| [GifDevice](./gifdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [GifDevice](./) con el tamaño de página y la resolución proporcionados. |
| [GifDevice](./gifdevice/)(int32_t, int32_t) | Inicializa una nueva instancia de la clase [GifDevice](./) con las dimensiones de la imagen proporcionadas, resolución predeterminada (=150). |
| [GifDevice](./gifdevice/)(const System::SharedPtr\<PageSize\>\&) | Inicializa una nueva instancia de la clase [GifDevice](./) con el tamaño de página proporcionado, resolución predeterminada (=150). |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Convierte la página a gif y la guarda en el flujo de salida. |
## Ver también

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
