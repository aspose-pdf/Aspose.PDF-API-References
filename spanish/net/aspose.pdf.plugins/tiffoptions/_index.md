---
title: Class TiffOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.TiffOptions. Representa las opciones del convertidor de Pdf a Tiff para el complemento Tiff
type: docs
weight: 9420
url: /es/net/aspose.pdf.plugins/tiffoptions/
---
## Clase TiffOptions

Representa las opciones del convertidor de Pdf a Tiff para el [`Tiff`](../tiff/) complemento.

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TiffOptions](tiffoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | Obtiene o establece un valor límite de la transformación de colores en blanco y negro. Este parámetro se puede aplicar con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o ColorDepth.Format1bpp == 1 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | Obtiene o establece el tipo de compresión. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Obtiene el modo de conversión de imagen. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | Obtiene o establece el tipo de coordenadas de la página (cajas Media/Crop). El valor CropBox se utiliza por defecto. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | Obtiene o establece la profundidad de color. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Devuelve la colección de datos del complemento [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | Devuelve el nombre de la operación. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Obtiene o establece el valor de resolución de las imágenes resultantes. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Obtiene o establece una lista de páginas para el proceso. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | Obtiene y establece un indicador que permite guardar todas las páginas en un tiff multipágina. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | Obtiene o establece el tipo de forma. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | Obtiene o establece un valor que indica si se deben omitir las páginas en blanco. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Agrega una nueva fuente de datos a la colección de datos del complemento [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Establece una nueva fuente de datos para guardar. Solo puede ser un . Si desea guardar imágenes en flujos de memoria, pase null como parámetro. |

### Ver También

* clase [PdfToImageOptions](../pdftoimageoptions/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblaje [Aspose.PDF](../../)