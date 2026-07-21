---
title: "Clase Aspose::Pdf::LowCode::TiffOptions"
linktitle: "TiffOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::LowCode::TiffOptions. Representa opciones del convertidor de Pdf a Tiff para el complemento Tiff en C++."
type: docs
weight: 8900
url: /es/cpp/aspose.pdf.lowcode/tiffoptions/
---
## TiffOptions class


Representa opciones del convertidor de [Pdf](../../aspose.pdf/) a [Tiff](../tiff/) para el complemento [Tiff](../tiff/).

```cpp
class TiffOptions : public Aspose::Pdf::LowCode::PdfToImageOptions
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Brightness](./get_brightness/)() | Obtiene o establece un límite de valor de la transformación de colores en blanco y negro. Este parámetro puede aplicarse con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o ColorDepth.Format1bpp == 1. |
| [get_Compression](./get_compression/)() | Obtiene el tipo de compresión. |
| [get_CoordinateType](./get_coordinatetype/)() | Obtiene o establece el tipo de coordenada de página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [get_Depth](./get_depth/)() | Obtiene la profundidad de color. |
| [get_OperationName](./get_operationname/)() override | Devuelve el nombre de la operación. |
| [get_SaveAsMultiPageTiff](./get_saveasmultipagetiff/)() const | Obtiene y establece la bandera que permite guardar todas las páginas en un TIFF multipágina. |
| [get_Shape](./get_shape/)() | Obtiene el tipo de la forma. |
| [get_SkipBlankPages](./get_skipblankpages/)() | Obtiene un valor que indica si se deben omitir páginas en blanco. |
| [set_Brightness](./set_brightness/)(float) | Obtiene o establece un límite de valor de la transformación de colores en blanco y negro. Este parámetro puede aplicarse con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o ColorDepth.Format1bpp == 1. |
| [set_Compression](./set_compression/)(Devices::CompressionType) | Establece el tipo de compresión. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Obtiene o establece el tipo de coordenada de página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [set_Depth](./set_depth/)(Devices::ColorDepth) | Establece la profundidad de color. |
| [set_SaveAsMultiPageTiff](./set_saveasmultipagetiff/)(bool) | Obtiene y establece la bandera que permite guardar todas las páginas en un TIFF multipágina. |
| [set_Shape](./set_shape/)(Devices::ShapeType) | Establece el tipo de la forma. |
| [set_SkipBlankPages](./set_skipblankpages/)(bool) | Establece un valor que indica si se deben omitir páginas en blanco. |
| [TiffOptions](./tiffoptions/)() | Inicializa una nueva instancia del objeto [TiffOptions](./). |
## Ver también

* Class [PdfToImageOptions](../pdftoimageoptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
