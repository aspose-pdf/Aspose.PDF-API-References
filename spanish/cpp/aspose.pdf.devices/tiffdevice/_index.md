---
title: "Clase Aspose::Pdf::Devices::TiffDevice"
linktitle: "TiffDevice"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Devices::TiffDevice. Esta clase ayuda a guardar el documento PDF página por página en una sola imagen TIFF en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.pdf.devices/tiffdevice/
---
## TiffDevice class


Esta clase ayuda a guardar el documento pdf página por página en una única imagen tiff.

```cpp
class TiffDevice : public Aspose::Pdf::Devices::DocumentDevice
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BinarizeBradley](./binarizebradley/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, double) | Realiza binarización Bradley para el flujo de entrada. |
| [get_FormPresentationMode](./get_formpresentationmode/)() const | Obtiene el modo de presentación del formulario. |
| [get_Height](./get_height/)() const | Obtiene la altura de salida de la imagen. |
| [get_RenderingOptions](./get_renderingoptions/)() const | Obtiene las opciones de renderizado. |
| [get_Resolution](./get_resolution/)() const | Obtiene la resolución de la imagen. |
| [get_Settings](./get_settings/)() const | Obtiene la configuración para mapear PDF a imagen TIFF. |
| [get_Width](./get_width/)() const | Obtiene el ancho de salida de la imagen. |
| [Process](./process/)(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) override | Convierte ciertas páginas del documento a TIFF y las guarda en el flujo de salida. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Realiza alguna operación en la página dada, p. ej., convierte la página en una imagen gráfica. |
| [set_FormPresentationMode](./set_formpresentationmode/)(Aspose::Pdf::Devices::FormPresentationMode) | Establece el modo de presentación del formulario. |
| [set_RenderingOptions](./set_renderingoptions/)(const System::SharedPtr\<Aspose::Pdf::RenderingOptions\>\&) | Establece las opciones de renderizado. |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<TiffSettings\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)() | Inicializa una nueva instancia de la clase [TiffDevice](./) con la configuración predeterminada. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<TiffSettings\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<TiffSettings\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&) | Inicializa una nueva instancia de la clase [TiffDevice](./). |
## Ver también

* Class [DocumentDevice](../documentdevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
