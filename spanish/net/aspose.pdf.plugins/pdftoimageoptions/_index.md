---
title: Class PdfToImageOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.PdfToImageOptions. Representa opciones para el plugin PdfToImage
type: docs
weight: 9130
url: /es/net/aspose.pdf.plugins/pdftoimageoptions/
---
## Clase PdfToImageOptions

Representa opciones para el [`PdfToImage`](../pdftoimage/) plugin.

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Obtiene el modo de conversión de imagen. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Devuelve la colección de datos del plugin [`PdfToImage`](../pdftoimage/). |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | Devuelve el nombre de la operación. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Obtiene o establece el valor de resolución de las imágenes resultantes. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Obtiene o establece una lista de páginas para el proceso. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Agrega una nueva fuente de datos a la colección de datos del plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Establece una nueva fuente de datos para guardar. Solo puede ser un . Si desea guardar imágenes en flujos de memoria, pase null como parámetro. |

## Otros Miembros

| Nombre | Descripción |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | Define diferentes modos que se pueden usar al convertir de un documento PDF a una imagen Jpeg. Consulte la clase [`JpegOptions`](../jpegoptions/). |

## Observaciones

La clase PdfImageOptions contiene funciones base para agregar datos (archivos, flujos) que representan documentos PDF de entrada.

### Véase También

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)