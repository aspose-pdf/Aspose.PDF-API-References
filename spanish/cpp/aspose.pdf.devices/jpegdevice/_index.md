---
title: "Aspose::Pdf::Devices::JpegDevice clase"
linktitle: "JpegDevice"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Devices::JpegDevice clase. Representa un dispositivo de imagen que ayuda a guardar las páginas de documentos pdf en jpeg en C++."
type: docs
weight: 800
url: /es/cpp/aspose.pdf.devices/jpegdevice/
---
## JpegDevice class


Representa un dispositivo de imagen que ayuda a guardar páginas de documentos pdf en jpeg.

```cpp
class JpegDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Métodos

| Método | Descripción |
| --- | --- |
| [JpegDevice](./jpegdevice/)() | Inicializa una nueva instancia de la clase [JpegDevice](./) con resolución predeterminada y calidad máxima. |
| [JpegDevice](./jpegdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [JpegDevice](./). |
| [JpegDevice](./jpegdevice/)(int32_t) | Inicializa una nueva instancia de la clase [JpegDevice](./). |
| [JpegDevice](./jpegdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, int32_t) | Inicializa una nueva instancia de la clase [JpegDevice](./). |
| [JpegDevice](./jpegdevice/)(int32_t, int32_t) | Inicializa una nueva instancia de la clase [JpegDevice](./) con las dimensiones de la imagen proporcionadas, resolución predeterminada (=150) y calidad máxima. |
| [JpegDevice](./jpegdevice/)(const System::SharedPtr\<PageSize\>\&) | Inicializa una nueva instancia de la clase [JpegDevice](./) con el tamaño de página proporcionado, resolución predeterminada (=150) y calidad máxima. |
| [JpegDevice](./jpegdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [JpegDevice](./) con las dimensiones de la imagen proporcionadas, resolución y calidad máxima. |
| [JpegDevice](./jpegdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [JpegDevice](./) con el tamaño de página proporcionado, resolución y calidad máxima. |
| [JpegDevice](./jpegdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, int32_t) | Inicializa una nueva instancia de la clase [JpegDevice](./) con las dimensiones de la imagen proporcionadas, resolución y calidad. |
| [JpegDevice](./jpegdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, int32_t) | Inicializa una nueva instancia de la clase [JpegDevice](./) con el tamaño de página, resolución y calidad proporcionados. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Convierte la página a jpeg y la guarda en el flujo de salida. |
## Ver también

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
