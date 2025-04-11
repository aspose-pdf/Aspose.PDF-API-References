---
title: Class PdfToXlsOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.PdfToXlsOptions. Representa opciones de conversión de PDF a XLSX para el plugin XlsConverter
type: docs
weight: 9150
url: /es/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## Clase PdfToXlsOptions

Representa opciones de conversión de PDF a XLSX para el plugin [`XlsConverter`](../xlsconverter/).

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | El constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | Formato de salida. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Devuelve la colección de datos del plugin PdfConverterOptions. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | Establecer verdadero si necesita insertar una columna en blanco como la primera columna de la hoja de cálculo. El valor predeterminado es falso; significa que no se insertará una columna en blanco. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | Establecer verdadero si necesita minimizar el número de hojas de cálculo en el libro de trabajo resultante. El valor predeterminado es falso; significa guardar cada página PDF como una hoja de cálculo separada. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | Obtiene el nombre de la operación. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Obtiene la colección de objetivos añadidos para guardar los resultados de la operación. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Añade una nueva fuente de datos a la colección de datos del plugin PdfConverter. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Añade una nueva fuente de datos a la colección de datos del plugin PdfToXLSXConverterOptions. |

## Otros Miembros

| Nombre | Descripción |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | Permite especificar el formato de archivo .xlsx, .xls/xml o csv. El valor predeterminado es XLSX. |

### Véase También

* clase [PdfConverterOptions](../pdfconverteroptions/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)