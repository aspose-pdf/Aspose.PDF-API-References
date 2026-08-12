---
title: "Clase Aspose::Pdf::Devices::EmfDevice"
linktitle: "EmfDevice"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Devices::EmfDevice. Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en emf en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf.devices/emfdevice/
---
## EmfDevice class


Representa un dispositivo de imagen que ayuda a guardar las páginas del documento PDF en emf.

```cpp
class EmfDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Métodos

| Método | Descripción |
| --- | --- |
| [EmfDevice](./emfdevice/)() | Inicializa una nueva instancia de la clase [EmfDevice](./) con la resolución predeterminada de la imagen raster escrita en emf. |
| [EmfDevice](./emfdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [EmfDevice](./). |
| [EmfDevice](./emfdevice/)(int32_t, int32_t) | Inicializa una nueva instancia de la clase [EmfDevice](./) con dimensiones de imagen proporcionadas y resolución predeterminada para la imagen raster escrita en emf (=150) |
| [EmfDevice](./emfdevice/)(const System::SharedPtr\<PageSize\>\&) | Inicializa una nueva instancia de la clase [EmfDevice](./) con el tamaño de página proporcionado y resolución predeterminada para la imagen raster escrita en emf (=150) |
| [EmfDevice](./emfdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [JpegDevice](../jpegdevice/) con dimensiones de imagen proporcionadas y resolución para la imagen raster escrita en emf. |
| [EmfDevice](./emfdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [JpegDevice](../jpegdevice/) con el tamaño de página proporcionado y la resolución para la imagen raster escrita en emf. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Convierte la página a emf y la guarda en el flujo de salida. |
## Ver también

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
