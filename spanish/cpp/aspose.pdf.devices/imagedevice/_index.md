---
title: "Aspose::Pdf::Devices::ImageDevice class"
linktitle: "ImageDevice"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Devices::ImageDevice class. Una clase abstracta para dispositivos de imagen en C++."
type: docs
weight: 700
url: /es/cpp/aspose.pdf.devices/imagedevice/
---
## ImageDevice class


Una clase abstracta para dispositivos de imagen.

```cpp
class ImageDevice : public Aspose::Pdf::Devices::PageDevice
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_CoordinateType](./get_coordinatetype/)() const | Obtiene el tipo de coordenadas de página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [get_FormPresentationMode](./get_formpresentationmode/)() const | Obtiene el modo de presentación del formulario. |
| [get_Height](./get_height/)() const | Obtiene la altura de salida de la imagen. |
| [get_RenderingOptions](./get_renderingoptions/)() const | Obtiene las opciones de renderizado. |
| [get_Resolution](./get_resolution/)() const | Obtiene la resolución de la imagen. |
| [get_Width](./get_width/)() const | Obtiene el ancho de salida de la imagen. |
| [GetBitmap](./getbitmap/)(const System::SharedPtr\<Page\>\&) | Convierte la página en [Bitmap](../). |
| [ImageDevice](./imagedevice/)() | Inicializador abstracto para los descendientes de [ImageDevice](./), establece la resolución a 150x150. |
| [ImageDevice](./imagedevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializador abstracto para los descendientes de [ImageDevice](./). |
| [ImageDevice](./imagedevice/)(int32_t, int32_t) | Inicializa una nueva instancia de la clase [JpegDevice](../jpegdevice/) con las dimensiones de imagen proporcionadas y la resolución predeterminada (=150). |
| [ImageDevice](./imagedevice/)(const System::SharedPtr\<PageSize\>\&) | Inicializa una nueva instancia de la clase [JpegDevice](../jpegdevice/) con las dimensiones de imagen proporcionadas y la resolución predeterminada (=150). |
| [ImageDevice](./imagedevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [JpegDevice](../jpegdevice/) con las dimensiones de imagen proporcionadas y la resolución. |
| [ImageDevice](./imagedevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [JpegDevice](../jpegdevice/) con las dimensiones de imagen proporcionadas y la resolución. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Establece el tipo de coordenadas de página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [set_FormPresentationMode](./set_formpresentationmode/)(Aspose::Pdf::Devices::FormPresentationMode) | Establece el modo de presentación del formulario. |
| [set_RenderingOptions](./set_renderingoptions/)(const System::SharedPtr\<Aspose::Pdf::RenderingOptions\>\&) | Establece las opciones de renderizado. |
## Ver también

* Class [PageDevice](../pagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
