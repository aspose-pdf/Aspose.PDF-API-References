---
title: "Clase Aspose::Pdf::Devices::TiffSettings"
linktitle: "TiffSettings"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Devices::TiffSettings. Esta clase representa la configuración para importar pdf a Tiff en C++."
type: docs
weight: 1600
url: /es/cpp/aspose.pdf.devices/tiffsettings/
---
## TiffSettings class


Esta clase representa la configuración para importar pdf a Tiff.

```cpp
class TiffSettings : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Brightness](./get_brightness/)() const | Obtiene o establece un límite de valor de la transformación de colores en blanco y negro. Este parámetro puede aplicarse con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o [ColorDepth.Format1bpp](../colordepth/) == 1. |
| [get_Compression](./get_compression/)() const | Obtiene el tipo de compresión. |
| [get_CoordinateType](./get_coordinatetype/)() const | Obtiene o establece el tipo de coordenada de página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [get_Depth](./get_depth/)() const | Obtiene la profundidad de color. |
| [get_Margins](./get_margins/)() const | Obtiene los márgenes. |
| [get_Shape](./get_shape/)() const | Obtiene el tipo de la forma. |
| [get_SkipBlankPages](./get_skipblankpages/)() const | Obtiene un valor que indica si se deben omitir páginas en blanco. |
| [set_Brightness](./set_brightness/)(float) | Obtiene o establece un límite de valor de la transformación de colores en blanco y negro. Este parámetro puede aplicarse con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o [ColorDepth.Format1bpp](../colordepth/) == 1. |
| [set_Compression](./set_compression/)(CompressionType) | Establece el tipo de compresión. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Obtiene o establece el tipo de coordenada de página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [set_Depth](./set_depth/)(ColorDepth) | Establece la profundidad de color. |
| [set_Shape](./set_shape/)(ShapeType) | Establece el tipo de la forma. |
| [set_SkipBlankPages](./set_skipblankpages/)(bool) | Establece un valor que indica si se deben omitir páginas en blanco. |
| [TiffSettings](./tiffsettings/)() | Inicializa una nueva instancia de la clase [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(ShapeType) | Inicializa una nueva instancia de la clase [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(CompressionType) | Inicializa una nueva instancia de la clase [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(ColorDepth) | Inicializa una nueva instancia de la clase [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(const System::SharedPtr\<Aspose::Pdf::Devices::Margins\>\&) | Inicializa una nueva instancia de la clase [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(CompressionType, ColorDepth, const System::SharedPtr\<Aspose::Pdf::Devices::Margins\>\&) | Inicializa una nueva instancia de la clase [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(CompressionType, ColorDepth, const System::SharedPtr\<Aspose::Pdf::Devices::Margins\>\&, bool) | Inicializa una nueva instancia de la clase [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(CompressionType, ColorDepth, const System::SharedPtr\<Aspose::Pdf::Devices::Margins\>\&, bool, ShapeType) | Inicializa una nueva instancia de la clase [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(bool) | Inicializa una nueva instancia de la clase [TiffSettings](./). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
