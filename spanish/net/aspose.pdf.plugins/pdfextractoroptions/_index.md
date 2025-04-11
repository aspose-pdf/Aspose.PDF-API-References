---
title: Class PdfExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.PdfExtractorOptions. Representa opciones para los plugins TextExtractor e ImageExtractor
type: docs
weight: 9070
url: /es/net/aspose.pdf.plugins/pdfextractoroptions/
---
## Clase PdfExtractorOptions

Representa opciones para los plugins TextExtractor e ImageExtractor.

```csharp
public abstract class PdfExtractorOptions : IPluginOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Devuelve la colección de datos del plugin PdfExtractor. |
| virtual [OperationName](../../aspose.pdf.plugins/pdfextractoroptions/operationname/) { get; } | Devuelve el nombre de la operación |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Agrega una nueva fuente de datos a la colección de datos del plugin PdfExtractor. |

## Observaciones

El `PdfExtractorOptions` contiene funciones base para agregar datos (archivos, flujos) que representan documentos PDF de entrada. Por favor, crea [`TextExtractorOptions`](../textextractoroptions/) o ImageExtractorOptions en lugar de esto.

### Véase también

* interfaz [IPluginOptions](../ipluginoptions/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)