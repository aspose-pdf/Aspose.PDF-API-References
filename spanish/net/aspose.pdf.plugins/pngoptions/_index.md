---
title: Class PngOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.PngOptions. Representa opciones de conversión de Pdf a Png para el plugin Png
type: docs
weight: 9180
url: /es/net/aspose.pdf.plugins/pngoptions/
---
## Clase PngOptions

Representa opciones de conversión de Pdf a Png para el [`Png`](../png/) plugin.

```csharp
public sealed class PngOptions : PdfToImageOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PngOptions](pngoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Obtiene el modo de conversión de imagen. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Devuelve la colección de datos del plugin [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/pngoptions/operationname/) { get; } | Devuelve el nombre de la operación. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Obtiene o establece el valor de resolución de las imágenes resultantes. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Obtiene o establece una lista de páginas para el proceso. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Agrega una nueva fuente de datos a la colección de datos del plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Establece una nueva fuente de datos para guardar. Solo puede ser un . Si desea guardar imágenes en flujos de memoria, pase null como parámetro. |

### Véase También

* clase [PdfToImageOptions](../pdftoimageoptions/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblaje [Aspose.PDF](../../)